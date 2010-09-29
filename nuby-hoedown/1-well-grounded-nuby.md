!SLIDE transition=scrollUp
.notes The well-grounded nuby by david black

# [The Well-Grounded Nuby](http://speakerrate.com/talks/4392-the-well-grounded-nuby)
## David Black

!SLIDE
* Everything evaluates to an object
    * Every expression is not an object (ifs, keywords, etc)....but every expression reduces to an object.
* It's all about sending messages to objects
    * "The answer to 75% of all questions about Ruby is:  because classes are objects"
    * You’re always sending messages to objects (brackets, case statements) even when it doesn’t look that way.
        * 3 + 2 is actually 3. + (2)
        * 7 * 3 is actually 7.*(3)
* Objects resolve messages into methods

!SLIDE
* Classes and modules are objects
* There's always a 'self'
* Variables contain references to objects
* True and False are objects; true and false are states
    * Every object as a boolean value: false and nil have a boolean value of false.  Every other object has a value of true.
