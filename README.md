# Group-39-clinic-queue-booking
Software Engineering: IT353

> Patients can book clinic appointments and follow their place in the queue, while clinic staff manage bookings and patient check-ins, helping reduce uncertainty and unnecessary waiting at the clinic.

## The problem

Patients often have to call or visit a clinic to arrange an appointment and may still have little information about how long they will wait. Clinic staff manage bookings and walk-ins manually, which can make the queue difficult to keep up to date. A shared booking and queue system can make the process clearer for both patients and staff.

## Core requirements

### Patient
- The patient can create an account, sign in, and manage basic contact details.
- The patient can view available clinic services and appointment slots, then book an appointment.
- The patient can view upcoming and past bookings and cancel or reschedule an upcoming booking, subject to clinic policy.
- The patient can check whether they are waiting, being seen, or finished after checking in.

### Clinic staff
- Staff can view the day's appointments and the current queue.
- Staff can check a patient in and update the patient's queue status.
- Staff can add a walk-in patient to the queue and mark an appointment as completed or cancelled.
- Staff can manage the clinic's services and appointment availability.

### Initial scope and assumptions
- The initial queue is first-in, first-out; clinical triage and emergency prioritization are out of scope.
- Booking policies, such as cancellation deadlines and slot duration, must be set by the clinic.
- The app should show clear booking and queue status changes. SMS delivery and wait-time predictions are not included until selected and confirmed.

### Later (out of scope for the initial version)

SMS reminders, online payments, multiple-clinic support, wait-time predictions, and analytics.

## External service and data

- **External service:** None selected. Any SMS or payment provider requires a separate team decision and integration.
- **Data planned:** Patient account and contact details, clinic services and availability, appointments, check-in and queue status, and notification preferences.
- The initial scope does not require storing diagnoses or clinical notes.

## Team (roles rotate every 3 weeks)

Team member names and GitHub usernames were not provided.

| Name | GitHub | Role (weeks 1-3) |
|------|--------|------------------|
| TBD | TBD | Project manager |
| TBD | TBD | Lead developer |
| TBD | TBD | Tester |
| TBD | TBD | Documentation lead |

## Process model

Iterative Agile development with short increments and regular review; team roles rotate every three weeks. The detailed process-model justification has not yet been added to `docs/02-process-model/process-model.md`.

## Documentation

The documentation folders referenced by the course template are not present in the repository yet.

| Folder | Intended contents |
|--------|-------------------|
| `docs/01-proposal` | Problem statement and member profiles |
| `docs/02-process-model` | Process model justification |
| `docs/03-requirements` | Software requirements specification and elicitation notes |
| `docs/04-uml` | UML diagrams |

## How to run

There is no application source code or run configuration in the repository yet. Add setup and run instructions when the first working increment is available.
