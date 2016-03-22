### Key Fingerprints

Fingerprints for public and private keys

 These functions generate key fingerprints for public keys, certificates and
 key data. The fingerprints are created so that they they will be identical
 for a key and its corresponding certificate.

 Note that in the case of certificates these are not fingerprints of the
 actual certificate data, but rather of the public key contained in a
 certificate.

 These fingerprints are created using the subjectPublicKeyInfo ASN.1 structure.

* [gcr_fingerprint_from_subject_public_key_info]()
* [gcr_fingerprint_from_attributes]()
