# Yank CLI

Pull the latest master for any number of repos with one command.

## Installation

1. `npm i -g @autome/yank-cli`

## Commands

Here are the commands that this package provides.

+ `yank`: This command performs a checkout on the master branch on all of the repos you have in your configuration and then pulls the latest commits.
+ `yank -a` || `yank --add`: This command can be used when inside of local repository to add that repository to your yank configuration. After adding a repo, it will be pulled whenever you perform `yank`.
+ `yank -r` || `yank --remove`: This command can be used when inside of local repository to remove that repository from your yank configuration. After removing a repo, it will not longer be pulled whenever you perform `yank`.
+ `yank --repos`: This command lists all of the repos you currently have in your yank configuration.

*Support*: Feel free to submit an issue if you find a bug or want a new feature.