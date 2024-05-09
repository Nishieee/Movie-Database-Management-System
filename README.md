# Movie Database Management System (MDBMS)

## Overview
The Movie Database Management System (MDBMS) is designed to manage and catalog a wide variety of movie-related data efficiently. It aims to improve the accessibility and organization of movie information, offering features like user reviews, ratings, and interactive tools for engagement.
 

## System Architecture

### Database Objects:
- **Tables**: 14 (including entities and associative entities with primary and foreign keys, ensuring normalization and data integrity)
- **Views**: 5 (created for optimized data retrieval and management of user access)
**Stored Procedures**: 4 (used for encapsulating data manipulation and business logic)
**User Defined Functions**: 3 (enhancing reusability and modularization of the system)
**DML Triggers**: 1 (automates processes like logging and audit trails)
**Column Data Encryption**: 1 (secures sensitive data such as user credentials)
**Non-clustered Indexes**: 3 (improve the speed of data retrieval operations without altering the physical order of the data)
**GUI for CRUD Operations**: Responsive and intuitive graphical user interface to create, read, update, and delete data, ensuring a seamless user experience.
**BI Data Visualization**: Advanced visualization tools implemented for analytical reporting and insights, enhancing decision-making capabilities.

## Purpose and Benefits
MDBMS was developed to address the challenges of managing an ever-growing library of movie-related data in the digital era. By providing a centralized platform, MDBMS makes movie data more accessible and manageable, enhancing the overall movie-watching experience.

### Key Features
**Cataloging and Retrieval**: Robust interface for cataloging and retrieving comprehensive details about movies, including titles, genres, release years, cast, crew, and user-generated content.
**Enhanced Movie-Watching Experience**: Offers users easy access to detailed movie information, critical reviews, and community ratings.
**Interactive User Engagement**: Allows users to rate movies, write reviews, create personalized watchlists, and engage with a community of like-minded movie lovers.
**Security**: Implements stringent security measures to protect user data and ensure data integrity.
Challenges and Solutions
**Data Quality and Currency**: Constant updates and new releases pose a challenge; the system uses automated scripts and manual oversight to maintain data accuracy.
User Interface: Designed to ensure ease of use, the GUI supports efficient navigation and makes complex data understandable at a glance.

## Business Rules and Data Schema
Detailed business rules outline the logic behind the relationships between various entities such as movies, awards, genres, users, and broadcasters.
The schema is designed to support complex queries, ensuring flexibility and scalability.

## Entity Relationship Diagram (ERD)
The **ERD** is meticulously crafted to represent all entities, their relationships, and constraints accurately, which is crucial for maintaining the database's integrity and efficiency.


## Future Enhancements
**Broadcaster Categorization**: Further refinement of broadcaster data to enhance filtering and search capabilities.
**Interactive Review Comments**: New features to allow users to comment on reviews, facilitating deeper engagement and community discussion.
**Complex Relationships Representation**: Improved data modeling to accurately depict the relationships between movies and production companies.

