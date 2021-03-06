---
title: "100 days with Rust, or, a series of brick walls"
published_at: 2018-03-20T16:05:43Z
hook: A few thoughts on Rust after a few months of regular
  use.
---

Rust development log: day 100. Or so. It's starting to get
fuzzy.

Programming is hard. Learning new things in programming is
_especially_ hard. When all you know is imperative Python
and you move onto declarative SQL, expect to have to wrap
your mind around a lot of new challenging ideas. Don't
expect it to be easy.

Beginning anything fundamentally new feels like staring at
a brick wall that's blocking your path. The wall is
impassable until a point that you make a key discovery
which lets you make your through. Often that discovery is a
eureka moment -- it felt impossible only hours before.

But eventually you find your way into the clear. The walls
get smaller and you navigate passed them more easily. At
some point you might gain so much mechanical dexterity that
you find yourself in an open field -- you know the language
and its tooling so well that there's practically nothing
that can stand in your way.

My experience so far with Rust is that this doesn't happen.
In the beginning, the walls are higher than in other
languages, but surmountable: learning the ownership system,
understanding references, building intuition around
lifetimes.

Eventually you become a more experienced Rust programmer,
but things don't get much easier. There's always another
wall waiting around the next corner. The horribly anti-user
futures system, compiler messages generated by a misused
macros that are second only to C++ template errors in how
egregiously difficult they are to parse, universally
terrible documentation and lacking examples, unstable APIs,
type annotation hell, and so much more.

I'm still undecided on the language. I love that
Haskell-esque feeling where a compiling program is usually
a working program. I like the syntax and the tooling. I
don't like how little time I spend solving the problems
that are interesting to me. I estimate that I spend about
5% of my time building new domain logic, and 95% of my time
fighting the compiler over problems that are _appallingly_
in how uninteresting they are. Even something as simple as
abstracting a new helper function often turns into a
veritable odyssey because getting type annotations right
can be so difficult (especially where a third party library
is involved).

These thoughts are intended to be comprehensive, and I'll
write a more substantial defense at some point, but I
wanted to sketch a few feelings first. I intend to keep
pushing forward, but if forward progress doesn't get easier
in a few more months, I'll probably give it up (hopefully
with a post-mortem). Learning is always valuable, but I'm
starting to feel seriously concerned by how glacially slow
it is to get anything done.
