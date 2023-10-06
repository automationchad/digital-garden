---
created: 2023-09-17
tags:
  - 0🌲
---
Particularly in Silicon Valley, when one has a prototype or an inkling that works well, the temptation is to scale it out. Make it work for more people and more use cases, turn it into a platform, make the graphs go up and to the right, etc. This is obviously a powerful playbook, but it should be deployed with careful timing because it tends to freeze the conceptual architecture of the system.

## Why

General infrastructure simply takes time to build. You have to carefully design interfaces, write documentation and tests, and make sure that your systems will handle load. All of that is rival with experimentation, and not just because it takes time to build: it also makes the system much more rigid.

Once you have lots of users with lots of use cases, it’s more difficult to change anything or to pursue radical experiments. You’ve got to make sure you don’t break things for people or else carefully communicate and manage change.

Those same varied users simply consume a great deal of time day-to-day: a fault which occurs for 1% of people will present no real problem in a small prototype, but it’ll be high-priority when you have 100k users.

Once this playbook becomes the primary goal, your incentives change: your goal will naturally become making the graphs go up, rather than answering fundamental questions about your system (contra [[Focus on power over scale for transformative system design]]).

## On remaining small

One huge advantage to scaling up is that you’ll get far more feedback for your [[Insight through making]] process. It’s true that [[Effective system design requires insights drawn from serious contexts of use]], but it’s possible to create small-scale serious contexts of use which will allow you to answer many core questions about your system. Indeed: technologists often instinctively scale their systems to increase the chances that they’ll get powerful feedback from serious users, but that’s quite a stochastic approach. You can accomplish that goal by carefully structuring your prototyping process. This may be better in the end because [[Insight through making prefers bricolage to big design up front]]

Eventually, of course, you’ll need to generalize the system to answer certain questions, but at least in terms of research outcomes, it’s best to make scaling _follow_ the need expressed by those questions. In that sense, it’s an instrumental end, not an ultimate end.

See: [[A small ontological unit of experts in their respective fields is a good way to build a company]]