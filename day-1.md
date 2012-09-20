# 2012 Rocky Mountain Ruby

- <http://twitter.com/i/#!/search/realtime/rmr12>
- "[once again i am keeping notes for #rmr12](http://twitter.com/mcmire/status/248809825029484545) here:
<https://docs.google.com/document/d/1MDrQQPQbnumoR055CyOTamsWDOE_50wCjcJ8Sa63f1k/edit>"

## Sandi Metz
- <http://twitter.com/sandimetz>
- <http://www.informit.com/store/product.aspx?isbn=0321721330>
- ["Please buy through my link, I make selling my book than I did writing it(!)"](http://www.poodr.info/)
### Go Ahead, Make a Mess

- using OO to clean up messes
- public and private APIs
- "design happens from the message-senders' point of view"

## Ben Orenstein
- <http://twitter.com/r00k>
- <https://github.com/r00k>

### Refactoring from Good to Great

- "a smell is not a problem-- it's an indicator of what might be a problem"

      class DateRange < Struct.new(:start_date, :end_date)
      end

- "Let's write the code we wish we had…"
- "Most people err on the side of being too unwilling to extract classes… lots of tiny classes-- that's the sign of a good object-oriented system."
- post-refactor: "what every programmer's favorite part of their job?" audience: "DELETING CODE!"

## Justin Searls

<http://about.me/searls>

### To Mock or Not to Mock

- "test double-- think 'stunt double'", e.g. <http://martinfowler.com/bliki/TestDouble.html>
- "GOOS" book - Growing Object Oriented Software
- "TDD gives rich feedback about abstractions" - e.g. 15-line mock set-ups are a smell.
- test doubles conflict w/ "The Rails Way" due to Rails architecture-- difficult to isolate an object
- "surface area: number of attributes and accessible methods"
- large surface area makes isolation hard!
- <http://searls.testdouble.com/2011/06/03/whats-wrong-with-rubys-test-doubles/>

## Roy Tomeij

<http://twitter.com/roy>

### Modular & reusable front-end code with HTML5, Sass and CoffeeScript

for modularity, CSS class names are prefixed w/ "mod-"

"Using ID's in CSS is evil"

[presentation slides](http://roy.io/rmr12)

## Angela Harms

### Enhance your code with rainbows!
- geek love is about:
  - ["profluence"](http://www.merriam-webster.com/dictionary/profluence):  a copious or smooth flowing
  - clean code

## Lightning Talks

### ruby motion

@colin-t-a

<http://github.com/colinta>

<http://www.rubymotion.com/>

compiles ruby to native iOS code

do not have to use xcode-- just a terminal and a text editor

## Tony Navarre, Factory Design Labs

### A Model Walks Into a JavaScript Framework

"I have a problem w/ MVC-- MVC Prisons"

## Sales Pitch from head of Davinci Coders

<http://davincicoders.com/>

## Derrick Ko, KickSend

### mailcheck.js

<https://github.com/Kicksend/mailcheck>

## Panel Discussion - Growing Developers

- Mike Gehard - Pivotal Labs, Boulder
- [Matt Yoho](https://github.com/mattyoho) - Jump-Start Lab, [HungryAcademy](http://hungryacademy.com/) Living Social trainer
- Elaine Merrino - just finished Davinci Coders 11-week class
- Jim Denton - Group-On Apprentice, starting learning Ruby and web development in January 2012
- Tom Frey - runs Davinci Institute, a 501c3, in Louisville


