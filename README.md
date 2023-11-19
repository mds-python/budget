# Home Budget

Create a system for managing a home budget. The system must track incomes and expenses, store their history
and allow to view the current and past ballance.

In particular the following user interactions must be implemented:

- Add an income. The program must ask and store the income amount, date, and description.

- Add an expense. The program must ask and store the income amount, date, and description.

- View current ballance (sum of all the incomes minus sum of all the expenses).

- View the ballance for the end of any month in the past. The program must ask for the year and month and present
  the balance for the end of the specified month (considering incomes and balances not later than executed in the specified
  month).

- View the summary of a specified month. The program must ask for the year and month and present all the incomes and expenses
  in the given month, show how the total balance changed (did we have a net gain or loss) and what was the total balance at the
  beginning and the end of the month.

The data should be stored in the disk in any form you choose. It should be persistent i.e. no data can be lost then the program is closed.

The program code must be **elegant and legible**. In the simplest approach you may use the basic text interface based on `print` and `input` functions. However, you must separate user interface from the logic code.

To get a higher mark, you may consider the following:

- Good error handling (proper reaction if the user enters invalid data).

- Adding more features; e.g.:
  - recurring incomes and expenses (that can be defined once and then they happen every month),
  - possibility to show history of operation in a given period (not just a single month).
  - if some operation involves band transfer or credit card operations, verify their numbers (use your modules from the exercise),
  - whatever else you think may be useful.

- Better user interface, using some graphical or web interface. You should browse the net for any library that allows to do this
  and implement it in your code.

The main file must be `main.py`. You may (and probably should) use other files as modules.
