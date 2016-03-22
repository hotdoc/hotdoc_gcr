### GcrKeyWidget

Key widget and renderer

 A [](GcrKeyWidget) can be used to display a RSA, DSA or EC key. The widget
 is normally in a collapsed state showing only details, but can be expanded
 by the user.

 Use [](gcr_key_widget_new) to create a new key widget. Only
 one key can be displayed.  A [](GcrKeyWidget) contains a
 [](GcrViewer) internally and [](GcrKeyRenderer) is used to render the
 key to the viewer. To show more than one key in a view,
 create the viewer and add renderers to it.

* [GcrKeyWidget]()
* [gcr_key_widget_new]()
* [gcr_key_renderer_new]()
* [gcr_key_renderer_get_attributes]()
* [gcr_key_renderer_set_attributes]()
* [GcrKeyWidgetClass]()
* [gcr_key_widget_set_attributes]()
* [gcr_key_widget_get_attributes]()
* [GcrKeyRendererClass]()
* [GcrKeyRenderer]()
