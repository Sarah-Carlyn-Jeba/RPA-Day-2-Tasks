🤖 RPA DAY 2 TASKS :UiPath – Condition and Looping Statements, Control Flow, Collections & Data Handling Tasks

📌 Overview

This repository contains a set of 19 UiPath Studio tasks focused on implementing core programming constructs within RPA workflows. The exercises cover conditional logic (If, If-Else, Else If), list operations, and array manipulations.

The goal of these tasks is to build a strong foundation in decision-making logic and data handling using UiPath activities.

🧠 Concepts Covered

Conditional statements:

If

If-Else

Else If

String validation

Date comparison

File existence validation

List operations (List<T>)

Array operations

Aggregation functions (sum, average)

Sorting and searching techniques

⚙️ Task Descriptions

🔹 If Condition

Check if a number is positive → Display “Positive Number.”

Verify if a string is not empty → Display “String is not empty.”

Compare today’s date with a specified date → Display “It’s the same day!”

Check if a file exists in a folder → Display “File found.”

🔹 If-Else Condition

Determine if a number is even or odd → Display “Even” / “Odd”

Validate if a string starts with “A”

True → “Starts with A”

False → “Does not start with A”

Check temperature condition

Above 30°C → “Hot”

Otherwise → “Cool”

Check string length

Length > 5 → “Long String”

Otherwise → “Short String”

🔹 Else If Condition

Grade classification:

Marks > 90 → “Grade A”

75–90 → “Grade B”

Otherwise → “Grade C”

Number categorization:

< 0 → “Negative”

= 0 → “Zero”

0 → “Positive”

Leap year validation:

Divisible by 4 and not 100 → “Leap Year”

Divisible by 400 → “Leap Year”

Otherwise → “Not a Leap Year”

🔹 List Operations

Create a list of fruits → Check “Apple” → Display “Apple Found.”

Add numbers (1–10) to a list → Display sum of elements

Create a list of names → Check “John” → Display “John is in the list.”

Clear all items from list → Display “List Cleared.”

🔹 Array Operations

Create an integer array → Find and display largest number

Create a string array → Sort alphabetically → Display result

Initialize array with 5 numbers → Calculate average

Reverse an array → Display elements in reverse order

🛠️ Implementation Details

Activities Used:

If Activity

Assign

Write Line / Log Message

Message Box

For Each

Add to Collection

Clear Collection

Data Types:

Int32

String

Boolean

DateTime

List<T>

Array

Key Methods & Functions:

.ToString()

.Contains()

.StartsWith()

.Length

.Sum(), .Average(), .Max()

.Sort(), .Reverse()

▶️ Execution

Each task is implemented as an independent workflow

Outputs are displayed using:

Message Box

Output Panel (Write Line / Log Message)

⚠️ Notes

Proper initialization of variables is required before execution

File existence checks depend on valid file paths

Date comparison should use .Date to ignore time component

Ensure correct type casting when working with collections

👩‍💻 Author

Sarah Carlyn Jeba.S
