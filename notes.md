# LIGHTNING TALKS!

## Hole Driven Development
- "Conversation with your editor, with your program, program writes itself"
- Emacs gfc-mode

## Code Literacy is Literacy Too
- "Writing across the Curriculum" - CU Boulder - Teach you to write, BUT write it ABOUT something
- We're teaching toy code, we're not teaching real-world code.  We need to write cross-discipline code.

## Riak guy - ordering in distributed systems
Lamport - Partial-ordered causal events, NOT physical clock  space-time process diagram

## SoundPuddle - spectrogram inside dome
Take a picture of this thing

## Trampolines
Look at his github site.  Learn you same Scala

## Haskell at DICOM Grid

### ASIDES to myself:

- There's LFE - Lisp Flavored Erlang - How about, computer-flavored Humanese (CFH) - terranese computer bisque - terran with a hint of functional - terrafunk - globalese but better - cosmic computer babble - compersonish - compersonese - compersanch - machuman - gepes - unborg

Remember about Newtypes!

# SATURDAY

## Ipecac of the ourobouros

- Virtual Filesystem
- Reactive Files
- Continuous Consistency
- Mary Ann Hoberman "W House is a House for me"
- Metadata needs to be less lazy than the actual data.

## The Virtual Filesystem
- "Suffuse" and the JVM
- File Holograms - Materialize - Virtual Michael Jackson
- Implicit File
- "Happy Jelly becomes Sharp Edges Jelly" - talking about smoothing over binary compatibility problems in the JVM (a.k.a. DLL Hell)
- Comment was made, this sounds similar to http://unisonweb.org . He say's it's complementary ; at different levels of the process/architecture.
- My own observation (privately): Isn't this kind of like the Internet, but at the edit/compile/link/deploy/run level?
Look up Parser Combinators w.r.t. Scala. - ok got it, here's a Clojure one --> https://github.com/youngnh/parsatron
- What is Fuse?

## Math and Haskell
- Jan Rutten - Stream Differential Equations

## ... Without sounding like and idiot
- Watch Paul Snively's "Type Systems: The Good, the Bad, and the Ugly"
- Read "A letter to a young Haskell Enthusiast"

## ooErlang
- WHat is PYPL (knew about TIOBE and redmonk before)

## Make your own language
- Would be interesting to see if there's a language that is lust as easily parsed from the end or beginning
- My Q: why are there more parentheses at the end of lisp forms than the beginning
  - My A: Becuase in LISP you need a function as the first list term.  Unless a function call returns a function, you'll never have double-left parens.
    - Maybe a LISP dialect that was SOV (liek German) would make it look different.  But then editing it would potentially suck?  Call it "Spill", which is LISP backwards, but not really.
- My Q: Why are there separate phases for lexing and parsing?  Doesn't seem necessary, and in fact seems harmful in that it constrains the set of possible languages

# My New Language Hobby
- Instead of toy stuff, I should write real stuff - properly-sized real stuff that's interesting to me.

## LFE
- Take Grossman's Coursera Programming Languages class

## Emily
- Lots of resonating ideas with The Awesome Languge
  - "Objects are just functions"
  - Scope hierarchy is like object inheritance.
    - Q How about polymorphism?  That's parallel scopes.
  - If the base language is unreadable, "Just make macros".

#@ The Next Great
- Decade of Accretion

Erlang - Process
Haskell - Type
Clojure - Data Structure
Suffuse - Virtual Files
Java - Classes
Prolog - Logic and Unification
Clips - Rules/Forward Chaining

So what matters, at the moment, according to me?
- Types (Theorems and Proofs)
- Processes (concurrency)
- Beauty/Aesthetics/Street Cred
- Productivity (debug cycle; tooling)
- Community/Maturity (libraries; stability)
- Performance
