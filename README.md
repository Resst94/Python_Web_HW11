# Task.

The goal of this task is to create a REST API for storing and managing contacts. The API should be built using the FastAPI infrastructure and use SQLAlchemy to manage the database.

<b>Contacts should be stored in the database and contain the following information:</b>
- First name.
- Last name.
- Email address.
- Phone number.
- Date of birth.
- Additional data (optional).

<b>The API should be able to perform the following actions:</b>
- Create a new contact.
- Get a list of all contacts.
- Get one contact by ID.
- Update an existing contact.
- Delete a contact.

## In addition to the basic functionality, the CRUD API should also have the following features:

- Contacts should be searchable by first name, last name, or email address (Query).
- The API should be able to retrieve a list of contacts with birthdays for the next 7 days.

## General requirements.

- Using the FastAPI framework to create the API.
- Use SQLAlchemy ORM to work with the database.
- PostgreSQL should be used as a database.
- Support for CRUD operations for contacts.
- Support for storing the date of birth of a contact.
- Providing documents for the API.
- Using the Pydantic data validation module.
