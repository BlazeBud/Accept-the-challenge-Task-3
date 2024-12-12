### Functional tests:
##### 1. Test for calculating the percentage of correct answers
 __Precondition.__
   * The user has completed the test.  __Steps:__ 
 Complete the test with 10 questions, of which 7 are correct.
 Check that the percentage of correct answers is displayed (70%).
1.3 __Expected result:__ 
* The user sees the total percentage of correct answers, a list of incorrect answers and recommendations.
___
##### 2. Test for displaying incorrect answers with explanations
__condition__
The test contains incorrect answers.
__Steps:__ 
Complete the test and select 3 incorrect answers.
Check that incorrect answers with an explanation are shown after the test is completed.
__Expected result:__ 
Each incorrect answer has an appropriate explanation.
___
##### 3. Test for taking into account the time of passing the test
__condition__
The user starts the test.
__Steps:__
Start the test with a timer for 20 minutes.
Check that a warning appears 5 minutes before the end of time.
Complete the test before the end of time.
__Expected result:__ 
The timer should count down the time correctly, and a warning should appear 5 minutes before completion.
___
##### 4. Test for saving the report in your personal account
__Precondition__
The user has completed the test.
__Steps:__
Start and finish the test.
Check that the test report appears in your personal account.
__Expected result:__
The test report is saved in the user's personal account.
___
##### 5. Test for connection loss
__Precondition__
The user is on the test page.
__Steps:__
Start taking the test.
&nbsp;Simulate connection loss.
Check that the system handles the connection loss correctly.
__Expected result:__ 
A connection loss message appears with the option to reconnect or save the intermediate result.
___
##### 6. Test for completing the test ahead of time
__condition__
The user is on the test page.
__Steps:__
Complete the test before the time expires.
Check that the test result is saved and displayed correctly.
__Expected result:__
The result should be saved even if the user completed the test before the end.
___
##### 7. Test for the correct display of recommendations
__Precondition__
The user has completed the test.
__Steps:__
Complete the test with a bad result.
Check that the system provides recommendations for improvement.
__Expected result:__ 
The recommendations should be displayed to the user.
