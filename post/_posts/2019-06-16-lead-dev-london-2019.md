---
title: Notes from The Lead Developer London 2019
background: london
excerpt_separator: <!--more-->
---

On 11th and 12th of June, I attended [The Lead Developer London 2019 conference](//london2019.theleaddeveloper.com). This was my fourth time attending Lead Dev. I've also attended it in [2015](//2015.theleaddeveloper.com), [2016](//2016.theleaddeveloper.com) and [2017](//2017.theleaddeveloper.com). I went alone to the first Lead Dev ever in 2015. Every subsequent time I brought more and more co-workers from [Vinted Engineering](//engineering.vinted.com). The conference itself grew too. It's now in multiple countries around the world and welcomes multiple times more participants.

<!--more-->

The things my co-workers and I learned over the years in Lead Dev have greatly influenced how we work and lead at Vinted. As one of us said this year - "it's the most useful conference I've ever attended". Lead Dev is also the conference that inspired the existence of [Vilnius Tech Leads](/vilnius-tech-leads-year-one).

I came to this year's conference in London without getting familiar with the schedule. I didn't have to. The conference is a two-day single-track event, and I trust the organizers with their curation skills. Even if I have never been able to get invited to speak myself. Not for lack of trying. The bar is high, and I hope to be someday able to clear it.

The videos from the conference will be uploaded in a couple of weeks, I recommend to check them out. In the meanwhile, I share some of my notes from the talks. I don't agree with everything I share here, but I found all of it interesting and compelling. Hopefully, they'll give you the sense of what Lead Dev is about and inspire you to visit also. Listed in chronological order.

------

### [Lara Hogan](//twitter.com/lara_hogan), <i>Navigating team friction</i>

The first day started with the wonderful Lara Hogan taking the stage. [Her book on Resilient Management](//resilient-management.com) came out during the conference. I've already bought it and started reading it.

- cardiac surgeons
  - more experience = kinda better at their job, but only at their home hospital
  - familiarity with the team/teams is important
- [Tuckman's stages of group development](//en.wikipedia.org/wiki/Tuckman%27s_stages_of_group_development)
  - forming, storming, norming, performing
  - it's a cycle that's always happening: team changes, goals change
  - team health is something to continue iterating on
- from storming to norming
  - critical
  - brains, feedback, team processes
- from forming to storming
  - amygdala, reacting
  - brains, core needs
  - [BICEPS](bit.ly/biceps-core-needs): belonging, improvement/progress, choice, equality/fairness, predictability, significance/status.
  - an example through desk move
- storming - norming
  - feedback equation: observation, the impact of behaviour, question (better "open question") or request
- norming - performing
  - team processes, retrospectives, team charters and docs

### [Asim Hussain](//twitter.com/jawache), <i>I can't do that for you Dave: undefined is not a function</i>

- [aijs.rocks](//aijs.rocks)
- [the mojifier](//themojifier.com), detects face and puts on an emoji on the face based on emotion
- there's an API for that, don't jump straight into machine learning
- [TenserFlow, MobileNet and I'm fine](//aijs.rocks/inspire/tensorflow-mobilenet-and-im-fine/)
- dynamically generated alt text
- [pix2pix: cats](zaidalyafeai.github.io/pix2pix/cats.html)
- [vid2vid](github.com/NVIDIA/vid2vid)
- [StackGAN](github.com/hanzhanggit/StackGAN)

### [José Caldeira](//twitter.com/jose_e_caldeira), <i>Engage teams to achieve high performance</i>

- high performance in 5 steps
  - goal: bold, crisp, impact, simple
  - constraints: embrace, impose, mandatory
  - principles: options, align, focus, fast
  - pitch: sell everything to everyone, energize, promote, consistent
  - storytelling: empathy, the path not the result, truth doesn't lie
- memorable goals, creativity through constraints, autonomy with principles, motivation by pitching, engagement by telling stories

### [Whitney O'Banner](//twitter.com/woobanner), <i>Bottoms up with OKRs</i>

- OKRs: we will (objective) as measured by (key result)
- [WCAG compliance](//www.w3.org/WAI/standards-guidelines/wcag/) - accessibility guidelines
- tip: skip individual OKRs, tasks not individual OKRs
- tip: ignore the metrics, focus on the outcomes
- what matters might not be measured, what is measured might not be important
- SWAG: sophisticated wild ass guess
- tip: avoid cascading goals, take a bottoms-up approach

### [Ronald Ashri](//twitter.com/ronald_istos), <i>The developer's conundrum: what on earth does it mean to build AI software</i>

- clearly an AI spring, everyone wants to do AI, the bubble will pop and the [winter is coming](//en.wikipedia.org/wiki/AI_winter)
- VCs, press and politicians might move on, but tools and techniques will stay
- AI: a field of science, attempts to understand how intelligence works and validates its hypotheses
- delegate decision-making to machines: AI provides methods that are pertinent to solving these problems
- agent-based engineering
- increasing self-direction: passive agent vs reactive agent vs proactive agent vs autonomous agent (generates goals based on its own motivations)
- design the model (F = ma) vs discover the model
- applications are hybrids of designed models and discovered models
  - Google Maps: a designed model of the route network, discovered model to recommend the best route
- don't ask if you're using AI, ask instead if you successfully delegated decision-making to software

### [Rebecca Hill](//twitter.com/rebekaka), <i>Guiding self-organizing teams</i>

- self-organizing teams
  - self-governing > self-forming > self-organising > manager-led
- people are unique, so are teams
- take care of yourself, be kind to yourself and others
- perfection doesn't exist, and that's ok
- shared a story of a single team that worked with Rebecca
- people come first, they take time, they are worth it

### [Heidi Waterhouse](//twitter.com/wiredferret), <i>12/10, Excellent doggo: the power of positive transformation</i>

- [Crufts dog videos](//www.youtube.com/watch?v=LW4HieJXX6A)
- how to get developers to write docs?
  - mouth noises, no punishment or reward for writing documentation = no documentation
- traditional training, aversives: shame, fear, threats, reprimands, electric shocks
- positive training, incentives: rewards, praise, excitement, teamwork, mutual care and goals
- what causes a behaviour: goals + action + feedback
- clear goals: be clear with ourselves and others, personal goals aligned with company goals, respect others' goals
- the learner chooses the reward
- [B. F. Skinner](//en.wikipedia.org/wiki/B._F._Skinner): training pigeons to drop bombs, training dog to run up a wall
- [Making Work Visible](//www.goodreads.com/book/show/36458712-making-work-visible)
- think clearly about everyone's goals, figure out rewards together, commit for the long term

### [Angie Jones](//twitter.com/techgirl1908), <i>The reality of testing in an artificial world</i>

- story time: ad inventory, ad recommendation system, dress/trousers
  - "we don't need to test the machine learning feature"
  - resident expert opened a bug, closed bug, works on my machine
- as technology advances, so must our test approaches
- there is still a need for thoughtful and critical testing
- POCS (plain old common sense) can still trump an algorithm
- the future is here... test it!

### [Steve Williams](//twitter.com/StickyWilliams), <i>A team in ten minutes</i>

- team of volunteers, [RNLI](//rnli.org), 2.5M pound boat
- do you ever have to 'respond to a crisis'?
- how to build the crews: identity, defined roles, cultural rituals, regular meetings, strong social element, shared experiences
- beyond training: exercising
  - the focus switches from acquiring skills to applying skills
  - exercises should be real-world scenario based. example: missing kayak group instead of "execute search pattern alpha"
  - likely outcomes: richer networks, resilience (due to the stronger network), preparedness for the real crisis, and maybe some novel solutions too
- [Dave Snowden model](//en.wikipedia.org/wiki/Cynefin_framework): complex, chaotic, obvious, complicated

### [Melinda Seckington](//twitter.com/MSeckington), <i>Level up: developing developers</i>

- learning through playing and progressing: Donkey Kong, [Horizon: Zero Dawn](//www.guerrilla-games.com/play/horizon)
- FutureLearn strategy: grow our own software engineers
    - as a manager, Melinda is responsible for internal developer experience
- 10 lessons of game design (not the same as gamification)
  1. don't overload new starters (new people have a lot to learn, onboarding checklist)
  2. support and guide new starters (provide a mentor)
  3. make it clear what people should focus on (personal development goals, tie in with bigger picture career goals)
  4. give people direct and timely feedback (encourage teammates to do it themselves)
    - [Thanks for the Feedback](//www.goodreads.com/book/show/18114120-thanks-for-the-feedback)
  5. provide space to reflect and learn from the past (self-reflection, retrospectives)
  6. provide opportunities to apply new skills (identify training, training budget)
  7. acknowledge people's growth (regular salary reviews)
  8. expose essential competencies and how they're used
  9. allow people to choose their own path (generalize or specialize)
  10. visualize what progression looks like (career progression framework)
- growth levels - allow growing into multiple ways
- create developer experience: take ideas from user/gaming experience

### [Bethan Vincent](//twitter.com/bethanvincent), <i>What I learn about hiring diverse teams from conducting a fully-anonymous recruitment process</i>

- learning from building an anonymous recruitment process:
  1. people want to showcase "soft" skills alongside "technical" ones
  2. jobseekers want human connection (the platform felt inhuman)
  3. lengthy tests and at home exercises are not inclusive
  4. your job listing is just as important as the application process
  5. if we really care about diversity and inclusion, we need to listen

### [Brian Scanlan](//twitter.com/brian_scanlan), <i>Volunteers, not conscripts: fixing out-of-hours on-call</i>

- on-call is terrific, a great way to grow and learn
- at the same time, on-call is terrible
- a virtual team of volunteers, who decide if they volunteer based on their situation
- outside of office hours, the on-call team gets all pages
- product teams are responsible for their stuff when they're in the office
- on-call for 1 week: Friday evening to Friday morning (UTC)
  - 6-7 engineers, 6 months until switching away from the team
  - there's also an on-call engineering leader (who engineers can escalate to)
  - remunerated for each on-call week
- lots of low-value paging alarms destroyed (low-value low-level symptoms instead of customer experience)
- accidentally built a global, diverse, engineer-led virtual team
- takeaways
  - challenge every part of your on-call setup
  - understand your customers and SLOs
  - optimise for people, humans > computers, [HumanOps](//www.humanops.com)
  - delete a lot of your alarms
  - continuously improving your on-call buys time and focus for your teams

### [Kate Beard](//twitter.com/sbinlondon), <i>Give 10%, Get 110%</i>

- side project: [lumpy-gull](//glitch.com/~lumpy-gull)
- people who spend more time on side projects progress faster
  - this model prefers certain people
  - it's ok to have a life outside of your job
- 10% time allows them to learn without spending time outside of work
  - the junior squad is an initiative for juniors to actually spend their 10% time (support + new skills)
  - used for blog posts, talks, preparing for conferences and meetups
- structure and autonomy can co-exist
- empower people: give people trust, permission and room to learn and grow

### [Nickolas Means](//twitter.com/nmeans), <i>Eiffel's Tower</i>

- every organization is political
  - politics doesn't have to be bad
  - instead of a shit umbrella, the manager could be called a heat shield (block just enough)
- Eiffel had to do networking and self-promotion
  - a better way to call them - making friends and telling stories
  - Eiffel would tell about his previous work, show the final drawing of the future tower
  - Eiffel would also listen to their stories
  - telling stories (self-promotion): not in a braggy way, but in an informative way
- [How to Win Friends and Influence People](//www.goodreads.com/book/show/4865.How_to_Win_Friends_and_Influence_People)
- negotiation -> cooperation, working together to find an outcome that works for everyone
- [You Can Negotiate Anything](//www.goodreads.com/book/show/2232479.You_Can_Negotiate_Anything)

### [Pat Kua](//twitter.com/patkua), <i>Flavours of technical leadership</i>

- machine language, going up at the stack, [Grace Hopper](//en.wikipedia.org/wiki/Grace_Hopper)
- [Talking with Tech Leads](//www.goodreads.com/book/show/23270194-talking-with-tech-leads)
- architects champion CFRs
- leadership
  - ability to lead, something you can learn
  - the act of leading a group of people
  - not something assigned, anyone can do it
  - anyone can be a Leader, all it takes is a single action
  - maker to multiplier
- [Trident Model](//www.thekua.com/atwork/2019/02/the-trident-model-of-career-development/)
  - technical leader, individual contributor, management (managing the system in which people work)
- [Feynman technique](//fs.blog/2012/04/feynman-technique/)
  - the act of trying to explain something to someone else
- [The Architect's Clue Bucket](//www.slideshare.net/RufM/the-architects-clue-bucket)
- knowledge cultivator, the advocate, the connector, the storyteller

### [Dora Militaru](//twitter.com/DoraMilitaru), <i>Inclusion starts with an I</i>

- fixing equality is not just getting to a certain quota
  - [Mad Men](//en.wikipedia.org/wiki/Mad_Men) - every man has a secretary
  - quotas are necessary, but only temporary
- review job descriptions to be inclusive and not have too many requirements

### [Jonathan Stott](//twitter.com/jonathan_stott), <i>Business as usual: how to stop drowning and learn to swim</i>

- the problem
  - BAU: business as usual is not interesting
- the kiwi
- the project that will not start
- everyone leaves
- leopard changes its spots
  - BAU: support and maintenance
- the new role
  - went through the story of how they learned to understand and deal with their BAU (business as usual)
- the cliffhanger
  - adjust and adapt based on changing circumstances
  - don't lose your heart

### [Ola Sitarska](//twitter.com/olasitarska), <i>Behind the scenes of an effective & inclusive hiring process</i>

- the best indicator of someone performing well in the job is evidence that they successfully done similar work in a similar environment
  - hire for the job you have, define your responsibilities clearly
  - instead of requirements, write down what they'll have to do
  - be transparent about the role (ideally with a salary range)
  - build a representative pipeline
- steps
  - gathering information and getting the candidate excited about the job and the company
  - coding test: solve a simple problem and do a code review
  - interview: go through work history, gather evidence of them doing the job you defined
- scorecard to evaluate homework/code-review
   - ask specifically for evidence in the scorecard template
- blind code review - no one knows the name of the person who did the homework
- remember it's a two-way street, minimize the stress, care about candidate's experience

### [Miriam Busch](//twitter.com/miphoni), <i>Mobile development in 2019: native vs. cross-platform</i>

- iOS and Android developers are becoming more and more specialized, despite the cross-functional nature of the teams
- alternatives to native: React Native, Xamarin, Flutter
- platform specific problems disappeared after moving to a cross-platform solution, but it's not a free lunch
- you remove "do everything twice", but you're introducing additional complexity
- instead of supporting two platforms (iOS, Android), you hope to support one (React Native), but you actually support three
- it depends

### [Franklin Hu](//twitter.com/thisisfranklin), <i>Building security culture on infrastructure teams</i>

- Stripe: increase the GDP of the internet
- security culture through shaming
  - shame erodes our courage and fuels disengagement - [Brené Brown](//www.goodreads.com/author/show/162578.Bren_Brown)
  - learn from mistakes, don't shame
- security is everyone's job
- Stripe has mailing lists for shipped@ and fixed@ that capture what's happening
  - also team-specific lists for security-shipped@ and pre-shipped@
- Stripe has a magazine called "increment", had a recent issue on security
- three critical elements for building a security culture: responsibility, learning/growth and empathy

### [James Birnie](//twitter.com/runningChairJB), <i>Why we should be scared of Shor's Algorithm right now</i>

- cryptography: easy to do in one direction, hard to do in the other direction
- RSA is not safe, it can be solved with quantum computers
- governments are building quantum computers are keeping all the RSA data and traffic for future use

### [Julia Nguyen](//twitter.com/fleurchild), <i>Navigating front-end architecture like a Neopian</i>

- [Neopets](//www.neopets.com) - capitalism for kids
- architecture is a lot about upholding, improving and evangelizing standards
- [Indiegogo](//technology.indiegogo.com) performance team was created after they started noticing performance issues in their main page
- started by collecting metrics and understanding performance
- they've decided that Angular was one of their key bottlenecks
  - did front-end spikes to determine the right front-end framework for Indiegogo, primarily focused on performance
- infrastructure team's customers are developers, so make what makes them happy
- infrastructure teams should have junior/mid devs too
  - diversity is essential, as those teams serve other developers
  - infrastructure teams can feel like gatekeepers, fix that by sharing a lot publicly

### [Jonathan Rigby](//twitter.com/JonathanRigby), <i>How long is a piece of string: the key to solving the conundrum of software estimation</i>

- [Cocomo II estimate formula](//en.wikipedia.org/wiki/COCOMO)
- [#NoEstimates movement](//dzone.com/articles/stop-estimating-the-noestimates-movement)
- be transparent, especially when failing
- don't overdo things
- show empathy
- educate on the complexity of software estimation

### [Paula Kennedy](//twitter.com/PaulaLKennedy), <i>Silence isn't golden, it's deadly!</i>

- the problem of distributed teams not feeling like a part of a team
- one to one is the most critical meeting
- weekly standup: new faces, helps, interestings, events
- [Project Aristotle](//rework.withgoogle.com/print/guides/5721312655835136/): what makes the team effective at Google?
  - number one: psychological safety
  - next: dependability, structure & clarity, meaning, impact
- virtual off-sites / virtual happy hours to come together and talk

### Joanna Chwastowska, <i>Leading the team through a rapid growth</i>

- mobile computer on wheels = mobile computing at hospitals
- technology at hospitals is old and could be improved by a lot
- from day one build with quality, security and privacy in mind
  - hire experts for the above-listed things - one person can make a huge difference
- foster and guard the team's culture
- be clear on the goal, communicate openly, hire responsibly, care for people

### [Neha Batra](//twitter.com/nerdneha), <i>Facilitation techniques 202</i>

- set, engage, include, finish
- preparation for meetings and how to get everyone involved
- build the schedule that involves all kinds of activities
- are inclusive (in all kind of ways, for example, introverts)

### [Sal Freudenberg](//twitter.com/SalFreudenberg) and [Clare Sudbery](//twitter.com/claresudbery), <i>A button to pause time: how to live outside the clock</i>

At this point, I opened work Slack to check something. Instead of a quick open-and-close, I got distracted and engaged in a discussion about tech leadership and project management. Sadly, I missed the whole talk. Luckily, I will be able to watch all of it in a couple of weeks, when it's going to be uploaded.
