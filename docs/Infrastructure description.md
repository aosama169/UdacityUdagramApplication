# Udagram Application Infrastructure


The Application uses Amazon Web Services for deployment.
1.	For Database Service, we used RDS Service from AWS.
Created a Postgres DB on aws available through this Endpoint:
                             `udgramdb.ccznsa6uitul.us-east-1.rds.amazonaws.com`
2.	For Application Backend Server, We used Elastic Beanstalk and created a nodeJs environment to serve as a backend server.
And it is available through this Endpoint:
                    `http://udagramapplicationenv.eba-x23spnri.us-east-1.elasticbeanstalk.com/`
3.	For Application FrontEnd, We used S3 Bucket and created Static website hosting.
And it is available through this Endpoint for End Users Access:
                    `http://udgramappbucket.s3-website-us-east-1.amazonaws.com/`


