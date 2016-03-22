### Non-pageable Memory

Secure non-pageable memory

 Normal allocated memory can be paged to disk at the whim of the operating
 system. This can be a problem for sensitive information like passwords, keys
 and secrets.

 The Gcr library holds passwords and keys in non-pageable, or locked memory.
 This is only possible if the OS contains support for it.

 These functions allow applications to use secure memory to hold passwords
 and other sensitive information.

* [gcr_secure_memory_is_secure]()
* [gcr_secure_memory_new]()
* [gcr_secure_memory_strdup]()
* [gcr_secure_memory_realloc]()
* [gcr_secure_memory_free]()
* [gcr_secure_memory_try_realloc]()
* [gcr_secure_memory_strfree]()
* [gcr_secure_memory_try_alloc]()
* [gcr_secure_memory_alloc]()
