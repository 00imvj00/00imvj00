# Overview

A high-level summary that every engineer at the company should understand and use to decide if it’s useful for them to read the rest of the doc. It should be 3 paragraphs max.

# Title and People

The title of your design doc, the author(s) (should be the same as the list of people planning to work on this project), the reviewer(s) of the doc, and the date this document was last updated.

# Feature Flags

List of feature flags used to roll out and purpose

# Name

# Purpose

# Goals and Non-Goals

### The Goals section should:

describe the user-driven impact of your project — where your user might be another engineering team or even another technical system

specify how to measure success using metrics — bonus points if you can link to a dashboard that tracks those metrics

Non-Goals are equally important to describe which problems you won’t be fixing so everyone is on the same page.

# Functional and Non Functional Requirements

List out all functional requirements related to a Persona. This could be user-focused and the flows that users experience in our web app or our app in 3rd party store. This is an extensive version of our goals which lists out user flows. 

Non Functional Requirements are the requirements that will enable function requirements to functional.

# Milestones

A list of measurable checkpoints, so PM and other members can skim it and know roughly when different parts of the project will be done. I encourage you to break the project down into major user-facing milestones if the project is more than 1 month long.

Use calendar dates so you take into account unrelated delays, vacations, meetings, and so on. It should look something like this:

Start Date: June 7, 2020Milestone 1 - MVP in dark mode: June 28, 2020Milestone 2 - Retire Old System: July 4th, 2020End Date: Add feature A, B, C to the new system: July 14th, 2020

Add a [Update] subsection here if the ETA of some of these milestone changes, so the stakeholders can easily see the most up-to-date estimates.

# Proposal

 Existing Solution

[In addition to describing the current implementation, you should also walk through a high-level example flow to illustrate how users interact with this system and/or how the data flows through it.

A user story is a great way to frame this. Keep in mind that your system might have different types of users with different use cases.]

# Proposed Solution

[Some people call this the Technical Architecture section. Again, try to walk through a user story to concretize this. Feel free to include many sub-sections and diagrams.

Provide a big picture first, then fill in lots of details. Aim for a world where you can write this, then take a vacation on some deserted island, and another engineer on the team can just read it and implement the solution as you described.]

# Alternate Solution

[What else did you consider when coming up with the solution above? What are the pros and cons of the alternatives? Have you considered buying a 3rd-party solution — or using an open-source one — that solves this problem as opposed to building your own?]

# Testability, Monitoring, and Alerting

[I like including this section because people often treat this as an afterthought or skip it altogether, and it almost always comes back to bite them later when things break and they have no idea how or why.]

# Open Questions

[Any open issues that you aren’t sure about, contentious decisions that you’d like readers to weigh in on, suggested future work, and so on. A tongue-in-cheek name for this section is the “known unknowns”.]

# Implementation and Timeline

[This section is mostly going to be read-only by the engineers working on this project, their tech leads, and their managers. Hence this section is at the end of the doc.

Essentially, this is the breakdown of how and when you plan on executing each part of the project. There’s a lot that goes into scoping accurately, so you can read this post to learn more about scoping.

I tend to also treat this section of the design doc as an ongoing project task tracker, so I update this whenever my scoping estimates change. But that’s more of personal preference.

