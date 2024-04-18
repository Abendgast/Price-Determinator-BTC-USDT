# Price-Determinator-BTC-USDT

Price-Determinator-BTC-USDT is a script designed to fetch the current price of Bitcoin for the last 24 hours. It provides a convenient way to obtain this information and can be automated for regular updates.

## Features

The main features of Price-Determinator-BTC-USDT include:

- **Current Bitcoin Price**: Retrieves the current price of Bitcoin for the last 24 hours.
- **Convenient Script Execution**: Offers a simple command to execute the script for obtaining price data.
- **Alias Configuration**: Provides instructions for setting up an alias to streamline script execution.
- **Automatic Execution Setup**: Guides users on configuring automatic execution of the script using crontab.

## Setup Instructions

For convenient use of the script, follow these setup instructions:

1. **Setting up an Alias**: 
   - Open your terminal and run the command `nano .bashrc` to edit the bashrc file.
   - Add the following alias to the file:
     ```bash
     alias B='cd Work/CryptoAnalitycs;source myenv/bin/activate;python Course.py;deactivate;cd'
     ```
   - Save and exit the file. This alias allows you to execute the script conveniently by typing `B` in the terminal.

2. **Automatic Execution Setup (Optional)**:
   - Open your terminal and run the command `crontab -e` to edit your crontab file.
   - Add the following command at the end of the file to execute the script automatically every day at 12 o'clock:
     ```bash
     0 12 * * * cd /home/way/to/your/middle;source myenv/bin/activate;/home/way/to /your/medium/bin/python Course.py;deactivate;cd
     ```
   - Save and exit the file.

Once you've completed these setup steps, you can simply enter `B` in the terminal to execute the script and fetch the Bitcoin price data. Additionally, the script will be executed automatically by crontab every day at 12 o'clock.

Wishing you a pleasant experience using Price-Determinator-BTC-USDT!
