# Shuttle-Booking-System-for-SNU


SHUTTLE BOOKING SYSTEM

PROJECT REPORT

Anoushka Mishra-2010110106
Maitreyi Singh- 2010110383
Megha K B - 2010110394

 
Table of Contents
1.	INTRODUCTION 
1.1.	Objective
1.2.	Scope
1.3.	Glossary (Acronyms, Abbreviations)
1.4.	Overview 
2.	OVERALL DESCRIPTION
2.1.	Product Perspective
2.2.	Product Functions
2.3.	User Characteristics
2.4.	Constraints
2.5.	Assumptions and Dependencies
3.	SYSTEM REQUIREMENT SPECIFICATION
3.1.	Function Requirements
3.1.1.	Performance Requirements
3.1.2.	Design Constraints
3.1.3.	Hardware Requirements
3.1.4.	Software Requirements
3.1.5.	Other Requirements
3.2.	Non-Function Requirements 
3.2.1.	Security
3.2.2.	Reliability
3.2.3.	Availability
3.2.4.	Maintainability 
4.	DATA STRUCTURES
4.1.	Shuttle Details
4.2.	Student Details
5.	DIAGRAMS
5.1.	Data Flow Diagram
5.1.1.	Level 0 DFD
5.1.2.	Level 1 DFD
5.1.3.	Level 2 DFD
1.	INTRODUCTION 
1.1.	Objective
The Shuttle Booking System is a software developed for automating the currently manual shuttle booking system. This software will provide a faster, more reliable system which will provide more transparency between the students and the transport committee. 
1.2.	Scope
“Shuttle Booking System” is an attempt to simulate the concepts of a ticket booking system online. The system enables the user to perform the following functions:
1.2.1.	Inquire about the availability of a shuttle for a given route by searching for an available route (pickup --- destination).
1.2.2.	Choose a shuttle and select their seat.
1.2.3.	Securely pay through an online portal.
1.2.4.	User can cancel bookings before a given time and will receive refund for the ticket.
1.2.5.	User can give feedback through the feedback form.
1.3.	Glossary (Acronyms, Abbreviations)
1.3.1.	SBS- Shuttle Booking System
1.4.	Overview 
1.4.1.	This SRS contains an analysis of the requirements necessary to help an easy design.
1.4.2.	The overall description provides interface requirements for the SBS, product perspective, hardware interfaces, software interfaces, communication interfaces, memory constraints, product functions, user characteristics and other constraints.
1.4.3.	Succeeding pages illustrate the characteristics of naive users accessing the system along with functional constraints enforced that affect the SBS.
2.	OVERALL DESCRIPTION
2.1.	Product Perspective
The current system (before online SBS) suffers from the following drawbacks:
2.1.1.	The existing system is highly manual involving a lot of paperwork and calculation. This may be erroneous. 
2.1.2.	The data stored on paper (however temporarily) may be lost, stolen or destroyed.
2.1.3.	The existing system consumes a lot of time, causing inconvenience to the people waiting in line for shuttle tickets. 
2.1.4.	People who are not present at the location of booking cannot access shuttle tickets.
2.1.5.	The number of people on campus have drastically increased and therefore maintaining and retrieving detailed record of each passenger is difficult.
2.1.6.	There is no option of cancellation of shuttle tickets. 
Therefore, the SBS is proposed with the following:
2.1.7.	The computerization of the current booking system will reduce paperwork and load of the administrative staff.
2.1.8.	Machine performs all calculations. Chances of error are reduced to nil.
2.1.9.	The passenger, reservation, cancellation list can easily be retrieved and any required addition, deletion or updating can be performed.
2.1.10.	Feedback system can be used to take input and improve the system.
2.2.	Product Functions
2.2.1.	Search: This function allows the user to search for available routes.
2.2.2.	Selection: This function allows a particular shuttle and a seat to be selected from the displayed list.
2.2.3.	Payment: This function allows the user to pay through an online portal.
2.2.4.	Cancellation and refund: This function allows the user to cancel their ticket and receive refund in a specified duration of time (duration to be updated).  The cancelled seat then becomes publicly available.
2.2.5.	Feedback system: This function allows the users to give feedbacks/ suggestions for improvement for the SBS.
2.3.	User Characteristics
2.3.1.	Educational Level: User should be comfortable with English language.
2.3.2.	Technical Expertise: User should be comfortable using general purpose applications on the computer system.
2.4.	Constraints
2.4.1.	The system will run on windows98 or higher operating systems.
2.5.	Assumptions and Dependencies
2.5.1.	Booking Agents will be having a valid Username (University NetID) and Password to access the software. 
2.5.2.	Software is dependent on access to the internet.
3.	SYSTEM REQUIREMENT SPECIFICATION
3.1.	Function Requirements
3.1.1.	Performance Requirements
3.1.1.1.	User Satisfaction: The system is such that it stands up to the user’s expectations. 
3.1.1.2.	Response Time: -The response of all the operation is good. 
3.1.1.3.	Portable: - The software should not be architecture specific. 
3.1.1.4.	User friendly: - The system is easy to learn and understand. A native user can also use the system effectively, without any difficulties.
3.1.2.	Design Constraints
3.1.2.1.	The interface should be intuitive, and the system should be simple to use with clear instructions.
3.1.2.2.	The system should work with a variety of hardware and operating systems, including those used by desktop computers, laptops, tablets, and cell phones.
3.1.2.3.	The system must be secure, with the right safeguards in place to safeguard user data and guard against unwanted access or tampering.
3.1.2.4.	The system must abide by all applicable laws and rules, including those governing data protection and payment processing.
3.1.2.5.	The system should be built with proper backup and recovery mechanisms to reduce errors and data loss.
3.1.3.	Hardware Requirements
3.1.3.1.	Standard servers and networking hardware with enough capacity to handle anticipated traffic should be able to run the system.
3.1.3.2.	The system must have enough storage to hold user information and transaction logs.
3.1.3.3.	To avoid data loss and guarantee system availability, the system needs to have suitable backup and disaster recovery solutions in place.
3.1.4.	Software Requirements
3.1.4.1.	To enable the necessary functionality, the system should be constructed utilising dependable and scalable software technologies along with the proper frameworks and libraries.
3.1.4.2.	The system must be able to interface with other systems, including messaging platforms and payment processors.
3.1.4.3.	To make sure the system is free of flaws and problems, it should be extensively tested.
3.1.5.	Other Requirements
3.1.5.1.	The feedback form should be created to gather pertinent data, such as ideas for enhancing the booking process, user experience, and other important system components.
3.1.5.2.	To ensure that users are able to utilise the system efficiently, it should be properly documented and trained.
3.1.5.3.	Users should receive the proper communications from the system, such as emails of confirmation, reminders, and notifications of changes or cancellations.
3.1.5.4.	The system should have the necessary safeguards in place, such as identification and verification procedures, to avoid fraud or misuse.
3.2.	Non-Function Requirements 
3.2.1.	Security
3.2.1.1.	The system secures all transactions that include any confidential customer information. The system should not leave any cookies on the customer’s computer containing the user’s password. The system’s back-end servers will only be accessible to authorized personnel. 
3.2.2.	Reliability
3.2.2.1.	The reliability of the overall project depends on the reliability of separate components. The reliability of the system is the backup of the database: which is updated to reflect recent changes.
3.2.3.	Availability
3.2.3.1.	System should be available at all times, only restricted by the down time of the server on which the system runs. In case of a hardware failure or a database corruption, a replacement page will be shown. 
3.2.4.	Maintainability 
3.2.4.1.	In case of a failure, a re-initialization of the project will be done. The software design is being done with modularity in mind so that maintainability can be done efficiently.
4.	DATA STRUCTURES
4.1.	Shuttle Details 
FIELD NAME	TYPE	CONTRAINS
REGISTRATION_PLATE	NUMBER	NOT NULL
SEAT_NUMBER	NUMBER	NOT NULL
SELECT_STATUS	TINYINT	NOT NULL, DEFAULT=0
PICKUP_LOC	TEXT	 
DROP_LOC	TEXT	 
DATE_TIMING	DATETIME	 

     4.2 Student Details
FIELD NAME	TYPE	CONTRAINS
REGISTER_NO	NUMBER	NOT NULL
FNAME	TEXT	 
LNAME	TEXT	 
GENDER	TEXT	 
DEPT	TEXT	 
EMAIL	TEXT	 
PASSWORDS	TEXT	 
SHUTTLE_SELECTED	NUMBER	 
SEAT_SELECTED	NUMBER	 
PAYMENT_STATUS	TINYINT	NOT NULL, DEFAULT=0

5.	DIAGRAM
5.1.	Data Flow Diagram
5.1.1.	Level 0 Data Flow Diagram




 
5.1.2.	Level 1 Data Flow Diagram









5.1.3.	Level 2 Data Flow Diagram

