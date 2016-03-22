### GcrSystemPrompter

a prompter which displays system prompts

 This is a DBus service which is rarely implemented. Use [](GcrSystemPrompt)
 to display system prompts.

 The GcrSystemPrompter service responds to dbus requests to create system
 prompts and creates [](GcrPrompt) type objects to display those prompts.

 Pass the GType of the implementation of [](GcrPrompt) to [](gcr_system_prompter_new).

* [gcr_system_prompter_get_type]()
* [gcr_system_prompter_get_mode]()
* [GcrSystemPrompterClass]()
* [gcr_system_prompter_get_prompting]()
* [GCR_IS_SYSTEM_PROMPTER]()
* [gcr_system_prompter_new]()
* [GCR_TYPE_SYSTEM_PROMPTER_MODE]()
* [GCR_TYPE_SYSTEM_PROMPTER]()
* [GcrSystemPrompterPrivate]()
* [GCR_SYSTEM_PROMPTER_CLASS]()
* [gcr_system_prompter_register]()
* [gcr_system_prompter_mode_get_type]()
* [gcr_system_prompter_get_prompt_type]()
* [GcrSystemPrompterMode]()
* [GCR_SYSTEM_PROMPTER_GET_CLASS]()
* [GCR_IS_SYSTEM_PROMPTER_CLASS]()
* [gcr_system_prompter_unregister]()
* [GcrSystemPrompter]()
* [GCR_SYSTEM_PROMPTER]()
