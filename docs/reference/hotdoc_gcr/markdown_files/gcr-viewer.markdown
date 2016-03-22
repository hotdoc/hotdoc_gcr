### GcrViewer

A viewer which can hold renderers

 A [](GcrViewer) is an abstract interface that represents a widget that can hold
 various renderers and display their contents.

 The interaction between [](GcrRenderer) and [](GcrViewer) is not stable yet, and
 so viewers cannot be implemented outside the Gcr library at this time.

 Use the [](gcr_viewer_new) and [](gcr_viewer_new_scrolled) to get default
 implementations of viewers.

* [gcr_viewer_count_renderers]()
* [gcr_viewer_new_scrolled]()
* [gcr_viewer_remove_renderer]()
* [GcrViewer]()
* [gcr_viewer_add_renderer]()
* [gcr_viewer_get_renderer]()
* [gcr_viewer_insert_renderer]()
* [GcrViewerIface]()
* [gcr_viewer_new]()
