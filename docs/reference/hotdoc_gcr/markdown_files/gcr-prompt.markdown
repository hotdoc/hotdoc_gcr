### GcrPrompt

a user prompt

 A [](GcrPrompt) represents a prompt displayed to the user. It is an interface
 with various implementations.

 Various properties are set on the prompt, and then the prompt is displayed
 the various prompt methods like [](gcr_prompt_password_run).

 A [](GcrPrompt) may be used to display multiple related prompts. Most
 implemantions do not hide the window between display of multiple related
 prompts, and the [](GcrPrompt) must be closed or destroyed in order to make
 it go away. This allows the user to see that the prompts are related.

 Use [](GcrPromptDialog) to create an in-process GTK+ dialog prompt. Use
 [](GcrSystemPrompt) to create a system prompt in a prompter process.

 The prompt implementation will always display the GcrPrompt:message property,
 but may choose not to display the GcrPrompt:description or GcrPrompt:title
 properties.

* [GCR_PROMPT_GET_INTERFACE]()
* [gcr_prompt_get_message]()
* [gcr_prompt_set_title]()
* [gcr_prompt_set_password_new]()
* [gcr_prompt_get_warning]()
* [gcr_prompt_set_choice_label]()
* [GCR_IS_PROMPT]()
* [gcr_prompt_get_password_strength]()
* [gcr_prompt_password_finish]()
* [gcr_prompt_set_caller_window]()
* [gcr_prompt_get_description]()
* [gcr_prompt_get_choice_label]()
* [GCR_TYPE_PROMPT]()
* [gcr_prompt_confirm_run]()
* [gcr_prompt_close]()
* [gcr_prompt_set_choice_chosen]()
* [gcr_prompt_get_choice_chosen]()
* [gcr_prompt_get_caller_window]()
* [GcrPrompt]()
* [gcr_prompt_password_async]()
* [gcr_prompt_confirm]()
* [gcr_prompt_set_message]()
* [GcrPromptReply]()
* [GcrPromptIface]()
* [gcr_prompt_password]()
* [gcr_prompt_get_password_new]()
* [gcr_prompt_get_type]()
* [gcr_prompt_get_title]()
* [gcr_prompt_reset]()
* [GCR_PROMPT]()
* [gcr_prompt_set_cancel_label]()
* [gcr_prompt_password_run]()
* [gcr_prompt_set_continue_label]()
* [gcr_prompt_reply_get_type]()
* [gcr_prompt_set_description]()
* [gcr_prompt_get_continue_label]()
* [gcr_prompt_confirm_async]()
* [gcr_prompt_confirm_finish]()
* [GCR_TYPE_PROMPT_REPLY]()
* [gcr_prompt_get_cancel_label]()
* [gcr_prompt_set_warning]()
