# Hotel Scraping Project
A web scraping project that extracts hotel information from booking websites, stores it in a SQLite database, and provides a REST API for data access.

## Overview
This project scrapes hotel data (ratings, reviews, services) from booking platforms and makes it available through a structured API. It follows SOLID principles for clean, maintainable code.

### Features
* Web Scraping: Extracts hotel data from booking websites

* Data Storage: SQLite database with structured tables

* REST API: GET endpoints to query hotel information

* Data Serialization: JSON support for API responses

### Architecture
The project consists of three main interfaces:

* HotelSource: Deserializes scraped data into POJO classes

* HotelDatabase: Inserts POJO objects into database tables

* JsonSource: Serializes objects to JSON for API responses

### Workflow
1. Scraping class extracts data from websites

2. Data is converted to POJO objects

3. SqliteHotelDatabase stores objects in database tables

4. HotelAPI provides GET endpoints for data retrieval

### Technologies
* Java

* IntelliJ IDEA / IntelliJ Ultimate

* SQLite

* Web scraping libraries
