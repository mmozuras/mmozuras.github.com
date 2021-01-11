---
title: "Moneycode: Moneyball-inspired Thoughts on Hiring"
background: baseball
excerpt_separator: <!--more-->
hn:
---

I've recently read [Moneyball](//goodreads.com/review/show/3596995010), a book seemingly about baseball. It's not. Moneyball is about analytics, data-driven culture, and how to apply analytics to picking players. In this blog post, I share my thoughts on the book and the parallels between selecting players in baseball and hiring.

<!--more-->

I've watched the movie [Moneyball](//letterboxd.com/film/moneyball/) long before I've read the book. I liked the movie and marked the book as to-read. I only got around to it now. The film follows the book's story quite closely. I consider it a good adaptation.

The central Moneyball's character is Billy Beane (played wonderfully in the movie by Brad Pitt), a general manager of the Oakland Athletics baseball team. This team has one of the lowest budgets in the top American professional baseball league. Their budget is 3-4 times lower than the largest one. Yet, despite this constraint, with Billy Beane as their general manager, they competed with the top teams during the last two decades. Since 2000, Oakland Athletics have won 54% of their games. The top budget owner - The New York Yankees - have won 58%. Not a big difference for a huge difference in the budget.

So, how do they do it?

They use analytics to find players who are undervalued by other teams. People making hiring decisions in baseball have biases and beliefs. They might trust a baseball player who throws the ball differently. Data doesn't care about how the throw looks. Data only shows whether the player is more or less efficient.

Baseball is a very data-friendly sport. The primary interaction happens between a pitcher throwing a ball and a batter trying to hit it. It's simple to assess whether pitchers and batters are good at these jobs. For example, basketball is more challenging to evaluate with data, as there are many more actions done by the whole team to score points.

To evaluate how good a batter is, Billy Beane and his team focused on a single metric - on-base percentage. It's a bit more complicated than that, but simply put, it's a ratio of successful attempts to the number of total attempts. Quite logical and practical.

> What did that say about the measurement of performance in other lines of work? If professional baseball players could be over-or undervalued, who couldn't?
<br>
> -- Micheal Lewis, Moneyball

How does that relate to the hiring of engineers?

Alas, when hiring engineers, we're at a disadvantage compared to baseball teams. We don't have a trove of statistics or videos of performance. And to be clear, I'm not arguing we should. And even if we did, what kind of statistics would be useful? Hours at the desk or lines of code don't correlate with the actual value delivered. Lines of code would be akin to be measuring how many meters a basketball player ran during the game. It does tell something about what the player did but is not useful to understand the actual performance.

As a thought exercise, let's say baseball teams wouldn't have access to individuals statistics and videos. How would they conduct a hiring interview? I imagine they would:
- ask how successful was the team the player played in - did they win a lot?
- ask what did the player contribute to the team's success?
- ask to see the player play to simulate something close to actual performance

They definitely wouldn't:
- quiz about historical baseball knowledge
- ask the interviewee would do in a hypothetical baseball situation
- ask to play a game of cricket

The first set helps figure performance; the second set doesn't. And yet, engineering interviews are filled with the second set:
- questions that supposedly demonstrate how interested you are in the field of software engineering
- hypothetical questions - "what would you do if X?"
- asking the person to solve a problem in the interview room - with constrains one never encounters in actual work

While we don't have a lot of data when hiring software engineers, we can still strive to be data-driven. We can try to understand the actual past performance. We can ask about real situations the person encountered instead of hypothetical ones. We can ask them for code written in a scenario that's closer to the actual job instead of asking to invert a binary tree.

Max Howell, author of the wildly popular homebrew package manager, [failed Google's tech interview, because he couldn't invert a binary tree](//twitter.com/mxcl/status/608682016205344768?lang=en). To me, that's a top baseball batter failing the interview because he couldn't play cricket. In Max's case, there's a ton of data saying he knows how to build good software. I'm sure Google could've used Max somewhere in its software engineering department, numbering tens of thousands of people.

> Managers tend to pick a strategy that is the least likely to fail, rather than to pick a strategy that is most efficient. The pain of looking bad is worse than the gain of making the best move.
<br>
> -- Pete Palmer, Moneyball

If you're interested in Vinted's (where I work) hiring process, on Vinted's engineering blog, [Ieva Gražulevičiūtė wrote how we conduct our hiring process at Vinted](//engineering.vinted.com/2020/09/21/backend_engineer_hiring_process/). It's a worthy read.

Most companies are tech companies these days. The search for tech talent is challenging. At the same time, it's one of the most important things any company does. A company that does hiring well, just as Oakland Athletics, can get ahead.
