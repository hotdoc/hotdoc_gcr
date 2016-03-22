### GcrParser

Parser for certificate and key files

 A [](GcrParser) can parse various certificate and key files such as OpenSSL
 PEM files, DER encoded certifictes, PKCS\[](8) keys and so on. Each various
 format is identified by a value in the [](GcrDataFormat) enumeration.

 In order to parse data, a new parser is created with [](gcr_parser_new) and
 then the [](GcrParser::authenticate) and [](GcrParser::parsed) signals should be
 connected to. Data is then fed to the parser via [](gcr_parser_parse_data)
 or [](gcr_parser_parse_stream).

 During the [](GcrParser::parsed) signal the attributes that make up the currently
 parsed item can be retrieved using the [](gcr_parser_get_parsed_attributes)
 function.

* [gcr_parser_format_supported]()
* [GcrDataFormat]()
* [gcr_parser_set_filename]()
* [gcr_parsed_unref]()
* [gcr_parsed_get_data]()
* [gcr_parser_get_parsed_attributes]()
* [gcr_parser_format_disable]()
* [gcr_parsed_get_description]()
* [gcr_parser_parse_bytes]()
* [gcr_parser_get_parsed_format]()
* [gcr_parser_get_filename]()
* [gcr_parser_add_password]()
* [gcr_parsed_ref]()
* [gcr_parser_new]()
* [gcr_parser_get_parsed_label]()
* [GcrDataError]()
* [gcr_parser_parse_stream_finish]()
* [gcr_parsed_get_bytes]()
* [gcr_parser_get_parsed_bytes]()
* [gcr_parser_parse_stream_async]()
* [gcr_parser_parse_stream]()
* [gcr_parser_get_parsed]()
* [GcrParserClass]()
* [GcrParsed]()
* [gcr_parser_format_enable]()
* [gcr_parsed_get_filename]()
* [gcr_parser_get_parsed_description]()
* [GcrParser]()
* [GCR_DATA_ERROR]()
* [gcr_parser_parse_data]()
* [gcr_parsed_get_format]()
* [gcr_parser_get_parsed_block]()
* [gcr_parsed_get_attributes]()
* [gcr_parsed_get_label]()
