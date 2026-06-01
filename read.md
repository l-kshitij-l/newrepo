subject: Weekly Work Status report

Hello Team,

I hope this message finds you well. I wanted to let you know that starting this week, I’d like everyone to send me a weekly status report every Friday outlining the work you’ve completed during the week. This will help us keep track of progress and ensure smooth coordination across our projects.

If you find that you don’t have any tasks assigned or are running short on work, please make sure to proactively reach out to the PM—either Gurpreet or Yogesh—to check if there are additional assignments you can take up.

Thank you all for your cooperation. I look forward to receiving your updates and working together to keep everything moving forward smoothly!

Regards, 
Uttam Jadhav (PMP)®



received this mail from manager read it properly and say yes



now I have to create a new email thread where I submit every weekly report, so accordingly give subject and body, for body these are the updates I have given till now in teams group to another client project manager:

Monday (25-05-2026): [Hi Yogesh, quick updates for the day:
I connected with Chiranjivi for most of the day to resolve the "dimension not found" error
In the UI section, modified the portfolio created, assigned portfolio to teams, and created rule for the respective portfolio.
Performed step-by-step debugging and traced the issue in detail
Identified that the existing transaction cannot be edited as it is already linked to multiple tables
We decided to trigger a new transaction instead
Initially faced issues while firing the new transaction
After I did thorough debugging and traceback, the issue was resolved and the new transaction was processed successfully.
Successfully fired a new transaction via AG for the credit channel (NEFT)]


tuesday (26-05-26):|
[Hi Yogesh, updates for the day:
While attempting to send SMS to the Midepush log table, encountered a "500 Internal Server Error"
Performed detailed debugging of the code and verified the endpoint configuration
Tried enabling logs by updating the correct log path in log4j.xml; currently working on getting the logs visible on RDP for better traceability
Made changes in the stored procedure, including aligning the date format with the procedure signature
Carried out both local and remote debugging
Deployed the code multiple times on WAS to validate the functionality
Focusing on enabling proper logging to gain more clarity on the 500 error and proceed further]

wednesday:
[Hi Yogesh, quick updates for the day:
Tried deployment via JAR on RDP using a .bat file, but encountered errors during execution
Attempted local deployment as well, where CORS-related issues were observed
Identified some configuration mismatches with the 2020 environment]

thursday:
[the message has been successfully inserted into Log Table  for NEFT Credit channel, huge success 1 channel successfully worked]

friday:
[Today's Update:
 
Successfully compiled all stored procedures related to SMS batch processing in Oracle SQL Developer.
This was specifically carried out for the NEFT channel.
Used sample input parameters and existing data from the database.

The following procedures were compiled and validated:
 USP_CREDIT_SMS_BATCH_REQUEST_POLLING_EVEN :
Verified that eligible records were picked based on criteria, inserted into TT_CREDIT_SMS_BATCH_POLLING_REQUEST_EVEN, and status updated in SMS_PUSH_MESSAGE_LOG_CREDIT_CHANNEL.

USP_CREDIT_SMS_BATCH_UPDATE_RESPONSE :
Tested success, failure, and system failure scenarios.
Confirmed correct status updates in SMS_PUSH_MESSAGE_LOG_CREDIT_CHANNEL (0 for success, 2 for failure), along with proper population of response fields and corresponding entries in the ACT table.
3. USP_CREDIT_SMS_BATCH_PENDING_REQUEST :
Verified that pending records were reprocessed by resetting , refreshing timestamps, and appending retry notes in SNOTE2 within SMS_PUSH_MESSAGE_LOG_CREDIT_CHANNEL..]



worked on manual sms csm, currently all 4 channels successfuly work. continously in touch with Yogesh, Aniket and Chiranjivi, amit bhat regarding the csm, heavily involved in development of the csm.



I have to include all this as mail to my manager, but in short and upto the mark bullet points not too much to read, informative, and highlight my effort it should look like i have wokred but not exaggerate too much

note that my manager doesnt know exact detail about csm and stuff, I have to mention tasks I have done, make sure content is such that it should be seen i have been working thoroughly and keep it short, precise and upto the mark
