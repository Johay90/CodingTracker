﻿# TODO List

- [x] Create a configuration file to store the database path and connection strings.
- [x] Create a `CodingSession` class in a separate file with properties: Id, StartTime, EndTime, Duration.
- [x] Create a SQLite database if not present at application start.
- [x] Create a table in the database for coding session logging.
- [x] Create a `UserInput` class to handle user input.
- [x] Create a `Validation` class to validate user input.
- [x] Use the "Spectre.Console" library to display data on the console.
- [x] Implement the main menu with options to the user. Also implemented the following sub options and crud operations
	- [x] Implement NewSession
		- [x] Implement a stopwatch feature to track coding time
	- [x] Implement AddManualSession
		- [x] Ensure end date/time is not before the start date/time	
	- [x] Implement ViewSessions
		- [x] Allow users to filter coding records by period (weeks, days, years) and order them (ascending/descending).
	- [ ] Implement Goals
		- [ ] Add a feature to set coding goals and track progress
	- [ ] Implement Reports
		- [ ] Create reports for total and average coding sessions per period.	
	- [x] Implement Exit the application
- [x] Implement data access using Dapper ORM.
- [ ] Include a ReadMe file explaining the app's functionality and how to use it.