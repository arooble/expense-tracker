# Expense Tracker -- Budget App 📱
Expense Tracker app this simple Python project allows users to track their expenses, categorize them, and monitor their budget on a monthly basis. It provides a straightforward interface for entering expenses, saving them to a CSV file, and summarizing spending habits. Additionally, the app performs mathematical calculations to display the remaining budget for the remainder of the month.




## Features <a name="about"></a> :bulb:

- **Expense Entry:**
  Users can input expense details, including name, amount, and category.
  
- **Category Selection:**
  Choose from predefined categories such as Food, Home, Work, Fun, and Misc.

- **Expense Saving:**
  Expenses are saved to a CSV file (`expenses.csv`) for future reference.

- **Expense Summarization:**
  The script calculates and displays expenses by category, total spent, and remaining budget.

- **Default Budget:**
  The default budget is set to $4000.


## Architecture Diagram <a name="architecture"></a> :pencil2:
- The diagram features expense.py, encapsulating essential data fields: name (str), category (str), and amount (float). Opting for a class was motivated by the goal to consolidate these elements into a cohesive structure, favoring it over a list or dictionary. After creating the class, the plan is to import it into another application, maintaining a separation of logic and data model for organizational clarity. This strategy streamlines the application's primary focuses: user input, CSV file writing, and generating a summary. The summary entails file reading and calculations to determine the total and remaining budget for the specified month.

<img width="1090" alt="architecture-diagram" src="https://github.com/arooble/expense-tracker/assets/90009031/ffaf2175-42d1-4d02-bc77-5bb95c9f1293">
