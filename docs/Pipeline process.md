# Udagram Application CI/CD Pipeline

The Application Repo is on a Github.
-- Link : https://github.com/aosama169/UdacityUdagramApplication

The Application CI/CD Pipeline done through CircleCi, and it is connected to the Github Repo,
So for Any updates done to the Application, Build Script is being run on CircleCi to build and deploy the Application to AWS as follows:
1.	Developer push changes to Github Repo.
2.	CircleCI Build Script starts to 
a.	Install dependencies.
b.	Build FrontEnd Application.
c.	Build Backend Application.
d.	Deploy Backend Application to Elastic Beanstack
e.	Deploy FrontEnd to AWS S3 Bucket.

