### GcrMockPrompter

a mock GcrSystemPrompter for testing

 A mock GcrSystemPrompter used for testing against.

 Use [](gcr_mock_prompter_start) to start the mock prompter in another
 thread. The returned string is the dbus address of the mock prompter.
 You can pass this to [](gcr_system_prompt_open) as the prompter bus name.

 Use the [](gcr_mock_prompter_expect_confirm_ok) function and friends before
 prompting to verify that the prompts are displayed as expected, and to
 provide a response.

* [gcr_mock_prompter_expect_confirm_cancel]()
* [gcr_mock_prompter_expect_password_ok]()
* [gcr_mock_prompter_get_delay_msec]()
* [gcr_mock_prompter_expect_password_cancel]()
* [gcr_mock_prompter_set_delay_msec]()
* [gcr_mock_prompter_is_expecting]()
* [gcr_mock_prompter_expect_confirm_ok]()
* [gcr_mock_prompter_stop]()
* [gcr_mock_prompter_disconnect]()
* [gcr_mock_prompter_start]()
* [gcr_mock_prompter_expect_close]()
* [gcr_mock_prompter_is_prompting]()
