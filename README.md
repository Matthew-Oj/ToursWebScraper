# Tour Web Scraper

## Table of Contents

- [Tour Web Scraper](#tour-web-scraper)
  - [Overview](#overview)
  - [Features](#features)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)


## Overview

This Python program utilizes web scraping techniques to fetch new tour dates for different bands and sends you an email notification when a new band is scheduled to perform. The tour information is stored in a SQLite database, organized by band, city, and date. The program is designed using Object-Oriented Programming (OOP) principles for better organization and maintainability.

## Features

- Web scraping to extract new tour dates.
- Store tour data in a SQLite database.
- Send email notifications for upcoming concerts.
- OOP design for modular and scalable code.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Python**: This program requires Python 3.7 or higher to be installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

- **Python Packages**: Install the necessary Python packages using `pip`:

## Installation

  ```bash
  pip install requests selectorlib smtplib_ssl os

