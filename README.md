# Loan Qualifyer Analyzer

## What this program does

This program allows a customer to input their financial data to determine if they qualify for a loan based on a list of banks with given loan requirements. The financial data includes the customers *credit score*, *montly debt* and *monthly income*, the *loan amount* they are requesting, and the *value* of their home.

This project was created to allow a more user friendly application that allows repeated use with any of the above given data. It also allows the customer to save their data in an easy-to-read spreadsheet if they choose.

---

## Technologies

This program can be run with Mac or PC with the following requirements:

Python 3.7.1

Questionary 0.2.5

Fire 1.15.0

---

## Installation Guide

To install fire, enter in the following prompt in your command line:

`pip install fire`   

More information can be found at [Python-fire](https://github.com/google/python-fire)



To install questionary, enter the following prompt:

`pip install questionary`

More information can be found at [Questionary](https://pypi.org/project/questionary/)

---

## Usage

To run this program, first navigate to your command line.

Type in `conda activate dev` to make sure you are in the dev environment to run the program.

You will then be prompted to enter in the file path to a rate sheet:

![File Path](URL)

*Hint: If you right click on the file you want to use, you can copy the path and paste into the command line*

Once you have entered in your path, you will be prompted with a series of questions:

![Financial Data](URL)

This will then calculate your debt-to-income ratio, loan-to-value ratio and the number of loans you qualify for:

![Qualifying loans](URL)

You will then be prompted to decide if you would like to save your data as a CSV file, and if so, the desired location you would like:

![Save data option]()

You can use tab and return/enter, which will show a pop up of your folders to chose the desired location:

![Tab/enter location data](URL)

Once you have entered in the location, you should then have a CSV file with your qualifying loans!

![CSV file!](URL)

---

## Contributors

In this section, list all the people who contribute to this project. You might want recruiters or potential collaborators to reach you, so include your contact email and, optionally, your LinkedIn or Twitter profile.

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.
