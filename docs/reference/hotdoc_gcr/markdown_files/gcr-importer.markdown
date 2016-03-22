### GcrImporter

Import certificates and keys

 An interface which allows importing of certificates and keys. Each
 [](GcrImporter) is registered with a set of PKCS\[](11) attributes to match
 stuff that it can import.

 An importer gets passed a [](GcrParser) and accesses the currently parsed
 item. To create a set of importers that can import the currently parsed
 item in a [](GcrParser), use [](gcr_importer_create_for_parsed). The list of
 importers returned has the parsed item queued for import.

 To queue additional items with a importer use [](gcr_importer_queue_for_parsed).
 In addition you can try and queue an additional item with a set of importers
 using the [](gcr_importer_queue_and_filter_for_parsed).

 To start the import use [](gcr_importer_import) or the async variants.

* [GcrImporter]()
* [gcr_importer_register]()
* [gcr_importer_import_async]()
* [GcrImporterIface]()
* [gcr_importer_get_interaction]()
* [gcr_importer_register_well_known]()
* [gcr_importer_import_finish]()
* [gcr_importer_queue_and_filter_for_parsed]()
* [gcr_importer_queue_for_parsed]()
* [gcr_importer_import]()
* [gcr_importer_set_interaction]()
* [gcr_importer_create_for_parsed]()
