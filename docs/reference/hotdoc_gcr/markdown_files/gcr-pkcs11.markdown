### Library PKCS#11

functions for manipulating GCR library global settings.

 Manage or lookup various global aspesct and settings of the library.

 The GCR library maintains a global list of PKCS\[](11) modules to use for
 its various lookups and storage operations. Each module is represented by
 a GckModule object. You can examine this list by using
 [](gcr_pkcs11_get_modules).

 The list is configured automatically by looking for system installed
 PKCS\[](11) modules. It's not not normally necessary to modify this list. But
 if you have special needs, you can use the [](gcr_pkcs11_set_modules) and
 [](gcr_pkcs11_add_module) to do so.

 Trust assertions are stored and looked up in specific PKCS\[](11) slots.
 You can examine this list with [](gcr_pkcs11_get_trust_lookup_slots)

* [gcr_pkcs11_set_trust_lookup_uris]()
* [gcr_pkcs11_initialize_finish]()
* [gcr_pkcs11_add_module]()
* [gcr_pkcs11_add_module_from_file]()
* [gcr_pkcs11_get_trust_store_slot]()
* [gcr_pkcs11_initialize_async]()
* [gcr_pkcs11_initialize]()
* [gcr_pkcs11_get_modules]()
* [gcr_pkcs11_get_trust_store_uri]()
* [gcr_pkcs11_set_trust_store_uri]()
* [gcr_pkcs11_set_modules]()
* [gcr_pkcs11_get_trust_lookup_slots]()
* [gcr_pkcs11_get_trust_lookup_uris]()
