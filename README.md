# I. Introduction to the project

### Title: Fitness Appointment Management Platform

### Description:
In today's fast-paced society, prioritizing personal fitness and health management has become increasingly crucial. However, despite the abundance of fitness resources available, many individuals struggle with effectively planning and tracking their fitness programs while accessing professional guidance. Our project aims to address these challenges by developing a comprehensive online platform that streamlines fitness appointment management for both customers and managers.

### Key Challenges:

- Limited time and energy in a fast-paced society hinder offline booking of coaches or courses, necessitating the need for efficient online platforms.
- Flexibility in online booking time is essential for customers with pre-planned fitness schedules.
- Existing solutions often lack the ability for users to directly book qualified trainers after purchasing specific fitness plans, leading to mismatches in user needs and trainer selection.
- The absence of an integrated system complicates the management of purchase and appointment data, increasing the burden on managers.

### Project Objectives:
Our project aims to:

- Develop an intuitive online platform that simplifies the process of booking trainers and managing schedules.
- Provide customers with the flexibility to book appointments according to their convenience.
- Enable users to directly select trainers with the appropriate qualifications based on their fitness plans.
- Implement an integrated system to automate the management of purchase and appointment data, reducing the workload for managers.
- By addressing these challenges and objectives, our platform endeavors to enhance the user experience and improve management efficiency in the realm of fitness appointment management.

### Test Account
manager: username:1234
password:1234

member(user_Id = 1): username:1234
password:12345678a


# II. Overall system design
## 1.Design structure
The system hierarchy is illustrated below:
![da1d7a7578e2d229dfac8e4bf223697](https://github.com/Tryingyuan/cpt202project/assets/129402785/11ac380d-9490-4307-b243-a01090fc8b11)

The system module mainly includes：
- User registration module
- Login module
- Member fitness plan purchase module
- Course reservation module
- User feedback module
- Personal information management module
- Order information management module
- Advertising and marketing module

Have not yet been developed：
User social interaction, fitness plan tracking, online customer service and other modules



## 2.Development environment:
- Java version: JDK18 (preferably)
- Database: Mysql
- Deployment Server: AliCloud
- IDE type: IDEA, Eclipse, etc. can run
- maven version: unlimited



## 3. Involved in the technical framework:
1. front-end technology: html, css, JavaScript
2. Front-end framework: Thymeleaf
3. Back-end framework: SpringBoot
4. and database interaction framework: JPA, Mybatis


# III. Main Page
### Home page
<img width="1440" alt="截屏2024-05-13 13 12 46" src="https://github.com/Tryingyuan/cpt202project/assets/129402785/b1dfc8cf-8567-4c81-8a66-2ed82be3bb28">

### User registration page
<img width="1440" alt="54658921b6587325ab54ae5053a4ba0" src="https://github.com/Tryingyuan/cpt202project/assets/129402785/884b0ed3-f26a-421f-8301-9a3fe83bb1fd">

### Login page
<img width="1440" alt="截屏2024-05-13 13 12 39" src="https://github.com/Tryingyuan/cpt202project/assets/129402785/f455e56c-37bb-4fae-99e3-259c79b0f717">
<img width="1440" alt="截屏2024-05-13 13 13 01" src="https://github.com/Tryingyuan/cpt202project/assets/129402785/01963f1c-8f4d-4eb8-9d0c-80963eeec79e">
<img width="1440" alt="截屏2024-05-13 13 12 46" src="https://github.com/Tryingyuan/cpt202project/assets/129402785/0fa7409c-8079-483b-9282-c3634c702423">

### Member fitness plan purchase page
<img width="1440" alt="截屏2024-05-13 13 13 24" src="https://github.com/Tryingyuan/cpt202project/assets/129402785/4dd91546-4da8-4809-aea2-503973e6fe17">

### User feedback page
![image](https://github.com/Tryingyuan/cpt202project/assets/129402785/3938f21a-c275-48b3-857c-c418b737b7a0)


### Manager management page
<img width="1440" alt="截屏2024-05-13 13 14 13" src="https://github.com/Tryingyuan/cpt202project/assets/129402785/f74ad5cd-1fec-4672-a224-718fc53d91df">

