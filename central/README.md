# Central

## `central-redirect-to-jira.user.js`

Redirect single Central Issue links to finding it in Jira.
Won't work for issues that didn't migrate over to Jira.
Won't work if your Central Issue URL has cruft on it, such as anchor links.

![Central issue redirecting to Jira](https://user-images.githubusercontent.com/1812179/71703646-6079d780-2d9b-11ea-85d0-692d86a98631.gif)

## `central-collapsable-sidebar.user.js`

Improves the content space and make sure sidebar is collapsible to the same width of http://tri.be/ and sidebar is accessible just by moving the cursor to the sidebar to  make it available when only needed it.

![collapsible sidebar](https://user-images.githubusercontent.com/3921289/37617341-82bc4994-2b78-11e8-8856-288de6d2c8e5.gif)

## `central-link-pr-formatting.user.js`

Format the links that points to Pull Request in Central from a format like: `https://github.com/moderntribe/event-tickets-plus/pull/490` into a format like `event-tickets-plus#490
`event-tickets-plus#490`  similar to what GitHub does when a Pull Request is referenced inside of an issue.  

## `central-friendly-ui-for-multiple-pr.user.js`

Improves the UI when an issue has more than a single Pull Request to improve the addition / removal of new Pull Requests. 

![Multiple PR Image](https://user-images.githubusercontent.com/3921289/36676235-b69b5434-1ad0-11e8-9df3-345627c01aff.gif)

## `central-estimates-time-conversion.user.js`

Updates the estimate field to make it wider and available to accepts entries such as: 4h 5m and make them work exactly the same as **Spent time** field.

## `central-issues-kanban.user.js`

Creates a kanban board for all issues queried. The board is hidden by default and can be toggled open and closed.

## `central-links.user.js`

Turns the _Pull Request_ field in Modern Tribe's "Central" issues pages into a link.

## `central-my-favorite-tickets.user.js`

Add your favorite ticket numbers to the main menu for easy access.
The ticket numbers and descriptions need to be manually adjusted in the script.

![screen shot](https://dl.dropboxusercontent.com/s/ni5i38m93hvxmjc/shot_190304_231637.jpg)

## `central-new-issue-templates.user.js`

Starter Templates for New Central Issues

## `clocking-nag.user.js`

Shows your week of clocking at the top of Central and prompts you to enter some clocked time if you are falling behind.

![screen shot 2017-08-16 at 10 04 53 am](https://user-images.githubusercontent.com/430385/29367332-8beceac6-826a-11e7-9e62-3800663c5b22.png)


## `issue-list-tools.user.js`

This script provides handy tools when viewing an issue list:

* Toggle open/close row groupings of issues

Ok...fine...that's just one tool, but this has room to grow.

## `issue-summary.user.js`

* Color-codes central issues by status and swaps out issue types (Support, Feature, Bug) with FontAwesome "icons".
* Adds a summary of on-page issues grouped by issue status.

![screen shot 2017-08-16 at 10 08 03 am](https://user-images.githubusercontent.com/430385/29367418-db3e3328-826a-11e7-8dd1-2e9e48a338c9.png)

## `key-commands.js`

Sorta like vim/gmail key commands
* `/` places your cursor in the search box.
* in query view: `j` and `k` move your selection up or down. Pressing `enter` on the selection takes you to that ticket.
* `i` takes you to the My Query.
If you don't like the query view `i` takes you to, change the URL in line 15. 

## `over-estimate.user.js`

* highlight the spent hours with pink if they are over estimate
* works on both issue lists and single issues

## `party-llamacorn.user.js`

When a ticket is set to _Pending Merge_ or _Complete_, a llamacorn flies across the screen.

## `qa-headers.user.js`

Styles QA headers so scanning QA activity on tickets is quicker. Relies on using the following headers in Central:

```
h2. QA PASSED (plus any extra text you want here)

h2. RETURNED (plus any extra text you want here)
```

## `qa-testing-instructions.user.js`

Adds a button to the update form in a specific issue.
When clicking the button, the notes and testing instructions fields are automatically populated with formatted starter text.

## `relay-for-toggl.user.js`

Adds a button to tasks in central to start toggl.
You need to provide your toggl API key and the proxy address.
You are welcome to use the proxy at https://relay-for-toggl.herokuapp.com/ 
Proxy repo: https://github.com/binarygary/relay-for-toggl
![example](https://github.com/moderntribe/tampermonkey-scripts/img/toggl.gif)

## `sticky-clocker-dropdowns.user.js`

Sets the __project__ and __activity__ to previous values after clocking time on the clocking tool.
This does not work if the clocking tool is opened in a pop-up window.

## `target-blank.user.js`

Auto-adds `target="_blank"` to all external links.

## `uncheck-email-all.user.js`

Auto-uncheck the "email all" checkbox so you only send an email when you _really_ want to.
