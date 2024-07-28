# SimpleDBMS - A Command Line Interface (CLI) Database Management System

## Overview

SimpleDBMS is a lightweight, command-line interface (CLI) database management system designed to facilitate easy storage and retrieval of data directly from the hard disk.

## Key Features

### Main Menu Options

- **Create Database**: Initializes a new database directory.
- **List Databases**: Displays all available databases.
- **Connect To Database**: Allows access to an existing database.
- **Drop Database**: Deletes an existing database.

### Connected Database Menu

After connecting to a specific database, users can perform various operations:

- **Create Table**: Sets up a new table within the connected database.
- **List Tables**: Shows all tables present in the current database.
- **Drop Table**: Removes an existing table from the database.
- **Insert Into Table**: Adds new records to a specified table.
- **Select From Table**: Retrieves data from a selected table.
- **Delete From Table**: Removes specific records from a table.
- **Update Table**: Modifies existing records in a table.

## Technical Details

- **Database Storage**: Each database is stored as a directory relative to the script file, ensuring data persistence across sessions.
- **Data Validation**: The application prompts for column data types during table creation and enforces these constraints during inserts and updates.
- **Primary Keys**: Users can define primary keys for tables, which are checked during insert operations to ensure uniqueness.

## Getting Started

To get started with SimpleDBMS, follow these steps:

1. Clone the repository or download the latest release.
2. Navigate to the project directory in your terminal.
3. Run `. ./mysql` to start the application.
4. Follow the on-screen instructions to manage your databases and tables.

## Contributing

Contributions to SimpleDBMS are welcome! Whether you're fixing bugs, adding new features, or improving documentation, your efforts will help make this tool better for everyone.
