# Cybersecurity Awareness Bot

**Cybersecurity Awareness Bot** is a simple C# command-line bot designed to educate users on key cybersecurity concepts such as **Password Safety**, **Phishing**, and **Safe Browsing**. This project is built to raise awareness of essential cybersecurity topics, with engaging ASCII art, a user-friendly interactive menu, and a welcome sound.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview

This C# project aims to provide an interactive, educational experience about cybersecurity concepts. The bot guides users through essential topics, such as protecting passwords, recognizing phishing attempts, and browsing the internet safely.

The bot includes:
- A **welcome sound** that plays when the bot starts.
- **ASCII art** to make the user experience more engaging.
- A simple **interactive menu** for users to select various topics.
- Educational **text-based responses** to explain each selected topic.

## Features

- **ASCII Art Bot**: Displays a fun and engaging ASCII art version of the bot.
- **Interactive Menu**: Provides the following options for the user to choose from:
  1. Password Safety
  2. Phishing
  3. Safe Browsing
  4. Exit the bot
- **Audio Integration**: Plays a welcoming sound when the bot is launched.
- **User Interaction**: Prompts the user for their name and greets them.
- **Text-based Educational Responses**: Provides a description of each cybersecurity topic when selected by the user.
- **Graceful Exit**: Ends the conversation with a friendly goodbye message.

## Requirements

- **.NET SDK**: Make sure you have the .NET SDK installed on your machine to run the project. You can download the latest version of .NET from [here](https://dotnet.microsoft.com/download).
- **Sound File**: Ensure you have a `.wav` sound file placed in the `Properties.Resources` folder for the welcome sound. 

## Installation Instructions

Follow these steps to clone and run the project locally:

1. **Clone the repository**:
   - Open your terminal or Git Bash and run the following command to clone the repository to your local machine:

     ```bash
     git clone https://github.com/yourusername/CybersecurityAwarenessBot.git
     ```

2. **Open the project**:
   - Open the project folder in **Visual Studio** or any C# IDE of your choice.

3. **Install dependencies**:
   - Ensure that the project is properly set up with the required .NET SDK and other dependencies. Run the following commands to restore the NuGet packages:

     ```bash
     dotnet restore
     ```

4. **Build the project**:
   - In Visual Studio, click on **Build > Build Solution** or use the following command in the terminal:

     ```bash
     dotnet build
     ```

5. **Run the project**:
   - You can run the project by pressing **F5** in Visual Studio or using the following command:

     ```bash
     dotnet run
     ```

6. **Test the bot**:
   - The bot will ask for your name and display a menu. You can interact with the bot by selecting different options from the menu.

## Usage

Once the bot is running, you'll interact with it via the terminal. Here's an example of what you might see:

```plaintext
CYBERSECURITY AWARENESS
------------------------

____________________
|| Cyber Awareness ||[0?0]
--------------------  ||
                      /\

What is your name? : John
Hello John, WELCOME TO THE CYBERSECURITY AWARENESS BOT!
How are you?: Good

════════════ MENU ════════════
  1. Password Safety
  2. Phishing
  3. Safe Browsing
  4. Exit
══════════════════════════════

What is your purpose: 1
Password Safety:
It’s crucial to use strong, unique passwords for all your accounts. Consider using a password manager to securely store and manage passwords.
