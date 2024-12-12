### Functional tests:
##### 1. Test for calculating the percentage of correct answers
__Precondition__
    The user has completed the test.
__ Steps:__ 
Complete the test with 10 questions, of which 7 are correct.
Check that the percentage of correct answers is displayed (70%).
__Expected result:__ 
The user sees the total percentage of correct answers, a list of incorrect answers and recommendations.
___
#####2. Test for displaying incorrect answers with explanations
  __condition__
The test contains incorrect answers.
__ Steps:__ 
Complete the test and select 3 incorrect answers.
&nbsp;&nbsp;&nbsp;&nbsp;Check that incorrect answers with an explanation are shown after the test is completed.
__ Expected result:__ 
&nbsp;&nbsp;&nbsp;&nbsp;Each incorrect answer has an appropriate explanation.
___
##### 3. Test for taking into account the time of passing the test
__condition__
The user starts the test.
__ Steps:__
&nbsp;&nbsp;&nbsp;&nbsp;Start the test with a timer for 20 minutes.
&nbsp;&nbsp;&nbsp;&nbsp;Check that a warning appears 5 minutes before the end of time.
&nbsp;&nbsp;&nbsp;&nbsp;Complete the test before the end of time.
__ Expected result:__ 
The timer should count down the time correctly, and a warning should appear 5 minutes before completion.
___
##### 4. Test for saving the report in your personal account
__Precondition__
The user has completed the test.
__ Steps:__
&nbsp;&nbsp;&nbsp;&nbsp;Start and finish the test.
Check that the test report appears in your personal account.
__ Expected result:__
The test report is saved in the user's personal account.
___
##### 5. Test for connection loss
__Precondition__
The user is on the test page.
__ Steps:__
&nbsp;&nbsp;&nbsp;&nbsp;Start taking the test.
&nbsp;&nbsp;&nbsp;&nbsp;Simulate connection loss.
&nbsp;&nbsp;&nbsp;&nbsp; Check that the system handles the connection loss correctly.
__ Expected result:__ 
&nbsp;&nbsp;&nbsp;&nbsp;A connection loss message appears with the option to reconnect or save the intermediate result.
___
#####6. Test for completing the test ahead of time
__condition__
The user is on the test page.
__ Steps:__
&nbsp;&nbsp;&nbsp;&nbsp;Complete the test before the time expires.
Check that the test result is saved and displayed correctly.
__ Expected result:__
The result should be saved even if the user completed the test before the end.
___
##### 7. Test for the correct display of recommendations
__Precondition__
The user has completed the test.
__ Steps:__
&nbsp;&nbsp;&nbsp;&nbsp;Complete the test with a bad result.
Check that the system provides recommendations for improvement.
__ Expected result:__ 
The recommendations should be displayed to the user.
