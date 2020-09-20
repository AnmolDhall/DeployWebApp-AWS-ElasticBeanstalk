# Deploying "Hello World" web application on AWS

### Create web application 

Create a "Hello World" web application locally, and zip the directory containing the application source code.

Download the nodejs directory from the repository and zip it to nodejs.zip and make use of this zip file for deploying.

### Steps to deploy web application on AWS:

Login to AWS account.

Navigate to AWS Elastic Beanstalk service console page.

Click "create application" and enter the name of an application and click create again.

Create environment for an application.

Select "Web Server Environment" and click "select".

Next, enter environment information such as name, description etc.

Select Platform as "Tomcat" and platform branch as "Tomcat 7 with Java 7 running on 64bit Amazon Linux".

Now, select option *'upload the source code from local file'* and upload the source code nodejs.zip file and click "Create environment".

Once the enviornmnet update completed successfully, it will reflect the Health as "ok" and in "Green" color.

The URL to access the deployed web application will be reflected on the same page:open the URL in the browser and it will display "Hello World"

ex: http://helloworldwebapp-env.eba-eygepjzt.us-east-2.elasticbeanstalk.com/
