# Bug Reporting Policies

Bugs are a fact of life.  When bugs are reported to the development team, it's important that the bug
ticket be as complete as possible to provide engineers a more complete picture of the problem 
and speed up diagnosis and resolution.  The information that needs to be included depends on
the type of bug being reported.  

How a bug is treated largely depends on it's **impact** to the user.  We use three levels of
classification for impact:

* **HIGH** - Service outage, all users are affected.  Ticket is pulled into current sprint and
senior engineering manager is notified.

* **MEDIUM** - Feature or service is malfunctioning, many users are affected.  Depending on the 
nature of the issue, the ticket may be pulled into the current sprint upon approval of the senior
engineering manager.  Otherwise, the ticket is moved to the top of
the backlog to be worked on in the next sprint.

* **LOW** - Feature or service is not working as expected, but it is not a serious problem,
few users are affected.  The bug is placed in the backlog and scheduled for a future
sprint.

With the exception of **HIGH** impact bugs, a ticket should not be pulled into the current
sprint without the approval of the senior engineering manager.

## Frontend Bug Reporting

When reporting a bug related to a frontend, or user facing product, it is important to gather
enough information to be included in the bug, otherwise the bug may be rejected by Engineering.
The following types of information should be included in the bug ticket:

* **Username** - The login name of the user reporting the bug.
* **Environment** - Is it the test, integrations or production environment?
* **Web Browser/Version** - If it's a website issue, please include the user's web browser and
version number.
* **Operating System** - What operating system was the user operating when the bug occurred. 
* **Hardware Platform** - If possible, get the type of hardware the user was running when the 
bug was discovered.  (For instance, the SDK is supported on specific CPU types)
* **Expected Behavior** - What was the user expecting to happen?
* **Actual Behavior** - What was the actual behavior of the software.  What was the error?
* **Steps to Reproduce** - This is important!  What steps can be used to reproduce the bug or
error?  Please be as complete as possible.

Gathering all of the required information is sometimes difficult or impossible.  Trying to
be as complete as possible will assist the engineer in troubleshooting and ultimately 
resolving the bug.

## Backend Bug Reporting

When reporting a bug related to a backend service or SDK, the critical information is the 
stack trace.  As always, try to be as complete as possible.  The following information
should be included:

* **Username** - The login name of the user reporting the bug.
* **Environment** - Is it the test, integrations or production environment?
* **Host Application** - If the bug is found on a DJ or other client application, include
the application and version.
* **Operating System** - What operating system was the user operating when the bug occurred.
* **Hardware Platform** - If possible, get the type of hardware the user was running when
the bug was discovered.
* **Error Message** - The error message or except that was thrown.
* **Stack Trace** - If available, provide the complete stack trace of the crash.
* **Steps to Reproduce** - If the bug is reproducible, include the steps that will reproduce
the bug.  Please be as complete as possible.