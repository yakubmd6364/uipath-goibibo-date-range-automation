# UiPath Goibibo Date Range Automation

This project is a UiPath workflow that automates selecting a travel date on the Goibibo website based on user input.  
It is designed to demonstrate browser automation, popup detection, and interaction with a calendar widget using dynamic navigation.

## Features

- Opens Goibibo in Google Chrome
- Detects and closes popups automatically
- Prompts the user for a date in `dd/MM/yyyy` format
- Navigates through the calendar to match the entered date
- Selects the correct date cell dynamically
- Uses loops and conditional logic to handle month/year changes

## Screenshot

WebAutomation_Goibibo.jpg  
*This screenshot shows the designed UiPath workflow which opens Goibibo, takes user input, navigates the calendar, and selects the given date.*

## Project Structure

- WebAutomation_Goibibo.xaml — Main workflow  
- project.json — UiPath project configuration and dependencies  
- WebAutomation_Goibibo.jpg — Workflow screenshot

## How to Use

1. Clone or download this repository to your local machine.  
2. Open the folder in UiPath Studio.  
3. Open `WebAutomation_Goibibo.xaml`.  
4. Run the workflow.  
5. Enter your desired date when prompted (format: `dd/MM/yyyy`).  
6. The automation navigates to and clicks the correct date.

## Requirements

- UiPath Studio (Community or Enterprise Edition)  
- Google Chrome browser with UiPath Chrome Extension installed  
- Stable internet connection  
- Correct date format input

## Done Using UiPath Studio Activities

Open Browser, UiElement Exists, Click, Input Dialog, Assign, Get Text, While Loop, If

---

*This project is for learning/demo purposes and works with Goibibo’s current interface. Website changes may require selector updates.*
