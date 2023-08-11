          AirBnB clone
description of the project:

The AirBnB clone project starts now until… the end of the first year. The goal of the project is to deploy on your server a simple copy of the AirBnB website.

description of the command interpreter:
The console
create your data model
manage (create, update, destroy, etc) objects via a console / command interpreter

HBNB is a complete web application, integrating database storage, HTML/CSS templating, API, front-end and others.

This team project is part of the ALX School Software Engineering program. It represents the first step towards building a full web application: the AirBnB clone.

This first step consists of:

a command-line interface for data management
and base classes for the storage of this data.
Usage
The console works both in interactive mode and non-interactive mode, much like a Unix shell. It prints a prompt (hbnb) and waits for the user for input.

Command	Example
Run the console	./console.p
Quit the console	(hbnb) quit
Display the help for a command	(hbnb) help
Create an object (prints its id)	(hbnb) create
Show all objects, or all instances of a class	(hbnb) all or (hbnb) all
Update an attribute of an object	(hbnb) update "" or (hbnb) .update(, , ""
Interactive mode
./console.py (hbnb) help

Documented commands (type help ):
EOF help quit

(hbnb) (hbnb) (hbnb) quit $

Non-interactive mode (example) $ echo "help" | ./console.py (hbnb)
Documented commands (type help ):
EOF help quit (hbnb) $ $ cat test_help help $ $ cat test_help | ./console.py (hbnb)

Documented commands (type help ):
EOF help quit (hbnb) $

Testing
Unittests for the HolbertonBnB project are defined in the [tests] To run the entire test suite simultaneously, execute the following command:

 python3 unittest -m discover tests

Alternatively, you can specify a single test file to run at a time:

 python3 unittest -m tests/test_console.py
