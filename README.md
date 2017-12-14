# Questions to Consider when considering education technology products
Our CIO and I recently had to come up with a list of questions to ask vendors that are being considered for curriculum and assessment products in our district.  Many of the questions here are routinely asked by either the CIO or myself when talking with education technology vendors and we thought this might be useful for other schools, local education agencies, and state education agencies as they consider technology purchases as well.  We're still in the process of organizing the questions and proofreading, but wanted to open this up to others who may want to contribute questions that may be important as well.  In the end, we hope to provide a list that others around the country can use to improve the quality of services provided by education technology vendors and to ensure that our educational organizations are able to access the best possible product(s) for their students.  

## TODO
- [ ] Group questions into subcategories.
- [ ] Develop rubrics for questions that provide information to other organizations about what to look for in the responses.
- [ ] Encourage other schools, LEAs, SEAs, and third parties to contribute questions to the list by submitting an issue.
- [ ] Document process for vetting and approving contributions to the list. 

## The questions: 

Does your product integrate or import unique numeric student identifiers used by schools and our student information system?

What level of detail is available for district wide export/access to student information in your product?  (Answer to this should be student level data with either the keyed response or the selected response)

Does your product integrate with the OneRoster API to import student rosters?  If not, what is the anticipated timeline to implement this API (e.g., < 1 month, 1-3 months, 3-6 months, 6-12 months, > 12 months)? 

Does your product integrate with Clever to import student rosters?  If not, what is the anticipated timeline to implement this API (e.g., < 1 month, 1-3 months, 3-6 months, 6-12 months, > 12 months)? 

If both of the previous answers were no, how are student and teacher data imported into your product?

Does the export process implement the Ed-Fi Assessment Outcomes Management API (see https://techdocs.ed-fi.org/display/EFDSRFC/ED-FI+RFC+8+-+ASSESSMENT+OUTCOMES+MANAGEMENT+API for additional information)?  If not, what is the anticipated timeline to implement this API (e.g., < 1 month, 1-3 months, 3-6 months, 6-12 months, > 12 months)?  

Does the export process implement a custom API?  If not, what is the anticipated timeline to implement this API (e.g., < 1 month, 1-3 months, 3-6 months, 6-12 months, > 12 months)?  

If the export process does not provide an API, are ODBC or JDBC connections available to export data from your product into our core systems?  If not, what is the anticipated timeline to implement this API (e.g., < 1 month, 1-3 months, 3-6 months, 6-12 months, > 12 months)?  

If the export process does not use an API, ODBC, or JDBC connections, what method does your platform provide to programmatically (e.g., using computer software/code not a graphical user interface) access our students' data?

Does the product support streaming access to student data?

Does the product export data according to any industry standard file formats/specifications (e.g., QTI, Ed-Fi, OneRoster)?

What frequency are data available to export (e.g., request only, weekly, daily, hourly, streaming/real time)?  

Is the item bank available for use if we wanted to use our own test deployment platform?  If so, which version of the QTI standard (https://www.imsglobal.org/question/index.html) is used to transfer item data?  

Have items been calibrated?  If so, how are the item parameters made available for use in subsequent scaling, linking, and/or equating needs?  If not, what is the timeline for items to be calibrated (e.g., < 1 month, 1-3 months, 3-6 months, 6-12 months, > 12 months)?  

What is the scaling method used by the platform?  How are missing/ignored responses treated?  

What attemptedness rules are used to determine whether or not a student will be assigned a score?

Describe the processes used for bias review of the items and distractors.

Have the items been vetted for differential item functioning?

Does your assessment tool implement the APIP standard (https://www.imsglobal.org/apip/index.html) to provide accessibility access/tools for students needing accommodations?

Does your platform satisfy all W3C accessibility standards to conform with §508? 

What encryption technology does your platform use to encrypt data in transfer?

Do you support SSO?  If so, what authentication/identity management services does your tool integrate with?  If not, what is the anticipated timeline to implement SSO (e.g., < 1 month, 1-3 months, 3-6 months, 6-12 months, > 12 months)? 

Has the company already signed and agreed to the terms and conditions of our data sharing agreement? If not, are you willing to sign our data sharing agreement?

What is the project plan related to implementation?  Specifically address deliverables related to training for IT/Data/Network/Security staff, Go-Live dates, and testing any import/export functionality.

How does the platform handle students with multiple enrollments (primary and secondary) in Infinite Campus?  

Can the platform manage staff assigned to multiple schools?

How does the platform handle user accounts for staff members that are not assigned students?

Does your platform support role based permissions?  Can users be assigned multiple roles?

Does your platform support assigning roles or permissions programmatically?

What level of support is included in the purchase of the product?  For example, is support only available to a limited number of central office staff, certain numbers of school staff, or can educators contact your company's support directly?  

How is support accessed?

What are the terms of the service level agreement?

If implementation will take place during the academic year, how would that affect any existing data?

If other products you offer are currently in use, will implementing this product have any effect on the other products currently in use?  

Does your application support impersonating user accounts for support/troubleshooting purposes?

Describe your data center, including power, access, data, and hardware redundancy.  Include details about geographical separation, if applicable.

Describe your disaster recovery plan.

Describe the architecture of the platform that ensures stability, scalability, high performance, and high availability.

What backups of the data are available?  What is the backup plan, including frequency, longevity, and full vs incremental strategy of backups?  What is the process to restore the application and data to an earlier state?

What data quality assurance/quality control checks are implemented for any import/export processes?  How does the system handle errors during import/export?

How are we notified of the type and number of errors during import/export?  

Who provides tier I support (e.g., password resets, lockouts, etc..)?  

What type of knowledge base is available to provide end-users with self-service supports?

What are the system requirements for the product to be used?

Which browsers is the product compatible with? (Include support browsers and versions)

What technologies are used to render animation/video/media content in the platform (e.g., Flash, HTML5, etc...)?

Is your platform accessible only through HTTPS?  Are HTTP requests automatically redirected through HTTPS?

Does your platform function fully on Windows, MacOS, ChromeOS, and IOS? (Include supported versions)

What is your feature request and bug reporting process?

What is your patch and and update cycle?

How are routine patches and updates distributed and applied?

How are emergency patches and updates distributed and applied?

What data is available about user sessions (e.g., timestamps, content being viewed, callbacks fired, etc...)?  If no data about user sessions is currently available, how soon will you make it available (e.g., < 1 month, 1-3 months, 3-6 months)?  { <- This is basically how we know staff and students are actually using the product we paid for.  }

Does the product use a computer algebra system (CAS)?  In other word is the product smart enough to distinguish that ‘x+1’ and ‘1+x’ are the same algebraic expressions.  Another good example is ‘x+x’ and ‘2x’.

How are mathematical expressions displayed on the screen? in print?  Are the expressions typeset/rendered using LaTeX, mathJax, etc... and is the font used to render these symbols approved by the American Mathematical Society?

What is the bandwidth per concurrent user?

How is content assigned or associated with each student, teacher, adn administrator?

If a student is in multiple classes that are assigned content, does that single student use multiple licenses?

Are the licenses named users or concurrent users for students?  Staff?  Administrators?

What reporting tool(s) are available to school and district administrators?  What level of detail is available in those reports?

Can the reporting tool(s) be embedded in an I-Frame?

Can reporting for administrators be limited to the school or schools that they are associated with?

Is the platform FERPA compliant?

What is your notification procedure for a suspected data breach?  Include the timeline for notification.

Do assessments save progress in the event of a network or system outage?

What processes are in place to minimize item exposure?

Does your platform administer adaptive, fixed form, or both types of assessments?

What are your five largest K-12 implementations?  Please provide district, number or total users, and typical number of concurrent users.

How has your system and platform been stress tested and what were the latest results?

Does your system automatically detect usage and scale as needed?

Do you have a system to load balance requests and system traffic and describe your load balancing? If not, what is the anticipated timeline to implement load balancing (e.g., < 1 month, 1-3 months, 3-6 months, 6-12 months, > 12 months)? 

If the system uses fixed forms, how mnay parallel forms are available for each assessment?

Do your assessments comply with the Standards for Educational and Psychological Assessment?

