**User Case Diagram***Author:* 

*System: Internship Finder App*

**Actors:**

1. Students

**Use Cases:**

**1. UC01 - Explore Internships**

- **Overview:** Allows the Student to explore a list of available internships.
- **Actors:** Student
- **PreConditions:** Student is logged into the application.
- **PostConditions:** Displays a list of available internships.
- **Include:** UC04 - Search Internships
- **Include:** UC06 - View Internship Details

**2. UC02 - Apply for Internship**

- **Overview:** Enables the Student to apply for a specific internship.
- **Actors:** Student
- **PreConditions:** Student is logged into the application.
- **PostConditions:** Student submits an application for the selected internship.
- **Include:** UC06 - View Internship Details
- **Extend:** Notify Student of Application Status

**3. UC03 - Manage Applications**

- **Overview:** Allows the Student to view and manage internship applications.
- **Actors:** Student
- **PreConditions:** Student is logged into the application.
- **PostConditions:** Displays a list of applied internships and their statuses.
- **Include:** UC06 - View Internship Details

**4. UC04 - Search Internships**

- **Overview:** Enables the Student to search for internships based on specific criteria.
- **Actors:** Student
- **PreConditions:** Student is logged into the application.
- **PostConditions:** Displays internships matching the search criteria.
- **Include:** UC06 - View Internship Details

**5. UC05 - Save Favorite Internship**

- **Overview:** Allows the Student to save an internship as a favorite for future reference.
- **Actors:** Student
- **PreConditions:** Student is logged into the application.
- **PostConditions:** Designates an internship as a favorite in the student's profile.

**6. UC06 - View Internship Details**

- **Overview:** Allows the Student to view detailed information about a selected internship.
- **Actors:** Student
- **PreConditions:** Student is logged into the application.
- **PostConditions:** Displays detailed information about the selected internship.

**7. UC07 - Receive Internship Recommendations**

- **Overview:** Provides personalized internship recommendations to the Student.
- **Actors:** Student
- **PreConditions:** Student is logged into the application.
- **PostConditions:** Recommends internships based on the student's profile and preferences.

**8. UC08 - Track Application Status**

- **Overview:** Allows the Student to track the status of submitted internship applications.
- **Actors:** Student
- **PreConditions:** Student is logged into the application.
- **PostConditions:** Displays the current status of submitted internship applications.

**9. UC09 - Receive Interview Notifications**

- **Overview:** Notifies the Student of interview invitations from prospective employers.
- **Actors:** Student
- **PreConditions:** Student is logged into the application.
- **PostConditions:** Sends notifications for interview invitations.

**10. UC10 - Update Profile**

- **Overview:** Enables the Student to update their profile information.
- **Actors:** Student
- **PreConditions:** Student is logged into the application.
- **PostConditions:** Updates the student's profile information.

**11. UC11 - Provide Feedback on Internship**

- **Overview:** Allows the Student to provide feedback on completed internships.
- **Actors:** Student
- **PreConditions:** Student has completed an internship.
- **PostConditions:** Submits feedback on the internship experience.

**12. UC12 - Explore Company Profiles**

- **Overview:** Permits the Student to explore profiles of companies offering internships.
- **Actors:** Student
- **PreConditions:** Student is logged into the application.
- **PostConditions:** Displays profiles of companies offering internships.
