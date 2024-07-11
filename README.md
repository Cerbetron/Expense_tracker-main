# Expense and Income Tracker App

This Flutter application tracks income and expenses, categorizing them into various categories and providing a summary of total income and expenses.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This app helps users track their income and expenses by categorizing them into different categories. Users can view the total income and expenses for the current month and see a breakdown of expenses by category.

## Features

- Add income and expenses with categories.
- View total income and total expenses for the month.
- View breakdown of expenses by category.
- Responsive UI with Material Design components.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/Cerbetron/Expense_tracker-main.git
    ```
2. **Navigate to the project directory:**
    ```sh
    cd expense-tracker-app
    ```
3. **Install dependencies:**
    ```sh
    flutter pub get
    ```
4. **Run the app:**
    ```sh
    flutter run
    ```

## Usage

1. **Add an Income:**
   - Navigate to the homepage.
   - Click on "Add Income".
   - Fill in the details and select the appropriate category.
   - Click "Save".

2. **Add an Expense:**
   - Navigate to the homepage.
   - Click on "Add Expense".
   - Fill in the details and select the appropriate category.
   - Click "Save".

3. **View All Transactions:**
   - Navigate to the All Transactions screen.
   - View the total income and expenses.
   - Click on any category to see a detailed list of transactions.

## Code Structure

- `lib/presentation/homepage_screen/`: Contains the main homepage screen and functionality for adding expenses and income.
- `lib/presentation/homepage_screen/functionality/expense/`: Contains the Expense model, BLoC, and events.
- `lib/presentation/homepage_screen/functionality/income/`: Contains the Income model, BLoC, and events.
- `lib/presentation/all_transactions_screen/`: Contains the All Transactions screen which displays a summary of expenses and income.

## Dependencies

- [Flutter](https://flutter.dev/)
- [flutter_bloc](https://pub.dev/packages/flutter_bloc): For state management.
- [equatable](https://pub.dev/packages/equatable): To simplify equality comparisons.

