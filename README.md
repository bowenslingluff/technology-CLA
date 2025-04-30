This repo was copied from a class project for CS 3240 Spring 2025 (UVA)

This is a cataloging and lending application for pieces of technology (laptops, phones, speakers, chargers, etc.). 

## Features include:

1. Users can log in through Google - implemented with Google account API and Django all-auth
2. Anonymous users: users without accounts that can look around with limited access
3. Patrons: users that have accounts in the CLA and will have a login (through Google), a profile, and can request to borrow various items
4. Librarians: users that have accounts in the CLA and will have a login (through Google), a profile, can borrow various items (same as Patrons), but also have the ability to add new items and collections to the CLA
5. Django administrators: users who have access to the Django Admin page through the Django login system
6. Cloud storage through Amazon S3 to handle file uploads. Application data, such as users, items, collections, etc. is stored in a PostgreSQL database using Django’s model infrastructure.
7. Projects must be built using Python 3, PostgreSQL, Django 5, GitHub Actions CI, GitHub, Heroku, Amazon S3.
