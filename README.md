## What is an Engineering Lead?

An Engineering Lead is an Engineer with the added responsibility of defining and owning technical direction for a project or technical area. They work, often with a team, to ensure project delivery or success and efficiencies in the area. Ultimately, they are a source of guidance and leadership on whichever area they are focused.

An Engineering Lead is expected to

* Set Technical Vision

* Define Architectural Constraints

* Assure Delivery

* Guide Solutions

* Prioritize Work

But an Engineering Lead is NOT expected to

* Give Performance Feedback

* Negotiate Conflicting Business Requirements

* Communicate Company Changes

* All Eng Quarter Planning

* People Manage

*Notes:* 

* I will use "Eng Lead" as a short form of the term Engineering Lead. In some of the reference articles, “Tech Lead” is also used. Consider them equivalent. 

## What are an Eng Lead’s responsibilities

### Set Technical Vision

One of the responsibilities of any Engineer, but especially an Eng Lead, is to understand project requirements and the business drivers that accompany them. Additionally, an Eng Lead must understand the systems with which they’re integrating. From that, one of the most important responsibilities of an Eng Lead is to set the Technical Vision of the project or area on which they are working. This includes committing to a technical stack, setting the architecture, and determining the interfaces with other services if necessary.  

### Define Architectural Constraints

Architectural Constraints are the named expectations and limits on a system. They define what the system should and shouldn't do as a whole and as it grows. These drive the design and technical implementation that get done, as well as test coverage and strategy. Any assumed constraints should be challenged and verified. At the same time, working with the team and stakeholders to set up and decide acceptable business and technical constraints helps create guide rails within which development can freely happen.

### Assure Delivery

In addition to defining the technical direction and guidelines, an Eng Lead will have an understanding of what it will take to deliver on a project. They will communicate that to interested parties and highlight blocks or changes in direction if they appear. Delivery and communication of status is essential to any project’s success, so this responsibility is as important as the technical guidance. 

### Guide Solutions

Both the larger direction and the individual steps to delivering are part of the Eng Lead’s overview. They will be a guide and consultant to delivery of the solution, ultimately being responsible for that solution. Successes (and failures) will often be managed by an Eng Lead, so communication and planning become an important part of the role.

### Prioritizing Work

For the team an Eng Lead should have an idea of what is next most important for themselves and others on the project. They will have work queued up and able to make adjustments as things change. This can include suggesting a dev methodology like Scrum or Kanban, setting code review standards, and determining how to prioritize bugs.

## What aren’t an Eng Lead’s responsibilities

### Giving performance feedback

It is up to the Engineering Manager to set goals, give performance feedback, and provide career opportunities to team members. Any feedback that an Eng Lead might have about someone else on the team, other than typical code or peer reviews, can be shared with their manager. That allows any potential issues to be managed according to company policy.  

### Dealing with conflicting Product Requirements

There are times when Product and Engineering requirements may differ. Or two or more Product teams are requesting work. The Eng Lead must work closely with Product to keep requirements up to date, but if there’s a conflict the Eng Lead should work with the Eng Manager and\or Product leadership to decide on the priorities. Certainly at times the Eng Lead will be able to work through conflicting needs, but if a solution isn’t clear, the Eng Lead isn’t responsible for being a tiebreaker. In that case, they are then only responsible for ensuring any issues are efficiently escalated. 

### Communicating company or org changes which affect projects

At times the company will announce a new goal, business direction, partnership, or org change. While the Eng Lead remains aware of business communications, there is no expectation that the Eng Lead shoulders the responsibility of communicating those changes to the team or deciding how it affects the responsibilities of the overall team.

### Managing the team’s priorities and projects in the larger Engineering quarter planning systems

Currently all of Engineering goes through the exercise of planning each quarter’s work. It’s not the responsibility of an Eng Lead to communicate the team’s projects in that process. The Eng Lead definitely will be sharing their project’s or area’s priorities, ideas, and [SWAGs](https://en.wikipedia.org/wiki/Scientific_wild-ass_guess) with the team, manager, and Product but isn’t expected to deal with sharing out to the larger Eng org process unless a special case is made for this to occur.

### Project to project or team to team switches

People at times are interested in moving onto other projects or other work, sometimes mid-project. Or more often, interesting in picking up work from another project. It is not the Eng Lead’s responsibility to negotiate or manage these kinds of changes in the number of engineers associated to a project. Instead, the Eng Manager and or Technical Project Manager would get involved to discuss and decide the most effective plan.

## The work product of an Eng Lead

It may vary by project and person, but in general an Eng Lead will spend 15-30% of their time on system design and strategy. They’d spend 15-30% of their time organizing the group’s work and sharing status. Then they’d spend 40-60% of their time coding, doing devops, and doing code reviews. 

When we break down some of that responsibility, it will take many forms. The technical work where coding is happening, code reviews, builds, deploys, etc is spent is similar to the work that is being done by an engineer on any project. The additional work is in the rest of the time away from the code. 

An Eng Lead effectively sets the [technical vision](#set-technical-vision) of a project via meetings with relevant parties and documentation explaining decisions and known directions. This can be as minimal as a wiki page with decisions or as complex as design documents with data flows, system [ERDs](https://en.wikipedia.org/wiki/Entity%E2%80%93relationship_model), [DAGs](https://airflow.apache.org/concepts.html), etc. 

They share any known and established [architectural constraints](#define-architectural-constraints) in conversations and documentation. This ensures that others on the project understand what the bounds should be. Again, this can be as simple as a "what we won’t do" section of the documentation. 

Once work gets started, the Eng Lead spends time [prioritizing work](#prioritizing-work) both for themselves and for the team. They do this through whichever means is the best fit for the project; often through JIRA organization or with the help of a Technical Project Manager. Things like keeping the ticket backlog ordered, running sprints, regularly checking in on dependent projects, and reporting updates on milestones all could fall into this area.  

Similarly, Eng Leads [guide solutions](#guide-solutions) so that developer and business expectations both are headed towards a positive and expected path. Often this comes in the form of regular status messages to engineering management, regular check-ins with the development team, and continued communication with other leaders in connected areas. If a sub-project is starting up, for example, then the Eng Lead will review the proposed solution and help guide implementation through code reviews or check-ins. 

Finally, the Eng Lead is responsible for [assuring delivery](#assure-delivery) of the project.  Often this will take the form of a rollout and test plan which would include setting internal milestones and KPIs for the project. It could also include working with Project or Product Managers to communicate out the release timing or ramp schedule. But no matter what, it will include communicating to all interested parties when and how the work has completed, either through a meeting, an email, or a collaborated communication with other teams. 

## Tricks for effective time management

Inevitably, an Eng Lead will find themselves crunched for time. With the responsibility to both produce and manage work, there will be conflicting needs. More communication means more meetings and more responsibility means more time explaining direction and sharing updates. While there are innumerable books, blogs, and ideas on how to be better at time management, for this article, here are a couple ideas.

* Schedule a 1-3 hour block once a day or a couple times a week to just code. Put Slack on DND and shut off Outlook. Come to these times with a plan and a body of work and be diligent about keeping the time free for coding.

* When estimating the time it will take to make a decision or deliver a project, for example, make sure to add time for communication, answering questions, testing and deploying. Estimate liberally instead of conservatively.  

* Find a task management tool that works for the project. Almost all teams use JIRA to manage milestones and backlog, including estimates for work. But there are other methods to keep tasks organized. Whichever is used, get comfortable keeping it updated as often as possible, weekly at minimum. 

## The difference between an Eng Lead and an Engineering Manager

There are often times when an Engineering Manager fills in some or all of the role of an Eng Lead. Many times an Eng Manager *was* an Eng Lead previously. So, there can be and will be overlap. But with an active Eng Lead on a project, an Engineering Manager explicitly shouldn’t be performing the responsibilities of an Eng Lead. The Eng Manager should be used as a sounding block, as back-up support, or as a mentor. They should also be taking care of the project and business [concerns that are not the Eng Leads responsibilities](#what-arent-an-eng-leads-responsibilities). 

## Recommended Articles

[The Well-Rounded Technical Lead (A Model for Technical Leadership)](http://www.engineeringandcareering.co.uk/2013/05/the-well-rounded-technical-lead-model.html)

[The Webflow Tech Lead Guide](https://github.com/webflow/leadership/blob/master/tech_lead.md)

[What Does a Software Tech Lead Do?](http://allyouneedisbackend.com/blog/2018/08/03/what-does-a-tech-lead-do/)

[The Effective Tech Lead is a 100x Engineer](https://hackernoon.com/the-effective-tech-lead-is-a-100x-engineer-fe49c0372a63)

