# MediTrack Software Requirements Specification (SRS)

**Client:** CityCare Clinic  
**System:** MediTrack online appointment system  
**Document status:** Baseline requirements submitted for validation  
**Version:** 0.1  
**Purpose:** This document records the requirements supplied for review. It preserves their meaning; unresolved gaps and conflicts are documented in `findings.md` rather than silently corrected here.

## 1. Stakeholders and context

The system is intended to support patients, doctors, receptionists, the clinic administrator, and the data protection officer. CityCare Clinic has 12 doctors, 6 receptionists, and approximately 400 patients per week. Appointments are currently booked by phone and recorded in a paper diary.

The clinic has identified these concerns:

- Double bookings must not occur.
- Patients forgetting appointments causes financial loss.
- Medical information must remain private.
- Elderly patients and emergency walk-ins must be accommodated.
- Monday mornings are particularly busy.

## 2. Functional and quality requirements

| ID | Requirement |
|---|---|
| R-01 | The system shall allow patients to book appointments online. |
| R-02 | The system shall respond quickly to booking requests. |
| R-03 | The system shall prevent double bookings. |
| R-04 | Each appointment shall last 15 minutes. |
| R-05 | The system shall allow doctors to set appointment length between 10 and 30 minutes. |
| R-06 | The system shall send reminders to patients before appointments. |
| R-07 | Patients may cancel appointments at any time and the system shall update the doctor’s schedule and notify the receptionist. |
| R-08 | The system shall be user-friendly for all age groups. |
| R-09 | Patient records shall be stored securely. |
| R-10 | Receptionists shall be able to book appointments for walk-in patients. |
| R-11 | Patients may book up to 3 active appointments. |
| R-12 | The system shall be available during normal working hours. |
| R-13 | Overdue payments shall be handled as per clinic policy. |
| R-14 | Doctors shall be able to view their daily schedule. |

## 3. Validation note

This is the baseline document assessed by the checklist. Phrases such as “quickly,” “securely,” and “normal working hours,” as well as the appointment-duration statements, require clarification before the requirements can be treated as an agreed, testable specification. See `findings.md` for the review results and recommended follow-up.
