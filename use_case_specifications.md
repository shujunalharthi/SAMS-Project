Task 4: Use Case Specifications

Student Name: Ghusun Almalki  
Role: UML Analyst  

System Actors:
* Student: Primary actor who browses and registers for activities.
* Organizer: Primary actor who creates event proposals and manages attendance.
* Student Affairs: Primary actor who reviews and approves activity proposals.
* Notification System: Secondary actor that dispatches notifications to users.


Use Case 1: Register for Activity
Actor: Student
Pre-conditions: Student is logged in and registration for the activity is open.
Steps:
1. Student selects an activity from the available list.
2. Student clicks on the Register button.
3. System validates availability and confirms the registration.
4. System triggers a notification to the student.
Post-conditions: Student registration status is recorded in the system.


Use Case 2: Check-in with QR Code
Actor: Student, Organizer
Pre-conditions: Student is registered for the activity and holds a valid QR ticket.
Steps:
1. Student presents the QR code ticket at the venue.
2. Organizer scans the QR code using the system scanner interface.
3. System verifies the ticket details against the database.
4. System updates the student's attendance status to Attended.
Post-conditions: Student attendance is recorded in the activity record.


Use Case 3: Create Activity Proposal
Actor: Organizer
Pre-conditions: Organizer is logged into their account.
Steps:
1. Organizer opens the activity proposal submission form.
2. Organizer fills in required details (title, date, location, capacity).
3. Organizer submits the proposal for evaluation.
Post-conditions: Proposal status is updated to Pending Approval for Student Affairs review.
