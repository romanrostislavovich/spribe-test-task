## Starting the App

Run `npm i` to install dependencies first, and then run `ng s` to start the app.


❗️ No dropdown list for countries
https://gitlab.spribe.io/fe/test-tasks/angular/-/merge_requests/196#note_408527

❗️ Datepicker allows future dates (not limited visually)
https://gitlab.spribe.io/fe/test-tasks/angular/-/merge_requests/196#note_408528

❗️ Pressing submit button for an empty form — does nothing, no validation
https://gitlab.spribe.io/fe/test-tasks/angular/-/merge_requests/196#note_408531

❗️ It is possible to remove/add form groups while submission is in progress
https://gitlab.spribe.io/fe/test-tasks/angular/-/merge_requests/196#note_408529

❗️ Console warnings when removing form groups. Something is wrong
https://gitlab.spribe.io/fe/test-tasks/angular/-/merge_requests/196#note_408530

Code Review

✅ Button unsubscription everywhere
✅ Timer implementation is simple and works properly
✅ Component decomposition

❌ OnPush strategy not everywhere
❌ Used both Renderer2 and DOM for elements manipulation
❌ A lot of magic numbers. Code smell "shotgun surgery"
❌ Date pipe was not used
❌ Redundant calculation for available list of countries — executed on each validator creation
❌ Getters in HTML templates
