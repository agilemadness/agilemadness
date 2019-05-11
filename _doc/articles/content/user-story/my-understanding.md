---
title: My Understanding
---
User stories - as described by [Ron Jeffries](https://en.wikipedia.org/wiki/Ron_Jeffries) one of the founders of XP -
have 3 critical aspects **Card**, **Conversation**, and **Confirmation**. I quote
these two paragraphs from his
[article](https://ronjeffries.com/xprog/articles/expcardconversationconfirmation/).

> User stories are written on  cards. The  card does not contain all the
> information that makes up the requirement. Instead, the  card has just
> enough text to identify the requirement, and to remind everyone what
> the story is.

> The requirement itself is communicated from customer to programmers
> through  **conversation**. The  **conversation** is largely verbal, but can be
> supplemented with documents. The best supplements are examples; the
> best examples are executable, We call these examples **confirmation**.

[Mike
Cohn](https://www.linkedin.com/in/mikewcohn/?lipi=urn%3Ali%3Apage%3Ad_flagship3_pulse_read%3B1lP6stfyQLGxm0Ocqbb0vQ%3D%3D) - Agile Coach and one of the founders of Scrum Alliance -
mentioned in [one of his presentations](https://www.mountaingoatsoftware.com/uploads/presentations/User-Stories-Product-Backlog-Scrum-Gathering-Chicago-2008.pdf) that **If requirements are written
down then at best you'll get what's written**. So the stories should
emphasize the user's **goal** not **system attributes**.

He mentioned the following in one of his
[articles](https://www.mountaingoatsoftware.com/agile/user-stories) too 

> Detail can be added to user stories in two ways:By splitting a user
> story into multiple, smaller user stories. Or by adding “conditions of
> satisfaction.”. The conditions of satisfaction is simply a high-level
> acceptance test that will be true after the agile user story is
> complete.

One more thing that I need to mention here is **the Product backlog
refinement session** which most of the cases has been merged - wrongly -
with the planning meeting, the below paragraph quoted from the [Scrum
Guide](https://www.scrumguides.org/docs/scrumguide/v2017/2017-Scrum-Guide-US.pdf).

> Product Backlog refinement is the act of adding detail, estimates, and
> order to items in the Product Backlog. This is an ongoing process in
> which the Product Owner and the Development Team collaborate on the
> details of Product Backlog items. During Product Backlog refinement,
> items are reviewed and revised. **The Scrum Team decides how and when
> refinement is done**. Refinement usually **consumes no more than 10% of
> the capacity of the Development Team**. However, Product Backlog items
> can be updated at any time by the Product Owner or at the Product
> Owner’s discretion.

### Based on the previous quotes, I see it as follow

1. Stories should start as a title (the front of the card) which is
considered as an invitation for conversation. It's advised to be in the
format of "As a ... I want to ... So that ..." to describe who, what and
why of the story.
2. In the backlog refinement (grooming) session, the team will have a
conversation to get more details about the story.
3. As a result of the grooming session the story should have its conditions
of satisfactions (The back of the card) which **should state an intent not
a solution** (e.g. “The user can choose an account” rather than “The user
can select the account from a drop-down”). Some people call it
Acceptance criteria and take it more further by using it in ATDD
(Acceptance test driven development) by converting this acceptance
criteria to executable (automated) test cases.
4. If there is still more details needed, These kind of details would be at
the sprint planning meeting or when the team starts coding this
particular story. These details go into two places, either Team
documentation or Automation Test cases.

Finally, I believe that there is nothing saying that agile has no
documentation **at all**! "Communication over Documentation" is a widely
used sentence, I don't know it's origin. Some consider it as one of
agile values, but the four [agile values](http://agilemanifesto.org/) are
* Individual and interactions over process and tools
* Working product over comprehensive documentation
* Customer collaboration over contract negotiation
* Responding to change over following a plan

I hope this was helpful. I'd like to talk about "Definition of Ready" in
more details and how I think it should be applied but that's another
article!

