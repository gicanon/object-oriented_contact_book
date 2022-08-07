# object-oriented_contact_book

Python program Lab to demonstrate polymorphism while interacting with a contact list.

## Description

This Python program is used to demonstrate polymorphism while interacting with a contact list. There will be a main class Contacts that controls the “view” the user sees and responds to user input. The contact information (personal and work) will be an instance of the Information class.

This lab is built around the Contacts class, which has four attributes:

- view - This attribute controls what the user sees. When the value for view changes, the information changes. There are four different views.
  - List view - Shows the list of all of the contacts.
  - Information view - Shows the work and personal information for a particular contact.
  - Add view - Add information for a new contact.
  - Quit view - Leave a message for the user and then end the script.
- contact_list - This is a list of objects that contain the information for each contact.
- choice - This attribute represents input from the user and is used to change the view.
- index - This attribute keeps track of the particular contact whose information is to be displayed.

Information class

The Information class is used to store the information about a contact. These objects are elements in the self.contact_list. The constructor is going to ask the user to input the first name, last name, personal phone number, personal email, work phone number, work email, and work title

## Getting Started

### Dependencies

This python project does not have any external libraries. However, starting this program will only require a Python 3 version.

### Installing

The latest version of python can be installed on the website: https://www.python.org/downloads/.

### Executing program

The program can be executed and tested at every Python IDE.

## Authors

Gianluca Cannone - https://github.com/gicanon

## License

Copyright (c) [2022] [Gianluca Cannone]

Permission is hereby granted, free of charge, to any person obtaining a copy of the project without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the project, and to permit persons to whom the project is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of this project.

THE PROJECT IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE PROJECT OR THE USE OR OTHER DEALINGS IN THE PROJECT.
