# Deploying "Hello World" web applicaation on AWS

Create a "Hello World" web application locally, and zip the directory containing the application source code.
To deploy web application on AWS:
Login to AWS account.
Navigate to AWS Elastic beanstalk service console page.
Click "create application" and enter the name of your application and click create again.
Now, create environment for your application.
Select "Web Server Environment" and click "select".
Next, enter environment information like name, description of your choice.
Select Platform as "Tomcat" and platform branch as "Tomcat 7 with Java 7 running on 64bit Amazon Linux".
Now, select option 'upload the source code from local file' and upload the source code .zip file and click "Create environment".
Once the enviornmnet update completed successfully, it will reflect the Health as "ok" and in "Green" color.
The URL to access the deployed web application will be reflected on the same page:open the URL in the browser and it will display "Hello World"
ex: http://helloworldwebapp-env.eba-eygepjzt.us-east-2.elasticbeanstalk.com/
