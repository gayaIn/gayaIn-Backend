![](https://img.shields.io/badge/Code%20Style-Standard-yellow.svg)
![](https://img.shields.io/badge/Dependencies-Express-green.svg)
![](https://img.shields.io/badge/License-Beerware-yellowgreen.svg)

# GayaIn Backend

---

## Table of Contents

- [Introduction](#introduction)
- [Configuration](#configuration)
- [Installation](#installation)
- [Other Dependencies](#Other_Dependencies)
- [License](#license)

---

## Introduction


Gayain Backend is an e-commerce application collaboration project with the team at the Arkaademy bootcamp. Gayain includes web and mobile platforms. Mobile applications are used for marketing,
while for the web platform it is used for product, user, and category management.
This application was built with Express Js and MySQL Database, shipping gateway using the API
rajaongkir.

---


## Configuration
<ol>
  <li>Basic Configuration</li>
  - Node.js - Download and Install [Node.js](https://nodejs.org/en/)
</ol>

---

## Installation
### Clone
```bash
$ git clone https://github.com/gayain/gayaIn-Backend
$ cd gayaIn-Backend
$ npm install
```
### Create Environment Variable
```bash
$ cp .env.example .env
$ nano .env
```
```bash
DB_HOST = "YOUR HOST"
DB_USER = "YOUR USER"
DB_PASSWORD = "YOUR PASSWORD"
DB_NAME = "YOUR DATABASENAME"
DB_IP = "YOUR IP"

JWT_KEY = "secret key"
HEADERS_SECRET = ""
```
### Start Development Server
```bash
$ npm start
```
---

## Other_Dependencies

- [mysql](#)
- [crypto](#)
- [nodemon](#)
- [morgan](#)
- [body-parser](#)
- [dotenv](#)
- [multer](#)
- [cors](#)
- [axios](#)
- [uniqid](#)

---

## License

© [GayaIn Team](https://github.com/gayaIn/ " GayaIn Team")

---

