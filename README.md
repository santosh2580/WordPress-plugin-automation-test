# WordPress Plugin Automation Test

This project automates the process of installing and activating the **Everest Forms** plugin on a local WordPress site using Selenium WebDriver and Python.

## Features

- Logs into WordPress Admin
- Searches for the **Everest Forms** plugin
- Installs and activates the plugin if not already active
- Takes screenshots at each step
- Logs every action for debugging
- Adds a welcome message after activation

## Requirements

- Python 3.7+
- Google Chrome + ChromeDriver
- A local WordPress installation (e.g., `http://wordpress-automation.local`)
- Required Python packages (install via `pip install -r requirements.txt`)

## Installation

```bash
git clone https://github.com/your-username/wordpress-plugin-automation-test.git
cd wordpress-plugin-automation-test
pip install -r requirements.txt
python test.py
