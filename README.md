# Myrient Annex

Git Annex repository of `myrient.erista.me`.

To use:

1. Install Git & Git Annex on your computer, then clone this repository using Git.
2. Navigate the files, and use `git annex get --user-agent 'Wget/1.8.0' <path>` to download the file or folder.
3. Tip: focus on rare files without copies! To find files needing copies: `git annex find --approxlackingcopies=2 .`