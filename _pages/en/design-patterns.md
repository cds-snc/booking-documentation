---
layout: page
title:  "Design Patterns"
lang: en
permalink: "/design-patterns/"
trans_url: "/modeles-de-conception/"
---


# Comparative Analysis
There are definitely some helpful design patterns to consider, based on heuristics and best practices. We conducted a comparative analysis to explore design patterns, and it raised some interesting questions. The following principles can be reasonably derived from the comparative analysis.

## Reduce cognitive load
- **Assume that attendees are stressed** with little cognitive load when designing a booking app. We hypothesize that seeing the next available appointment will help an attendee make other appointment-related decisions like choosing a location or choosing a timeslot. 
- **Minimize the number of steps required** just to view availability. We hypothesize that attendees likely have some criteria an available time slot or location needs to meet for them to book an appointment. If the design burdens their cognitive load just to find out availability, they may forget their pre-existing criteria or quit.
- **Use research with your users** to determine any instructions about steps required before or after booking. In some cases, attendees may already know what they need to do, and instructions just slow them down. In others, particularly if attendees are initiating the appointment, inadequate instructions could cause people to show up for appointments with missing documents or information, wasting everyone’s precious time.
- **Don’t force attendees to choose the type of appointment**, unless they genuinely have a choice. It’s just wasting their time.

## Wireframes

- **Postpone collecting personal information** from the attendee until after they’ve chosen a time. Forcing attendees to register or log in before they can see availability is onerous. 
- **Include accessibility information** whenever an attendee needs to choose a location. ServiceOntario (right image) is an exemplar of the kind of information needed.
- **Choose an appropriate time frame to display** at a time. We hypothesize that for government contexts with no weekend hours, a five-day view may be most useful. Many booking apps use a month or two-month view, requiring users to first select a date before they can see available times.
- **Skip to the first available time by default** when displaying available times. Don’t force people to waste their time making unnecessary selections.
- **Show available time slots from the first view.** Many calendars force users to choose a date before displaying available times for that date. If none of those times work for the attendee, they have to go back and choose another date to see if any slots could work. It quickly becomes onerous.

## Accessibility Fundamentals

- **Start designing for mobile first.** Especially if you’re using some kind of calendar visual, fitting it usefully onto a mobile screen will be much more difficult than for desktop.
- **Ensure everything can be navigated by keyboard** only. From our analysis, this is rare.
- **Ensure all text is structured and ordered** in a way that makes sense for people using screen readers. This was also a common pitfall for booking apps we looked at.




