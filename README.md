# Instagram-Followers-Following-Scraper

## Project Overview
This project automates the process of scraping and comparing followers and following lists on Instagram using Selenium. Its just a fun project, made to help one of my friend who was struggling to identify users who do not follow back, by extracting data from Instagram and processing it programmatically.

## Features
- **Follower and Following Extraction:** Collects a list of followers and following from an Instagram profile.
- **Unfollowers Identification:** Compares the two lists to find users who are not following back.
- **Automated Scrolling:** Handles infinite scrolling to load and retrieve all user data.
- **Reusable Code:** Modular functions for scraping and processing.
- **CSV Export:** Optionally export the results to a CSV file (can be added for enhanced functionality).

## Technologies Used
- **Programming Language:** Python
- **Tools and Libraries:**
  - Selenium for browser automation
  - ChromeDriver for controlling Chrome browser
  - `webdriver_manager` for managing ChromeDriver
  - Standard Python libraries like `time` and `set` for handling delays and processing data

## Installation
### Prerequisites
- Python 3.8 or higher
- Chrome browser installed
- ChromeDriver installed (or managed via `webdriver_manager`)

## Usage
1. Run the script:
   ```bash
   python Instagram_scraper.ipynb
   ```
2. Follow these steps during execution:
   - Login to your Instagram account when prompted by the browser.
   - Wait for the script to load followers and following lists.
3. View the output:
   - The script will display the followers, following, and users who are not following back in the console.

## Example Output
```
Followers: ["user1", "user2", "user3"]
Following: ["user1", "user4"]
Not following back: ["user4"]
```

## Key Files
- `Instagram_scraper.ipynb`: Main script for scraping and processing Instagram data.
- `config.py`: Configuration file for storing your Instagram username.

## Future Enhancements
- **Export to CSV:** Save the results of followers, following, and non-followers to a CSV file.
- **GUI Integration:** Add a user interface for easier interaction.
- **Error Handling:** Improve error handling for scenarios like blocked accounts or rate limits.
