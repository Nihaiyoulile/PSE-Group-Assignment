I. Test Objectives
(1)Verify that all three users (students, lecturers, administrators) can successfully log in and enter the corresponding page.
(2)Verify that the core functions of each role can run correctly.
(3)In order to ensure that users can complete the operation tasks smoothly, evaluate whether the prototype interface is easy to use.
(4)Find and record the problems that occur during the test.

II.Test scope
Test content
(1)Login module: Correct account login, wrong password prompt, Reset Password 
(2)Student module: View the course list, search for courses, enter the course to check materials, Bookmark function, submit questions, upload pictures
(3)Lecturer module: Upload learning materials, create new courses, view and answer pending questions
(4)Administrator module: Review and approve the account, block the account, and remove the course

III.Test Environment
(1)Test file: campus_connect.html
(2)Browser: Google Chrome 
(3)Equipment: Windows laptop 
(4)Testers: ZHANG HAO RAN, ZHANG WEN BO and ZHANG HAO YAN
(5)Test date:Feb 28


IV. Test Case
| Num ber | Test module  | Function               | Test steps                                                                                     | Result                                              |
|---------|--------------|------------------------|-----------------------------------------------------------------------------------------------|-----------------------------------------------------|
| TC01    | Login        | Account login          | Input student, lecturer and administrator account & password, then click Login               | Successfully logged                                 |
| TC02    | Login        | Wrong password to log in | Enter the email address, and then enter the wrong password                                   | Display the error prompt letter                     |
| TC03    | Student      | Search for courses     | Log in as a Student, then enter the keywords in the search bar, and finally click Search     | Successfully display courses related to keywords    |
| TC04    | Student      | Check the course materials | Log in as a Student, and then click any course                                               | Successfully display materials                      |
| TC05    | Student      | Bookmark               | Enter any course and then click Bookmark                                                     | Success                                             |
| TC06    | Student      | Submit questions       | Click Ask a Question to fill in the content, then click Submit                               | The question was submitted successfully             |
| TC07    | Student      | Choose the course style | Enter any course and choose academic style or casual style                                   | Fail, lack of style                                 |
| TC08    | Lecturer     | Upload materials       | Log in to teacher’s account and select the course, then upload materials                     | Uploaded successfully                               |
| TC09    | Lecturer     | Check the students’ questions | Click QUESTIONS to view and answer questions                                              | The status of the problem change to Answered        |
| TC10    | Administrator| Approve & block accounts | Login to Administrator’s account, then click Approve or Ban                                 | The account status has been updated to active or banned |
| TC11    | Administrator| Content Moderation     | Click Content Moderation, then click Remove                                                  | Content removed successfully                        |
| TC12    | Administrator| Course Approval        | Click Course Approval, and then click Approve or Reject                                      | Fail, this part is missing                          |

V.Test Summary
1.Test result
The total number of test cases: 12
Pass: 10
Fail: 2

2.Problems found
| Question number | Describe | Severity |
|----------------|----------|----------|
| Bug-01 | The course lacks description of the teaching style. | Medium |
| Bug-02 | Lack of the function of approving courses | High |

3.Improvement measures
Bug01: The marking of different teaching materials in the course belongs to academic style or casual style. In this way, it is convenient for students to choose quickly according to their own needs.

Bug02: Immediately add the function that the administrator can approve or reject the course. In order to be consistent with the UML diagram.

