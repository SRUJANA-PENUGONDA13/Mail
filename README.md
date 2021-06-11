# Mail
A simple mail service developed using flask and google API. To send mails to anyone from my mail id in particular format.

Service - "https://sample-srujana-deploy.herokuapp.com/mail/{{toMail}}/{{subject}}/{{message}}

Instructions:

Message: Message must be sent in the below dictionary format
 {  
    senderName : name of the sender, 
    receiverName : Receiver name ,
    mail : senders mail , 
    message : message to receiver 
}
Subject: Subject of mail (plain text format)
toMail: Receivers Mail Address


