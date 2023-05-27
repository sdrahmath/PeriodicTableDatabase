# Periodic Table database 

This project implements a Periodic Table database using PostgresSQL and Bash, allowing users to search for information about elements.

## Output Examples

When running the `element.sh` script with different arguments, the following output examples can be observed:

### Example 1: No Argument Provided

***Example 1***
$ ./element.sh
Please provide an element as an argument.

***Example 2:*** Valid Element Argument

$ ./element.sh 1

The element with atomic number 1 is Hydrogen (H). It's a nonmetal, with a mass of 1.008 amu. Hydrogen has a melting point of -259.1 celsius and a boiling point of -252.9 celsius.

$ ./element.sh Hydrogen

The element with atomic number 1 is Hydrogen (H). It's a nonmetal, with a mass of 1.008 amu. Hydrogen has a melting point of -259.1 celsius and a boiling point of -252.9 celsius.

$ ./element.sh H

The element with atomic number 1 is Hydrogen (H). It's a nonmetal, with a mass of 1.008 amu. Hydrogen has a melting point of -259.1 celsius and a boiling point of -252.9 celsius.

***Example 3:*** Invalid Element Argument

$ ./element.sh 1000

I could not find that element in the database.
