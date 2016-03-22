### GcrRenderer

An interface implemented by renderers.

 A [](GcrRenderer) is an interface that's implemented by renderers which wish
 to render data to a [](GcrViewer).

 The interaction between [](GcrRenderer) and [](GcrViewer) is not stable yet, and
 so new renderers cannot be implemented outside the Gcr library at this time.

 To lookup a renderer for a given set of attributes, use the [](gcr_renderer_create)
 function. This will create and initialize a renderer that's capable of viewing
 the data in those attributes.

* [GcrRenderer]()
* [gcr_renderer_register_well_known]()
* [gcr_renderer_popuplate_popup]()
* [gcr_renderer_register]()
* [GcrRendererIface]()
* [gcr_renderer_get_attributes]()
* [gcr_renderer_render_view]()
* [gcr_renderer_set_attributes]()
* [gcr_renderer_emit_data_changed]()
* [gcr_renderer_create]()
