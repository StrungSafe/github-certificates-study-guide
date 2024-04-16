# Domain 3: Collaboration Features

## Issues

1. Describe how to link a PR to an issue
    - Issue in the same repository
        - KEYWOARD #ISSUE-NUMBER Ex: Closes #123
    - Issue in a different repository
        - KEYWOARD OWNER/REPOSITORY#ISSUE-NUMBER Ex: Fixes strungsafe/awesome-repo#123
    - Multiple Issues
        - Full syntax above separated by comma Ex: Resolves #10, resolves #123, resolves octo-org/octo-repo#100
1. Describe how to create an issue
    - GitHub.com you can go to Issues and click New
1. Describe the difference between an issue, discussion, and pull request
    - Issue is a way to communicate a a bug, enhancement, or other changes
    - A PR is a request to merge changes from one repo or branch into another repo or branch
    - A discussion is a place for community discussion that may or may not produce change to the repository
1. Explain how to create a branch from an issue
    - Open the issue, create new branch from development section on the right of the page
    - Can link a branch to the issue after the branch has been created too
1. Identify how to assign issues
    - On the right side of the page, under the Assignees, an Assignee can be assigned
1. Describe how to search and filter issues
    - Opening Issue page there is a dropdown to filter issues based on state
    - A search bar exists to w/ ```is:issue```
    - Can also search by other issue attributes like author, label, projects, milestones assignee
1. Describe how to pin an issue
1. Explain basic issue management
    - Using labels the issues can be categorized to identify various attributes of issues
    - Ensure issues are in correct and updated states
1. Explain the difference between issue templates and issue forms
    - Templates is the skeleton of an issue
    - Forms is an instance of an issue
1. Explain how to use keywords in issues
    - Same usage as in a PR
    - close, closes, closed, fix, resolves, etc.

## Pull Requests

1. Describe a pull request
    - A pull request is the way code is moved from one branch or fork into another
1. Explain how to create a new pull request
    - Open Pull Requests, select Create, select `base` and `compare` branches, click Create or Draft
1. Describe the `base` and `compare` branches in a pull request
    - `base` is the branch being requested to pull the `compare` branches changes
1. Explain the relationship of commits on a pull request
    - The commits shown in a pull requests represents the changes being requested to be pulled into the `base` branch
1. Describe draft pull requests
    - A draft PR is much like a regular PR except it means it's not in a state to immediately merge
1. Describe the purpose of the pull request tabs (conversation, commits, checks, files changed)
    - The pull request tabs separates important components of the PR
    - Conversation is active conversations about the changes being requested to be pulled
    - Commits lists the changes being requested to be pulled
    - Checks are the automated checks performed against the PR
    - Files changed is a diff of the files changed in the commits
1. Identify how to link activity within a pull request
    - Using keywords and issue numbers or commit hashes
1. Explain the different pull request statuses
    - Draft and Open are the initial states of a PR
    - Merged means the PR has been merged into the target branch
    - Closed means the PR has been closed without merge
1. Recognize how to comment on a posted link to a line or lines of code from a file
    - When a PR get's a comment on a line or lines of code it starts a conversation and others can add or continue that conversation
1. Describe code review with a codeowners file
    - A CODEOWNERS file identifies users or teams that will automatically be added to a PR for a code review
1. Explain the different options for providing a code review on a pull request (comment, approve, request changes, suggested changes)
    - A comment is just a comment that doesn't require any additional action
    - An approval approves the PR for merge, an approval can include comments or no comments
    - Request changes requires additional changes to the PR before they will be merged
    - Suggested changes is inline changes that can be immediately committed to the branch and PR

## Discussions

1. Describe the difference between discussions and issues
    - Discussions can be open ended conversations or questions about the repository and project
    - Discussions can end up with having issues being created
    - Issues are changes that are ready to be implemented
1. Explain the options available with discussions (announcements, ideas, polls, Q&A, show and tell)
    - The various options allows different ways to engage the community about answering various discussions about the project
1. Identify how to mark a comment as an answer to a discussion
    - Find the comment that answers the discussion and there is a 'Mark as answer' button
1. Explain how to convert a discussion to an issue
    - Open the discussion and click the 'Create issue from discussion'
1. Recognize how to pin a discussion
    - A discussion can be pinned 'Pin discussion' within a discussion

## Notifications

1. Describe how to manage notification subscriptions
    - Under your user's profile settings you can manage your notifications
    - Fine detail management can be done here https://github.com/notifications/subscriptions
1. Explain how to subscribe to notification threads
    - via an Issue or a PR
1. Describe how to find threads where you are at-mentioned
    - https://github.com/notifications/subscriptions?reason=mention
    - Or your notifications if you are configured to hear at-mentions via email and/or GitHub
1. Identify the notification filtering options
    - There are various ways to filter your notifications subscriptions
    - By reasons such as: At-mention, assign, author, comment, manual, mention, review requested, state change, or team mention
    - By repositories
1. Explain the different notification configuration options
    - Send notifictions to one or more emails and/or github

## Gists, Wikis, and GitHub Pages

1. Explain how to create a GitHub gist
    - Can use the '+' symbol to create a new public or secret gist
    - Can also go to gist.github.com and Create a new gist here
1. Describe how to fork and clone a gist
    - Gists are just like git repositories and follow same cloning and forking steps
1. Explain GitHub Wiki pages
    - A github wiki page lives in a repo and let's you share long form content
    - A wiki hosts documentation for you repository
1. Describe how to create, edit, and delete wiki pages
    - Open the repo's wiki page and click 'New Page'
    - Navigate to the wiki page to be edited, in the upper-right corner click 'Edit'
    - Navigate to the wiki page to be deleted, edit the page, then in the upper-right corner click 'Delete'
1. Explain the visibility of wiki pages
    - Wiki pages have the same visibility as the repo
1. Describe GitHub Pages
    - Hosted directly from your GitHub repository
    - Is a way to host pages directly from a repository
    - Able to configure a CNAME file to use your own URL domain
    - https://username.github.io and a repo named username.github.io
