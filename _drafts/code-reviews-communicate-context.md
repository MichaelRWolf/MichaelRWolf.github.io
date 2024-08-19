---
Title: Code Reivews Communicate Context
---

# LinkedIn post

Points

## Code Crafter's Common Challenge: Communicating Context

## Setup of common code review practices

- 'Developer' develops 'code' with access to much 'context'
- 'Developer' creates 'PR' (AKA code review request) for 'code'
- [Time passes...]  
- 'Reviewer' reviews 'code'
- 'Reviewer' assumes all 'context' is in the 'code'
- 'Reviewer' does not communicate directly with 'Developer'
- 'Reviewer' makes annotations in 'PR'
- [Time passes...]  
- [Repeat N times...]
- 'Reviewer' approves 'PR'
- [Time passes...]  
- 'Ship It!"


## Intro

In podcast episode #161 of "Legacy Code Rocks" (https://www.legacycode.rocks/episodes/161/), host Scott Ford and guest Chelsea Troy discuss Chelsea's claim that code reviews are a shell of what they could be if only the focus was on CONTEXT (i.e. regulatory constraints, avoiding buggy code, performance, backward compatability).  Focusing only on the code is to miss the core of a developer's job - find (or create) CONTEXT related to a  bug fix or feature request, then change the CODE while honoring the CONTEXT.

This piece of writing started as a way for me to summarize their discussion.  It had such "juice" for me that I expanded it to share with others.

## The State of the Practice (of code reviews)

The collection of developers (i.e. proto-team) has shared code, but
not shared context.  Communication is incomplete, and happens only through code and PR's (AKA code reviews).  Human-to-human communication is rare.  The context used (or created) by the developer is not available to the reviewer (who only has access to the code and the PR).

Code reviews have devolved to the prior century's (prior millinium's!)  hope (which is neither a plan nor a strateg) that we can achieve quality injection by gated inspection and hierarchical connection.  The hope is that developers will access context and tribal knoweledge, which in turn is expanded by individuals.

This podcast episode centered on code reviews, but complementary customs were considered, clarified, and critiqued.

## Current Customs

Chelsea observed (and Scott concurred) that most code reviewes have
become cargo-cult "approval gates", with minimal value to the code,
and no (or negative) value for the people.

People avoid code reviews like this

## Room for improvement?

Code contains a condensed collection of the real work -


Chelsea claims -
    Contrary to current customs, 
    CODE REVIEWS could communicate complex CONTEXT, 
    creating clean, consise, communal CODE


CODE is a conseuqnce of CONTEXT, condensing of all the REAL WORK -
conversations, collaborations, constraints, consensus, compromise,
compliance (to regulations), creativity, and critical thinking

All of this context was required to create the code.

None of this context (except the code) is available to review the code.

Having context during code review would create the primary desired outcome (better code).  Additionally, it would allow for learning - about the product, the architecture, the customer problem.  Imagine the richness that flows as a reviewer asks "Why did you choose this solution?" or "What alternatives did you consider?" or "What constraints prevented you from doing something else?"

Boulding's Backward Bias:
    Things are the way they are because they got that way.
  -- Gerald Weinberg, "The Secrets of Consulting".  1985.

This quip is not a tautology, it emphasizes the importance of context.

## Reviewers Revalidate and Reflect

One of the practices that Chelsea uses is brilliant - requiring that suggested improvements be communicated as working modifications to the submitted code.  By taking the role of developer, the reviewer must consider all the original context.  If (when!) they are missing a piece, that becomes a just-in-time learning opportunity to look it up, ask the team, or have a convetrsation with the original developer.

A free side-effect: having the reviewer do an independant edit and test will stress the build system, helping eliminate a class of problems: "But it works on MY machine"

## Multiply HOW and WHY (not WHAT)

If this is beginning to look like pair- (or ensemble-) programming,
I'm with you.  It looked that way to me, too, but Chelsea's focus on
CONTEXT, instad of CODE was both subtle and profound.  Move your focus
back a little bit (2-3 inches is enough).


Instead of imagining the expense  achieved by multiplying the number of eyeballs looking at the code,
imagine the investment achieved by multiplying the number of brains understanding the context.

This is how teams grow tribal knowledge.  And shared understanding.  And shared vision.


They share context.


================================================================
================================================================
================================================================
================================================================

## WIIFM?


Inspect-and-adapt is magic.  If the way you are doing code reviews isn't bringing the value you want, stop doing them that way.  Experiment.  Change.  Grow.  Uncover better ways to developing software, then help others do it.




This cross-training, cross-building is not repetative waste.  It is a quality test of the build process.  The "friction" is required for context transfer from one brain to another.  Repetion is not waste, it is a cornerstone for learning.  It's byproduct is a resiliant team, not prone to the fragility of siloed knowledge.

Whether you call this a social engineering hack, or (developer-to-developer) interaction design, doesn't matter.  I call it brilliant.

## Take-aways

Sofware is about soft stuff - knowledge.  We are knowledge workers.  If we treat knowledge as a valuable resource, we will engineer processes and practices that preserve our investment in its creation.  Or we will loose it, only to reinvest in reacquisition, or continue context-less.

Code reviews are one practice to preserve that knowledge by transferring CONTEXT to the community for communal code ownership and robust teams.


## Notes...

"WHAT" knowledge is typically captured by tools
 - Changes to files (git diff)
 - Commit message (git log) - No guarantee of quality

"WHY" knowledge is typically lost
 - Constraints surfaced during "spelunking", digital archeology, change management by walking around (i.e. regulatory compliance, security issues, performance constraints)




When a reviewer has a change, there is great value (to reviewer and team) if the _reviewer_ makes the change instead of suggesting it in a comment.  Far from being an ineffective way to communicate typographic changes, it is a HIGHLY EFFECTIVE way for the reviewer to EXPERIENCE the forces at play while original change was made.  This is a more effective learning opportunity for the reviewer, thus providing knowledge transfer that helps a team become more resiliant (i.e. less brittle to original developer getting hit by a bus (or, more likely IRW, a better job offer).

This is brilliant!  What originally FELT (to me) like an unthinking form of blame shifting during a beaurocratic check-off is ACTUALLY a quality check on the build process with a just-in-time training opportunity.  This is not friction as waste, but rather friction as effective social engineering that "waits for the teachable moment" by a clever hack of social engineering (OK. I'll let the process wonks call it continual process improvement, but only if you don't shame me for playing the role of technical coach)

================================================================


Lots of mention for "context transfer".  I replayed a few sections replacing those words with learning, training, pairing, collaborating, playing well together, valuing diverse inputs (e.g. nowledge, skills, perspective, experience, caffiene).

================================================================

Althought I have invested a lot of energy over the years trying to get value from code reviews, it feels like the industry is finally catching up with me (or, more likely: fluently articulating what could only feel in a vagu



