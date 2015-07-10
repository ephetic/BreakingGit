# BreakingGit

## REALLY Deleting Pushes
Having pushed commits I shouldn't have, I now want to erase those commits forever.  I created a test file that I made and pushed four commits.  I then used `--reset hard` to get back to the second commit locally.  I made some new changes and finally pushed them with `--force` to overwrite the third and fourth commits with my new fifth commit now sitting on top.

To demonstrate that it's possible I could have done `push --force` to push the deletion before even making new commits, I `--reset hard` again and `push --force` immediately.  Now my second commit is sitting on top (not included these changes to this README).
