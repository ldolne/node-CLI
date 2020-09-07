# `holidates` country
## Presentation
This was an assignment during my BeCode training in web development.

The goal was to create a tool to get the holidays of the current year for the given country. 

## Installation
You can install it with npm:

```
npm install @ldolne/holidates
```

## Usage
This module is a command line tool that will take a country name (mandatory) 
and a year (optional, default is current year) as parameters:
```
holidates Belgium [2019]
```

This tool will verify that the parameter is a well-formatted country name, transform it onto a two-letters country code,
then perform an HTTP request to the API of the [nager.date]("https://date.nager.at/") service to get the holidays for the chosen country and year.

The results, which take the form of a list of holidays dates for the year selected, is showed in a readable way in the terminal.

## Versioning
* ...
* Version 1.0.0: launch of the module
