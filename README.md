# git-autostash

Tool based on `git stash` to let you take automatic backups of your Git working directory.

 - Relies on cronjobs to regularly take backups.
 - Uses separate stash from `git stash`.
 - Saves both staged and unstaged changes.
 - Easy to clean up old backups.

# Usage

Install `git-autostash` somewhere in your path. Run as `git autostash <COMMAND>`.

Run `git autostash save` to backup the current Git working tree.

Run `git autostash list` to show all backups.

Run `git autostash expire` to remove all backups older than 1 week.
