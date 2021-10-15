### Hi there, I'm Neil 👋

[![Linkedin Badge](https://img.shields.io/badge/Neil--Kakkar-0077b5?style=flat-square&logo=Linkedin&logoColor=white&labelColor=0077b5&link=https://www.linkedin.com/in/neilkakkar/)](https://www.linkedin.com/in/neilkakkar/)
[![Twitter Badge](https://img.shields.io/badge/-@neilkakkar-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/neilkakkar)](https://twitter.com/neilkakkar)

I work at [PostHog](https://github.com/PostHog/posthog), which is open source, which means I can now have Github stats and not feel disappointed:

[![neilkakkar's GitHub stats](https://github-readme-stats.vercel.app/api?username=neilkakkar&show_icons=true&include_all_commits=true)](https://github.com/neilkakkar)

---

<!--
**neilkakkar/neilkakkar** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

I love learning in public, and I want to use this section to track what I did at work. I'm a big fan of [data driven understanding](https://neilkakkar.com/the-human-log.html) - and I hope this log gives me a better understanding of what I'm getting done.

<details>
<summary>Things I'm doing: Click to expand!</summary>

## 15 October 2021
   
Wow, what a sprint! I finally started implementation on the huge-ass Quantitative Analysis Project. What's unique about this project is that I'm leading one for the first time. It started off like this: https://github.com/PostHog/posthog/issues/5543

I was working closely with one other person, and we got an MVP out in week 1. This was faaaast! It allowed us to iterate quickly, gather feedback, and fix data issues quickly. With a product that depends on data being good, this was critical.

I wouldn't link specific PRs, because there were a shit-tonne

![image](https://user-images.githubusercontent.com/7115141/137518354-09ce7a51-bbd9-476a-ae62-13060d287699.png)

Interestingly, I spent a lot more time thinking about the problems to solve here, even after work (which didn't bode well for sleeping peacefully). At the same time, this allowed for some cool technical breakthroughs, where we could run correlations much quicker.

Finally, doing live user interviews was fun - getting feedback from actual users, reading between the lines, figuring out what they want, and then putting those ideas together was a fun challenge: https://github.com/PostHog/posthog/issues/6474. The next sprint is going to be scary ambitious.

## 1 October 2021

Two weeks of working on Paths. We shored up the API, and I finally got my hands on the frontend code. Kea is an amazing library to work with.

One very interesting problem: Validating Graph Edges on Paths: https://github.com/PostHog/posthog/issues/6041 (and linked PRs!)

- Connect Persons on a Path to an API request: https://github.com/PostHog/posthog/pull/6035, https://github.com/PostHog/posthog/pull/6070
- API additions: https://github.com/PostHog/posthog/pull/6124, https://github.com/PostHog/posthog/pull/6111, https://github.com/PostHog/posthog/pull/6052
- Query Optimisations: https://github.com/PostHog/posthog/pull/6125
- Random Frontend stuff: https://github.com/PostHog/posthog/pull/6175, 

## 17 September 2021

A (missed) Offsite, Support Hero, vacation to Mallorca <3

## 20 August 2021

I owned my first project! https://github.com/PostHog/posthog/issues/5543

Apart from thinking hard about this, the regular sprint continues. [Working on Paths](https://github.com/PostHog/posthog/issues/5545) - the new feature!

https://github.com/PostHog/posthog/pull/5646

This week's been pretty cool, because I'm finally doing more of the ground-up startupy stuff: thinking through things from scratch, building PoCs, gathering results, and then finally building the product.

## 13 August 2021

Final sprint for Funnels, got the vaccine, got sick afterwards, didn't do much, except this one big bug fix for funnel breakdowns: https://github.com/PostHog/posthog/pull/5655, https://github.com/PostHog/posthog/pull/5538

## 6 August 2021

Remember how Support Hero was a lot of fun? (Week of 21 May, 2021). Time for round 2. A lot less overwhelming, as I knew a lot more about things (but still not everything).

Random bug fixes: https://github.com/PostHog/posthog/pull/5486 etc. etc.
   
## 30 July 2021

More bug fixes, some tricky things to grasp, and finally dipped into other unknown areas. I follow a land-and-expand strategy: get really good at understanding one part of the system, then slowly expand from that "base" to understand rest of the system. This usually means that my work speed slows down, as I parse through all the new stuff.

A good way to do this is to pick up bugs at the edges of what you know. That's what I've been doing:
- Dashboard bug: https://github.com/PostHog/posthog/pull/5395 
- Caching bugs: https://github.com/PostHog/posthog/pull/5399
- Breakdown in funnels bug: mix of frontend and backend issues - https://github.com/PostHog/posthog/pull/5357
   
## 23 July 2021

Final sprint before Funnels meant lots of QA, lots of bugfixing, and lots of testing :) - I'm so tired now.

- Special Bugs: When your new technologies don't work like you'd expect: https://github.com/ClickHouse/ClickHouse/issues/26580, and patches for it: https://github.com/PostHog/posthog/pull/5283
- Bug fixes: https://github.com/PostHog/posthog/pull/5174, https://github.com/PostHog/posthog/pull/5277, https://github.com/PostHog/posthog/pull/5292, https://github.com/PostHog/posthog/pull/5308, https://github.com/PostHog/posthog/pull/5315, https://github.com/PostHog/posthog/pull/5316

## 16 July 2021
   
Lots of gathering requirements, getting to the bottom of new features we want to implement: https://github.com/PostHog/posthog/issues/5074 - and reminders to think from first principles.

- And then doing it: https://github.com/PostHog/posthog/pull/5104
- Some code rearchitectures that make future-work so much easier: https://github.com/PostHog/posthog/pull/5043
- Random bug fixes: https://github.com/PostHog/posthog/pull/5055
   
## 9 July 2021

Who knew playing around with SQL, and generating interesting queries could be so much fun? This week was more dakka: more add ons, more functionality to the basic funnel APIs. Some clever refactoring + testing mechanisms, that I enjoyed setting up

- Interesting test infra setup with Funnel Breakdowns - https://github.com/PostHog/posthog/pull/5043
- Refactoring to remove obsolete concepts - https://github.com/PostHog/posthog/pull/5037
- Bells and whistles - https://github.com/PostHog/posthog/pull/5024
- Random bug fixes: https://github.com/PostHog/posthog/pull/5055


## 2 July 2021

Some big funnel improvements

- Remember to create tests for backwards compatibility! - https://github.com/PostHog/posthog/pull/4946
- Unordered funnels, people, and more - https://github.com/PostHog/posthog/pull/4943, https://github.com/PostHog/posthog/pull/4890

## 25 June 2021

I was getting pretty comfortable with my role, and that seemed like the best time to switch teams 😂. Purely co-incidental, we shifted focus, and I've been writing wonderful SQL this week. Damn, this is SO MUCH FUN. This week (and hopefully the coming few weeks, really want to brush up on my querying skills). This has been very helpful: https://pgexercises.com/

- Some complex funnels: https://github.com/PostHog/posthog/pull/4868, https://github.com/PostHog/posthog/pull/4863
- When revisiting setting up, always update docs for whoever comes after you :) - https://github.com/PostHog/posthog.com/pull/1506

## 18 June 2021

Finishing up new processes for the Plugin Developer Experience, plus excellent docs.

- https://github.com/PostHog/posthog-plugin-starter-kit/pull/7, https://github.com/PostHog/posthog.com/pull/1467
- Fun bug fixes: https://github.com/PostHog/posthog/pull/4772
- Odds and ends: https://github.com/PostHog/posthog/pull/4755, https://github.com/PostHog/posthog.com/pull/1497

## 11 June 2021

Well, plugin installation is deprioritized for now. New focus: plugin development experience! Lots of time spent thinking about how the documentation should look like, what workflows should the code promote, and what feels confusing.

- Making the Plugin Development Experience nicer: https://github.com/PostHog/posthog.com/pull/1467, https://github.com/PostHog/posthog/pull/4688
- Wrangling with BigQuery: https://github.com/PostHog/bigquery-plugin/pull/9
   - Good Habit of mind - when things are hard to debug, write code to make it easier to debug similar issues in the future: https://github.com/PostHog/plugin-server/pull/465

## 4 June 2021

Thinking about a big project, and learning enough about the interacting systems to design a decent solution can be hard! Really looking forward to finishing the plugin installation step.

- Plugin Install Step: https://github.com/PostHog/plugin-server/issues/405, https://github.com/PostHog/plugin-server/pull/456
- Debugging S3 Queues: https://github.com/PostHog/plugin-server/pull/451

## 28 May 2021

Getting comfortable with the codebase, starting to focus on reviewing others' code. It's interesting to try and model how new changes would affect the existing code. Further, this helped uncover my blindspots - glad I started this earlier than later!

- Some interesting bug fixes: https://github.com/PostHog/posthog-js/pull/233, https://github.com/PostHog/posthog-js/pull/234
  - Accompanying blog post: 
- Random odds and ends: https://github.com/PostHog/plugin-server/pull/441, https://github.com/PostHog/plugin-server/pull/447, https://github.com/PostHog/posthog-js/pull/236


## 21 May 2021

I was Support Hero this week! It's... intense! Lots of user issues that I first have to learn about myself, and then solve. This took a surprisingly long amount of time, but was very worth it: it helped me see where actual users of PostHog get stuck.

- Built Plugin Capabilities: https://github.com/PostHog/plugin-server/pull/384, https://github.com/PostHog/posthog/pull/4371
  - This was my first big feature: involving touching a lot of things and understanding the system, so I could come up with a decent solution. Fun stuff!
- Support fixes: https://github.com/PostHog/posthog-python/pull/32

It's funny how this appears to be the least productive week so far, but I felt I got much more out of it, vs the past 2 weeks. I ought to do Support Hero more often than the usual schedule, if possible.

## 14 May 2021

- Disallow Plugins from changing the teamID: https://github.com/PostHog/plugin-server/pull/381
   - I messed up here a bit, forgot to take care of batch events (https://github.com/PostHog/plugin-server/pull/396)
- Add Sentry+Django integration to Python library: https://github.com/PostHog/posthog-python/pull/13
- Bug fixes: feature flag rollout %: https://github.com/PostHog/posthog-python/pull/30
- Random typos and fixes: https://github.com/PostHog/posthog/pull/4315, https://github.com/PostHog/posthog.com/pull/1335

## 7 May 2021

Week 1 at PostHog!

- Build a new plugin - the Downsampling Plugin: https://github.com/PostHog/downsampling-plugin/pull/1
- Add support for `$set` and `$set_once` to Python library: https://github.com/PostHog/posthog-python/pull/23
   - I messed up here a bit: https://github.com/PostHog/posthog-python/pull/28 - be moaar careful about tests that don't pass on local but pass on master
   - Interesting difference in workflow causing bugs: I didn't think of pulling master because I'm used to working off of forks, vs pre-existing branches
- Random typos and fixes: https://github.com/PostHog/posthog/pull/4220, https://github.com/PostHog/posthog.com/pull/1307, https://github.com/PostHog/posthog.com/pull/1316

</details>

