### GcrCertificateRequest

Represents a certificate request

 This is an object that allows creation of certificate requests. A
 certificate request is sent to a certificate authority to request an
 X.509 certificate.

 Use [](gcr_certificate_request_prepare) to create a blank certificate
 request for a given private key. Set the common name on the certificate
 request with [](gcr_certificate_request_set_cn), and then sign the request
 with [](gcr_certificate_request_complete_async).

* [GCR_CERTIFICATE_REQUEST]()
* [GCR_TYPE_CERTIFICATE_REQUEST_FORMAT]()
* [gcr_certificate_request_capable_async]()
* [gcr_certificate_request_get_private_key]()
* [gcr_certificate_request_capable_finish]()
* [gcr_certificate_request_encode]()
* [gcr_certificate_request_prepare]()
* [GCR_IS_CERTIFICATE_REQUEST]()
* [gcr_certificate_request_complete]()
* [gcr_certificate_request_complete_finish]()
* [gcr_certificate_request_set_cn]()
* [gcr_certificate_request_get_format]()
* [GcrCertificateRequestFormat]()
* [GCR_TYPE_CERTIFICATE_REQUEST]()
* [gcr_certificate_request_capable]()
* [gcr_certificate_request_format_get_type]()
* [GcrCertificateRequest]()
* [gcr_certificate_request_get_type]()
* [gcr_certificate_request_complete_async]()
