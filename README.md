# ECommerce Back-End

## Description

This project implements a MySQL/Sequelize + Express backend for an ECommerce front end. Restful operations are tested with Insomnia.

See a walkthrough of setup and testing of this application: [Walkthrough]()

![License Badge](https://img.shields.io/badge/License-MIT-informational?logoColor=white&color=1CA2F1)

## Table of Contents

- [Installation](#installation)
- [How to Use](#how-to-use)
- [Tests](#testing)
- [Questions](#questions)
- [License](#license)

## Installation

This project can be cloned from this repository and then run using Node.js.

## How to Use

To initialize the application ensure that MySQL is downloaded and place a .env file in the root directory with the database information as follows:

```console
  DB_NAME='ecommerce_db'
  DB_USER=<user>
  DB_PW=
```

```console
  mysql -u <user> -p < db/schema.sql
  node seeds/index.js
```

mysql -u <user> -p < db/schema.sql
node seeds/index.js

Lastly, run the server.js main file to start the server on localhost.

## Tests

Tests can be performed with Insomnia using the included tests/insomniaTesting.json export file. Import the insomnia config file and test the routes after setting up the local host server.

## Questions

Find my other projects at: [Ellisonac](https://github.com/Ellisonac)

Contact me at: acannonellison@gmail.com

## License

![License Badge](https://img.shields.io/badge/License-MIT-informational?logoColor=white&color=1CA2F1)

This project is covered under the following license:

MIT License

Copyright (c) [2021]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
