
<h1>
  <br /><br /><strong>Bookstore Management System</strong>
</h1>


---

<!-- markdownlint-disable -->
## Project Status[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#project-status)
<table class="no-border">
 
  <tr>
    <td><img src="https://img.shields.io/badge/OS-linux%20%7C%20windows-blue??style=flat&logo=Linux&logoColor=b0c0c0&labelColor=363D44" alt="Operating systems"/></td>
    <td colspan="2"><img src="https://img.shields.io/badge/CPU-x86%20%7C%20x86__64%20%7C%20arm%20%7C%20aarch64-blue?style=flat&logo=amd&logoColor=b0c0c0&labelColor=363D44" alt="CPU Architect"/></td>
  </tr>
</table>

---

## Introduction[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#introduction)

**Bookstore** 
This project is part of a Django-based book management system(Only backend). It provides the following features:
- Add books and authors
- View inventory and filter books
- Update and delete books
- Bulk delete books


## Installation and Run

1. Clone the project to your local machine:

```bash
git clone https://github.com/your_username/your_project.git
cd your_project
```

2. Create a virtual environment and install dependencies:
```bash
python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate  # For Windows

pip install -r requirements.txt
```
dependencies:

django
python>3.11
croshead

3. Perform database migration:
```
python manage.py migrate
```
4. Run the development server:
```
python manage.py runserver
```
5. Visit http://localhost:8000/ to view the project.

> 💡 xxx [xxx](). 

---

## Table of contents[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#table-of-contents)
- [Project Status](#project-status)
- [Introduction](#introduction)
- [Installation and Run](#installation-and-run)
- [Table of contents](#table-of-contents)
- [API Endpoints](#api-endpoints)
- [Models](#models)
- [Thank you all!](#thank-you-all)

---

## API Endpoints[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#motivation)

1. Add a Book

Endpoint: /add_book
Method: POST


2. Bulk Add Books

Endpoint: /add_books
Method: POST

3. View Inventory

Endpoint: /inventory
Method: GET
Returns information about all books.

4. Filter Books

Endpoint: /filter
Method: GET


5. Update a Book

Endpoint: /update_book/<book_id>
Method: PUT


6. Delete a Book

Endpoint: /delete_book/<book_id>
Method: DELETE

7. Bulk Delete Books

Endpoint: /aggregate_delete
Method: DELETE


* _Increase data privacy_, which is an important factor for sensitive data.
* _Decrease data streaming_, which is a fundamental condition to optimize network communication.
* _Autonomous, intelligent and self-aware devices_ with services directly in the environment of data origin.

<div align="right">[ <a href="#table-of-contents">↑ Back to top ↑</a> ]</div>

---

## Models[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#interface-centricity)

1. Author Model

name: CharField with a maximum length of 100 characters to store the author's name.
method: It returns the string representation of the Author object, which is the author's name.


2. Book Model

title: CharField with a maximum length of 100 characters to store the book's title.
authors: ManyToManyField linking to the Author model, allowing multiple authors for a single book.
price: DecimalField to store the book's price with a maximum of 5 digits, 2 of which are after the decimal point.
method: It returns the string representation of the Book object, including the book's ID and title.

<div align="right">[ <a href="#table-of-contents">↑ Back to top ↑</a> ]</div>

---



## Thank you all!![![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#thank-you)

Special thanks to all contributors and supporters that starred this repository.

Do you like this project? Please join us or [give](https://github.com/aregtech/areg-sdk/stargazers) a ⭐. This will help to attract more contributors.<br/>
Do you have an idea or found a bug? Please open an [issue](https://github.com/aregtech/areg-sdk/issues) or start a [discussion](https://github.com/aregtech/areg-sdk/discussions).

<div align="right">[ <a href="#table-of-contents">↑ Back to top ↑</a> ]</div>

---

**Contact us** at<br />

y.cheng22@lancaster.ac.uk

---

**Share** the project link with your network on social media.

<!-- markdownlint-enable -->
