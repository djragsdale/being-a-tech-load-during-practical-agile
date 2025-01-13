# Being a Tech Lead during Practical Agile

_This was originally developed as a conference talk for Nebraska.Code() on July 19, 2024._

In an ideal world, agile software teams smoothly build an incremental product with clearly defined roles and process, but who lives in an ideal world?

In practice, agile software teams have to cooperate with non-agile teams, turnover, external responsibilities, and changing needs. How and when do software teams evolve their methodology, such as moving from Scrum to Kanban? How do you manage cross-functional team members on loan from other teams? How do you coordinate with stakeholders that have conflicting goals? How do you transition from initial product development to feature development? How do you deal with inevitable turnover on your team?

While there is no silver bullet to being a tech lead during practical agile, each phase in the lifecycle of a product has goals, mindsets, and practices that guide you toward success.

## Why should you listen to me?

You shouldn't. Every company, every organization, every product is different. Your mileage will certainly vary.

I have been a tech lead, amongst other roles and responsibilities, for 8 years. Most importantly, I've failed many times and learned from my mistakes.

## 🛡 Always

### Roles

There are some roles you always have to fill as a tech lead.

* Shield
* Representative
* Decider (but not a dictator)

#### Shield

The tech lead's biggest role is being a buffer and a shield. Stakeholders are not the enemy, no matter how much it feels that way. They don't have the same goals and desires as the software team, which can greatly affect the team if given unfettered access to the team. You have to mediate the desires of the team with the goals of the stakeholders. You often have to parse complicated messaging from stakeholders or read the tea leaves. The reality is that stakeholders' goals need to be balanced against proper process and methodology. You have to show them how your process will help them achieve their desires. The best way to show them this is with results, and the best way to achieve results is to keep the development team focused on building software instead of dealing with politics or tasks outside their expertise.

#### Representative

Oftentimes, the organization needs a technical person to sit in conversations. You may need to sound an alarm when something is wrong. You may need to simply raise your hand and ask a question. In order to sound the right alarms or ask the right questions, you need to be competent in the technology your team uses. You don't need to be an expert. You don't need to know facts and figures off the top of your head. You need to have an intuition for when something needs to be checked. Your best friends will be the phrases "it is my understanding that", "in my experience", and "I will follow up on that."

#### Decider

You are not a dictator, but you will often have to cast the deciding vote or make judgment calls. It does not take much for decision paralysis to take effect. When you make a deciding vote like this, always ask yourself "how will I know if I was wrong?" There will be many times you have to simply choose one of a few acceptable options. All software development decisions involve tradeoffs; it is rare that a decision has no downside. Your team may disagree on which option is most likely to be the best fit. The best way to get consensus behind these decisions is to put a monitor in place which can detect when the chosen option is no longer acceptable. This is easier said than done. There will inevitably be a decision that not everyone likes, even you, but you must get everyone on board. Assume decisions were not made out of malice. Find the most charitable reason, share it with the team, and tell them plainly (yet compassionately) that the decision is made.

### Mindset

#### Big picture

Everybody on the team will be focused on the details of their tasks. You have to counter that. These aren't 2 sides fighting against each other. It is a matter of keeping your team balanced. Know the problems you are currently solving, but know that is merely a part of an overall, long-term product strategy.

#### Future-oriented

Most people will be looking at the present. When an architect is trying to figure out how to construct something, you have to lock them into the present but also make sure they are focused on the future. Don't reduce your adaptability. You can make a lot of mistakes by planning for an imaginary future, but you can make more mistakes by focusing on present conditions instead of anticipating what future needs will be. Some stakeholders may be extremely focused on the present. You have to remind them that maintaining software is expensive, and building it for the future, now, is cheaper than constantly revising the software to meet the present moment.

#### Principles, not specifics

A decent-sized team will have a few senior developers that can focus on specifics. Specific practices and implementation details should be decided by the team. You don't tell them what rules to apply, but you help them maintain the principles to focus on.

#### Humility

You won't be the person to get the acclaim. You may actually do some things that are really cool. It is likely that you were not alone in that, so you need to pass that on to the team. Share in every victory.

### Practices

#### Balance team and stakeholders

This is part of your role as a shield, but also something that is natural if you maintain a big picture, future-oriented mindset.

#### Keep technical skills sharp

You always have to do this. This is the easiest thing to let drop. You may be asked for 4x what you can deliver, meaning you cut 75% of that out in order to deliver working software. You will need to cut 80% of that out if you keep your technical skills sharp. Letting your skills dull is a strategic failure. Technical skills are part of the benefit you bring.

#### No blinders

You don't need to do all the code reviews. You probably shouldn't be touching much of the code your team is working on. You do need to know how it is being developed so that you can see what problems will occur. Otherwise, you will get blindsided by errors or miss red flags until they are causing urgent problems.

#### Set goals and values

Let your most senior team members define the rules. Goals and values are a structure to work within. Set aside the specifics. Communicate values and goals down to all team members so that they can make informed, smart decisions. Treat them like adults.

#### Don't overdue criticism

You probably became a Tech Lead because you were a good developer, architect, have a lot of experience, or are very good with a specific technology. Whatever reason you became a Tech Lead, you need to let your team do their jobs. The old adage "praise publicly, criticize privately" is still good advice. Steven Sinofsky said to "Save feedback for the critical and strategic elements." This extends to micromanaging, including micromanaging through editing. If you feel the need to put your fingerprint on every piece of work that comes from your team, you are reducing the amount of praise a team member can achieve. High-performing team members will choose to go to where they can be recognized for their good work. You want the best people on your team. As long as you communicate goals and values, people are probably making the right decisions. If you feel like you need to edit a lot, that is a sign that you're not communicating those goals and values well enough.

#### More questions than answers

There are always non-technical aspects to every job. In all of those, be compassionate and empathetic. It is really hard to put yourself in someone else's shoes. The easiest way to do that is to ask more questions than you give answers.

## 🧭 Planning

This could be a company that is ready to start up. This could be a new product in the works. This could be an incubated team within a larger company. Whatever the cause for the planning phase, you will likely have similar goals and roles.

### Goals

#### Risk detection

As a Tech Lead during a planning phase, you want to find the things that could throw you way off course. This does not include fixing the risk. You were likely chosen for this role because non-technical individuals needed someone to help them identify problems as early as possible, and to limit the amount of investment is lost to uncertainty. When you sit in a room with external stakeholders or people making budget decisions, risk is what they want you to communicate. You likely need to grade those risks in a clear, comprehensible, functional way.

### Mindset

* Boundaries and limitations/mental models
* User-centered design
* Basics
* Estimation
* Context
* Establish trust

You have to develop a communication strategy for stakeholders. These illustrations and analogies will be repeated by non-technical stakeholders, so always make sure you include what the limitations are to these illustrations and the products they represent. A mental model is simply the understanding of how something works combined with the boundaries it operates under. When you start developing software, you don't often know the market-fit and imagine it works everywhere for everything. You have to communicate boundaries.

You have to focus on the user. If you have designers, user-centered design may already be worked into your software. Focusing on the user helps to keep you from locking into technical decisions you don't want to make yet. You want to focus on the basics. Don't figure out how all the bricks fit together. Software takes time to design, architect, and build. Don't plan things too detailed. Much of what is designed should be flexible enough that the user can still get what they need even if minor details need to change.

### Practices

* Build team intentionally
* Set expectations
* Establish values
* Choose technologies and architecture
* Identify risks
* Project charter and team working agreement!

## 🕵 Start-up

Goals:

* Mitigate risk
* Prove product
* Deep education
* Flexibility

Mindset:

* Speed
* Simplicity

Practices:

* Time boxing
* Code reviews
* Teaching (or learning) how to troubleshoot
* Only document what's necessary
* Adjust when plans don't pan out
* 80/20 rule
* Research

## 🧙 Scale-up

Goals:

* Wide education
* Product market fit
* Find your blind spots
* Set yourself up to be profitable
* Redundancy

Mindset:

* Attach complexity for edge cases
* Priorities

Practices:

* Break down silos, team sharing
* Commmunicate with other teams
* Delegate, aggressively
* Automate and opreationalize
* Be a force multiplier
* Listen, uncomfortably

## 🛰 Feature Development

Goals:

* Triage bugs
* Answer questions
* Communication

Mindset:

* Know your people
* Know your product
* Know your problems

Practices:

* Find team members' strengths and weaknesses
* Whatever you have to do, do it compassionately and intentionally
* Reposition team, place people better
* Grease wheels internally, but face outward
* Write documentation that lowers cognitive overhead
* Remind your team of values
* Practice presenting and public speaking
* Statistics! You only do what you measure

## Questions

### How and when do software teams evolve their methodology, such as moving from Scrum to Kanban?



### How do you manage cross-functional team members on loan from other teams?



### How do you deal with inevitable turnover on your team?



### How do you coordinate with stakeholders who have conflicting goals?



### How do you transition from initial product development to feature development?


