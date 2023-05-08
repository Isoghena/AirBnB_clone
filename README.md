<h1>AirBnb_clone<h1>

<h1>Description<h1>

<p>HBNB is a complete web application, integrating database storage, HTML/CSS templating, API, front-end and others.<p>

<p>This team project is part of the ALX School Software Engineering program. 
It represents the first step towards building a full web application: the AirBnB clone.<p>

<p>This first step consists of:<p>

<li>a command-line interface for data management
<li>and base classes for the storage of this data.

<h2>Usage<h2>

<p>The console works both in interactive mode and non-interactive mode, much like a Unix shell. It prints a prompt (hbnb) and waits for the user for input.<p>

| Command |                         Example|
|---------| -------------------------------|
| Run the console| ./console.p|
| Quit the console| (hbnb) quit |
| Display the help for a command | (hbnb) help <command>
| Create an object (prints its id) | (hbnb) create <class>
| Show all objects, or all instances of a class | (hbnb) all or (hbnb) all <class>|
| Update an attribute of an object | (hbnb) update <class> <id> "<attribute value>" or (hbnb) <class>.update(<id>, <attribute name>, "<attribute value>"

<h2>Interactive mode<h2>

$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$

<h2>Non-interactive mode (example)
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$

<h2>Testing<h2>

<p>Unittests for the HolbertonBnB project are defined in the [tests] To run the entire test suite simultaneously, execute the following command:<p>

<p>$ python3 unittest -m discover tests<p>

Alternatively, you can specify a single test file to run at a time:

$ python3 unittest -m tests/test_console.py
