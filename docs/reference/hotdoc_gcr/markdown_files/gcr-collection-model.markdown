### GcrCollectionModel

A GtkTreeModel that represents a collection

 This is an implementation of [](GtkTreeModel) which represents the objects in
 the a [](GcrCollection). As objects are added or removed from the collection,
 rows are added and removed from this model.

 The row values come from the properties of the objects in the collection. Use
 [](gcr_collection_model_new) to create a new collection model. To have more
 control over the values use a set of [](GcrColumn) structures to define the
 columns. This can be done with [](gcr_collection_model_new_full) or
 [](gcr_collection_model_set_columns).

 Each row can have a selected state, which is represented by a boolean column.
 The selected state can be toggled with [](gcr_collection_model_toggle_selected)
 or set with [](gcr_collection_model_set_selected_objects) and retrieved with
 [](gcr_collection_model_get_selected_objects).

 To determine which object a row represents and vice versa, use the
 [](gcr_collection_model_iter_for_object) or [](gcr_collection_model_object_for_iter)
 functions.

* [gcr_collection_model_set_collection]()
* [GcrCollectionModel]()
* [GcrCollectionModelMode]()
* [gcr_collection_model_object_for_iter]()
* [gcr_collection_model_change_selected]()
* [gcr_collection_model_is_selected]()
* [gcr_collection_model_get_collection]()
* [gcr_collection_model_column_for_selected]()
* [gcr_collection_model_toggle_selected]()
* [gcr_collection_model_set_selected_objects]()
* [gcr_collection_model_get_selected_objects]()
* [gcr_collection_model_new]()
* [gcr_collection_model_iter_for_object]()
* [GcrCollectionModelClass]()
* [gcr_collection_model_new_full]()
* [gcr_collection_model_set_columns]()
