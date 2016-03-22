### GcrCollection

A collection of objects.

 A [](GcrCollection) is used to group a set of objects. This is an abstract
 interface which can be used to determine which objects show up in a selector
 or other user interface element.

 Use [](gcr_simple_collection_new) to create a concrete implementation of this
 interface which you can add objects to.

* [gcr_collection_get_length]()
* [gcr_collection_get_objects]()
* [gcr_collection_emit_removed]()
* [gcr_collection_contains]()
* [gcr_collection_emit_added]()
* [GcrCollection]()
