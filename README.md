# Phone Book Management System

This is a simple phone book management system implemented using classes `PhoneBookEntry`, `PhoneBook`, and `User`. The system allows you to manage phone book entries, including adding, updating, removing, and printing entries.

## Class Descriptions

### PhoneBookEntry

The `PhoneBookEntry` class represents a phone book entry and stores the full name (i.e., both surname and name), phone number, email, and address. The class provides a human-friendly representation of the entry (toString()).

### PhoneBook

The `PhoneBook` class represents a phone book and stores phone book entries in a map based on their details, where details are mapped as: "full name" → "entry". Phone book entries are stored in a map of type: `Map<String, PhoneBookEntry>`. Duplicates of full names are not allowed. The class allows phone book entries to be inserted (an entry for a new full name), updated (updating an entry for an existing full name), or deleted (deleting an entry for an existing full name). It can print the details of an existing entry (if present in the phone book) by searching the phone book based on a given full name (thus showing the corresponding number) and print all entries within the phone book.

### User

The `User` class is responsible for creating a `PhoneBook` instance and subsequently inserting, updating, removing, and printing phone book entries.

## Usage

1. Clone this repository
2. Compile and run the main class (`User`)
3. Follow the prompts to insert, update, remove, or print phone book entries
4. The phone book entries will be displayed as requested

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch with your feature or bug fix
3. Commit your changes and push them to your fork
4. Create a pull request to this repository

## License

This project is released under the MIT License. Please see the `LICENSE` file for more details.
