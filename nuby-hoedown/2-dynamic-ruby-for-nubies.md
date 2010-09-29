!SLIDE transition=scrollUp
.notes Dynamic Ruby for Nubies

# [Dynamic Ruby for Nubies](http://speakerrate.com/talks/4393-dynamic-ruby-for-nubies)
## Kevin Gisi

!SLIDE

## Metaprogramming is:

* method_missing
* dynamically writing code
* evaluating code in different contexts
    * method_missing
        * Object.send(:message)
        * Do I have a method named message?
        * Do any of my ancestors?
        * Call method_missing("message")
    * instance_eval
        * @dsl_object.instance_eval do
            * Everything in this block will treat @dsl_object as self.
