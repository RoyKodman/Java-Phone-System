# Java Phone System

**Java-Phone-System** is a comprehensive Java-based phone application suite developed as a group project for the "Software Engineering" course in Bar-Ilan University.
This project simulates a full-featured phone system that includes various applications such as Phone Book, SMS, Calendar, Media, Phone Calls, Wallet, and Casino.
The objective was to implement object-oriented principles, design patterns, and an interactive graphical user interface (GUI) using Java Swing.

The project received a grade of **98/100**, reflecting its technical complexity, functionality, and adherence to software engineering best practices.

## Features

- **PhoneBook**: Manage your contacts in a Phone-Book (add, delete, search, sort, save and load).
- **SMS**: Send messages and view conversations with your contacts.
- **Calendar**: Manage events, schedule meetings.
- **Media Player**: Add and play songs and videos (simulation - only prints).
- **Phone Calls**: Simulate making calls to your contacts, and view call history.
- **Casino**: Enjoy games like BlackJack and Slots.
- **Wallet**: Manage virtual currency for trasnfers, deposits and use in the Casino.
- **User Interface**: Java Swing-based GUI for an intuitive user experience.

## Setup and Usage

### Prerequisites

- Java Development Kit (JDK).
- An IDE like Eclipse or VS Code.

### Running the Project

1. Clone the repository or download the project files.
2. Open the project in your preferred IDE.
3. Build the project and run the `TestMobilePhone.java` file to start the application.

## Application Descriptions

### PhoneBook
Manage contacts (name, phone-number) with these features:
*  Add Contact.
*  Delete Contact.
*  Print All Contacts.
*  Search Contact.
*  Sort Contacts (by name/phone-number).
*  Remove Duplicates (same name).
*  Reverse Order (by name).
*  Save to file / Load from file (.txt file).

### SMS
Send text messages to your contact with these options:
* Send SMS to your contact.
* View (print) conversation with contact.
* View (print) all conversations.
* Search messages.
* Delete Conversation.

### Calendar
The calendar provides an overview of all scheduled events. You can:
* Add an Event or a meetig with your contacts.
* Delete an event / meeting.
* View all events on a specific date.
* view all future meetings with a contact.
* List all future events.

The app manages time and makes sure meetings don't conflict.  

### Media Player
Media is defined as Song or Video, with name and time. Simulates youtube.
The app can accept new media (Add Media) and play it: Play Media by Name / Play all Media.

### Phone Calls
Simulate making phone calls. Users can: 
* Call a contact from the PhoneBook.
* View Call History with a contact.
* View all call histories.

When calling a contact, the app randomly generates respones (Answered/No), and if the phone call have been answered then the app generates a random number of minutes and seconds of the call length.

### Wallet
Manage virtual currency used for deposits, transfers and betting in the Casino. The Wallet keeps track of the user’s balance and features:
* View current balance.
* Deposit money.
* Transfer money (To a contact or to the casino balance).
* View transfers history.
* Add new credit card.
* Delete credit card.
* View credit cards.

### Casino
Works in full coordination with the wallet, and features:
* Playing Black-Jack against the dealer.
* Playing Slot-Machine.
* Withdraw money to your wallet.

You can place various amount of bets in both games. 

The games simulate real-life casino odds with randomly generated outcomes.

## Technical Details

- **Programming Language**: Java
- **GUI Framework**: Java Swing
- **Data Management**: In-memory data structures (can be extended to use databases).

## Team Contributions

This project was developed collaboratively by a team of software engineering students:
- **[@RoyKodman](https://github.com/RoyKodman)** (Me)
- Daniel Negbi
- Shimon Ben-Ami
- Amitay Ziv

## License

This project is open-source and available under the [MIT License](LICENSE).

