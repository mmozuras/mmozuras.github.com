---
title: Theory of Constraints
background: traffic_jam
excerpt_separator: <!--more-->
---

I've been thinking about [theory of constraints (TOC)][toc] and organizational design for the last couple of weeks. In this blog post, I start by describing TOC, give an example on how it can be used and my thoughts on how to apply TOC when thinking about team or organizational design.

<!--more-->

### Constraints

I learned about TOC through the book "Critical Chain" by [Eliyahu Moshe Goldratt][eli]. The book was recommended to me by my good colleague. Goldratt's earlier book "The Goal", which is still in my to-read list, introduced the world to TOC.

TOC is a management philosophy to help understand and adjust operations within an organization. Before TOC can be used, we have to know the objectives of the team or organization. Then we start by identifying what's hindering the achievement of those objectives and we improve the operations by eliminating that constraint.

There's always at least one constraint in an organization. If there was nothing preventing from achieving higher throughput, its throughput would be infinite – which is impossible. When the constraint is eliminated, something else becomes the constraint. The process to find and eliminate constraints is continuous.

That's the gist of it. In full, TOC consists of three core principles, six implementation steps and five step thinking process. I won't go in depth in this post.

### Example

Let's use an example to understand TOC. Imagine five cross-functional development teams. The overall objective is to launch a new product. Each team is working on a part of the product. Four of the teams plan to complete their parts in a month. The fifth team - two months, which means the product will be launched in two months. In this example, the development in the fifth team is the constraint preventing from achieving the objective faster.

Next, we must maximize the productivity of that fifth team. Non-constraints should provide the constraint with exactly enough to fully utilize the constraint. For example, by transfering software developers from non-constraint teams to the fifth team.

It would be a mistake for one of the four teams to optimize their own work. This kind of isolated throughput improvement - a local optima - would do nothing for the overall objective. The product wouldn't be launched faster if one of the teams ships their part sooner. Instead of the local optimizations, we should consider global optimization.

It would also be a mistake for the other teams to start new projects before this product is launched. That might only make the constraint worse by interacting with the constraint.

### Org

iv. example of how to use in org design

v. misidentifying can lead to poorly performing organisation (example: optimising supporting teams when the delivery team is the constraint)

[toc]: //en.wikipedia.org/wiki/Theory_of_constraints
[chain]: //goodreads.com/book/show/848514.Critical_Chain
[eli]: //en.wikipedia.org/wiki/Eliyahu_M._Goldratt
