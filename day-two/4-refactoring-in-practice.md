!SLIDE transition=scrollUp
.notes Refactoring in Practice

# [Refactoring in Practice](http://speakerrate.com/talks/4405-refactoring-in-practice)
## Alex Sharp
### [Slides](http://www.slideshare.net/drumwurzel/refactoring-in-practice-ruby-hoedown-2010)

!SLIDE
* Shantytown application: you want to bulldoze it, but people live there
* Rules of Refactoring:
    * Tests are essential
    * Avoid rabbit holes
    * Take small wins (avoid epic refactor)

!SLIDE
* "To refactor code is to change its implementation while maintaining its behavior" -- Martin Fowler, Kent Beck, et. al.
* For web apps this means the behavior for the end user stays the same

!SLIDE
* deprecate action
    * for example, hoptoad a deprecation warning on old calls to actions
    * helpful when there are ajax calls you are not sure about
* take out small chunks and get them under test
* lack of framework knowledge – often using existing solutions is an easy refactor
* Domain driven development & domain modeling
* Document the smells
* delete code that you aren’t using
