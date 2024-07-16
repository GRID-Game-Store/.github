## GRID

### Introduction
Welcome to GRID! This GitHub organization is dedicated to developing an educational cutting-edge gaming website built on the Spring Boot and React stack.
Our goal is to create a platform that provides an exceptional gaming experience for gamers, similar to industry leaders like Steam.

### Technologies Used
- Maven - Build tool
- Spring Boot - Web framework
- JUnit - Testing framework
- React

## GRID Demo Video

Check out our demo video showcasing the main features of the GRID project:

### Main Page

https://github.com/user-attachments/assets/540fdc0d-b89e-4ab5-b09a-98554d3e0f59

### AI Chat Consultant

https://github.com/user-attachments/assets/48e87a2d-fe04-44a7-b9c8-6060a6840901

### Authentication, Authorization 

https://github.com/user-attachments/assets/759e81ef-abc9-462f-bc86-2146ac7ed2e6

### Payment Abilities

https://github.com/user-attachments/assets/8648e341-3ea2-4f1c-968f-13e65f6395f2


The demo includes:
- Overview of the main page
- AI-powered chat consultant using Vertext Gemini
- Registration and authorization process with Keycloak
- Payment integration with Stripe and PayPal
- Admin panel walkthrough

## Features

- **AI Chat Consultant**: Powered by Vertext Gemini, providing intelligent customer support.
- **Secure Authentication**: Implemented using Keycloak for robust user management.
- **Multiple Payment Options**: Integrated with Stripe and PayPal for flexible payment processing.
- **Admin Panel**: Comprehensive admin interface for easy management of the platform with a help of Astro.js and Spring Boot


### Getting Started
#### Backend
This application requires pre-installed [JDK 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html) or higher. [See more.](https://www.oracle.com/java/technologies/downloads/#jdk19-windows)

* Clone this repository
```
git clone https://github.com/GRID-Game-Store/backend
```
* Make sure you are using JDK 17 and Maven
* You can build the project and run the tests by running ```mvn clean package```
or 
```mvn install / mvn clean install```

##### Run Spring Boot app using Maven:
Now you can launch the server 8081.

* run Spring Boot app using Maven:
```mvn spring-boot:run```
* [optional] Run Spring Boot app with``` java -jar command
java -jar target/grid-0.0.1-SNAPSHOT.jar```

#### Frontend
First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

### License
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/GRID-Game-Store/.github/blob/main/LICENSE) file for details.
