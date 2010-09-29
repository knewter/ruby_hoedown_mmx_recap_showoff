!SLIDE transition=scrollUp
.notes Configuration Management In the Cloud with Chef

# [Configuration Management In the Cloud with Chef](http://speakerrate.com/talks/4404-configuration-management-in-the-cloud-with-chef)
## John Willis

!SLIDE
* infrastructure as code
* need to be able to share with teammates
* can't have "the deploy guy"
* Chef is a library for configuration management
* Chef client runs on the system (to accept commands and configuration)
* Chef server is a RESTful API
* Each system you configure is a Node
* Attributes are searchable

!SLIDE
* Knife is the tool you use to interact with the API
* Nodes have Roles, which describe what a Node should be
* Nodes have a Run List
    * What Roles or Recipes to apply in Order
* A Resource is a Package or a Service
* E.G. Package "sudo" "1.6.8p12" and it figures out what package manager to use
* Services support actions (e.g. apache supports "restart" and "status")
* Resources take action through providers

!SLIDE
* Data bags store arbitrary data
    * E.G. put a user w/ their ssh key in a data bag, so you can add them as a user on the server
* Cookbooks are shareable
* "Open source for infrastructure"
* Open training
* Cloud service independence (swap from slicehost to rackspace just by adding credentials)
* http://www.opscode.com
    * 5 chef servers for free
* @opscode @botchagalupe
* Chef beats puppet on cloud support (more vendors)
