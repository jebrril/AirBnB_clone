# The AirBnB Clone Project
![AirBnB Logo](https://www.pngitem.com/pimgs/m/132-1322125_transparent-background-airbnb-logo-hd-png-download.png)

## Project Description
This is the first part of the AirBnB clone project where we worked on the backend of the project while interfacing it with a console application using the cmd module in Python.

Generated data (Python objects) are stored in a JSON file and can be accessed using the JSON module in Python.

## Description of the Command Interpreter:
The application's interface resembles the Bash shell but supports a limited number of predefined commands designed specifically for the AirBnB website's usage.

The command line interpreter serves as the frontend of the web app, enabling users to interact with the backend developed using Python's OOP programming.

Supported commands include:
- `show`
- `create`
- `update`
- `destroy`
- `count`

This implementation of the command line interpreter, combined with the backend and file storage system, supports various actions:
- Creating new objects (e.g., a new User or a new Place)
- Retrieving objects from files, databases, etc.
- Performing operations on objects (counting, computing stats, etc.)
- Updating object attributes
- Destroying objects

## Additional Feature: Search Command
We've introduced an additional command, `search`, to the command interpreter. This command lets users search for specific objects based on specified criteria, enhancing the interaction with the data.

To use the `search` command, enter the following in the command interpreter:
search <class_name> <attribute_name> <attribute_value>

bash
Copy code
This command will return a list of objects that match the search criteria.

## Authors
Anas KHEIREDDINE & Abderrazaq FERMAQ