# gdrive_management
Rust tools for file and account management via the Google Drive API



### Branching strategy

General guidelines:
+ Do not make direct commits to the main branch. Instead, work on a feature, bug, or hotfix branch and submit a pull request to merge into main.
+ Make a best effort to ensure that your work is somehow captured on the Trello board
+ To enhance an already merged feature, use a new feature branch.
+ Use bug branches to fix a feature already merged to main.
+ Use hotfix branches to make quick fixes to the production environment (this does not currently apply, since dev and production environments are not separated)


Branch naming conventions:
- New features: ```feature/[whatever_camel_case_name]```
- Bug fixes ```bug/[what-you-are-fixing-in-what-feature]```
- Hotfix ```hotfix/bare-minimum-description-of-broken-thing```
