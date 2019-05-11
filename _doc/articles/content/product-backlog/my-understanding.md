---
title: My Understanding
sections: 
  - What is Product Backlog?
  - What is managing product backlog?
  - How to Manage Product Backlog?
  - How to write a good product backlog item?
  - Splitting User Stories
---

Before talking about how to manage product backlog, we need to agree on
what is a product backlog? and what is its managing process?

### What is Product Backlog?

Product backlog described in [Scrum
Guide](https://www.scrumguides.org/docs/scrumguide/v2017/2017-Scrum-Guide-US.pdf) as follows

> It's **an ordered list of everything that is known to be needed in the
product**. It lists all *features*, *functions*, *requirements*, *enhancements*,
and *fixes* that constitute the changes to be made to the product in
future releases. **Product Backlog items have the attributes of a
description, order, estimate, and value**. Product Backlog items **often
include** test descriptions that will prove its completeness when “Done.”

That's why mostly product backlog item (PPI) has one of these types
Epics, User stories, Tasks, Bugs, Spikes and Enhancements.

It's also mentioned that the product backlog is **dynamic**, **never complete** and **exists as long as the product exists**.

### What is managing product backlog?

[Scrum
Guide](https://www.scrumguides.org/docs/scrumguide/v2017/2017-Scrum-Guide-US.pdf) states that product backlog management includes

* Clearly expressing Product Backlog items;
* Ordering the items in the Product Backlog to best achieve goals and missions;
* Optimizing the value of the work the Development Team performs;
* Ensuring that the Product Backlog is visible, transparent, and clear to all, and shows what the Scrum Team will work on next; and,
* Ensuring the Development Team understands items in the Product Backlog to the level needed.

So I can tell that managing product backlog process is aiming to make the backlog **Clear, Ordered, Visible, Transparent and Understandable**.

### How to Manage Product Backlog?

When [Mike Cohn](https://www.linkedin.com/in/mikewcohn/?lipi=urn%3Ali%3Apage%3Ad_flagship3_pulse_read%3Bne9LqTCpRvy8rcrKn9vtOg%3D%3D&) tries to describe how to manage the product backlog items
in his
[presentation](https://www.mountaingoatsoftware.com/uploads/presentations/User-Stories-Product-Backlog-Scrum-Gathering-Chicago-2008.pdf), he mentioned that the product backlog is like
"iceberg". This image from
"[managedagile](http://managedagile.com/product-backlog-grooming-iceberg/)" describes it.

<img style="width:100%" 
src="https://media.licdn.com/dms/image/C4D12AQHXBlAMnKQOrg/article-inline_image-shrink_1000_1488/0?e=1562803200&amp;v=beta&amp;t=gNeoJhBYU5-Gy95a377iK5tZvl95h7WqbGLPTnjAcr0">

The “iceberg” idea is that as you pull items off of the top of the
iceberg, other stories that are at lower levels in the iceberg move up
to take their place. The process of developing stories and moving them
up the iceberg goes on continuously to feed the development
process.[*](http://managedagile.com/product-backlog-grooming-iceberg/)

### How to write a good product backlog item?

[Bill Wake](https://www.industriallogic.com/people/bill) - agile coach and trainer - created the [INVEST](https://xp123.com/articles/invest-in-good-stories-and-smart-tasks/) model for user
stories, which define the characteristics of a good story and it could
be applied to any PPI

* **I – Independent**: not overlap in concept, and be able to schedule and
implement them in any order.
* **N – Negotiable**: It is not an explicit contract for features; A good
story captures the essence, not the details.
* **V – Valuable**: valuable to the customer
* **E – Estimable**: Not an exact estimate, but just enough to help the
customer rank and schedule the story’s implementation.
* **S – Small**: should not be so big as to become impossible to
plan/task/prioritize with a certain level of accuracy.
* **T – Testable** : must provide the necessary information to make test
development possible.

### Splitting User Stories

One of the most challenging points in INVEST model is "**S- Small**", to
achieve it you need to split big user stories to smaller ones.

Splitting user stories is not as easy as it looks, it could lead to
dependency problems or to decrease the value of a PPI. that's why Mike
Cohn created the [S.P.I.D.R](https://www.mountaingoatsoftware.com/exclusive/spidr-poster-download) approach to splitting stories, each character
in S.P.I.D.R stands for a way of splitting a user story:

* **S - Spike:** Make a large story smaller by pulling out a spike. Doing a
spike makes the remaining work a manageable size or makes it easier to
see ways to split the story.
* **P - Paths:** Consider the paths through a story and split each path into
its own story.
* **I - Interfaces:** Split a story across multiple interfaces if supporting
those interfaces makes the story take significantly longer to develop.
Split out stories by browser type or version, or by different hardware.
Consider building a minimal user interface first or leave styling out of
an interface initially. 
* **D - Data:** Look for ways to split the story based on the type of data
that must be supported.Can a first story support valid data and a later
story add support for invalid data? How about frequent types of data and
less frequently seen types of data?
* **R - Rules:** Relaxing support for these rules in an initial story. Add
support for additional rules in subsequent stories. 

Finally, I'd like to mention what Mike Cohn mentioned in one of his
articles about small stories "**small stories are generally good, but
stories that are too small come with their own problems**". He said that
you can discover if you have too small stories when you face one of
these three problems

* Managing dependencies among many stories can become an issue.
* Prioritizing the product backlog becomes more challenging and
time-consuming.
* Too much stories in the sprint that make the team spend too much time in
tracking and updating stories in whatever tool the team uses.

I hope this was helpful. I'd like to talk about "Personas" in more
details and how it could be combined with user stories in "Product
Canvas" **but that's another article!**
