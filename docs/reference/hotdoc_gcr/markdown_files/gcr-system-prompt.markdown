### GcrSystemPrompt

a system modal prompt

 A [](GcrPrompt) implementation which calls to the system prompter to
 display prompts in a system modal fashion.

 Since the system prompter usually only displays one prompt at a time, you
 may have to wait for the prompt to be displayed. Use [](gcr_system_prompt_open)
 or a related function to open a prompt. Since this can take a long time, you
 should always check that the prompt is still needed after it is opened. A
 previous prompt may have already provided the information needed and you
 may no longer need to prompt.

 Use [](gcr_system_prompt_close) to close the prompt when you're done with it.

* [GcrSystemPromptError]()
* [GCR_SYSTEM_PROMPT_ERROR]()
* [GcrSystemPromptPrivate]()
* [GCR_TYPE_SYSTEM_PROMPT]()
* [GCR_TYPE_SYSTEM_PROMPT_ERROR]()
* [gcr_system_prompt_open]()
* [gcr_system_prompt_open_for_prompter_async]()
* [gcr_system_prompt_open_async]()
* [gcr_system_prompt_open_finish]()
* [GCR_IS_SYSTEM_PROMPT_CLASS]()
* [GCR_IS_SYSTEM_PROMPT]()
* [gcr_system_prompt_close_finish]()
* [gcr_system_prompt_close]()
* [GCR_SYSTEM_PROMPT_GET_CLASS]()
* [gcr_system_prompt_error_get_domain]()
* [GcrSystemPrompt]()
* [gcr_system_prompt_get_type]()
* [gcr_system_prompt_error_get_type]()
* [GCR_SYSTEM_PROMPT_CLASS]()
* [gcr_system_prompt_close_async]()
* [gcr_system_prompt_get_secret_exchange]()
* [GcrSystemPromptClass]()
* [gcr_system_prompt_open_for_prompter]()
* [GCR_SYSTEM_PROMPT]()
