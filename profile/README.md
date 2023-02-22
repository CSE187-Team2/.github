# CSE187 Team 2 Project

## Installation Instructions

You will first need to navigate to our [front-end Github repository](https://github.com/CSE187-Team2/frontend) and run ``git clone`` in order to install our front-end source files. You will then need to navigate to our [back-end Github respository](https://github.com/CSE187-Team2/backend) and run ``git clone`` to install our back-end source files. Both the front-end and back-end respositories contain the ``npm run test`` and ``npm run lint`` commands to run our unit tests and the ESLint static analyzer, respectively.

The next step is to install the microservices that is utilized by our back-end source code. The links to the repositories holding our microservices are described in the below bullet points:
*  [Shopping Cart Microservice Repository](https://github.com/CSE187-Team2/Shopping-Cart-Microservice)
*  [Account Microservice Repository]()
*  [Category Microservice Repository]()
*  [Item (Listing) Microservice Repository]()
*  [Image Microservice Repository]()

You will need to run ``git clone`` for each microservice repository to download them to your computer. Each microservice supports ``npm run test`` and ``npm run lint`` to run their respective unit tests and the ESLint static analyzer, respectively. Instructions on how to run each microservice individually is described in the README for each microservice repository.

Once the front-end, back-end, and all microservice repositories have been installed, you first need to navigate to each microservice repository and run ``docker-compose up -d `` or ``sudo docker compose up -d``, in order to start up the PostgreSQL database Docker containers used by the microservices.

Next you will need to to run ``npm run dev`` at the main directory of each repository. You can then now navigate to ``localhost:3000`` on your web browser to utilize our web application. In addition, you can navigate to ``localhost:4000/graphql`` to see GraphQL Yoga interface that can be used to intreact with our back-end GraphQL API.

After stopping the front-end and back-end servers, you will need to run ``docker-compose down`` or ``sudo docker compose down`` in main directory of each microservice repository order to stop the database used by each microservice.

## How to Run the CI Tests in the Continuous Integration Repository

We are currently still working on developing the CI workflows for our CI repository. We will post the instructions once we have created the workflows for our CI repository. 


## Technology Stack Utilized

### Back-end:
- DB: Postgres
- Server: Express with GraphQL Yoga
- Schema Generator: TypeGraphQL

### Front-end:
- Meta Framework: Next.js 13
- Build: Turbopack
- UI Framework: MaterialUI
- Authentication: NextAuth
