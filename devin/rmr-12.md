# rocky mountain ruby conf 2012

+ ej motes on github

## mocking

+ @searls
+ testing, "fake tests"
+ a question of thoroughness v. cost
-types of tests    
    + end to end test
    + integration tests
    + unit tests
    + isolation test
+ mock / test double / spy
+ stubs: pre-configured to expect messages
+ why do we test?
+ the GOOS way - growing oo software
+ collaborative complexity 
+ test doubles great for isolation tests
+ surface area of objects
+ http://is.gd rubymocks gimmie

## front end

+ @roy
+ modules not tables
+ reusable and independent
+ modules w/ HTML 5
+ screw seo "experts"
+ modular css
+ clean code goes in clean files
- `mod-`
+ use generic class names
+ super shallow selectors
+ ID's are evil

## rainbows

+ @angelaharms
+ soft skills
+ geek joy
+ irresponsible unprofessional
+ clean code!
+ coding out of fear
+ remove duplications and fix bad names
+ unexpected emergence
+ letting it go...
    - getting it right the first time
    - having everything in your head
    - holding back (of being wrong, not speaking up, etc.)
+ be there fully, be humble (confident humility)
    - take your part, even if you feel like you're slowing others down
+ be more courageous, less afraid
    - love / befriend yourself like others, asshole.
+ junior pairs, step up, share!

## lightning

+ @colinta
+ rubymotion
+ iOS apps

+ mvc prisons
+ limiting roles of mvc
+ cocoa (complementary to mvc)
+ bad / clean js issues

+ teacherless education
+ redefining how we view knowledge
+ more digestible and entertaining learning
+ inserting teachers between knowledge becomes an impediment

+ @derrickko
+ keep it simple, over engineering
+ /#speakerdeck
+ small nudges for useability
+ `mailcheck.js`
+ simple solutions for users

## real life context switches

+ avoid being tired by focusing tasks 
+ avoid excessive context switches
+ be less tired / mentally fatigued
+ mindlessness

# concurrency

+ platformatec
+ executing several tasks simultaneously
+ multiple servers
+ single process, multi-core
+ (ruby lambda)
+ determinism, same in same out (always return he same results)
+ dataflow variables
+ threading intelligently
+ state / concurrency : on = bad
+ race conditions 
+ locks synchronize, message passing (mailbox, hand-off, centralized computation, one way incrementation), transactional memory (atomic) 
+ ruby:locks, stm:closure, message:go/erlang
+ celluloid / elixir
+ "defaults matter"

## chat ops

+ @techpickles
+ irc, internet chat, etc.
+ robot in chat
+ rails machine
+ knowing how "the business" works as an employee
+ hubot
+ imperial probe droid / campfire / propane / god
+ nagiosish irc...

## large code

+ @shageman
+ don't build large apps!
+ massive code base = evil
+ structure!
+ namespaces / modules 
+ adding structured layers to code bases
+ "tell the story of the system"
+ high cohesion, looser coupling
+ annoyance
+ DHH
+ `Rails::Engine`
+ assets
+ "all gems start with a namespace"
+ namespace everything in a rails app

## rails backbone

+ kicksend
+ user experience 
+ speed, notifications, real time features
+ multiple client
+ derby, meteor, firebase, ember.js, etc.
+ Kicksend: rails, backbone (fe web framework), handlebars, XMPP
+ use coffeescript
+ thin controllers, fat models
+ keep views atomic
+ progressive loading / rendering
+ caching!
+ russian doll setup
+ render before call
+ "be greedy"
+ avoid rails bloat

## lightning

+ service does not take, it gets what it needs

+ refactoring patterns

+ learning to program
+ internship, learn the 28 things
+ apprenticeship
+ then jr. dev

+ algorithms
+ sinatra
+ sql is bomb
+ @gordondiggs

+ ack
+ @theaboutbox
+ better than grep, faster
+ maintaing focus is primary
+ get with brew
+ ack integrated with vim

+ @nelstrom
+ problems...`this`
+ scoping...

## expert consulting

+ @p_elliott
+ redefine consulting process
+ adding professional value
+ stakeholder relationship
+ disseminating an appropriate amount of info
+ making appropriate calls when situation / knowledge dictates
+ separating bias / targeting questions
+ own the roll as an expert
+ scope creep
+ shutting the client down ... be more 'yes'
+ framing your words (positive)
+ unified front, !arguing before client
+ asking questions once
+ context and information granularity
+ short meetings, minimal information
+ overwhelming clients with TMI
+ don't present the opportunity for failure
+ presenting the right context

## eloquent explanations

+ @russolsen
+ design patters in ruby
+ eloquent ruby
+ breaking limits
+ what are programming limits
+ ideas are centrals, tools are abstractions
+ self limitation
+ "5% more"
+ explaining = expanding smarts
+ makings explanations stick
+ the art of explaining
+ if you don't care, i don't care

### steps to be an effective explainer

0. take explaining seriously
1. you need a plan
    + "zoom in plan" - start big, add details incrementally0
    + lincoln's speech
    + zoom out plan
    + process explanation
    + simple to complex, context of learnee
    + "screw the experts"
2. be agile
    + do it, measure it, fix it, repeat it
    + failing: silence, looking at you funny, reoccurring questions
    + failing: "it's you"
    + many explanations fail due to "gaps"
    + experts forget there's anything to know
3.
    + teaching as "innings" vs "timing"
        - explanation is done when leaning is done
    + put important stuff first
    + terminology isn't important
    + supply small victories
    + managable chunks
4. DRY is for machines, repeat!
    + looping back
    + RYE, repeat yourself for emphasis 
5. mix in humor / humanity
    + numerical methods that work
    + one small joke to remember it all
    + subtle jokes, don't explain
    + show up

### understanding

+ vocalizing when a gap is present