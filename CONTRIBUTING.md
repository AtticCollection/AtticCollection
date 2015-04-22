Contributing
===

##Phrasinggg
![Phrasingg](http://i.imgur.com/iYiptaw.jpg)
We are a collective. We will *try* to always use we instead of I.
We want this to be us, and other cliches and whatnot.

##Project Management
All project management will be done through Github issues for now.
We want a better alternative, but it seems that the issues here are
the easiest and most available way for everyone to get involved.

##Project Lifecycle
1. An idea is had
2. It becomes an issue
3. We comment and refine the idea in the issue
4. We create smaller Issue Tasks if needed
5. We start claiming said issues
6. `git branch IN_issue_number/leading_label` or `git branch IN_1/meta`
7. ???
8. `git commit -m "fixes #issue_number"`
9. pull request to master
10. Some of us check it off and see its good
11. Revisions needed go back to step 7
12. Its good pull request accepted welcome abord
13. Test in staging for a bit
14. Add issues to github issues
15. Make pull request to `production`
16. All of us check it as good
17. Merge & Deploy!

##Branches
####`master`
This is our staging branch, all merges to this branch should be
by **pulll request only**. All approved pull requests will auto deploy via
codeship.

####`IN_issue_number/leading_label`
This is where development actually gets done. When finished with a branch
submit a pull request and after we pull this branch in it will be deleted
if it is still hanging around.

####`production`
This is the production branch all merges will be via pull requests and
evaluated by almost everyone. After careful consideration we will merge
and the manualy deploy to the production servers.
