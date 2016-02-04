CLInt
=====

CLI Note-Taking program
-----------------

clint stores all the notes in a local git repo. This has multiple advantages, including:

  * note history
  * you can make backups easily by pushing to a remote
  * collaboration
  * all of git's features

Notes are stored as markdown.

This is a little script I made that will hopefully turn into something big. I made it to learn bash.

### Usage

```bash
clint usage           # Print usage
clint new <note name> # Create or edit an existing note
clint log             # Show git log
clint preview         # Preview note in borwser. Requires markdown. xdg-open and a browser.
clint preview-cli     # Preview note in the terminal
```

After you save you note, it will be automatically added to the git repo and commited.

### Todo

The note format is not finished yet. Currently it is just a plain markdown file.

- [ ] Header metadata
  - [ ] Date created
  - [ ] Tags
- [ ] Search by tags/author/date created.
