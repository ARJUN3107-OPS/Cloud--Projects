# Prerequisites
#
- JDK 11 
- Maven 3 
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch
# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql


1️⃣ Key Pairs and Security Groups: Created secure SSH key pairs and security groups to manage access and enforce network-level security for the EC2 instances.

2️⃣ Launch EC2 Instances with User Data: Spun up EC2 instances using Bash scripts in the user data section to automate setup tasks like installing dependencies and configuring the environment.

3️⃣ IP-to-Name Mapping in Route 53: Configured Amazon Route 53 to map IP addresses to domain names for streamlined access.

4️⃣ Build and Upload to S3: Built the application from source code and uploaded the artifacts to an S3 bucket for reliable storage and easy access.

5️⃣ Deploy to Tomcat on EC2: Downloaded the application artifact from S3 and deployed it to an Apache Tomcat server hosted on an EC2 instance.

6️⃣ Set Up Load Balancing: Configured an Elastic Load Balancer (ELB) with both HTTP and HTTPS support for improved availability, scalability, and security.

7️⃣ Testing and Verification: Ensured end-to-end functionality by validating the deployment and load balancing configuration.

This project enhanced my skills in AWS infrastructure, automation, and scalable app deployment. Looking forward to tackling more cloud challenges! 🌐


