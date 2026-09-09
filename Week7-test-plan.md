# Fountain Care — Week 7 first prototype

## Hypothesis
Park visitors who notice a faulty drinking fountain can submit a report with less effort when a QR entry point identifies the facility automatically, the form uses simple fault categories, and no account is required. A report reference and understandable progress states may increase confidence that a report is acknowledged and traceable.

This is a hypothesis, not a finding established by the prototype. A classroom test can assess usability and perceived confidence, but cannot demonstrate real maintenance outcomes or increased reporting in everyday use.

## Research basis
Three interview transcripts inform this concept. The first Dutton Park participant described avoiding lengthy reporting steps and wanted a QR entry point. The second Dutton Park participant described returning to report a fault out of concern about waste and possible harm, and wanted acknowledgement, a realistic timeframe and closure. The Ramen Danbo participant valued a written record and described how trust, responsibility and connection to a place affect willingness to report. Our_work.pdf currently summarises only two participants and still needs to incorporate the third.

Do not treat the second transcript's mention of a 311 service as a verified Brisbane service. Verify unclear transcription against the recording before quoting it. Hygiene concerns reflect participant perceptions; they are not water-quality measurements.

## Prototype and scope
A mobile-friendly, clickable web prototype, with a short public-facing flow:
Simulated QR entry → prefilled facility and issue form → confirmation → report progress.

Open index.html in a browser; no installation is needed. The QR scan is simulated by an explicitly labelled button. Facility ID and precise location are fictional examples. All input stays in the page's memory and clears on reload or reset. There is no council integration, actual submission, email delivery, durable report storage or maintenance backend. Photo selection provides a local preview. A facilitator control demonstrates possible later statuses.

## Test scenario (read to participant)
“You are walking in a park and notice that water keeps flowing from a drinking fountain after the button is released. You want to report the problem before leaving. Starting from this fountain label, show what you would do. Afterwards, find out whether the issue has been repaired and how you could identify your report.”

Avoid naming controls or explaining the intended route during the task. Ask participants to think aloud. Use invented details rather than personal contact information.

## Procedure and proposed success criteria
1. Start from the label screen and time the reporting task. Observe whether the participant completes it unaided within two minutes. This is a proposed classroom target, inspired by the first interview, not a validated service benchmark.
2. Note hesitation, errors, attempts to find registration, and confusion about the location or optional fields.
3. Ask the participant to locate the report reference and current status. Check whether they distinguish “received” from “resolved”.
4. Use Facilitator controls to advance through example updates. Ask what each state means and what information remains missing.
5. Ask “What, if anything, would make you trust that this report will be acted on?” and “Would you use this in a real park? Why or why not?” Do not equate positive answers with proven behaviour change.
6. Restart and clear the report before the next participant. Record actual results rather than filling in assumed success.

For this formative exercise, try 3–5 classmates or tutors if available; they are proxy users, not necessarily representative park visitors. Investigate each failure and revise the flow. Future research should include target park visitors and facility operators.

| Participant | Completion / time | Errors or hesitation | Understood received vs resolved? | Confidence and missing information | Change to try |
|---|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |

## Week 6 design rationale
- Hick’s Law: a short list of plain-language fault categories and one primary action per screen.
- Fitts’ Law: large selectable category areas and primary buttons at least 48 px tall.
- Miller’s Law / chunking: facility, fault details and optional supporting information are grouped; location and reference remain visible rather than relying on memory.
- Gestalt proximity and common region: related facility information is contained in a card; category labels sit beside their controls.
- Gestalt similarity: primary actions and category controls use consistent visual styles.
- Gestalt continuation: a vertical sequence communicates the order of maintenance states.
- Figure and ground: primary actions and the current progress state stand out against quieter surfaces.

These are design rationales to evaluate, not proof that the interface is intuitive. The form also uses labelled inputs, keyboard focus indicators and text status labels.

## Short explanation for the tutor
“Our prototype tests whether a facility-specific entry point and a short, account-free form make fault reporting easier. It also tests whether a reference number and clear status updates help users understand what happens after submission. We have three interviews, including contrasting levels of willingness to report. We are starting with the public-facing flow; operator needs and real repair processes remain unvalidated.”

## AI acknowledgement
Codex helped translate the group's interview findings into a prototype flow, implement the interactive HTML prototype and draft this test plan. The group should review the design decisions, validate the transcript wording, conduct the tests and report the actual results.
