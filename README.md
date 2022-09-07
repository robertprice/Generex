# Generex
A Mendix wrapper to the Generex library for generating random Strings that match a given regular expression.

## Usage

### RandomStringFromPattern

* Pattern - A String with the regular expression the random string needs to match.

Returns a String that matches the passed pattern.

This action can throw an error if a bad Pattern value is passed to it, so remember to set error handling to catch and handle this appropriately.

## Dependencies
* automaton-1.11-8.jar
* generex-1.0.2.jar

## Contributing
The source code, examples, and unit tests can be found on [https://github.com/robertprice/Generex](https://github.com/robertprice/Generex).

When exporting the module from source make sure to include the .jar dependencies listed in the Dependencies section of this document.

## Author
Robert Price - (Deck Chair Digital Ltd)[https://deckchair.digital/]

## See Also
[Generex Java project](https://github.com/mifmif/Generex)

## License
Generex is licensed under the Apache License, Version 2.0.  
http://www.apache.org/licenses/LICENSE-2.0