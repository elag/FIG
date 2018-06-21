# FIG: Fix Interest Group 
The goal of the Fix Interest Group (FIG) is to create an implementation-independent specification for the Fix Language based on the work originally done as part of [Catmandu](https://metacpan.org/pod/Catmandu). The Fix Language is intended to be a macro-language for data transformations. See some specific uses of the current Fix implementation by Catmandu here: https://metacpan.org/pod/Catmandu::Fix The Fix Language is a DSL (domain specific language) for describing data transformations. It is written to be independent of the data format, i.e., it is not limited to XML data or JSON data transforms like their requisite transform specifications. It is also a specification meant to be machine-actionable, i.e. supporting the development & use of Fix Language parsers in various libraries for acting on those transforms. However, the goal of this work is not to make the Fix Language into a programming or generalized language; instead, it is to be specification that others could pick up for their own programming packages and act upon.

## Synopsis

```
# FIX is a macro-language for data transformations

# Simple fixes
add_field(hello,"world")
remove_field(my.deep.nested.junk)
copy_field(stats,output.$append)

# Conditionals
if exists(error)
    set_field(is_valid, 0)
elsif exists(warning)
    set_field(is_valid, 1)
    log(...)
else
    set_field(is_valid, 1)
end

# Loops
do list(path:demo)
   add_field(foo,bar)
end

# Domain specific transformations
marc_map(245a,title)

do marc_each()
  if marc_has(700)
     marc_map(700a,authors.$append)
  end
end

lido_date(
    path,
    -earliest_date:      earliestDate,
    -earliest_date_type: earliestDate.type,
    -latest_date:        latestDate,
    -latest_date_type:   latestDate.type
)
```
## Motivations for this Work

Why are we writing this Fix specification instead of using such transform specifications as already exist? We have a few reasons:

1. The existing transform specifications were not generalized enough (they were tied to MARC, or XML, for example);
2. There are general tools, but they tend to be in a corporate or enterprise domain, and can be too complicated for one-time usage, whereas we want this specification to be usable by people not familiar with programming (e.g. `jq` tool is powerful but can be hard to use for people without a programming background);
3. Many of the existing tools and specifications also focus on flat data, whereas the data coming from many cultural heritage spaces is hierarchical or more structurally complex;
4. Many of the tools that exist are coupled to a single programming language (Ruby, Java, etc.);
5. We want to have this syntax to be command line friendly, so you can leverage existing command line tools as part of this data parsing;
6. And this language should be easily extensible to have added functionalities.

## Logistics

### Current Participants:
- [Christina Harlow](http://github.com/cmh2166/)
- Patrick Hochstenbach
- Nics
- Johols
- Others as invited, with the goal to have people who can do at least 2 implementations of this work


### Communication

We primarily use the ELAG Slack Channel #FIG channel (sign up for [ELAG Slack here](https://t.co/8z9zBKaUnj)), or the connection information below for our monthly meetings.

### Meeting Schedule:
Monthly meetings, every 3rd Friday of the month at 16:00 CET, 7:00 Pacific. Connection information;

```
Join from PC, Mac, Linux, iOS or Android: https://stanford.zoom.us/j/937445143

Or iPhone one-tap:
   US: +16507249799,,937445143#  or +18778535257,,937445143# (Toll Free)
Or Telephone:
   Dial(for higher quality, dial a number based on your current location):
       US: +1 650 724 9799  or +1 877 853 5257 (Toll Free) or +1 855 880 1246 (Toll Free)
   Meeting ID: 937 445 143
   International numbers available: https://zoom.us/u/Dq5ExTlT

Or an H.323/SIP room system:
   H.323:
       162.255.37.11 (US West)
       162.255.36.11 (US East)
       221.122.88.195 (China)
       115.114.131.7 (India)
       213.19.144.110 (EMEA)
       202.177.207.158 (Australia)
       209.9.211.110 (Hong Kong)
       64.211.144.160 (Brazil)
       69.174.57.160 (Canada)
   Meeting ID: 937 445 143

   SIP: 937445143@zoomcrc.com (edited)
```

### Milestones

Preliminary / Summer 2018 Milestones:
1. **Logistics**: set up group, set the scope of work, reach out to interested parties for involvement;
2. **Evaluate**: evaluate existing implementation & abstract out a starting grammar of Fix Language, and examples of this language;
3. **Core Changes to Existing**: review the derived grammar, and identify Perl-isms or other aspects we want to change for implementation neutrality (like data types).

Further work based on the first few milestones.

### Success Criteria

To be filled in later after the preliminary milestones are achieved.

## Deliverables

To be filled in later after the preliminary milestones are achieved.

## Licensing

This work is intended to be open for use / reuse. Specific license to be selected as the work evolves (and we can make a better selection of the appropriate license). 
