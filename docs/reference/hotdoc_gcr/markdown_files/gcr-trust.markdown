### Trust Storage and Lookups

Store and lookup bits of information used for
 verifying certificates.

 These functions provide access to stored information about which
 certificates the system and user trusts as certificate authority trust
 anchors, or overrides to the normal verification of certificates.

 Trust anchors are used to verify the certificate authority in a certificate
 chain. Trust anchors are always valid for a given purpose. The most common
 purpose is the [](GCR_PURPOSE_SERVER_AUTH) and is used for a client application
 to verify that the certificate at the server side of a TLS connection is
 authorized to act as such. To check if a certificate is a trust anchor use
 [](gcr_trust_is_certificate_anchored).

 Pinned certificates are used when a user overrides the default trust
 decision for a given certificate. They're often used with self-signed
 certificates. Pinned certificates are always only valid for a single peer
 such as the remote host with which TLS is being performed. To lookup
 pinned certificates use [](gcr_trust_is_certificate_pinned).

 After the user has requested to override the trust decision
 about a given certificate then a pinned certificates can be added by using
 the [](gcr_trust_add_pinned_certificate) function.

 These functions do not constitute a viable method for verifying certificates
 used in TLS or other locations. Instead they support such verification
 by providing some of the needed data for a trust decision.

 The storage is provided by pluggable PKCS\[](11) modules.

* [gcr_trust_is_certificate_pinned]()
* [gcr_trust_is_certificate_anchored_finish]()
* [gcr_trust_is_certificate_pinned_finish]()
* [GCR_PURPOSE_SERVER_AUTH]()
* [gcr_trust_is_certificate_anchored_async]()
* [gcr_trust_is_certificate_anchored]()
* [GCR_PURPOSE_CLIENT_AUTH]()
* [gcr_trust_is_certificate_pinned_async]()
* [gcr_trust_add_pinned_certificate]()
* [gcr_trust_remove_pinned_certificate]()
* [gcr_trust_remove_pinned_certificate_finish]()
* [gcr_trust_add_pinned_certificate_async]()
* [gcr_trust_add_pinned_certificate_finish]()
* [GCR_PURPOSE_EMAIL]()
* [GCR_PURPOSE_CODE_SIGNING]()
* [gcr_trust_remove_pinned_certificate_async]()
