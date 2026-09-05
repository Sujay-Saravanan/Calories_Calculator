# Calorie Calculator

A simple Java console application that calculates the Basal Metabolic Rate (BMR) and estimated daily calorie requirement of a person.

The program takes details such as gender, age, weight, height, and activity level from the user. Based on these details, it calculates the BMR and then estimates the number of calories required per day.

## How it works

The user is asked to enter the following details:

* Gender
* Age
* Weight
* Height
* Activity level

The program first calculates the BMR based on the user's gender, age, weight, and height. After that, an activity multiplier is applied to calculate the estimated daily calorie requirement.

The supported activity levels are:

* Sedentary
* Moderate
* Active

## Project Structure

* `MainApp.java` - Starts the application and controls the program flow.
* `UserInputHandler.java` - Takes input from the user and validates it.
* `UserData.java` - Stores the user's details.
* `CalorieCalculator.java` - Contains the logic for calculating BMR and daily calorie requirements.
* `ResultDisplay.java` - Displays the calculated results.

## Calculation

The application first calculates the Basal Metabolic Rate (BMR).

After calculating the BMR, the daily calorie requirement is calculated using an activity multiplier.

| Activity Level | Multiplier |
| -------------- | ---------- |
| Sedentary      | 1.2        |
| Moderate       | 1.55       |
| Active         | 1.725      |

Daily calorie requirement:

```text
BMR × Activity Multiplier
```

## Concepts Used

* Classes and Objects
* Encapsulation
* Constructors
* Methods
* Scanner
* Input Validation
* Conditional Statements
* Switch Statements
* Exception Handling

## How to Run

Compile all the Java files:

```bash
javac *.java
```

Run the application:

```bash
java MainApp
```

## Sample Input

```text
Gender: M
Age: 25
Weight: 70
Height: 175
Activity Level: Moderate
```

The program will display the user's BMR and estimated daily calorie requirement.

