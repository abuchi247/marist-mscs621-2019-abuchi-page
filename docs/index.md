# Book Review Management System
The goal of this application is to allow book readers to connect with the world by letting other readers know how they feel about the books that they read.

Currently our database only has about 5000 books. There are plans to add additional book data.


## Want to try our app? [click here](http://ec2-18-218-59-12.us-east-2.compute.amazonaws.com/)

## Technologies Used:
* Docker
* Docker-compose
* Python: Programming language of choice
* Flask: Web framework
* Swagger: API documentation
* JSON: Response format from our backend REST API services
* Nginx: Web server and reverse proxy for our rest services and frontend container application
* Postgres: Relational database of choice
* uWSGI: Application server for our rest services and frontend application
* DockerHub: For hosting our containerize application images
    * [Book review frontend application](https://hub.docker.com/repository/docker/abuchi247/book_review_frontend)
    * [Book review frontend web server and reverse proxy](https://hub.docker.com/repository/docker/abuchi247/book_review_frontend_nginx)
    * [Book review REST web service](https://hub.docker.com/repository/docker/abuchi247/book_review_web_service)
    * [Book review web service and reverse proxy for REST web service](https://hub.docker.com/repository/docker/abuchi247/book_review_web_service_nginx)
* AWS EC2 VM: For hosting our frontend application
* Google Cloud Compute Engine VM: For hosting our rest web service
* Heroku Postgres DB Instance

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

#### **For more information on how to setup our application on your local machine, [click here](https://github.com/abuchi247/marist-mscs621-2019-abuchi)**
