# twin-turbo-v8-in-a-tesla

## Team Members
- Raiyan27 (Team Leader)
- saif-kabeer
- Mahbi-Rahman

## Mentor
- arrafintehaalvybs23

## Project Description
# The Proctored Quiz & Assignment Platform

The Proctored Quiz & Assignment Platform is a **mobile-based application** (built with React Native) designed to provide a **secure, user-friendly** experience for students, instructors, department heads, and parents. This project aims to **streamline academic activities** by offering robust features for quiz creation, automated grading, face recognition-based proctoring, assignment management, and a **Parents Portal** for performance monitoring and communication.

---

## Purpose

The platform caters to **four** main user groups:

1. **Students**  
   - Allows learners to register for quizzes, submit assignments, and view their grades.  
   - Offers automated grading feedback for MCQs and written answers.  
   - Provides options to schedule consultations with instructors.

2. **Instructors**  
   - Enables educators to create and manage quizzes, assignments, and class schedules.  
   - Includes a “View as Student” feature to preview assessments from the student’s perspective.  
   - Facilitates virtual meetings or consultations with students and parents.

3. **Department Heads (Admin Mode)**  
   - Combines the privileges of both instructor and student roles.  
   - Oversees high-level administration, user management, scheduling, and appeals from students.  
   - Monitors platform-wide performance metrics and usage.

4. **Parents (Limited Portal)**  
   - **View Student Grades & Performance**: Access the student’s quizzes, assignments, and performance metrics.  
   - **Schedule Meetings with Instructors**: Book consultation sessions to discuss student progress.  
   - **Consent-Based Access**: Students must grant permission before parents can join and view their academic data, ensuring privacy compliance.

---

## Key Features

1. **User Onboarding & Privacy Policy**  
   - Comprehensive signup flow requiring acceptance of privacy policies.  
   - Multiple account types (Student, Instructor, Department Head, Parent) with distinct permissions.

2. **Quiz Creation & Automatic Grading**  
   - **MCQ Auto-Grading**: Instantly grades objective-type questions and provides immediate feedback.  
   - **NLP Grading for Written Answers**: Assigns preliminary scores for essays or short answers, allowing students to file appeals for human re-check.  
   - Results are viewable by both **students** and **authorized parents**.

3. **Camera Face Recognition**  
   - **Exam Start Verification**: Confirms that the correct student is taking the quiz.  
   - **Real-Time Proctoring**: Flags instances where the student’s face is out of the camera frame for more than 8 seconds, saving a 15-second recording clip for instructor review.  
   - **No App Switching Restriction**: The app does not restrict switching to other apps, but continues to track face presence during active quizzes.

4. **Assignment Submission & Auto-Checking**  
   - Enables students to submit written assignments or file uploads through the app.  
   - Basic automated checks (e.g., grammar or structure) to assist instructors.  
   - Instructors can override auto-check results or provide additional feedback.

5. **Scheduling of Classes & Consultations**  
   - Instructors and department heads can schedule classes, quizzes, and assignment deadlines.  
   - Students can request **consultation meetings** with instructors.  
   - Parents can also schedule **virtual or in-person meetings** with instructors to discuss their child’s progress (subject to the student’s consent).  
   - Integrated calendar view for upcoming events, accessible to all roles with relevant permissions.

6. **Notifications & Topic Suggestions**  
   - Sends push notifications about upcoming exams, assignment due dates, or new feedback.  
   - Recommends study topics to students based on past exam performance.  
   - Parents receive alerts about significant changes in performance or new meeting confirmations.

7. **Parents Portal**  
   - **Performance Tracking**: Displays overall grades, quiz results, assignment scores, and progress over time.  
   - **Meeting Scheduler**: Allows parents to book a meeting slot with an instructor or department head to discuss student progress.  
   - **Consent Management**: Students must grant access for parents to join and view their academic records.

8. **Data Storage**  
   - Stores user information, quiz data, assignment details, and performance metrics in a secure database (e.g., Firebase or a custom REST API).  
   - Ensures data is encrypted in transit (HTTPS) and protected at rest, aligning with standard security practices.

---

By integrating a **Parents Portal**, **student consent mechanism**, and **consultation scheduling** alongside the existing **automated grading** and **face recognition** features, **The Proctored Quiz & Assignment Platform** provides a **comprehensive ecosystem** for modern educational needs—combining robust **assessment tools**, **privacy compliance**, and **collaborative communication** among students, instructors, department heads, and parents.


## Getting Started
1. Clone the repository
2. Install dependencies
3. Start development

## Development Guidelines
1. Create feature branches
2. Make small, focused commits
3. Write descriptive commit messages
4. Create pull requests for review

## Resources
- [Project Documentation](docs/)
- [Development Setup](docs/setup.md)
- [Contributing Guidelines](CONTRIBUTING.md)
