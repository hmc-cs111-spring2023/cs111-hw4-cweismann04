What's easy to do in Scala? What's not?
It's (relatively) easy to develop DSLs, run unit tests, and do most things that you can do in Python or Java. It's a bit more difficult to do things with some sort of graphical output.

So far, what is/are your favorite language design choice(s) that the designers of Scala made? Why?
Pattern matching was one of my favorite features of Haskell,, so I was pleasantly surprised to find that it's an option in Scala as well. In general, I think that the combination of imperative and functional features gets rid of many of my frustrations with both types of languages- imperative code often feels inelegant, while functional code seems obtuse and hard to read. The test suites are really cool too, and its nice to be able to both compile through scalac and run through the REPL.

So far, what is/are your least favorite language design choice(s)? Why? And why do you think the designers made that / those choice(s)?
There's a few features that I'm a bit picky about, like the awkward List syntax, and val and var being picked instead of some more common alternatives. I would guess they made the List choice since they already have arrays, and keyword picks are always a bit strange so I can't really fault val and var too much.

What Scala features would you like to learn more about?
I want to learn more about writing SBT tests: it seems we just scratched the surface and it's far and away the best unit testing language I've ever tried.
