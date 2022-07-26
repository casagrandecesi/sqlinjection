<a href="https://www.bernardi.cloud/">
    <img src=".readme-files/sqlinjection-logo-72.png" alt="SQL Injection Sample logo" title="SQL Injection Sample" align="right" height="72" />
</a>

# SQL Injection Sample
> Web application that can be used by high-school students to test SQL injection attacks.

[![Python](https://img.shields.io/badge/python-v3.7+-blue.svg)](https://www.python.org)
[![License](https://img.shields.io/github/license/casagrandecesi/sqlinjection.svg)](https://opensource.org/licenses/AGPL-3.0)
[![GitHub issues](https://img.shields.io/github/issues/casagrandecesi/sqlinjection.svg)](https://github.com/casagrandecesi/sqlinjection/issues)

## Table of contents

- [What is this?](#what-is-this)
- [Usage](#usage)
- [License](#license)

## What is this?

This is a sample web application that runs on **your computer**. Usually, when you connect to a web site, there is a connection between your and someone else's computer (e.g. Google, Facebook). This web application, instead, uses connections that go from your own computer to itself: this kind of connection is called **loopback**.

## Usage

If you're on Windows, run `start.bat`, then open your web browser and go to the following URL: [http://127.0.0.1:8080](http://127.0.0.1:8080)

This sample web application doesn't do much: you can log into it and that's it.

Valid user names and password can be found in cleartext (brrr...) in the `users` table of the `users.db` SQLite database. If you're on Windows you can run `db.bat` to see the database content.

Finally, if you want to see what's going on under the hood, run `edit.bat` (again, if you're on Windows): this will open an editor with the web application source code.

## License

This sample web application is licensed under the terms of the GNU Affero General Public License version 3.