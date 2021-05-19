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

