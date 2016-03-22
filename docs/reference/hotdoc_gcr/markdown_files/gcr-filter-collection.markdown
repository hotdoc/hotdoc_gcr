### GcrFilterCollection

A collection which filters a GcrCollection

 An implementation of [](GcrCollection) which filters objects from another
 underlying collection. Use [](gcr_filter_collection_new_with_callback)
 to create a new filter collection.

 The callback will determine the criteria for whether an object shows through
 the filter or not.

* [gcr_filter_collection_get_underlying]()
* [gcr_filter_collection_refilter]()
* [GcrFilterCollectionFunc]()
* [gcr_filter_collection_new_with_callback]()
* [GcrFilterCollection]()
* [gcr_filter_collection_set_callback]()
* [GcrFilterCollectionClass]()
