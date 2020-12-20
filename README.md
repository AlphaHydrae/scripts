# Random Shell Scripts

* `git-ignore-list` - Lists `.gitignore` patterns and where they are used, to
  help identify configuration files you might need to back up.
* `git-status-report` - Goes through local Git repositories and counts:

  * Untracked files.
  * Unstaged or uncommitted changes.
  * Stashes.
  * Branches that have no upstream.
  * Commits that have not been pushed.

  Basically any change you might permanently lose if the machine dies and you
  have no backup.

  > **WARNING:** this script does not check ignored files. Use `git-ignore-list`
  > to identify files ignored by Git that you might want to back up.

## License

[The MIT License](https://opensource.org/licenses/MIT)
