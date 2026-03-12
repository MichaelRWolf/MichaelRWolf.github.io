---
layout: post
title: "Getting into the head of a developer"
date: 2026-03-12
tags: [AI, TDD, SoftwareCraftsmanship, OpenSource, LLM]
---

![Constraints allow testing](/images/Constraints_allow_testing.png)

I used to get into a developer's head by reading their books.
Then I learned to read their code.
Now I read their `SKILL.md` files.

These are plain English documents that developers write to instruct AI agents on how to behave. Not Python scripts. Not JSON configs. Just readable paragraphs — distillations of decades of hard-won expertise, accessible to anyone in a two-minute scan.

Matt Pocock [skill_repo] recently wrote about the `SKILL.md` he built to teach an AI how to do test-driven development [tdd_skill]. His AI `skill` is easy reading — a testament to the human skills he's spent decades sharpening: coding, testing, writing, and teaching.

What's in it? A checklist of constraints:

- strict red/green/refactor cycles
- vertical slices
- using only external interface
- minimal new test when green
- minimal new code when red

That list doesn't just tell an AI what to do. It shows anyone exactly what Matt believes about software craftsmanship. His mental model, compressed and made visible.

He puts it well:

> "The skill isn't about perfect tests. It's about honest tests through forced constraints."

I've been working through other people's `SKILL.md` and `AGENT.md` files lately. The good ones (and this is a great one) distill decades of technical wisdom in comprehensible English.

But GIGO also applies — if someone has unclear thinking, the garbage-in to the skill will generate garbage-out when applied through the AI.

Good writing is an act of thinking clearly and communicating effectively, whether that is a murder-mystery, an AWS micro-service, or an AI skill.

The GNU Manifesto argued, in 1985, that charging a royalty to use a shared language is inherently wrong — and that shouldn't have stopped teachers, novelists, or reporters from charging for their mastery of that free-of-charge language — English. That fundamental idea has created enormous value to humanity even as free and open have taken on new realms: Open Source, Open Data, Open Interfaces.

Continuing the upward trend, I am starting to see *Open Work Flows* as I read people's minds (by reading their `SKILL.md` and `AGENT.md` files). As argued over 40 years ago, freely giving away what now amounts to the "source code" does not diminish the value of practitioners' mastery while using that free-of-charge artifact. Matt knows that he doesn't need to charge for the AI 'SKILL.md' files, but *can* charge for his own skill at using them.

Thanks, Matt, and many others for carrying on the tradition of letting us see freely into your minds and stand gently on your shoulders.

That's how civilization advances.

---

References:

- Original article: <https://www.aihero.dev/skill-test-driven-development-claude-code>
- [skill_repo] Matt Pocock's skills repository: <https://github.com/mattpocock/skills>
- [tdd_skill] TDD skill in that repo: <https://github.com/mattpocock/skills/blob/main/tdd/SKILL.md>

---

#AI #AISkills #TDD #SoftwareCraftsmanship #OpenSource #LLM #AgentDrivenDevelopment
