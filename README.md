
# Odd Job Finder

An end-to-end solution for our daily odd job requirements. The website handles the entire transaction from the user requesting a
service to final payments.

The COVID pandemic has had a significant impact on India's employment rate. People with non-technical backgrounds, in particular, are having a difficult time finding work. Despite the fact that household jobs are in great demand, people are still not able to locate the ideal candidate. Our project, Odd Job Finder aims to bridge this gap between the employer and the job seeker. Everyone now has access to a smartphone, thanks to technological advancements. Using this online platform, the user(customer) will be able to search across different odd job categories and select one according to their needs. The customer can select an appropriate candidate for the job and send him/her request. The job seeker can choose to accept or reject the job based on the job description and salary details. In this way, Odd Job Finder provides an efficient platform for communication between the employer and the job seeker.
## Tech Stack

**Client:** React, Redux, HTML, CSS, JavaScript

**Server:** Nodejs, Express

**Database:** MongoDB



## Features

- Three user types - Admin, customer, Job seeker
- End-to-end working
- Full featured servises
- Reviews and ratings
- Service search feature
- Admin user management
- PayPal / credit card integration


## Env Variables

Create a .env file in then root and add the following

```bash
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
```

## Install Dependencies (frontend & backend)

```bash
npm install
cd frontend
npm install
```

## Run

```bash
# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

## Build & Deploy

```bash
# Create frontend prod build
cd frontend
npm run build
```
