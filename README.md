# Project1

You have been Hired Sr. DevOps Engineer in Wazooz Software company. They want to
implement DevOpsLifecycle in their company. You have been asked to implement
this lifecycle as fast as possible. Birla Software is a product-based company, their
product is available on this GitHub link

https://github.com/birlasoft/product.git

# Following are the specifications of the lifecycle:

1. Install the necessary software on the machines using a configuration management tool.
2. Git Workflow has to be implemented.
3. Code Build should automatically be triggered once commit is made to
   master branch or develop branch.
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

<img src="https://github.com/sharfuddin1986/logo/blob/4cc4a40024ac8c2692fef02783ec06e35235a20f/Untitled%20Diagram.drawio.png" alt="Diagram" width="100" height="100" style="max-width: 100%; padding :100px">
