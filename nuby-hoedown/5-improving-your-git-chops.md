!SLIDE transition=scrollUp
.notes Improving Yout Git Chops

# [Improving Yout Git Chops](http://speakerrate.com/talks/4396-improving-your-git-chops)
## Scott Chacon

!SLIDE
* [http://github.com/schacon/showoff-wrangling-git](http://github.com/schacon/showoff-wrangling-git)
* [http://gitref.org](http://gitref.org)
* [http://progit.org](http://progit.org)
* tree -a for nice tree list of a directory

!SLIDE
* git log branchA ^branchB
* show commits reachable by A but not by B
* for example, I’m working on branch my-feature
* git log my-feature ^master
* is the stuff I’ve done that’s not in master yet
* git branch --merged
* show me all branches that have been merged (safe to delete)
* git branch --no-merged
* show me all branches that have not been merged
