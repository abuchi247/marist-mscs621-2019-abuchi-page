# Book Review Management System
The goal of this application is to allow book readers connect with the world by letting other readers know how they feel about the books that they read.

Currently our database only has about 5000 books. There are plans to add additional book data.

## Want to try our app? [click here](http://ec2-18-218-59-12.us-east-2.compute.amazonaws.com/)

## Technologies Used:
1. Docker
2. Docker-compose
3. Python
4. Flask
5. Swagger
6. JSON
7. Nginx
8. Postgres
9. uWSGI
10. Swagger
11. AWS EC2 VM: for hosting Frontend Application
12. Google Cloud Compute Engine VM for Hosting Rest services for application
13. DockerHub: For hosting all containers used by this application 
    1. [Book review webservice](https://hub.docker.com/repository/docker/abuchi247/book_review_web_service)
    2. [Web Server and reverse proxy for webservice](https://hub.docker.com/repository/docker/abuchi247/book_review_web_service_nginx)
    3. [Book review frontend Application](https://hub.docker.com/repository/docker/abuchi247/book_review_frontend)
    4. [Web Server and reverse proxy for frontend application](https://hub.docker.com/repository/docker/abuchi247/book_review_frontend)

## Our production application infrastructure
![BookReviewArchitectureDiagramProd](BookReviewArchitectureDiagramProd.jpg)
<br/>
## Using our web applicaion
### Unauthorized User HomePage
![homePage](homePage.jpg)

### Registration Page
![RegisterationPage](registrationPage.jpg)

### Login Page
![LoginPage](loginPage.jpg)

### Authorized User HomePage
![authorizedHomePage](authorizedHomePage.jpg)

### Authorized User HomePage
![authorizedHomePage](authorizedHomePage.jpg)

### LookUp Book
![lookup](lookup.jpg)

### Found Book
![foundBook](foundBook.jpg)

### Add review on a book
![addReview](addReview.jpg)

### View Reviews on Book
![bookReviews](bookReviews.jpg)

### View Your Reviews
![userReviews](userReviews.jpg)

#### **For more information on how to setup our application on your local or any deloyment machine, [click here](https://github.com/abuchi247/marist-mscs621-2019-abuchi)**