# INCIDENT DATE - INCIDENT TYPE

## Meeting

#### Waiving meetings

In some cases the IC might determine that a PM meeting for the incident isn't needed.
If the IC decides to waive the meeting please replace the `Meeting` section with a
note indicating the meeting has been waived (example: `Meeting waived: Paul Mooring`)

#### Start every PM stating the following

1. This is a blameless Post Mortem.
2. We will not focus on the past events as they pertain to "could've", "should've", etc.
3. All follow up action items will be assigned to a team/individual before the end of the meeting. If the item is not going to be top priority leaving the meeting, don't make it a follow up item.

### Incident Leader: Someone's name

## Description

Short explanation of the issue (1 or 2 sentences)

## Timeline

_*Please note the time to detect and time to resolve and add to the [incidents list](./Incidents.md)*_

Timeline of events, including exact duration of downtime.
The timeline should be in chronological order, showing what happened when, but
it should also explain what the team knew at the time.

For example, someone deploys a bad build that triggers an alert, but no one
initially realizes this is what happened. The timeline should list first that the
bad build was deployed, but that the oncall person was not aware of this at the
time it occured. Later the timeline might list an event where the oncall person
becomes aware this is the case.

## Contributing Factor(s)

Technical explanation of the issue.  Should define the contributing factor(s) and
why it's an issue.

## Stabilization Steps

What specific steps and actions were taken to stabilize the issue.  This
does not always entail a "fix" as further actions should be listed under
"corrective actions"

## Impact

What was the impact of the incident.  This should include the total
duration of the outage if applicable.

## Corrective Actions

Action items going forward to fix the issue and reduce chance of contributing factors being an issue.

This **MUST** include owners/teams assigned to these actions to see them through, and have an issue tracked in this repository (or otherwise linked to external team kanban/issue tracker).
