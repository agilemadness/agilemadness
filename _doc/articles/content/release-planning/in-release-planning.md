---
title: What needs to be done in Release Planning?
sections:
  - Defining Scope User Story Mapping
  - Estimation User Story Sizing
---

Mainly in release planning you will need to define the scope and
estimate how long will it take.

### Defining Scope User Story Mapping

For defining the scope I really like the User Story Mapping approach, it
may be used for planning multiple releases too.

[User story mapping](https://jpattonassociates.com/user-story-mapping/) is a technique introduced by Jeff Patton, It's a way
to replace traditional flat backlog. One of its objective is to collect
requirement collaboratively by enabling all participants from creating
backlog on a wall.

Story map structure is **Activities** > **Tasks** > **Stories**, and it may look
like the following board.

Activities should show from left to right a complete user journey,
Stories should be ordered top-down by priority. each horizontal swim
lane shows a release.

<img style="width:100%" 
src="https://media.licdn.com/dms/image/C4D12AQGbh-VkGq6WRw/article-inline_image-shrink_1500_2232/0?e=1562803200&amp;v=beta&amp;t=BruJpeEpzZyrXOj7dIPWm2QzTUytYfCS9WkilMM_V58">

### Estimation User Story Sizing

The most famous approach for estimating group of product backlog items
is relative sizing, which is concerned by the relative value instead of
the absolute value of the PBI. Imagine PBI sized like T-Shirts Small,
Medium, Large, X-Large..etc. this is good to show the relativity idea
but it won't be easy to say "we have 10 Large & 20 Small PBIs, how long
will it take?"

That leads us to **story point sizing**, Story points are a measure for
expressing estimated effort to finish PBI, the available values are
derived from the Fibonacci sequence 1,2,3,5,8,13 to express the
relativity. When you have a backlog with total 100 story points, If you
knew that the team able to finish 20 points in one sprint. Then you can
easily have an estimated time to finish the whole backlog after 5
sprints.

A FAQ here why story points? Why not time like the usual man-hour or
man-day? In Scrum besides "The Increment", there are 2 more artifacts
"Sprint Backlog" & "Product Backlog" both need to be estimated in
different times with different amount of available information.

* **Product Backlog**: Estimates needed in release planning or once a new PBI
is available to define priorities and basic schedule. Only abstract
information are available.
* **Sprint Backlog**: Estimates needed in sprint planning when detailed
information are available
That's why it's preferred to measure both backlogs in different units,
Sprint backlog in hours and product backlog in points, Mike Cohn write a
very detailed
[article](https://www.mountaingoatsoftware.com/blog/sprint-and-release-planning-should-be-in-different-units) answering this question.

There are many techniques that could be used to estimate your backlog by
story points. The most common techniques is **"The Planning Poker"**, but
there are some other useful techniques like **"Relative Sizing Grid"** and
**"Crumb Scale"**.

**The Planning Poker** is a consensus-based estimating technique. to start
a poker planning session, the product owner describes user story to the
team. Each member is holding a deck of Planning Poker cards with values
like 0, 1, 2, 3, 5, 8, 13 ..etc. When the feature has been fully
discussed, each member privately selects one card to represent his
estimate. All cards are then revealed at the same time. If all members
agree on the same value, that becomes the estimate. If not, The high and
low estimators should share their reasons. Then the whole team reselects
an estimate card and the process is repeated until consensus is
achieved.*

As planning poker relies on relative sizing, the main challenge that
face the team is estimating the first item in the backlog or setting the
baseline that will be followed in the rest of the estimation process. My
recommendation is the team selects 3 stories with values 1, 3 and 8
without using planning poker just through the discussion, then the team
use planning poker to estimate the rest relatively to the chosen
stories. Mike Cohn recommending almost a similar idea in this
[article](https://www.mountaingoatsoftware.com/blog/the-best-way-to-establish-a-baseline-when-playing-planning-poker).

Based on my experience planning poker is not that easy for teams that
are new to the relative sizing concept, that's why I recommend either
"Relative Sizing Grid" or "Crumb Scale" for teams new to the concept.

**Relative sizing grid** [*](https://www.excella.com/insights/sizing-agile-stories-with-the-relative-sizing-grid) session starts by having a 2-axis grid for risk
and effort, team starts to put stories in the suitable position
relatively to each other, then reveal the boundaries to determine story
sizes.

<img style="width:100%" 
src="https://media.licdn.com/dms/image/C4D12AQED4D5lZsJIow/article-inline_image-shrink_1500_2232/0?e=1562803200&amp;v=beta&amp;t=FDILja1gcX_eaC7d2g2_l9-9yylT5Q9DblalBUMKrNo">

**CrumbScale** [*](https://rallypointbacklog.squarespace.com/crumbscale/) session starts by dropping stories one by one ordered in a
new list, just like "Insertion Sort". Then starting at the smallest and
give it **1**, then when you find a story twice as big as it's previous one
give it **2** and so on.

I hope this was helpful. I'd like to talk about "Consensus Games" in
more details **but that's another article!**


