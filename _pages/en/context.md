---
layout: page
title:  "Booking Context"
lang: en
permalink: "/context/"
trans_url: "/contexte/"
---

### Summary/Overview

Government appointments for synchronous interactions can include anything from in-person appointments like citizenship tests or getting fingerprints and photographs taken for Visas or Work Permits, to telephone calls to find out details for a decision, or maybe even eventually video conference. 

At its core, successfully booking and attending an appointment involves:
- At least 1 attendee
- At least 1 civil servant or “service agent”
- Showing up at an appointed time
- At a specific place or device connection (for phone calls, instructions about who will be calling which number would be important)
- For some kind of purpose or task(s) to complete in the appointment

The team identified six use cases where a booking application is valuable. These use-cases may have similar or very divergent needs for their end-users or business processes and requirements. 

Use cases in order of time spent investigating:

- Book an appointment with a department or agency as part of receiving a benefit or service;

- Schedule an interview for a job interview or a language assessment with government;

- Hypothesis: Change service channels from online to in-person or telephone;

-------- Not assessed ---------- 

- Comply with regulations;

- Information as a service; and,

- Book a facility or location.


### Common vocabulary

Different terms are used in different departments and service contexts for the people who are involved in appointments. For our purposes, we settled on the following provisional terms so we could avoid confusion.

- **End-user or Attendee:** People who need appointments to accomplish a goal. Could be a member of the public or a government employee, may or may not be a Canadian citizen or resident.

- **Booking agent:** People who are involved in an aspect of booking but don't interact with the attendee or manage a team.

- **Service agent:** People who directly interact with the attendee. When they book an appointment they are scheduling their own time. 

- **Team manager:** People who manage teams of service and/or booking agents.

- **Service owner:** People in departments that have the power to decide whether or not to use a booking application.

- **Use case:** The broader category of why a team would use a booking application. We explored the following use cases: 
  - To provide a benefit or service to an end-user
  - To help an end-user change service channels
  - To help government schedule job interviews or language assessments
 
- **Service context:** The specific service and context that might use a booking application. For example, citizenship tests.  

### Complexity variables

We identified the following variables that can add complexity to making and managing appointments:

- **Needs for direct integrations with legacy software.** For example, case management systems.

- **Requiring additional personal information** at the point an attendee is booking increases the sensitivity of the data. For example, requiring a home address or language of preference in addition to a name and email.

- **Appointments for services or benefits that are sensitive in-and-of-themselves.** For example, when receiving an unemployment or medical benefit. 

- **Asynchronous approvals required to book an appointment** introduce delays into the process of booking. This limits the end-user experience because they are not able to confirm their appointment in real-time. 

- **Appointments that require multiple attendees or civil servants** increase schedule coordination. For example, citizenship tests or ceremonies

- **Booking appointments in the middle of a service journey.** Appointments are initiated by government, which means there needs to be a way to notify the attendee when they need to make an appointment and match them in a case management system.

- **Appointments with a specific civil-servants** require more coordination than those with anyone present at a staffed desk.

- **Services only providing walk-ins likely experience more cultural change** than those providing appointment booking through non-digital channels. 

- **Location of appointment, from least complex to most:** at a staffed desk, in a room that needs to be booked, at a remote location or at a home where travel time is needed.

- The more **eligibility requirements that need to be met before booking** the appointment, the more complex.

#### The problem with technical integrations
Technical integrations with legacy systems to retrieve end-user data can be prohibitively time-consuming and a lower organizational priority, since legacy systems can often be very onerous to make changes to. 

Switching to a new system or managing multiple systems can increase cognitive load and decrease productivity. Interviews with individuals in the Government Digital Service in the UK noted that solutions either had to integrate with existing systems or new systems needed to become the single source of truth. Due to the lengthy direct integration processes, we explored creating a single source of truth.
