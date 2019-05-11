---
title: How to overcome Faux-agile/Flaccid Scrum/Dark Scrum?
---
As you might notice, all the references in this article are
coauthors of the Agile Manifesto, and the most important most of
them are Extreme Programming gurus - Developers in the first
place, So I think you won't be surprised If I told you that they
think the solution of all these issues by adopting XP practices.
and I think they are totally right. XP are the only Agile
methodology that advice and tells how to do it, I believe it's
the only methodology made by developers to make their life
better.



**Ron Jeffries** in his article Dark Scrum mentioned some practices
that could help Scrum teams do it right and avoid Dark Scrum,
here it follow

*   Refactoring (Incremental Design)


    *   In a Scrum project, we’re supposed to deliver a tested,
working, potentially shippable Product Increment after each
Sprint. Obviously, we can’t have the whole design figured out at
the beginning: we only know roughly what the product will even
be. Equally obviously, we need to wind up with a good design at
the end. Therefore, the design of our software must be created
incrementally, a bit at a time.

    *   if we are going to deliver a Product Increment every Sprint,
we must find a way to do good design, incrementally.

    *   The best way we know today to do incremental design is
called “Refactoring”. Refactoring is the process of improving
the design of existing code — without breaking it!


*   Automated Acceptance Test


    *   PO and the developers to agree on concrete, executable
acceptance tests for each story.

    *   When we automate these examples, we can run all of them and
show with certainty that the product is still doing what we
agreed it should do.


*   TDD


    *   It’s very helpful to have a lot of little tests supporting
each larger acceptance test, because the little tests tell us
which bit we got wrong, while the acceptance test just screams
“Something Broke!”

    *   These tests also help us with larger refactorings.


*   Continuous Integration


    *   An automated build process, running the system’s test suite,
turns out to be an essential part of a Scrum team’s development
process. For most teams, the more frequently they build, the
better things go. Building “all the time” seems to go best

