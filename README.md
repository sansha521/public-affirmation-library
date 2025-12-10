# public-affirmation-library
This is the repository to showcase a sample public library database application called Public Affirmation Library.  This project was done for completion of CS-GY 6083, Principles of Database Systems
project.


# Project Specification
🔧 Dev Stack
- Backend Server: Django, Python
- Frontend: React, TypeScript, JavaScript, HTML/CSS
- Database: PostgreSQL
- Authentication: JWT-based auth flow

# Running the webapp in development mode
## See the Readme in backend directory

This is a role-based library booking system where you can book books and library rooms. 

The database consists of a total of 22 entities, including rooms, reservations, books, authors, events, customers, and payments. 

The logical model looks like this:

<img width="1279" height="718" alt="image" src="https://github.com/user-attachments/assets/845986dd-2c67-4567-8bff-1d024bf9d29b" />

The relational model looks like this:

<img width="1278" height="678" alt="image" src="https://github.com/user-attachments/assets/52b25665-f218-482f-a0c8-6c1e7dd8ee60" />

The web application is separated into library staff access and customer access. 
All staff can use the Django admin to use the service. 
All customers interact with the app through the custom frontend created using NextJS and Django Rest Framework. 

An overview of the dev stack of this application is:
Software  
● Database server: pgAdmin 
● Development platform: Docker 
● Object Storage: MinIO 
Programming Languages  
● Frontend: TypeScript, NextJS 
● Backend: Python, Django, Django Rest Framework 
Database 
● RDBMS development: PostgreSQL 
● Cache/In-memory Database: Redis 
Tools 
● GitHub 
● VSCode 
● Docker Compose

The main page looks like this:

<img width="1133" height="566" alt="image" src="https://github.com/user-attachments/assets/6b5af5bf-d8b9-4368-b5b1-703b7c68f6ea" />

The login page:

<img width="1196" height="602" alt="image" src="https://github.com/user-attachments/assets/3f328e4b-5539-4d50-8a94-29d64a6accc7" />

Book booking page:

<img width="1290" height="438" alt="image" src="https://github.com/user-attachments/assets/50e90acd-47a9-4e5b-baaa-f6901f610d25" />

Books checkout page:

<img width="1292" height="542" alt="image" src="https://github.com/user-attachments/assets/31c5c080-aa40-4b98-98ee-503d3adcfb10" />

Room bookings page:

<img width="1276" height="480" alt="image" src="https://github.com/user-attachments/assets/fe8e0122-7bdf-4c30-b14c-07188730e966" />

Room reservation form:

<img width="1282" height="601" alt="image" src="https://github.com/user-attachments/assets/a25e8779-d061-4e5d-9b71-7168b28e8af7" />

Staff/Admin views give a rental list of books:

<img width="1281" height="554" alt="image" src="https://github.com/user-attachments/assets/2d29a7a2-80ec-46d5-8a96-073508085b46" />

Staff can also view the list of all books along with their status:

<img width="1286" height="720" alt="image" src="https://github.com/user-attachments/assets/13aa9e7b-48b3-4c23-8717-982836c88d39" />

New books can be added:

<img width="1294" height="634" alt="image" src="https://github.com/user-attachments/assets/f38733a7-cea5-4594-a973-dd58fa23c580" />

Book data can be updated:

<img width="894" height="715" alt="image" src="https://github.com/user-attachments/assets/d6bd2969-fd5c-4579-b7d6-00bf7fbe86c0" />


The application includes:
- Security features such as JWT authentication, protected API endpoints, role-based access control, and SQL injection prevention.
- Redis caching to help users open the app from other devices with saved additions to their booking cart, and persistent data across devices.
- Stale-While-Revalidate(SWR) strategy for Frontend Fetching and Caching for a reactive and smooth UI with up-to-date data.
- Applied CSRF Protection by generating and embedding a CSRF token in every form submission and verifying during the form request. 
