| fix name | description | synopsis |
|----------|-------------|----------|
| Catmandu::Fix::Base | Base class for all code emitting Catmandu fixes| https://metacpan.org/pod/Catmandu::Fix::Base#SYNOPSIS |
| Catmandu::Fix::Bind | a wrapper for Catmandu::Fix-es| https://metacpan.org/pod/Catmandu::Fix::Bind#SYNOPSIS |
| Catmandu::Fix::Bind::Group | a role for a binder that executes all fixes as one group| https://metacpan.org/pod/Catmandu::Fix::Bind::Group#SYNOPSIS |
| Catmandu::Fix::Bind::benchmark | a binder that calculates the execution time of Fix functions| https://metacpan.org/pod/Catmandu::Fix::Bind::benchmark#SYNOPSIS |
| Catmandu::Fix::Bind::each | a binder that executes fixes for every (key, value) pair in a hash| https://metacpan.org/pod/Catmandu::Fix::Bind::each#SYNOPSIS |
| Catmandu::Fix::Bind::each | a binder that executes fixes for every (key, value) pair in a hash| https://metacpan.org/pod/Catmandu::Fix::Bind::each#SYNOPSIS |
| Catmandu::Fix::Bind::hashmap | a binder to add key/value pairs to an internal hashmap| https://metacpan.org/pod/Catmandu::Fix::Bind::hashmap#SYNOPSIS |
| Catmandu::Fix::Bind::identity | a binder that doesn't influence computation| https://metacpan.org/pod/Catmandu::Fix::Bind::identity#SYNOPSIS |
| Catmandu::Fix::Bind::importer | a binder runs fixes on records from an importer| https://metacpan.org/pod/Catmandu::Fix::Bind::importer#SYNOPSIS |
| Catmandu::Fix::Bind::iterate | a binder iterates fixes in a loop| https://metacpan.org/pod/Catmandu::Fix::Bind::iterate#SYNOPSIS |
| Catmandu::Fix::Bind::list | a binder that computes Fix-es for every element in a list| https://metacpan.org/pod/Catmandu::Fix::Bind::list#SYNOPSIS |
| Catmandu::Fix::Bind::mab_each | a binder that loops over MAB2 fields| https://metacpan.org/pod/Catmandu::Fix::Bind::mab_each#SYNOPSIS |
| Catmandu::Fix::Bind::marc_each | a binder that loops over MARC fields| https://metacpan.org/pod/Catmandu::Fix::Bind::marc_each#SYNOPSIS |
| Catmandu::Fix::Bind::maybe | a binder that skips fixes if one returns undef or dies| https://metacpan.org/pod/Catmandu::Fix::Bind::maybe#SYNOPSIS |
| Catmandu::Fix::Bind::pica_each | a binder that loops over PICA fields| https://metacpan.org/pod/Catmandu::Fix::Bind::pica_each#SYNOPSIS |
| Catmandu::Fix::Bind::timeout | run fixes that should run within a time limit| https://metacpan.org/pod/Catmandu::Fix::Bind::timeout#SYNOPSIS |
| Catmandu::Fix::Bind::visitor | a binder that computes Fix-es for every element in record| https://metacpan.org/pod/Catmandu::Fix::Bind::visitor#SYNOPSIS |
| Catmandu::Fix::Bind::with | a binder that computes Fix-es in the context of a path| https://metacpan.org/pod/Catmandu::Fix::Bind::with#SYNOPSIS |
| Catmandu::Fix::Condition | Role for all Catmandu::Fix conditionals| https://metacpan.org/pod/Catmandu::Fix::Condition#SYNOPSIS |
| Catmandu::Fix::Condition::SimpleAllTest | Base class to ease the construction of all match conditionals| https://metacpan.org/pod/Catmandu::Fix::Condition::SimpleAllTest#SYNOPSIS |
| Catmandu::Fix::Condition::SimpleAnyTest | Base class to ease the construction of any match conditionals| https://metacpan.org/pod/Catmandu::Fix::Condition::SimpleAnyTest#SYNOPSIS |
| Catmandu::Fix::Condition::SimpleCompareTest | Base class to ease the construction of compare conditionals| https://metacpan.org/pod/Catmandu::Fix::Condition::SimpleCompareTest#SYNOPSIS |
| Catmandu::Fix::Condition::all_equal | Execute fixes when all path values equal a string value| https://metacpan.org/pod/Catmandu::Fix::Condition::all_equal#SYNOPSIS |
| Catmandu::Fix::Condition::all_match | only execute fixes if all path values match the given regex| https://metacpan.org/pod/Catmandu::Fix::Condition::all_match#SYNOPSIS |
| Catmandu::Fix::Condition::any_equal | Execute fixes when at least one of the path values equal a string value| https://metacpan.org/pod/Catmandu::Fix::Condition::any_equal#SYNOPSIS |
| Catmandu::Fix::Condition::any_match | only execute fixes if any path value matches the given regex| https://metacpan.org/pod/Catmandu::Fix::Condition::any_match#SYNOPSIS |
| Catmandu::Fix::Condition::exists | only execute fixes if the path exists| https://metacpan.org/pod/Catmandu::Fix::Condition::exists#SYNOPSIS |
| Catmandu::Fix::Condition::file_test | only execute fixes of file test is successfull| https://metacpan.org/pod/Catmandu::Fix::Condition::file_test#SYNOPSIS |
| Catmandu::Fix::Condition::greater_than | Execute fixes when a field is greater than a value| https://metacpan.org/pod/Catmandu::Fix::Condition::greater_than#SYNOPSIS |
| Catmandu::Fix::Condition::in | only execute fixes the data in one path is contained in another| https://metacpan.org/pod/Catmandu::Fix::Condition::in#SYNOPSIS |
| Catmandu::Fix::Condition::is_archived_web_uri | check of a field contains an HTTP or HTTPS URI which is archived in a web archive| https://metacpan.org/pod/Catmandu::Fix::Condition::is_archived_web_uri#SYNOPSIS |
| Catmandu::Fix::Condition::is_array | only execute fixes if all path values are arrays| https://metacpan.org/pod/Catmandu::Fix::Condition::is_array#SYNOPSIS |
| Catmandu::Fix::Condition::is_false | only execute fixes if all path values are the boolean false, 0 or "false"| https://metacpan.org/pod/Catmandu::Fix::Condition::is_false#SYNOPSIS |
| Catmandu::Fix::Condition::is_http_uri | check of a field contains an HTTP URI| https://metacpan.org/pod/Catmandu::Fix::Condition::is_http_uri#SYNOPSIS |
| Catmandu::Fix::Condition::is_https_uri | check of a field contains an HTTPS URI| https://metacpan.org/pod/Catmandu::Fix::Condition::is_https_uri#SYNOPSIS |
| Catmandu::Fix::Condition::is_live_orcid | test if the ORCID can be resolved| https://metacpan.org/pod/Catmandu::Fix::Condition::is_live_orcid#SYNOPSIS |
| Catmandu::Fix::Condition::is_live_web_uri | check of a field contains an HTTP or HTTPS URI which is available online| https://metacpan.org/pod/Catmandu::Fix::Condition::is_live_web_uri#SYNOPSIS |
| Catmandu::Fix::Condition::is_null | only execute fixes if all path values are null| https://metacpan.org/pod/Catmandu::Fix::Condition::is_null#SYNOPSIS |
| Catmandu::Fix::Condition::is_number | only execute fixes if all path values are numbers| https://metacpan.org/pod/Catmandu::Fix::Condition::is_number#SYNOPSIS |
| Catmandu::Fix::Condition::is_object | only execute fixes if all path values are objects (unordered sets of name-value pairs)| https://metacpan.org/pod/Catmandu::Fix::Condition::is_object#SYNOPSIS |
| Catmandu::Fix::Condition::is_string | only execute fixes if all path values are strings| https://metacpan.org/pod/Catmandu::Fix::Condition::is_string#SYNOPSIS |
| Catmandu::Fix::Condition::is_true | only execute fixes if all path values are the boolean true, 1 or "true"| https://metacpan.org/pod/Catmandu::Fix::Condition::is_true#SYNOPSIS |
| Catmandu::Fix::Condition::is_uri | check of a field contains an URI| https://metacpan.org/pod/Catmandu::Fix::Condition::is_uri#SYNOPSIS |
| Catmandu::Fix::Condition::is_valid_isbn | condition on validity of isbn numbers| https://metacpan.org/pod/Catmandu::Fix::Condition::is_valid_isbn#SYNOPSIS |
| Catmandu::Fix::Condition::is_valid_issn | condition on validity of issn numbers| https://metacpan.org/pod/Catmandu::Fix::Condition::is_valid_issn#SYNOPSIS |
| Catmandu::Fix::Condition::is_valid_orcid | checks of a field looks like an ORCID| https://metacpan.org/pod/Catmandu::Fix::Condition::is_valid_orcid#SYNOPSIS |
| Catmandu::Fix::Condition::is_web_uri | check of a field contains an HTTP or HTTPS URI| https://metacpan.org/pod/Catmandu::Fix::Condition::is_web_uri#SYNOPSIS |
| Catmandu::Fix::Condition::less_than | Excute fixes when a field is less than a value| https://metacpan.org/pod/Catmandu::Fix::Condition::less_than#SYNOPSIS |
| Catmandu::Fix::Condition::mab_match | Conditionals on MAB2 fields| https://metacpan.org/pod/Catmandu::Fix::Condition::mab_match#SYNOPSIS |
| Catmandu::Fix::Condition::marc_all_match | Test if a MARC (sub)field matches a value| https://metacpan.org/pod/Catmandu::Fix::Condition::marc_all_match#SYNOPSIS |
| Catmandu::Fix::Condition::marc_any_match | Test if a MARC (sub)field matches a value| https://metacpan.org/pod/Catmandu::Fix::Condition::marc_any_match#SYNOPSIS |
| Catmandu::Fix::Condition::marc_has | Test if a MARC (sub)field exists| https://metacpan.org/pod/Catmandu::Fix::Condition::marc_has#SYNOPSIS |
| Catmandu::Fix::Condition::marc_has_many | Test if a MARC has more than one (sub)field| https://metacpan.org/pod/Catmandu::Fix::Condition::marc_has_many#SYNOPSIS |
| Catmandu::Fix::Condition::marc_match | Test if a MARC (sub)field matches a value| https://metacpan.org/pod/Catmandu::Fix::Condition::marc_match#SYNOPSIS |
| Catmandu::Fix::Condition::marc_spec_has | Test if a MARCspec references data| https://metacpan.org/pod/Catmandu::Fix::Condition::marc_spec_has#SYNOPSIS |
| Catmandu::Fix::Condition::pica_match | Conditionals on PICA fields| https://metacpan.org/pod/Catmandu::Fix::Condition::pica_match#SYNOPSIS |
| Catmandu::Fix::Condition::valid | Execute fixes if the data passes validation| https://metacpan.org/pod/Catmandu::Fix::Condition::valid#SYNOPSIS |
| Catmandu::Fix::Datahub | Utility functions and generic fixes developed for the Datahub project| https://metacpan.org/pod/Catmandu::Fix::Datahub#SYNOPSIS |
| Catmandu::Fix::Datahub::Util | Utility functions and generic fixes developed for the Datahub project| https://metacpan.org/pod/Catmandu::Fix::Datahub::Util#SYNOPSIS |
| Catmandu::Fix::Date | Catmandu fixes for processing dates| https://metacpan.org/pod/Catmandu::Fix::Date#SYNOPSIS |
| Catmandu::Fix::File | Catmandu fixes to check file attributes| https://metacpan.org/pod/Catmandu::Fix::File#SYNOPSIS |
| Catmandu::Fix::Has | helper class for creating Fix-es with (optional) parameters| https://metacpan.org/pod/Catmandu::Fix::Has#SYNOPSIS |
| Catmandu::Fix::Inline::marc_add | | https://metacpan.org/pod/Catmandu::Fix::Inline::marc_add#SYNOPSIS |
| Catmandu::Fix::Inline::marc_map | A marc_map-er for Perl scripts (DEPRECATED)| https://metacpan.org/pod/Catmandu::Fix::Inline::marc_map#SYNOPSIS |
| Catmandu::Fix::Inline::marc_remove | remove marc fields (DEPRECATED)| https://metacpan.org/pod/Catmandu::Fix::Inline::marc_remove#SYNOPSIS |
| Catmandu::Fix::Inline::marc_set | A marc_set-er for Perl scripts (DEPRECATED)| https://metacpan.org/pod/Catmandu::Fix::Inline::marc_set#SYNOPSIS |
| Catmandu::Fix::Inlineable | Role for all Catmandu fixes that can be inlined| https://metacpan.org/pod/Catmandu::Fix::Inlineable#SYNOPSIS |
| Catmandu::Fix::LIDO::DescriptiveNote | | https://metacpan.org/pod/Catmandu::Fix::LIDO::DescriptiveNote#SYNOPSIS |
| Catmandu::Fix::LIDO::ID | | https://metacpan.org/pod/Catmandu::Fix::LIDO::ID#SYNOPSIS |
| Catmandu::Fix::LIDO::Nameset | | https://metacpan.org/pod/Catmandu::Fix::LIDO::Nameset#SYNOPSIS |
| Catmandu::Fix::LIDO::Term | | https://metacpan.org/pod/Catmandu::Fix::LIDO::Term#SYNOPSIS |
| Catmandu::Fix::LIDO::Utility | | https://metacpan.org/pod/Catmandu::Fix::LIDO::Utility#SYNOPSIS |
| Catmandu::Fix::LIDO::Value | | https://metacpan.org/pod/Catmandu::Fix::LIDO::Value#SYNOPSIS |
| Catmandu::Fix::Parser | the parser of the Catmandu::Fix language| https://metacpan.org/pod/Catmandu::Fix::Parser#SYNOPSIS |
| Catmandu::Fix::SimpleGetValue | helper class for creating emit Fix-es| https://metacpan.org/pod/Catmandu::Fix::SimpleGetValue#SYNOPSIS |
| Catmandu::Fix::XML | Catmandu fixes for processing xml (deprecated)| https://metacpan.org/pod/Catmandu::Fix::XML#SYNOPSIS |
| Catmandu::Fix::aat_match | Perform a direct match between a term and a Subject in the AAT| https://metacpan.org/pod/Catmandu::Fix::aat_match#SYNOPSIS |
| Catmandu::Fix::aat_match | Perform a direct match between a term and a Subject in the AAT| https://metacpan.org/pod/Catmandu::Fix::aat_match#SYNOPSIS |
| Catmandu::Fix::aat_search | Perform a search for a term in the AAT| https://metacpan.org/pod/Catmandu::Fix::aat_search#SYNOPSIS |
| Catmandu::Fix::aat_search | Perform a search for a term in the AAT| https://metacpan.org/pod/Catmandu::Fix::aat_search#SYNOPSIS |
| Catmandu::Fix::add | shortcut for Catmandu::Fix::add_field| https://metacpan.org/pod/Catmandu::Fix::add#SYNOPSIS |
| Catmandu::Fix::add_field | add or change the value of a HASH key or ARRAY index| https://metacpan.org/pod/Catmandu::Fix::add_field#SYNOPSIS |
| Catmandu::Fix::add_to_exporter | Export a record as side effect| https://metacpan.org/pod/Catmandu::Fix::add_to_exporter#SYNOPSIS |
| Catmandu::Fix::add_to_store | add matching values to a store as a side effect| https://metacpan.org/pod/Catmandu::Fix::add_to_store#SYNOPSIS |
| Catmandu::Fix::append | add a suffix to the value of a field| https://metacpan.org/pod/Catmandu::Fix::append#SYNOPSIS |
| Catmandu::Fix::aref_query | copy values of RDF in aREF to a new field| https://metacpan.org/pod/Catmandu::Fix::aref_query#SYNOPSIS |
| Catmandu::Fix::array | creates an array out of a hash| https://metacpan.org/pod/Catmandu::Fix::array#SYNOPSIS |
| Catmandu::Fix::assoc | associate two values as a hash key and value| https://metacpan.org/pod/Catmandu::Fix::assoc#SYNOPSIS |
| Catmandu::Fix::basename | get file basename| https://metacpan.org/pod/Catmandu::Fix::basename#SYNOPSIS |
| Catmandu::Fix::capitalize | capitalize the value of a key| https://metacpan.org/pod/Catmandu::Fix::capitalize#SYNOPSIS |
| Catmandu::Fix::clone | create a clone of the data object| https://metacpan.org/pod/Catmandu::Fix::clone#SYNOPSIS |
| Catmandu::Fix::cmd | pipe data to be fixed through an external process| https://metacpan.org/pod/Catmandu::Fix::cmd#SYNOPSIS |
| Catmandu::Fix::code | run arbitrary code as fix| https://metacpan.org/pod/Catmandu::Fix::code#SYNOPSIS |
| Catmandu::Fix::collapse | convert nested data into a flat hash using the TT2 dot convention| https://metacpan.org/pod/Catmandu::Fix::collapse#SYNOPSIS |
| Catmandu::Fix::compact | remove undefined values from an array| https://metacpan.org/pod/Catmandu::Fix::compact#SYNOPSIS |
| Catmandu::Fix::copy | shortcut for Catmandu::Fix::copy_field| https://metacpan.org/pod/Catmandu::Fix::copy#SYNOPSIS |
| Catmandu::Fix::copy_field | copy the value of one field to a new field| https://metacpan.org/pod/Catmandu::Fix::copy_field#SYNOPSIS |
| Catmandu::Fix::count | replace the value of an array or hash field with its count| https://metacpan.org/pod/Catmandu::Fix::count#SYNOPSIS |
| Catmandu::Fix::datetime_diff | Catmandu Fix to compute difference in seconds between two datetimes| https://metacpan.org/pod/Catmandu::Fix::datetime_diff#SYNOPSIS |
| Catmandu::Fix::datetime_format | Catmandu Fix for converting between datetime formats| https://metacpan.org/pod/Catmandu::Fix::datetime_format#SYNOPSIS |
| Catmandu::Fix::dirname | get file directory| https://metacpan.org/pod/Catmandu::Fix::dirname#SYNOPSIS |
| Catmandu::Fix::downcase | lowercase the value of a field| https://metacpan.org/pod/Catmandu::Fix::downcase#SYNOPSIS |
| Catmandu::Fix::end_day | Catmandu Fix retrieving date string for end of the current day| https://metacpan.org/pod/Catmandu::Fix::end_day#SYNOPSIS |
| Catmandu::Fix::end_week | Catmandu Fix for retrieving date string for end of the current week| https://metacpan.org/pod/Catmandu::Fix::end_week#SYNOPSIS |
| Catmandu::Fix::end_year | Catmandu Fix for retrieving date string for end of the current year| https://metacpan.org/pod/Catmandu::Fix::end_year#SYNOPSIS |
| Catmandu::Fix::epmc_dblinks | converts the nested hash from EuropePMC in a nice form and provides the url to the database entry| https://metacpan.org/pod/Catmandu::Fix::epmc_dblinks#SYNOPSIS |
| Catmandu::Fix::error | die with an error message| https://metacpan.org/pod/Catmandu::Fix::error#SYNOPSIS |
| Catmandu::Fix::expand | convert a flat hash into nested data using the TT2 dot convention| https://metacpan.org/pod/Catmandu::Fix::expand#SYNOPSIS |
| Catmandu::Fix::expand_date | expand a date field into year, month and date| https://metacpan.org/pod/Catmandu::Fix::expand_date#SYNOPSIS |
| Catmandu::Fix::export_to_string | convert the value of field using a named exporter| https://metacpan.org/pod/Catmandu::Fix::export_to_string#SYNOPSIS |
| Catmandu::Fix::file_size | get file size| https://metacpan.org/pod/Catmandu::Fix::file_size#SYNOPSIS |
| Catmandu::Fix::file_stat | get file status information| https://metacpan.org/pod/Catmandu::Fix::file_stat#SYNOPSIS |
| Catmandu::Fix::filter | Filter values out of an array based on a regular expression| https://metacpan.org/pod/Catmandu::Fix::filter#SYNOPSIS |
| Catmandu::Fix::flatten | flatten a nested array field| https://metacpan.org/pod/Catmandu::Fix::flatten#SYNOPSIS |
| Catmandu::Fix::format | replace the value with a formatted (sprintf-like) version| https://metacpan.org/pod/Catmandu::Fix::format#SYNOPSIS |
| Catmandu::Fix::from_json | replace a json field with the parsed value| https://metacpan.org/pod/Catmandu::Fix::from_json#SYNOPSIS |
| Catmandu::Fix::geocode | Provide access to the Google geocoding API| https://metacpan.org/pod/Catmandu::Fix::geocode#SYNOPSIS |
| Catmandu::Fix::get_json | get JSON data from an URL as fix function| https://metacpan.org/pod/Catmandu::Fix::get_json#SYNOPSIS |
| Catmandu::Fix::hash | creates a hash out of an array| https://metacpan.org/pod/Catmandu::Fix::hash#SYNOPSIS |
| Catmandu::Fix::html_filter_tag | filter html tags| https://metacpan.org/pod/Catmandu::Fix::html_filter_tag#SYNOPSIS |
| Catmandu::Fix::html_filter_type | filter html on type type| https://metacpan.org/pod/Catmandu::Fix::html_filter_type#SYNOPSIS |
| Catmandu::Fix::html_text | keep only the textual data in the HTML| https://metacpan.org/pod/Catmandu::Fix::html_text#SYNOPSIS |
| Catmandu::Fix::human_byte_size | convert from size in bytes to human readable form| https://metacpan.org/pod/Catmandu::Fix::human_byte_size#SYNOPSIS |
| Catmandu::Fix::import | change the value of a HASH key or ARRAY index by replacing its value with imported data| https://metacpan.org/pod/Catmandu::Fix::import#SYNOPSIS |
| Catmandu::Fix::import_from_string | Import data from a string into an array ref, using a named importer.| https://metacpan.org/pod/Catmandu::Fix::import_from_string#SYNOPSIS |
| Catmandu::Fix::include | include fixes from another file| https://metacpan.org/pod/Catmandu::Fix::include#SYNOPSIS |
| Catmandu::Fix::index | Find all positions of a (sub)string in a field| https://metacpan.org/pod/Catmandu::Fix::index#SYNOPSIS |
| Catmandu::Fix::int | convert a value to an integer| https://metacpan.org/pod/Catmandu::Fix::int#SYNOPSIS |
| Catmandu::Fix::isbn10 | normalize the isbn value of a key in 10-digit form| https://metacpan.org/pod/Catmandu::Fix::isbn10#SYNOPSIS |
| Catmandu::Fix::isbn13 | normalize the isbn value of a key in 13-digit form| https://metacpan.org/pod/Catmandu::Fix::isbn13#SYNOPSIS |
| Catmandu::Fix::isbn_versions | provide different forms for an ISBN| https://metacpan.org/pod/Catmandu::Fix::isbn_versions#SYNOPSIS |
| Catmandu::Fix::issn | normalize the issn value for a given key| https://metacpan.org/pod/Catmandu::Fix::issn#SYNOPSIS |
| Catmandu::Fix::join | shortcut for Catmandu::Fix::join_field| https://metacpan.org/pod/Catmandu::Fix::join#SYNOPSIS |
| Catmandu::Fix::join_field | join the ARRAY values of a field into a string| https://metacpan.org/pod/Catmandu::Fix::join_field#SYNOPSIS |
| Catmandu::Fix::lido_actor | create a LIDO actorInRole node at a specified path| https://metacpan.org/pod/Catmandu::Fix::lido_actor#SYNOPSIS |
| Catmandu::Fix::lido_baseid | Create a basic id component in a path| https://metacpan.org/pod/Catmandu::Fix::lido_baseid#SYNOPSIS |
| Catmandu::Fix::lido_basenameset | Create a basic nameset in a path| https://metacpan.org/pod/Catmandu::Fix::lido_basenameset#SYNOPSIS |
| Catmandu::Fix::lido_basevalue | Create a basic XML node in a path| https://metacpan.org/pod/Catmandu::Fix::lido_basevalue#SYNOPSIS |
| Catmandu::Fix::lido_classification | create an objectClassificationWrap.| https://metacpan.org/pod/Catmandu::Fix::lido_classification#SYNOPSIS |
| Catmandu::Fix::lido_date | create a generic date component in path| https://metacpan.org/pod/Catmandu::Fix::lido_date#SYNOPSIS |
| Catmandu::Fix::lido_descriptivenote | create a descriptiveNoteValue in a path| https://metacpan.org/pod/Catmandu::Fix::lido_descriptivenote#SYNOPSIS |
| Catmandu::Fix::lido_inscription | create a inscriptions node| https://metacpan.org/pod/Catmandu::Fix::lido_inscription#SYNOPSIS |
| Catmandu::Fix::lido_objectmeasurements | Create a objectMeasurements node| https://metacpan.org/pod/Catmandu::Fix::lido_objectmeasurements#SYNOPSIS |
| Catmandu::Fix::lido_term | create a term and conceptID node in a path| https://metacpan.org/pod/Catmandu::Fix::lido_term#SYNOPSIS |
| Catmandu::Fix::log | Log::Any logger as fix| https://metacpan.org/pod/Catmandu::Fix::log#SYNOPSIS |
| Catmandu::Fix::lookup | change the value of a HASH key or ARRAY index by looking up its value in a dictionary| https://metacpan.org/pod/Catmandu::Fix::lookup#SYNOPSIS |
| Catmandu::Fix::lookup_in_store | change the value of a HASH key or ARRAY index by looking up its value in a store| https://metacpan.org/pod/Catmandu::Fix::lookup_in_store#SYNOPSIS |
| Catmandu::Fix::mab_map | copy mab values of one field to a new field| https://metacpan.org/pod/Catmandu::Fix::mab_map#SYNOPSIS |
| Catmandu::Fix::make_pid | Use the Resolver to create/retrieve a PID for a record| https://metacpan.org/pod/Catmandu::Fix::make_pid#SYNOPSIS |
| Catmandu::Fix::marc_add | add new fields to marc| https://metacpan.org/pod/Catmandu::Fix::marc_add#SYNOPSIS |
| Catmandu::Fix::marc_append | add a value at the end of a MARC field| https://metacpan.org/pod/Catmandu::Fix::marc_append#SYNOPSIS |
| Catmandu::Fix::marc_copy | copy marc data in a structured way to a new field| https://metacpan.org/pod/Catmandu::Fix::marc_copy#SYNOPSIS |
| Catmandu::Fix::marc_cut | cut marc data in a structured way to a new field| https://metacpan.org/pod/Catmandu::Fix::marc_cut#SYNOPSIS |
| Catmandu::Fix::marc_decode_dollar_subfields | decode double encoded dollar subfields| https://metacpan.org/pod/Catmandu::Fix::marc_decode_dollar_subfields#SYNOPSIS |
| Catmandu::Fix::marc_in_json | transform a Catmandu MARC record into MARC-in-JSON| https://metacpan.org/pod/Catmandu::Fix::marc_in_json#SYNOPSIS |
| Catmandu::Fix::marc_map | copy marc values of one field to a new field| https://metacpan.org/pod/Catmandu::Fix::marc_map#SYNOPSIS |
| Catmandu::Fix::marc_paste | paste a MARC structured field back into the MARC record| https://metacpan.org/pod/Catmandu::Fix::marc_paste#SYNOPSIS |
| Catmandu::Fix::marc_remove | remove marc (sub)fields| https://metacpan.org/pod/Catmandu::Fix::marc_remove#SYNOPSIS |
| Catmandu::Fix::marc_replace_all | regex replace (sub)field values in a MARC file| https://metacpan.org/pod/Catmandu::Fix::marc_replace_all#SYNOPSIS |
| Catmandu::Fix::marc_set | set a marc value of one (sub)field to a new value| https://metacpan.org/pod/Catmandu::Fix::marc_set#SYNOPSIS |
| Catmandu::Fix::marc_spec | reference MARC values via MARCspec - A common MARC record path language| https://metacpan.org/pod/Catmandu::Fix::marc_spec#SYNOPSIS |
| Catmandu::Fix::marc_xml | transform a Catmandu MARC record into MARCXML| https://metacpan.org/pod/Catmandu::Fix::marc_xml#SYNOPSIS |
| Catmandu::Fix::markdown_to_html | converts markdown to html elements| https://metacpan.org/pod/Catmandu::Fix::markdown_to_html#SYNOPSIS |
| Catmandu::Fix::memento_find | find Mementos for a url| https://metacpan.org/pod/Catmandu::Fix::memento_find#SYNOPSIS |
| Catmandu::Fix::move | shortcut for Catmandu::Fix::move_field| https://metacpan.org/pod/Catmandu::Fix::move#SYNOPSIS |
| Catmandu::Fix::move_field | move a field to another place in the data structure| https://metacpan.org/pod/Catmandu::Fix::move_field#SYNOPSIS |
| Catmandu::Fix::nothing | does nothing (for testing)| https://metacpan.org/pod/Catmandu::Fix::nothing#SYNOPSIS |
| Catmandu::Fix::orcid_bio | find an ORCID bio for an identifier| https://metacpan.org/pod/Catmandu::Fix::orcid_bio#SYNOPSIS |
| Catmandu::Fix::orcid_find | find ORCID id for an query| https://metacpan.org/pod/Catmandu::Fix::orcid_find#SYNOPSIS |
| Catmandu::Fix::orcid_profile | find an ORCID profile for an identifier| https://metacpan.org/pod/Catmandu::Fix::orcid_profile#SYNOPSIS |
| Catmandu::Fix::orcid_works | find ORCID works for an identifier| https://metacpan.org/pod/Catmandu::Fix::orcid_works#SYNOPSIS |
| Catmandu::Fix::parse_text | parses a text into an array or hash of values| https://metacpan.org/pod/Catmandu::Fix::parse_text#SYNOPSIS |
| Catmandu::Fix::paste | concatenate path values| https://metacpan.org/pod/Catmandu::Fix::paste#SYNOPSIS |
| Catmandu::Fix::perlcode | execute Perl code as fix function| https://metacpan.org/pod/Catmandu::Fix::perlcode#SYNOPSIS |
| Catmandu::Fix::pica_add | add new subfields to record| https://metacpan.org/pod/Catmandu::Fix::pica_add#SYNOPSIS |
| Catmandu::Fix::pica_map | copy pica values of one field to a new field| https://metacpan.org/pod/Catmandu::Fix::pica_map#SYNOPSIS |
| Catmandu::Fix::pica_set | sets a new value to an existing subfield| https://metacpan.org/pod/Catmandu::Fix::pica_set#SYNOPSIS |
| Catmandu::Fix::prepend | add a prefix to the value of a field| https://metacpan.org/pod/Catmandu::Fix::prepend#SYNOPSIS |
| Catmandu::Fix::random | create an random number in a field| https://metacpan.org/pod/Catmandu::Fix::random#SYNOPSIS |
| Catmandu::Fix::rdf_ldf_statements | lookup an object into a LDF endpoint| https://metacpan.org/pod/Catmandu::Fix::rdf_ldf_statements#SYNOPSIS |
| Catmandu::Fix::reject | remove a record form the data| https://metacpan.org/pod/Catmandu::Fix::reject#SYNOPSIS |
| Catmandu::Fix::remove | shortcut for Catmandu::Fix::remove_field| https://metacpan.org/pod/Catmandu::Fix::remove#SYNOPSIS |
| Catmandu::Fix::remove_field | remove a field form the data| https://metacpan.org/pod/Catmandu::Fix::remove_field#SYNOPSIS |
| Catmandu::Fix::rename | rename fields with a regex| https://metacpan.org/pod/Catmandu::Fix::rename#SYNOPSIS |
| Catmandu::Fix::replace_all | search and replace using regex expressions| https://metacpan.org/pod/Catmandu::Fix::replace_all#SYNOPSIS |
| Catmandu::Fix::retain | delete everything except the paths given| https://metacpan.org/pod/Catmandu::Fix::retain#SYNOPSIS |
| Catmandu::Fix::retain_field | delete everything from a field except| https://metacpan.org/pod/Catmandu::Fix::retain_field#SYNOPSIS |
| Catmandu::Fix::reverse | reverse a string or an array| https://metacpan.org/pod/Catmandu::Fix::reverse#SYNOPSIS |
| Catmandu::Fix::reverse_geocode | Provide access to the Google geocoding API| https://metacpan.org/pod/Catmandu::Fix::reverse_geocode#SYNOPSIS |
| Catmandu::Fix::rkd_name | Retrieve items from the RKD by name| https://metacpan.org/pod/Catmandu::Fix::rkd_name#SYNOPSIS |
| Catmandu::Fix::rkd_name | Retrieve items from the RKD by name| https://metacpan.org/pod/Catmandu::Fix::rkd_name#SYNOPSIS |
| Catmandu::Fix::search_in_store | use the value as query, and replace it by a search object| https://metacpan.org/pod/Catmandu::Fix::search_in_store#SYNOPSIS |
| Catmandu::Fix::set | shortcut for Catmandu::Fix::set_field| https://metacpan.org/pod/Catmandu::Fix::set#SYNOPSIS |
| Catmandu::Fix::set_array | add or change the value of a HASH key or ARRAY index to an array| https://metacpan.org/pod/Catmandu::Fix::set_array#SYNOPSIS |
| Catmandu::Fix::set_field | add or change the value of a HASH key or ARRAY index| https://metacpan.org/pod/Catmandu::Fix::set_field#SYNOPSIS |
| Catmandu::Fix::set_hash | add or change the value of a HASH key or ARRAY index to a hash| https://metacpan.org/pod/Catmandu::Fix::set_hash#SYNOPSIS |
| Catmandu::Fix::sfx_threshold | parse the SFX threshold data| https://metacpan.org/pod/Catmandu::Fix::sfx_threshold#SYNOPSIS |
| Catmandu::Fix::sfx_year_range | parse the SFX threshold data| https://metacpan.org/pod/Catmandu::Fix::sfx_year_range#SYNOPSIS |
| Catmandu::Fix::sleep | Do nothing for a specified amount of time| https://metacpan.org/pod/Catmandu::Fix::sleep#SYNOPSIS |
| Catmandu::Fix::sort | shortcut for Catmandu::Fix::sort_field| https://metacpan.org/pod/Catmandu::Fix::sort#SYNOPSIS |
| Catmandu::Fix::sort_field | sort the values of an array| https://metacpan.org/pod/Catmandu::Fix::sort_field#SYNOPSIS |
| Catmandu::Fix::split | shortcut for Catmandu::Fix::split_field| https://metacpan.org/pod/Catmandu::Fix::split#SYNOPSIS |
| Catmandu::Fix::split_date | split a date field into year, month and date| https://metacpan.org/pod/Catmandu::Fix::split_date#SYNOPSIS |
| Catmandu::Fix::split_field | split a string value in a field into an ARRAY| https://metacpan.org/pod/Catmandu::Fix::split_field#SYNOPSIS |
| Catmandu::Fix::start_day | Catmandu Fix for retrieving date string for start of the current day| https://metacpan.org/pod/Catmandu::Fix::start_day#SYNOPSIS |
| Catmandu::Fix::start_week | Catmandu Fix for retrieving date string for start of the current week| https://metacpan.org/pod/Catmandu::Fix::start_week#SYNOPSIS |
| Catmandu::Fix::start_year | Catmandu Fix for retrieving date string for start of the current year| https://metacpan.org/pod/Catmandu::Fix::start_year#SYNOPSIS |
| Catmandu::Fix::stat_mean | calculate the mean of an array| https://metacpan.org/pod/Catmandu::Fix::stat_mean#SYNOPSIS |
| Catmandu::Fix::stat_median | calculate the median of an array| https://metacpan.org/pod/Catmandu::Fix::stat_median#SYNOPSIS |
| Catmandu::Fix::stat_mode | calculate the mode of an array| https://metacpan.org/pod/Catmandu::Fix::stat_mode#SYNOPSIS |
| Catmandu::Fix::stat_stddev | calculate the standard deviation of an array| https://metacpan.org/pod/Catmandu::Fix::stat_stddev#SYNOPSIS |
| Catmandu::Fix::stat_variance | calculate the variance of an array| https://metacpan.org/pod/Catmandu::Fix::stat_variance#SYNOPSIS |
| Catmandu::Fix::string | convert a value to a string| https://metacpan.org/pod/Catmandu::Fix::string#SYNOPSIS |
| Catmandu::Fix::substring | extract a substring out of the value of a field| https://metacpan.org/pod/Catmandu::Fix::substring#SYNOPSIS |
| Catmandu::Fix::sum | replace the value of an array field with the sum of its elements| https://metacpan.org/pod/Catmandu::Fix::sum#SYNOPSIS |
| Catmandu::Fix::template | add a value to the record based on a template| https://metacpan.org/pod/Catmandu::Fix::template#SYNOPSIS |
| Catmandu::Fix::timestamp | Catmandu fix that stores the current unix time, in high resolution| https://metacpan.org/pod/Catmandu::Fix::timestamp#SYNOPSIS |
| Catmandu::Fix::to_json | convert the value of a field to json| https://metacpan.org/pod/Catmandu::Fix::to_json#SYNOPSIS |
| Catmandu::Fix::trim | trim leading and ending junk from the value of a field| https://metacpan.org/pod/Catmandu::Fix::trim#SYNOPSIS |
| Catmandu::Fix::uniq | strip duplicate values from an array| https://metacpan.org/pod/Catmandu::Fix::uniq#SYNOPSIS |
| Catmandu::Fix::upcase | uppercase the value of a field| https://metacpan.org/pod/Catmandu::Fix::upcase#SYNOPSIS |
| Catmandu::Fix::uri_decode | percent decode a URI| https://metacpan.org/pod/Catmandu::Fix::uri_decode#SYNOPSIS |
| Catmandu::Fix::uri_encode | percent encode a URI| https://metacpan.org/pod/Catmandu::Fix::uri_encode#SYNOPSIS |
| Catmandu::Fix::uri_status_code | check the HTTP status of a uri| https://metacpan.org/pod/Catmandu::Fix::uri_status_code#SYNOPSIS |
| Catmandu::Fix::uuid | create a Globally/Universally Unique Identifier| https://metacpan.org/pod/Catmandu::Fix::uuid#SYNOPSIS |
| Catmandu::Fix::vacuum | delete all empty fields from your data| https://metacpan.org/pod/Catmandu::Fix::vacuum#SYNOPSIS |
| Catmandu::Fix::validate | validate data and keep errors| https://metacpan.org/pod/Catmandu::Fix::validate#SYNOPSIS |
| Catmandu::Fix::viaf_match | Perform a direct match between a name and a mainHeadingEl from VIAF| https://metacpan.org/pod/Catmandu::Fix::viaf_match#SYNOPSIS |
| Catmandu::Fix::viaf_match_id | Fetch the RDF representation of a person based on his/her VIAF ID.| https://metacpan.org/pod/Catmandu::Fix::viaf_match_id#SYNOPSIS |
| Catmandu::Fix::viaf_read | query the OCLC VIAF service| https://metacpan.org/pod/Catmandu::Fix::viaf_read#SYNOPSIS |
| Catmandu::Fix::viaf_search | Perform a search for a name in VIAF| https://metacpan.org/pod/Catmandu::Fix::viaf_search#SYNOPSIS |
| Catmandu::Fix::wd_language | Limit string values in a Wikidata entity record to a selected language| https://metacpan.org/pod/Catmandu::Fix::wd_language#SYNOPSIS |
| Catmandu::Fix::wd_simple | Simplify Wikidata entity records| https://metacpan.org/pod/Catmandu::Fix::wd_simple#SYNOPSIS |
| Catmandu::Fix::wd_simple_claims | Simplify claims of a Wikidata entity record| https://metacpan.org/pod/Catmandu::Fix::wd_simple_claims#SYNOPSIS |
| Catmandu::Fix::wd_simple_strings | Simplify labels, descriptions, and aliases of Wikidata entity records| https://metacpan.org/pod/Catmandu::Fix::wd_simple_strings#SYNOPSIS |
| Catmandu::Fix::xID | query the OCLC xID service| https://metacpan.org/pod/Catmandu::Fix::xID#SYNOPSIS |
| Catmandu::Fix::xml_read | parse XML to MicroXML| https://metacpan.org/pod/Catmandu::Fix::xml_read#SYNOPSIS |
| Catmandu::Fix::xml_simple | parse/convert XML to simple form| https://metacpan.org/pod/Catmandu::Fix::xml_simple#SYNOPSIS |
| Catmandu::Fix::xml_transform | transform XML using XSLT stylesheet| https://metacpan.org/pod/Catmandu::Fix::xml_transform#SYNOPSIS |
| Catmandu::Fix::xml_write | serialize XML| https://metacpan.org/pod/Catmandu::Fix::xml_write#SYNOPSIS |
| Catmandu::Fix::xpath_map | map values from a XML::LibXML::Element value to a field| https://metacpan.org/pod/Catmandu::Fix::xpath_map#SYNOPSIS |
