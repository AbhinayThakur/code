# code
Services to send Mail..

REST url http://localhost:8080/CodeChallenge/rest/sendmail? to=mailId_of_person_send_mail &subject=subject_of_mail &msg=Message_body

UI @ http://localhost:8080/CodeChallenge/

///////////////////
Changes You have to make before Running the Code..

Go to Source Packages/com.challenge.util.SendMail.java and edit line number 28 & 29 accordingly 

////////////

Do clean Build and run in Netbeans..

For first mail it will give error, you have to authenticate your gmail account by allowing less secure device notification to true by going to your gmail account..

///////////////////

I have also added custom Exception handling Class which will give you exact reason for exception in REST. 
