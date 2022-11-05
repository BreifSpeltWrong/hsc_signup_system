# hsc_signup_system
Signup system intended for use in a school setting.

-  Web-based
    * Compatible with both mobile and computers
    * Compatible with all web browsers
- Identification system
   * [Based off school email?]
   * Student, Teacher and Admin panels
        - Students can access and edit their current options , access the list of possible options and [access and edit a profile system, to put in interest and achievements]
        - Teacher can access and edit their clubs, [access student profiles?], and access and edit the student list of those in their clubs
        - Admins can access and edit everything that students and teachers can access, but also edit configuration files.
- Databases to store lists of who is in which club
- JSON config files
- EASY TO USE export functionality
    * Registers
    * Options listings
- User's individual data stored in individual JSON files with the following content:
    * Titled by Firstinital_Surname e.g. J_Bloggs. If there are multiple instances of the same Title, append with _0, _1 and so on.
    * First and Last names
    * Form / Tutor (If applicable. Enter null if the user is not in a form)
    * School email (Used for login.)
    * Status at school / organisation (Student, Teacher , *Volunteer?*)
    * UUID for anonymization in database.
