# CSE187 Team 2 Project

## Installation Instructions

You will first need to navigate to our [front-end Github repository](https://github.com/CSE187-Team2/frontend) and run ``git clone`` in order to install our front-end soure files. You will then need to navigate to our [back-end Github respository](https://github.com/CSE187-Team2/backend) and run ``git clone`` to install our back-end source files. Both the front-end and back-end respositories contain the ``npm run test`` and ``npm run lint`` commands to run our unit tests and the ESLint static analyzer, respectively.

The next step is to install the microservices that is utilized by our back-end source code. The links to the repositories holding your microservices are described in the below bullet points:
*  [Shopping Cart Microservice Repository](https://github.com/CSE187-Team2/Shopping-Cart-Microservice)
*  [Account Microservice Repository]()
*  [Category Microservice Repository]()
*  [Item (Listing) Microservice Repository]()
*  [Image Microservice Repository]()

You will need to run ``git clone`` for each microservice repository to download them to your computer. Each microservice supports ``npm run test`` and ``npm run lint`` to run their respective unit tests and the ESLint static analyzer, respectively. 


## Technology Stack

### Backend:
- DB: Postgres
- Server: Express w/ GraphQL Yoga
- Schema Generator: TypeGraphQL

### Frontend:
- Meta Framework: Next.js 13
- Build: Turbopack
- UI Framework: MaterialUI
- Authentication: NextAuth
