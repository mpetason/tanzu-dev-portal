---
title: "Post Mortem"
linkTitle: "Post Mortem"
description: "An exercise to process the learning from any incident that impacted the product and user. In the SRE community, this exercise is called an incident retrospective."
# Note: remove any tags that are not relevant.
tags: ["Delivery", "Transition"]
length: "1 hour"
participants: "Core delivery team and relevant parties"
# custom "cover" image example: "boris/boris.png"
image: "default-cover.png" 
lastmod: "2021-06-07"
why: 
- To help teams identify the lesson learned for incidents that happen with products and to help avoid such incidents in the future. 
when:
- Team consensus that they would all learn something about the incident or near miss
- During an incident or as soon as the incident is resolved
- Stakeholder or impacted team asked for a post mortem 
- If there is an error budget violation
what:
- "Whiteboard or digital version like [Miro](https://miro.com/)"
- Sticky notes
- Markers
- Painter’s tape

remote: false
miro_template_url: "" 
---
## How to Use this Method
#### What is an Incident?
For this session, ***Incident*** is defined as the following: 
- An event in the live product that interrupted the user's ability to interact with the product
- When you experience an unexpected negative event that has high impact to your development process

#### More on who should participate 
**Core Team:** The core delivery team should particpate, such as Product Manager(s), Engineer(s), Designer(s).

**Relevant parties:** These are anyone who was in a key role and involved in the incident. For example:
   - Member of platform team
   - Member of security team
   - On-call support team
   - Customer service team

### Sample Agenda & Prompts
Prior to the session, collect as much information about the incident as you can. 

For example, you might send a survey to relevant teams requesting information. 

If teams took notes about the incident while it was in progress, collect these as well.

{{< callout >}}
Tip: If taking notes during an incident is not already as a well-established practice, institute note-taking for future incidents.
{{< /callout >}}

If the timeline for the incident is very well understood, and creating it as a group would not be beneficial, consider creating it prior to the session. See below.

1. Explain the goal of the post mortem (5 mins)

   Embrace a [blameless culture](https://sre.google/sre-book/postmortem-culture/). Reinforce with the group that the goal is not to "get people into trouble" -- the goal is to identify what happened and how to avoid it in the future. Make sure you establish [psychological safety](https://en.wikipedia.org/wiki/Psychological_safety) for each team member.

   {{< callout >}}
   Tip/Example: You might say something like: _“We want to identify what caused the recent incident and how we fixed it. Additionally, we want to define action items to avoid this in the future. We are not looking to find someone to blame.”_
   {{< /callout >}}

1. Optional: Create the timeline as a group (1h max)

   Create a timeline of the incident: what happened and when. Consider whether or not creating the timeline together would be beneficial for the group. If not, create the timeline prior to the session. See above.  

   ![Insident Timeline](/images/practices/post-mortem/timeline.jpg)

1. Present the incident timeline (5 mins)
   
   Show the incident timeline and confirm it with the team.

1. Brainstorming Post Mortem Topic (5 mins)
   
   Ask team to write on sticky notes or in the shared digital workspace:
      - What went wrong - what caused the recent incident?
      - What went well - what parameters that worked well to fix the incident?
      - Where we got lucky - are there any events/things that help us out?

1. Quick Topic Clustering (5 mins)
   
   Ask the team to cluster the items based on similar topics.

1. Discuss each cluster (20 mins)
   
   Discuss each cluster as a group. 
   
   For the “What went wrong” column, ask the group to identify the following: 
      - Why did this happen?
      - How can we reduce the impact if it happens again? 
   
   {{< callout >}}
   Tip: consider using the [Five Whys](https://en.wikipedia.org/wiki/Five_whys) technique to identify root causes, while still keeping blamelessness top of mind. 
   {{< /callout >}}

1. Discuss and assign action items (15 mins)
   
   Discuss with the team what actions they can take to avoid such incidents future.  
   
   Each action item should have at least one owner.

1. Agreed on the post mortem owner(s) (4 mins)
   
   Decide as a team the post mortem owner(s). The owner is responsible to:

   - Create post mortem document for future reference. This document should contain:
      - Overview of the incident
      - Action items to resolve the incident
      - Root cause analysis - note that there might be multiple root causes
      - Learning and next steps to avoid the incident happen in the future
   - Communicate the stakeholder regarding the update on post mortem
   - Plan review meetings to make sure all action items are complete

1. Schedule the follow up (1 min)
   
   Scheduled follow-up sessions with action item owners to review their assignments. The incident should not be closed or considered resolved until all actions are complete. 

### Success/Expected Outcomes
At the end of this exercise, you will have a clear alignment of what and how the incident happened. Moreover, the team will have a set of plans.

- To reduce impact of recurring incident
- To avoid the incident in the future

## Facilitator Notes & Tips
Example post mortem documents: 
- [Example Postmortem from Google's SRE Book](https://sre.google/sre-book/example-postmortem/)
- ["sredocs" on GitHub](http://github.com/google/sredocs)

## Related Practices
[3 Column Retrospective](/practices/3-column-retro)

## Variations
None at the moment.

### Preceding
None at the moment.
 
### Following
None at the moment.

## Real World Examples
None at the moment.

## Recommended Reading
Coming soon!