# Expense Tracker Application

## Overview
The **Expense Tracker** application allows users to log and track their daily expenses with a simple GUI. The app follows the **Model-View-Controller (MVC)** pattern for better modularity.

## Features
- **Add Transactions:** Users can enter an amount and select a category before clicking "Add Transaction" to save the record.
- **Input Validation:** Ensures the amount is a valid number between 0 and 1000, and the category is from a predefined list.
- **Expense Table:** Displays a list of recorded transactions with columns for Serial, Amount, Category, and Date.
- **Total Calculation:** The last row of the table displays the total sum of all expenses.
- **Error Handling:** Provides error messages if the input is invalid.

## Project Structure
expense_tracker/ 
  │── src/ 
    │├── ExpenseTrackerApp.java # Controller 
    │├── ExpenseTrackerView.java # View 
    │├── Transaction.java # Model 
    │├── InputValidation.java # Validation Helper 
  │── jdoc/ # Javadoc Documentation 
  │── README.md # Project Documentation

## Technologies Used
- **Java** (Swing for GUI)
- **Javadoc** for Documentation

## Running the Application
To compile and run the application, use the following commands:

```sh
javac src/*.java
java src/ExpenseTrackerApp
```

## API Documentation
The Javadoc-generated documentation is available in the jdoc/ folder.

To generate the Javadoc documentation, run:

```sh
javadoc -d jdoc -sourcepath src -subpackages expense_tracker
This will create HTML documentation inside the jdoc/ directory.
```

## Contribution Guidelines
Fork the repository.
Create a feature branch (git checkout -b feature-name).
Commit changes (git commit -m "Added new feature").
Push to your branch (git push origin feature-name).
Submit a pull request.
