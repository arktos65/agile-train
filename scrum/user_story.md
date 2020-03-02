# From User Story to Feature

In more traditional settings, many software development teams rely on very detailed Use Case documents
that describe a feature in great detail.  The problem with this approach is that it often requires as
much time to generate the documentation than to develop the feature.  Additionally, once the Use Case
is defined it tends to become resistent to inevitable changes that occur during the development
cycle.

User stories should be thought of as the beginning of a conversation.  They are intentionally meant to
be written from the user perspective absent of technical jargon.  A user story might look something
like the following example:

    As a DJ, I would like to be able to search for song titles, artists, and labels then 
    add one or more songs to a playlist.
    
This summarizes what the use case is in the simplest terms -- the user's perspective.  At this 
point, the Development Team sits down with the Product Manager and begins breaking the story
down.  In this example, examining the verbs in the sentence we can surmise the following
high level features:

* Searching for songs by title, artist or label
* Returning a list of results displayed in some unknown order
* Adding one or more songs to a playlist

At the very least, we now have potentially three issues to be created in the product backlog.
The Product Manager has the responsibility to enlighten the Development Team to the rationale
behind the user story, why it's important, and help the team understand it from the user's
point of view.

As the conversation continues, the Development Team breaks the features down collaboratively
with the Product Manager defining the various elements of the features, what the acceptance
criteria are for each feature and so forth until a sufficient number of issues have been
defined.  Mockups, wire frames, and flow charts are drafted and reviewed by the team.

At this point, the UX designer will go off and create the designs based on the work produced
by the Development Team.  When the designs are ready, the team meets and reviews the design,
makes last minute adjustments.  Once all stakeholders have signed off, the issues are 
placed in the product backlog.  At the next backlog grooming meeting, the issues are estimated
and assigned story points.  The Product Owner prioritizies the backlog of issues and at the
next available sprint, the Development Team selects the issues to work on.

By the time the issues are placed in the backlog for estimation, the Development Team
should already have a clear picture of what needs to be done and should not require further
work on the tickets unless changes are made by the Product Manager or Development Team.

## Defining an Issue

An issue is an entity that will be entered into the Jira system as a ticket.  An issue
explains a feature, and improvement, or engineering change.  Issues may
include Jira ticket types of stories (issues that must be estimated for work), tasks,
or bugs.

    An issue must represent a logical unit of work that incrementally 
    improves the value of the product.
    
An appropriate analogy would be building a model using Lego blocks.  Each Lego
represents a single issue in the backlog that when assembled forms the entire feature.

    An issue must meet the Definition of Ready before it is accepted into
    the backlog for estimation and scheduling.
    
This is a critical point that must be strongly adhered to.  Otherwise, the Development
Team runs the risk of having an incomplete understanding of the feature and the 
issues that comprise its development.  Learn more about the [Definition of Ready](backlog.md).

## What is an Epic?

Often a feature will require a significant number of issues to be generated that
forms the entirety of the feature.  The epic is a means of grouping all related
issues into a coherent list that when put together forms the feature.  

Typically an epic will span two or more sprints while an issue must be completed
within a single sprint.  The Development Team along with the Product Owner has
the discretion to define epics and track the overall progress of development
across sprints.

Several issues that can be completed in a single sprint typically should not
be grouped into an epic.

    An epic should be defined if development of the feature spans two or
    more sprints.
    
To reiterate, the epic assists in organizing and tracking the progress of
a feature across multiple sprints.

TODO: **ADD AN EXAMPLE OF AN ISSUE READY FOR ESTIMATION**