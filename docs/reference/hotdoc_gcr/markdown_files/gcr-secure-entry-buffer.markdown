### GcrSecureEntryBuffer

a GtkEntryBuffer that uses non-pageable memory

 It's good practice to try to keep passwords or sensitive secrets out of
 pageable memory whenever possible, so that they don't get written to disk.

 This is a [](GtkEntryBuffer) to be used with [](GtkEntry) which uses non-pageable
 memory to store a password placed in the entry. In order to make any sense
 at all, the entry must have it's visibility turned off, and just be displaying
 place holder characters for the text. That is, a password style entry.

 Use [](gtk_entry_new_with_buffer) or [](gtk_entry_set_buffer) to set this buffer
 on an entry.

* [gcr_secure_entry_buffer_new]()
* [GcrSecureEntryBuffer]()
* [GcrSecureEntryBufferClass]()
