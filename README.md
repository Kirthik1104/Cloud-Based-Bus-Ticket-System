# Cloud-Based-Bus-Ticket-System

<h1>Problem Statement</h1>
The aim of this report is to identify the challenges faced by the existing online ticket booking system and 
propose a solution to make it scalable, dependable, and easy to maintain by utilizing cloud technologies 
and services. Although the current application has been developed using PHP, Javascript, HTML, and CSS, 
it faces several challenges in terms of scalability, security, and accessibility. The database used in the 
development of the application's backend, Amazon RDS MySQL, may also face issues related to 
conventional data storage. The platform's administration has limited control over managing both inperson and online bookings, which can impact the website's performance and user experience. The 
proposed solution aims to leverage the scalability, security, and accessibility of cloud-based services such 
as Amazon Elastic Compute Cloud (EC2), Amazon RDS, Amazon CloudFront, AWS CloudWatch to overcome 
these challenges and offer a reliable and efficient ticket booking system for the users.

<h1>Abstract/ Introduction</h1>
The objective of the website is to make it possible for customers to purchase tickets using a variety of 
payment options and travel to any destination. The software also enables the administration to control 
the trips that are offered, all of their online bookings, and direct customer bookings.
The project's goal is to make this application scalable, dependable, and maintained by utilizing cloud 
technologies and services. Since the application is hosted on AWS cloud services, we have access to a wide 
range of services such as Amazon Elastic Compute Cloud (EC2), Amazon RDS, Amazon CloudFront, AWS 
CloudWatch that assist us in getting the application ready for production. The stylistic framework for the 
front end of the online application is created using PHP, Javascript, HTML, and CSS. The goal when
designing the user interface was to make it as simple and intuitive as possible for clients who wish to 
utilize the site to purchase their tickets. Amazon RDS MySQL is the database used in the development of 
the application's backend. The issue of conventional data storage will also be resolved by the website. The 
platform's administration will be able to manage all bookings (both in-person and online) using the system 
offered by the website. All of the data is kept on the cloud and may also be kept locally.

<h1>Deployment</h1>
1. Code the project locally: The first step is to develop the project on your local system, using the 
appropriate languages and frameworks (HTML, CSS, JavaScript, PHP, etc.).
2. Push the project to GitHub: Once the project is ready, you can push it to a GitHub repository, 
(GitHub Link: https://github.com/Kirthik1104/ticket_reservation.git) where it will be stored and 
version-controlled.
3. Set up an EC2 instance: The next step is to create an EC2 instance on AWS. This will be a virtual 
server that you can use to run your application. You can choose the appropriate instance type, 
operating system, and other configuration options based on your requirements.
4. Install Git on EC2: Once the EC2 instance is up and running, you will need to install Git on it, so 
that you can clone the project from GitHub onto the instance. You can do this using the package 
manager on the EC2 instance (e.g., yum or apt-get).
5. Clone the project onto EC2: With Git installed, you can now clone the project from GitHub onto 
the EC2 instance. This will copy all the project files onto the instance, ready for deployment.
6. Install LAMP on EC2: To run the PHP code in the project, you will need to install a LAMP (Linux, 
Apache, MySQL, PHP) stack on the EC2 instance. This will provide the necessary web server, 
database, and PHP runtime components. You can install these using the appropriate package 
manager and configuration tools (e.g., yum, apt-get, or the AWS Marketplace).
7. Connect to PHPMyAdmin: With the LAMP stack installed, you can now connect to PHPMyAdmin, 
which is a web-based tool for managing MySQL databases. You can use PHPMyAdmin to create 
the necessary database tables and configure the database connection settings for your 
application.
8. Connect EC2 to RDS: Finally, you can connect the EC2 instance to an RDS (Relational Database 
Service) instance on AWS, which will provide a scalable, managed MySQL database for your 
application. You can do this by specifying the RDS instance endpoint and credentials in your PHP 
code or configuration files.
9. To implement CloudFront in the bus ticket system project, you can create a new distribution in 
the AWS Management Console, specifying the origin server (i.e., the EC2 instance hosting your 
application) and the appropriate caching and security settings. Once the distribution is created, 
you can update the URLs for your static assets in your application code to use the CloudFront 
domain name (e.g., d1234.cloudfront.net) instead of the EC2 instance IP address.
10. To implement Load Balancer in the bus ticket system project, you can create a new load balancer 
in the AWS Management Console, specifying the appropriate configuration options (e.g., the 
instance protocol and port, the health check settings, and the security groups). Once the load 
balancer is created, you can register your EC2 instances with the load balancer and update the 
DNS records for your application to point to the load balancer endpoint instead of the EC2 
instance IP address.
