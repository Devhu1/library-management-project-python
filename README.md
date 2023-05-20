# library-management-project-python
A library management system keeps track of the books present in the library. It is an important piece of software which is a must at schools and colleges. We will build a library management system using Tkinter to make it interactive.


# Tkinter

Python offers various utilities to design the GUI wiz Graphical User Interface, and one such utility is Tkinter which is most commonly used. It is indeed one of the fastest and easiest ways to build GUI applications. Moreover, Tkinter is cross-platform, hence the same code works on macOS, Windows, and Linux.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Tkinter.

```bash
pip install Tk

pip install pillow

pip install pymysql
```

## Usage

```python
import tkinter
m = tkinter.Tk()
'''
widgets are added here
'''
m.mainloop()

```
##Description

Description of Project Files
Below are the project files you will get once you download and extract the Library project:

main.py – which does function call to all other python files

AddBook.py – To add the book

ViewBooks.py – To View the list of books in the library

DeleteBook.py – To Delete a book from library

IssueBook.py – To Issue a book from library

ReturnBook.py – To Return a book to the library

## Create Tables

create database db;

create table books(bid varchar(20) primary key, title varchar(30), author varchar(30), status varchar(30));

create table books_issued(bid varchar(20) primary key, issuedto varchar(30));

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
