# serverless-text-notification-website
Full stack application that allows to send text notifications on mobile. Using AWS, Node.js, Serverless framework, Google reCAPTCHA to protect from bot attacks and Twilio to send notifications to phones.

# How to make it work
- Clone this repository
- Install Node.js
- On your terminal, type "npm i serverless"
- On your terminal, type "npm i"
- Create an AWS account
- Setup a recaptcha account using this [link](https://www.google.com/recaptcha/admin#list)
- Setup a twilio account using this [link](https://www.twilio.com/console/phone-numbers/getting-started)
- Update environment variables and bucket-name in your serverless.yml file
- On your terminal, type "serverless deploy"
- Update "your-google-recaptcha-site-key" and "your-api-endpoint" (copy it from your terminal) on your client/index.html file
- On your terminal, type "serverless client deploy"
- Go to the website provided on your terminal after the previous command
