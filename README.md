# Project-1
You have been Hired Sr. DevOps Engineer in Analytics Pvt ltd. They want to
implement DevOpsLifecycle in their company. You have been asked to implement
this lifecycle as fast as possible. Analytics is a product-based company, their
product is available on this GitHub link

https://github.com/Analytics/product.git

# Following are the specifications of the lifecycle:
![Diagram](https://github.com/sharfuddin1986/Project1/assets/106474548/73d5983b-5edc-44e1-854d-0f9215b2cc1c)# Project1

1. Install the necessary software on the machines using a configuration management tool.
2. Git Workflow has to be implemented.
3. Code Build should automatically be triggered once commit is made to master branch or develop branch.
   If commit is made to master branch, test and push to prod
   If commit is made to develop branch, just test the product, do not push to prod
4. The Code should be containerized with the help of a Dockerfile. The
   Dockerfile should bebuilt every time there is a push to Git-Hub. Use the
   following pre-built container for your application:
   The code should reside in '/var/www/html'
5. The above tasks should be defined in a Jenkins Pipeline, with the
   following jobs.
   
#   Job1 : build 
#   Job2: test
#   Job3 : prod


