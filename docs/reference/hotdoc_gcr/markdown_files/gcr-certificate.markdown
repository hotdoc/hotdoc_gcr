### GcrCertificate

Represents an X.509 certificate

 This is an interface that represents an X.509 certificate. Objects can
 implement this interface to make a certificate usable with the GCR
 library.

 Various methods are available to parse out relevant bits of the certificate.
 However no verification of the validity of a certificate is done here. Use
 your favorite crypto library to do this.

 You can use [](GcrSimpleCertificate) to simply load a certificate for which
 you already have the raw certificate data.

 The [](GcrCertificate) interface has several properties that must be implemented.
 You can use a mixin to implement these properties if desired. See the
 [](gcr_certificate_mixin_class_init) and [](gcr_certificate_mixin_get_property)
 functions.

 All certificates are comparable. If implementing a [](GcrCertificate), you can
 use [](GCR_CERTIFICATE_MIXIN_IMPLEMENT_COMPARABLE) to implement the [](GcrComparable)
 interface.

* [gcr_certificate_get_issuer_cn]()
* [GCR_CERTIFICATE_MIXIN_IMPLEMENT_COMPARABLE]()
* [gcr_certificate_get_expiry_date]()
* [GcrCertificate]()
* [gcr_certificate_get_basic_constraints]()
* [gcr_certificate_mixin_get_property]()
* [gcr_certificate_get_subject_dn]()
* [gcr_certificate_get_subject_cn]()
* [gcr_certificate_get_issuer_raw]()
* [GcrCertificateIface]()
* [gcr_certificate_get_issuer_part]()
* [gcr_certificate_get_der_data]()
* [gcr_certificate_get_key_size]()
* [gcr_certificate_mixin_comparable_init]()
* [gcr_certificate_get_serial_number]()
* [gcr_certificate_is_issuer]()
* [gcr_certificate_mixin_class_init]()
* [gcr_certificate_mixin_emit_notify]()
* [gcr_certificate_get_subject_name]()
* [gcr_certificate_get_fingerprint]()
* [gcr_certificate_get_issuer_dn]()
* [gcr_certificate_get_subject_part]()
* [gcr_certificate_get_markup_text]()
* [gcr_certificate_get_serial_number_hex]()
* [gcr_certificate_get_fingerprint_hex]()
* [gcr_certificate_get_issuer_name]()
* [gcr_certificate_get_icon]()
* [gcr_certificate_get_subject_raw]()
* [gcr_certificate_get_issued_date]()
* [gcr_certificate_compare]()
