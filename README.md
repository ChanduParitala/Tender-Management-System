# Tender-Management-System
Intern Project

US_1	Contractor Registration	Contractor  	As a user, I should be able to register to this website	"1. Clicking on the “Register” button should open the Registration form. 
2. User to fill the basic attributes:
First Name- 3 - 15 characters
Last Name- 3 - 15 characters
DoB - Age should be >18, should be selected front the calendar drop down
Gender - Radio button
Contact Number- 10 digit numeric
Category - drop down
User Id - Auto generated, to be used for login
 Password - minimum lenth of 6 with numeric and special charatcers.
3. Clicking ‘Submit’ button should validate the datatype constraints for each field
4. User failing to provide information for the mandatory fields be presented with an alert message – ‘Please update the highlighted mandatory field(s).’ Also, highlight the missed out field in red
5. Post-successful field validation, save the information in the database
6. Upon saving the information in the database, display the message “New user created successfully”
Note - Trainees can add required fields as necessary and validation to be handled during the project phase.
Note - Use drop downs , radio button, check box etc wherever applicable."
US_2	Admin credentials	Admin	As a  Admin, I should be able to log in	"1. System should have a Admin Login credentials stored in the DB.
2. When keyed in with correct credentials, it should log in. 
3. If User ID is not present, it should throw error saying "" User ID not present.
For wrong password, it should say ""Password not matching"" "
US_3	Contractor / admin Authentication	Contractor / Admin	As a user, I should be able to log in	"1. Clicking “Sign In” link should allow the user to enter the User ID and Password and click 
2. Portal to validate the entered user credentials against the database and allow login for registered users.
3.  If User ID is not present, it should throw error saying "" User ID not present.
For wrong password, it should say ""Password not matching"" "
US_4	Tender management	Admin	As a admin, I should be able to display the tender details through online	"1.The admin should be able to display the tender details through online
2.Admin should give the “Tender details” link through online
3.Tender link should redirect to the tender details page
4. Tender details like - tender id, tender type, tender date date, Minimum quote etc can be the fields
"
US_5	Contractor /Tender search	Admin/ Contractor	As a admin, I should be able to select the supplier	"1)Admin should be able to search contractor details based on category like pwd contractor/canteen contractor etc
2)Admin should get the contractor list with basic details based on the search 
3)Clicking the  selected contractor, admin should be able to view more details
4)Tender search should be enabled for both contractor and admin
5)Search result should be displayed with basic details
6)Contractor details like contractor id, contractor name, Contracter address, email id etc can be added
Note - Use Pagenation for listing the search results"
US_6	Apply Tender	Contractor	As a user , I should be able to know the tender details	"1.The user can be able to know the tender details through online
2.The user click on the “Tender details” link should redirect to the tender details page
3.The user also be able to copy the tender details by clicking the “Tender link”
"
US_7	Upload documents	Contractor	As a user, I should be able to upload the documents	"1.The user can be able to upload their documents through online
2.The user clicking the “upload documents” link should redirect to the upload documents page
3.User failing to provide information on the mandatory fields be provided with an alert message – ‘Please update the highlighted mandatory field(s).’ Also, highlight the missed out field in red
4.Post-successful field level validation, save the documents
5.Upon saving the documents , display the message, ‘Your documents are uploaded successfully’.
"
US_8	Tender evaluation	Admin	As a admin, I should be able to evaluate the tender	1.Admin should be able to evalutate the tender based on the tender amount and through other information
US_9	Contract approval	Admin	As a admin, I should be able to give the approval for the contract	"1.Admin should be able to approve the tender or contract
2.After approval the admin send the message to the user through online
3.The user receives the message “Contract has been approved”
"
US_10	Contract start	User	As a user I should be able to start the contract	1.The user should be able to start the contract and should also be completed
US_11	Help	Contractor	As a user, I should be able to get help.	"1. Page that displays the basic details text about how to search documents
2. Portal to display a form that allows user to report the technical issues-
Issue
Description
Send Button
3. Portal to display the Contact number to report issues
4- The issues raised by the user should be solved by the Admin.
"
US_12	Feedback  Questionnaire	Admin	As an admin I should be able to create feedback Questionnaire	"1 Admin should be able to create feedback questionnaires
2-Attached is the sample questionnaries, can be modified.
"
US_13	 User Feedback	Contractor	As a user, I should be able to submit the feedback.	1. User should be able to provide feedback / reviews 
US_14	Log off	User	As a user, I should be able to log off	1. When the user clicks Log off, the system should disconnect from the system.
US_15	Password reset	User	As a user I should be able to reset password	"1. During registration, System should pop up three secret questions for Password recovery.
2. When the user clicks Forgot User ID, system should ask for the secret questions, Email id and Mobile number. On answering the questions correctly, the User ID should be displayed.
3. When the user clicks Forgot Password, system should ask for the User ID, Email id n Mobile number and secret questions. On answering the questions correctly, the password reset page should be displayed.
4. On entering the details in the password reset page, password should be validated
5. On clicking Submit, the details should be saved to the Database"
US_16	Generate Report	Admin	As Admin, I want to generate report	"1- Admin should be able to generate report to get all the contract details.
2- Admin should select the from date and to date.
3- Selecting the date, admin should click generate report button.
4- Report should be generated with the contract details for the period admin selected in the from and to date.
5- Report should be downloadable in excel format.

