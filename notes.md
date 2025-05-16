# Truffula Notes
As part of Wave 0, please fill out notes for each of the below files. They are in the order I recommend you go through them. A few bullet points for each file is enough. You don't need to have a perfect understanding of everything, but you should work to gain an idea of how the project is structured and what you'll need to implement. Note that there are programming techniques used here that we have not covered in class! You will need to do some light research around things like enums and and `java.io.File`.

PLEASE MAKE FREQUENT COMMITS AS YOU FILL OUT THIS FILE.

## App.java

- Have no idea

- Looks like We have to implement something

- -h shows hidden files -nc disables color for files

## ConsoleColor.java

- Obstructs color? 

- All setup I believe

- ansi text color codes always starts with \033[0;incrementfrom30-37 reset at 0]

- We define our objects and colors 
the code provided defines a method getCode() and provides us with all the calls in english vs \033 blah blah

## ColorPrinter.java / ColorPrinterTest.java

- Example code to print red text
ColorPrinter printer = new ColorPrinter(System.out);
printer.setCurrentColor(ConsoleColor.RED);
printer.println("This is red text");

## TruffulaOptions.java / TruffulaOptionsTest.java

- Controller? Helps with functionality for displaying hidden files and displaying 
-h for showing hidden files
-nc for displaying no color to the file

## TruffulaPrinter.java / TruffulaPrinterTest.java

## AlphabeticalFileSorter.java