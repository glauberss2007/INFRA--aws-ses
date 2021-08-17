# aws-ses
Configuring an Amazon Simple Email Service.

Amazon Simple Email Service (SES) is a cost-effective, flexible, and scalable email service that enables developers to send mail from within any application. You can configure Amazon SES quickly to support several email use cases, including transactional, marketing, or mass email communications. Amazon SES's flexible IP deployment and email authentication options help drive higher deliverability and protect sender reputation while sending analytics measure the impact of each email. With Amazon SES, you can send email securely, globally, and at scale. If you are a data scientist and wanna use this service in your application then you can set up a system that analyses emails sent and received for your specific application.

## Verify Email

In this step you need to select an AWS domain or indicate an account from any other domain, for example a gmail, etc... 

Mail verification

![image](https://user-images.githubusercontent.com/22028539/129796910-78284ef2-beeb-43c7-bb25-fd617165d341.png)

Domain verification

![image](https://user-images.githubusercontent.com/22028539/129796856-e89c1414-f12b-486d-8429-054746a181a8.png)

As soon as you verify the mail you can use it to send automatic messges.

Optional: Configure DKIM to protect agains spoofing.

## Send Test Email

Now back to email addres conf and send a test mail

![image](https://user-images.githubusercontent.com/22028539/129797758-d435dfa0-b229-4501-b4c3-903bdd618d92.png)

## Email Sending Statistics

You can see the statistic at email sending

![image](https://user-images.githubusercontent.com/22028539/129797917-ae0811ab-da3a-4900-9e3d-12f41dcd5b5e.png)

![image](https://user-images.githubusercontent.com/22028539/129798159-3796c40a-40b4-41aa-8a22-4c28c3c504ac.png)

## Apply for Production use of AWS SES

In Edit your account details you can edit the message to be sent and contact info.

![image](https://user-images.githubusercontent.com/22028539/129798108-e7d151d4-2a57-416f-8df9-765e758f21b4.png)

The SMTP configurations to be used in the APP can be founded in SMTP settings

![image](https://user-images.githubusercontent.com/22028539/129798260-bf03a414-c15d-48bd-8c8f-ef0b341e15b4.png)

PS: in this [LINK](https://docs.aws.amazon.com/pt_br/ses/latest/DeveloperGuide/examples-send-using-smtp.html) you can see diferent languages implementation of SES message sender.

You can test the credentials using https://smtper.net
