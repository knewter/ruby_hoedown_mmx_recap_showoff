!SLIDE transition=scrollUp
.notes Gem Authoring and Deployment

# [Gem Authoring and Deployment](http://speakerrate.com/talks/4395-gem-authoring-and-deployment)
## Matt Yoho
## [Slides](http://slidesha.re/aQtk9m)

!SLIDE
* In the beginning...
* Overview of how rubygems works, changing load path, etc
* Use Rake tasks to make gem building easier
* Documentation (RDOC, Yard, Rocco, Ronn/man pages)

!SLIDE
* Add a license early in your gem development
* DWTFYWTPL
    * Do what the ___ you want to public license
* Bundler + RVM = WIN
* Don't require rubygems in your gem
* Semantic versioning (X.Y.Z)

!SLIDE

* "require" loads code once, it is smart
* "load" loads the code without doing any checks
* You should not "require 'rubygems'" it should already be on the load path
* Don’t use jeweler, use a real gemspec
* [http://yehudakatz.com/2010/04/02/using-gemspecs-as-intended/](http://yehudakatz.com/2010/04/02/using-gemspecs-as-intended/)
* Unsure about this, maybe the gemspec has enough automation you don’t have to do this any more?
* Aruba lets you write cuke specs within cuke specs. Helps with command line applications
