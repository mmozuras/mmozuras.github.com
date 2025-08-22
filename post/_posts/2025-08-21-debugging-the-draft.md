---
title: Debugging the Draft
background: notebook
excerpt_separator: <!--more-->
---

This blog post explores why and how I use LLMs to help me write these blog posts. And yes, this blog post itself had help from ChatGPT.

Crafting a blog post (or any longer article for that matter) from a blank page has never been easy for me. That was true no matter the circumstances - even when I have a clear idea of what I want to write and a structure in mind. I write "was true" because that was the case until [LLMs (Large Language Models)](https://en.wikipedia.org/wiki/Large_language_model) reached a point where they are sufficiently capable for the task of drafting.

<!--more-->

### Editor

Give me something that already exists - no matter how messy and wrong - and I can immediately start patiently refining it until perfection. Give me a blank page, on the other hand, and I'll experience writer's block and start crossing all the other tasks off my to-do list.

This ability to focus on improvements has also been true in my career as an engineer. While some engineers love building things from scratch, the task I've enjoyed the most was debugging. As an engineer, I loved solving complex bugs - loading the system into my head, figuring out what's happening, and finding the right line of code to change. I took great satisfaction in solving this kind of puzzle and improving the system at the same time.

(_especially satisfying when the solution was just a single code change_)

And if it wasn't debugging, improving the code in other ways also brought me great delight.

I can build from scratch, but it isn't where I shine. I know engineers who have the superpower of building things. The list includes Vinted's co-founder and another early teammate. I still remember Vinted's co-founder coming back after a weekend, having created an admin site. Was the code perfect? Far from it. Was it working? Yes.

I admire this ability, but it's not something I possess. My happy place is when there's already something to improve.

(_or delete, deleting code is always fun_)

### Tooling

Something to improve is what LLMs can provide. I use [ChatGPT](https://chatgpt.com), but imagine other models and tools would work just as well. ChatGPT provides me with an instant first draft that I can edit. I won't publish that draft - honestly, not even close - but it gives me something to refine, and refining is much easier for me.

I created a custom GPT, titled "Coding Fearlessly." I uploaded my recent posts and tuned the GPT for my style: short headings, simple language, and some meta commentary.

The drafts this GPT produces are still off. They were way off with GPT-3 and GPT-3.5, to the extent that I did not use them at all - there are things that can be improved, and there are things that are so far off that it seems impossible. With the GPT-4 family of models, the drafts have become good enough to serve as a helpful starting point.

Getting a helpful draft also requires me to provide enough detail in my initial prompt. Otherwise, how can it try to tell my story? Oddly, unlike writing a draft, writing a long prompt to ChatGPT is easy. I know that it's just a prompt, and I can just throw a bullet list of things I want the draft to include.

Editing these drafts provides me with a very similar experience to refactoring code. It's easier to edit something that vaguely sounds like me than to conjure "me" from scratch. It makes the writing and thinking process more enjoyable for me.

When I'm happy with the text, I also use ChatGPT as a feedback generator. I input my text and ask for feedback. Some of the feedback is very helpful (e.g., noting that a specific paragraph lacks personal details/story), and it forces me to make further edits.

### Example

As an example, I'll share what I used to craft my most recent blog post on [Mortality](mortality) (click the link to view the blog post itself). Here's the prompt I used:

> Draft a blog post about mortality. Thoughts to build around:
> - I first started thinking about my own mortality early in my teenage years. Before then, I was religious (Christianity) and it was not something I thought too much about. Religion provides a convenient answer. I distinctly remember dawning on me that there's noone answering when I try and talk to God. The more I thought about it, the more I started seeing religion as a human-made thing. It was a very powerful experience, especially when I started considering my own mortality.
> - My atheism was further strengthened when in my late teenage years and early adulthood, I've read several books, "God Delusion" by Richard Dawkins among them. I became quite aggressive in my atheism for a year at that moment.
> - These days, the topic of mortality is on my mind for several reasons. My son (5-months now) just made me think about life a lot more. The book "More Everything Forever" triggered these thoughts, because it describes how some people are trying to escape mortality.
> - Thinking about my own mortality is still very difficult for me. I hope that writing this blog post will help me. It is very painful to imagine that there will be a moment when I am no more.
> - It also makes me feel a lot more powerful towards my son. Life is the biggest gift.

And you can click [here](/static/mortality-draft.txt) to look at the draft that ChatGPT generated.

If you take a look at both, you can probably see how the two texts are related to each other. Some sentences survived the evolution from the draft to the final text entirely.

Yet, there are also very significant differences. The initial draft is only 550 words (from my 220-word prompt), and the final text is over 1200 words. I added more personal details and stories, and removed some sentences that didn't align with how I want to communicate.

(_I can't imagine myself saying "the way the rules were always human-sized"_)

### Wiring

This editor-over-inventor bias is likely connected to [my borderline-autistic tendencies](/am-i-autistic). I prefer structure, am comfortable with routines, and enjoy loading a system into my head and probing it for errors. It feels like the same wiring: debugging suits me, editing suits me, and inventing from nothing suits me less so. The trick is to accept my strengths and build a workflow that respects my brain chemistry instead of fighting it.

So yes, ChatGPT helps me write the first draft. I still debug the draft until it runs exactly as I intend. What I publish still feels like something that is completely mine, coming from a process that was easier than before.
