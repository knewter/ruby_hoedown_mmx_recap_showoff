!SLIDE transition=scrollUp
.notes There's a Wheel for That Already

# [There's a Wheel for That Already](http://speakerrate.com/talks/4406-there%E2%80%99s-a-wheel-for-that-already)
## Brian Hogan

!SLIDE

* Use the Ruby Standard Library
* FileUtils, Forwardable, Pathname, open-uri, TempFile, Webrick

!SLIDE

* "I don’t want to use that because I don’t like how it looks"
* How often is "better" really just an opinion
* Forwardable - delegate a method to another class
* Rails.root.join('config', 'x.yml')
* dir, base = path.split
* open-uri wraps net/http, net/https, net/ftp
* Tempfile (like tmpdir, but just for one file)
* x = Tempfile.new('hydra.yml')
* OpenStruct.new(Yaml.load('config.yml'))

!SLIDE
* Observer

  @@@ ruby
  def initialize
    add_observer MyObserver.new
  end

* bash alias for serving static files via webrick
* PStore for storing data
* CSV is great if it doesn’t need to be faster
* Home Run for datetime speedup via C extension
