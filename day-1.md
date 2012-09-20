# 2012 Rocky Mountain Ruby

- <http://twitter.com/i/#!/search/realtime/rmr12>
- "[once again i am keeping notes for #rmr12](http://twitter.com/mcmire/status/248809825029484545) here:
<https://docs.google.com/document/d/1MDrQQPQbnumoR055CyOTamsWDOE_50wCjcJ8Sa63f1k/edit>"

## Sandi Metz
- <http://twitter.com/sandimetz>
- <http://www.informit.com/store/product.aspx?isbn=0321721330>

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

