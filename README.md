# Project Overview

## Airbnb Clone Project 
The Airbnb Clone Project is a comprehensive, real-world application designed to simulate the development of a robust booking platform like Airbnb. It involves a deep dive into full-stack development, focusing on backend systems, database design, API development, and application security using Python (Django), MySQL, GraphQL, JWT, etc.

## Team Roles
* Backend Developer -  implement the core of an app—its algorithms and business logic.

* Frontend Developer - create the part of an application that users interact with, ensuring that an app offers an equally smooth experience to all—no matter the device, platform, or operational system

* DevOps - automate the software delivery process and helping strike a balance between introducing changes quickly and keeping an application stable

* Quality Assurance Engineer - verify whether an application meets the requirements—both functional and non-functional.

* UI/UX Designer - devises intuitive, easy-to-use, and eye-pleasing interface for the product, while the UX for thinks out an entire journey of a user’s interaction with a product.


## Technology Stack
* Django: a web framework for building RESTFUL

* openAPI: A standard formating and documentation of the RESTAPI for the project

* PostgreSQL: the relational database being used

* GraphQL: 

* Kafta: Event service

* Redis: Casching system


## Database Design
* User Authentication
	* Endpoints: `/users/`, `/users/{user_id}/`
	* Features: Register new users, authenticate, and manage user profiles.

*	Property Management
	* Endpoints: `/properties/`, `/properties/{property_id}/`
	* Features: Create, update, retrieve, and delete property listings.

*	Booking System
	* Endpoints: `/bookings/`, `/bookings/{booking_id}/`
	* Features: Make, update, and manage bookings, including check-in and check-out details.

*	Payment Processing
	* Endpoints: `/payments/`
	* Features: Handle payment transactions related to bookings.

*	Review System
	* Endpoints: `/reviews/`, `/reviews/{review_id}/`
	* Features: Post and manage reviews for properties.



## Feature Breakdown

* User Management: Provides interfaces for the user to be able to manage their data

* Property Management: Provides interfaces for project managers or owners to manage their property

* Booking System: Provides interfaces for users to book property and property owner/managers to manage bookings


## API Security
* Authentication: Protecting user data, securing payments

* Authorization: Protecting user data

* Rate Limiting: Limit the amount of API calls


## CI/CD Pipeline

CI/CD means continuous Integrating and merging all changes made to the code. It also involves testing the codes integrated together to make sure they works without errors when integrated. CD involves automatically deploying the tested ingrated code and deploying it to productive without delay or it manually done.


* GitHub Actionns

* Docker

* Jetkins


## UI/UX Design Planning

The aim isss to create a clean, modern and intuitive interface that allows users to effortlessly browse, view and book properties. The design must prioritize ease of use, responsive layouts for all devices, fast interaction, and visual clarity to ensure a pleasant user journey from search to checkout.

## Design Goals
* Create intuitive booking flow
* Maintain visual consistency
* Ensure fast loading times
* Prioritize mobile responsiveness

## Key Featuress
* Property search and filtering
* Detailed property viewing
* Secure checkout process
* User authentication

## Primary pages:

| Pages	| Description|
|-------|------------|
| Property Listing View | Grid display of available propertiess with filters |
| Listing Detailed View | Complete property details with imagess and booking form |
| Simple Checkout View  | Streamlined payment and booking confirmation |


## Importance of User-Friendly Design

A well-dessigned booking system reduces friction in the user journey, increases conversion rates, and improves customer satisfaction. Clearn navigation, intuitive interfaces, and ressponsive design are critical for successss.
