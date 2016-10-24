# Why Syntax Changes Matter

## (a.k.a why changes to JS mean a lot more than you think)

---

# Hey! I'm Kas

* Developer Relations Engineer at Auth0/Webtask.io
* Serverless/Node.JS afficionado
* Also pretty good at Auth (OAuth, OIDC, etc.)
* Gender non-binary (they/them, she is OK, Yes you may ask polite questions)

![fit right](GIFS/charmbomb.gif)

---

# I'm also a hardware hacker

* Some people actually just call me 'nodebotanist'
* In-Progress EE degree
* Tessel open-source committee member
* I wrote a book on JS Robotics

![left fit](./bowie.jpg)

---

# But today I'm not here to talk about that

![inline](GIFS/calculon-nooooo.jpg)

---

# Today I'm here to talk about education

---

# "But your talk title says..."

![inline](GIFS/thanks-for-your-input.gif)

---

# I **Know** what it says. But they're related.

---

# Close your eyes for a second, and pretend you're learning software development for the first time

---

## What does this do?

```
function foo(x=4){
  return () => {
    let sum = x--;
    for(y = x; y > 0; y--){
      sum *= y;
    }
    return sum;
  }
}

console.log(foo(5)() + foo()());
```

---

## If your response starts with "Well, **obviously**...

![inline](GIFS/annoying.gif)

... you didn't pretend hard enough (or didn't try)

---

## If your response was more...

![inline](GIFS/huh.gif)

Good! You're ready!

---

## If your response was more...

![inline](GIFS/no-idea-what-im-doing.gif)

"Well [expletive], even without pretending I don't get it! I'm a terrible programmer!"

---

## Calm down. no you're not.

![inline](GIFS/carl-sagan-youre-awesome.gif)

You are smart and awesome and cool, don't let overly clever code get you down.

---

# "Overly Clever Code"? Don't we **want** code to be as clever as possible?

---

# We want code to be well-written.

And clever use of abstractions is a part of that.

The thing is, good code **is a balance of a lot of different things that are subjective and situation-dependent.**

---

## Like what?

* Are you working on a team? What in your team **composition**?
* Are you **teaching someone** with this (the answer is almost always yes!)?
* Are you **open sourcing** this? Do you want **contributors**?
* What's your **primary function**? What can you **not do without**?

---

# Balancing that sounds **hard**

![inline](GIFS/done-carry-me.jpg)

---

# The secret of software development

Writing code **isn't the hard part**. Solving problems in a way that is sustainable for your team, completes its function, using the right tools is the hard part.

---

# So how does this relate to ES 2015 and new yearly JS releases?

(I say ES 2015 because I want to pretend 2016 didn't happen. Not ES 2016, just 2016 as a year. Unless the Cubs win the world series. Then maybe.)

---

# ES6 added a lot of awesome abstractions for previously arcane/annoying features of JS:

* Arrow syntax for callbacks
* `let` for block syntax
* rest and spread for optional arguments and array manipulation
* generators
* Destructuring for moving values and other fun stuff

---

# And now we're getting yearly releases for standards!

![inline](GIFS/yey.gif)

---

## But these abstractions make a much steeper learning curve-- not just for new programmers, but those of us trying to keep up!

---

Software developers exist on a constant state of needing to learn new things. So becoming a software developer can be like **trying to learn how a car works while it moves at about 5 mph.** If you're already a developer, it's 2 mph.

![inline](GIFS/yoyofail.gif)

---

## Some abstractions make code easier to read. Some make it harder

* Class syntax is usually easier to teach new devs.
* Destructuring...not so much.

---

# The problem is we have to teach (or learn) the hard way to do things,  usually before we teach/learn the easy way

---

# Class Syntax

learning the theory behind classes is a big stepping stone. Trying to wedge how JS prototypes into that is a nightmare.

But once you get how classes work, **you have to follow through with how prototypes work in JS**.

---

# Destructuring

Arrays are tricky, but easier to grasp when you use temp variables and do things the verbose way first.

Destructuring makes sense when you learn how arrays work!

---

## So it turns out every time your math teacher made you do things the hard way, them taught you a formula? That **was** for your own good.

![inline](GIFS/dog-not-impressed.jpg)

---

## An aside on code reviews

We need to change the way we think about code reviews from this:

![inline](GIFS/codereview.jpg)

---

## And this

![inline](GIFS/sheldon-smug.gif)

---

## To this

![inline](GIFS/goodcarousel.gif)

---

# But why do we care about new developers?

---

(If you're really asking yourself that...you might want to think about your outlook and get yourself some perpsective...)

![inline](GIFS/rethinkthatmove.gif)

---

# New developers are vital to the continuation and life of the software development community

---

We don't solve some **really important** problems because we don't have the perspective to be aware they exist or solve them in a way that actually helps those that are affected

---

# More developers = more diversity = more perspective = BETTER SOLUTIONS.

---

We need to think more about how to make our code more readable, more understandable, and reach out to new developers.

---

# It's hard. But it's absolutely worth it.

![inline](GIFS/victory.gif)

---

# In summary

* ES2015 and new features are great! 
* But we need to keep new (and not-so-new) folks in mind!
* We're all in this together

---

# Thanks for listening!

![inline](GIFS/mine-mine-mine.gif)

@nodebotanist on twitter, github (slides are up there under frontporch-2016)
the@nodebotani.st