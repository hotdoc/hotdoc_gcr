### GcrCertificateChain

A certificate chain

 [](GcrCertificateChain) represents a chain of certificates, normally used to
 validate the trust in a certificate. An X.509 certificate chain has one
 endpoint certificate (the one for which trust is being verified) and then
 in turn the certificate that issued each previous certificate in the chain.

 This functionality is for building of certificate chains not for validating
 them. Use your favorite crypto library to validate trust in a certificate
 chain once its built.

 The order of certificates in the chain should be first the endpoint
 certificates and then the signing certificates.

 Create a new certificate chain with [](gcr_certificate_chain_new) and then
 add the certificates with [](gcr_certificate_chain_add).

 You can then use [](gcr_certificate_chain_build) to build the remainder of
 the chain. This will lookup missing certificates in PKCS\[](11) modules and
 also check that each certificate in the chain is the signer of the previous
 one. If a trust anchor, pinned certificate, or self-signed certificate is
 found, then the chain is considered built. Any extra certificates are
 removed from the chain.

 Once the certificate chain has been built, you can access its status
 through [](gcr_certificate_chain_get_status). The status signifies whether
 the chain is anchored on a trust root, self-signed, incomplete etc. See
 [](GcrCertificateChainStatus) for information on the various statuses.

 It's important to understand that the building of a certificate chain is
 merely the first step towards verifying trust in a certificate.

* [gcr_certificate_chain_get_status]()
* [gcr_certificate_chain_build]()
* [gcr_certificate_chain_get_endpoint]()
* [GcrCertificateChainClass]()
* [GcrCertificateChain]()
* [GCR_TYPE_CERTIFICATE_CHAIN_FLAGS]()
* [GcrCertificateChainStatus]()
* [gcr_certificate_chain_get_length]()
* [gcr_certificate_chain_new]()
* [gcr_certificate_chain_add]()
* [gcr_certificate_chain_get_anchor]()
* [gcr_certificate_chain_get_certificate]()
* [GCR_TYPE_CERTIFICATE_CHAIN_STATUS]()
* [gcr_certificate_chain_build_async]()
* [GcrCertificateChainFlags]()
* [gcr_certificate_chain_build_finish]()
