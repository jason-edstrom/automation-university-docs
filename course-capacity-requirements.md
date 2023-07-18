### How should course capacity controls be implemented?

Course capacity control is an important feature of a university registration system. Here is a step-by-step approach on how it could be implemented:

**1. Set Capacity:**
When creating a course, the system should allow administrators or academic staff to set the maximum number of students that can enroll in the course. This could be based on factors like classroom size, teaching resources, and educational objectives. 

**2. Track Enrollments:**
The system should keep a real-time count of the number of students enrolled in the course. Each time a student enrolls, the count should increment.

**3. Check Capacity:**
Before a student is allowed to enroll, the system should check the current enrollment against the maximum capacity. If the current enrollment is less than the maximum, the enrollment should proceed. If not, the system should not allow the enrollment and instead offer the student to be added to a waitlist.

**4. Waitlist Management:**
If a course is at capacity, the system should allow students to join a waitlist. The waitlist should be managed on a "first come, first served" basis. Students should be able to see their position on the waitlist.

**5. Automatic Enrollment from Waitlist:**
When a spot becomes available (e.g., a student drops the course), the system should automatically enroll the first student on the waitlist, decrementing the waitlist count and sending a notification to the student.

**6. Course Full Indication:**
Courses that have reached their maximum capacity should be clearly marked as "Full" in the course catalogue. Students should still be able to see the course details, but they should be made aware that they can only join the waitlist.

**7. Over-enrollment Control:**
For exceptional cases, the system should allow for over-enrollment with an override function, but only by specific staff roles like academic advisors or course instructors.

**8. Reporting:**
Administrators and academic staff should be able to easily view reports on course enrollments, including how many students are enrolled, how many are on the waitlist, and whether any courses are over-enrolled.

Implementing these controls will ensure that courses are not overfilled and that all students have an equal opportunity to enroll in the courses they need. It also aids the academic staff in managing course resources effectively.