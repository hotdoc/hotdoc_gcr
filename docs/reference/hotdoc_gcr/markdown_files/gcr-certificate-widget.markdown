### GcrCertificateWidget

Certificate widget and renderer

 A [](GcrCertificateWidget) can be used to display a certificate. The widget
 is normally in a collapsed state showing only details, but can be expanded
 by the user.

 Use [](gcr_certificate_widget_new) to create a new certificate widget. Only
 one certificate can be displayed.  A [](GcrCertificateWidget) contains a
 [](GcrViewer) internally and [](GcrCertificateRenderer) is used to render the
 certificate to the viewer. To show more than one certificate in a view,
 create the viewer and add renderers to it.

* [GcrCertificateWidget]()
* [gcr_certificate_widget_new]()
* [GCR_CERTIFICATE_COLUMNS]()
* [gcr_certificate_renderer_new_for_attributes]()
* [GcrCertificateRendererClass]()
* [GcrCertificateRenderer]()
* [gcr_certificate_renderer_set_certificate]()
* [GcrCertificateWidgetClass]()
* [gcr_certificate_renderer_get_certificate]()
* [gcr_certificate_widget_set_certificate]()
* [gcr_certificate_widget_get_certificate]()
* [gcr_certificate_renderer_new]()
