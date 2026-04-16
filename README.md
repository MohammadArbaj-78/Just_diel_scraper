📊 Justdial Data Scraper (Selenium + Pandas)
📌 Project Overview

This project is a web scraping tool built using Python, Selenium, and Pandas to extract business data from Justdial.

It automatically collects:

Business Name
Ratings
Address
Contact Number

And saves the data into a structured CSV file for further analysis.

🚀 Features
Automated browser using undetected-chromedriver
Human-like behavior (mouse movement + scrolling)
Extracts multiple business listings
Handles missing data safely
Saves clean structured data into CSV
Fully dynamic and reusable
🛠️ Technologies Used
Python 🐍
Selenium
Undetected ChromeDriver
Pandas
OS Module
📂 Project Structure
project-folder/
│
├── scraper.py
├── data/
│   └── CSV.csv
⚙️ How It Works
Script opens Justdial in automated browser
Scrolls the page to load data
Extracts business details:
Name
Ratings
Address
Phone Number
Stores data into a list
Converts it into a Pandas DataFrame
Saves final output as CSV
▶️ How to Run
1. Install dependencies
pip install selenium pandas undetected-chromedriver
2. Run the script
python scraper.py
📄 Output
CSV file will be saved inside:
data/CSV.csv
💡 Example Output
Name	Ratings	Address	Number
ABC Agency	4.5 ⭐	Indore	9876543210
⚠️ Notes
Website structure may change, selectors may need updates
Use reasonable delays to avoid blocking
For educational and portfolio purposes
🎯 Use Cases
Lead generation
Market research
Data analysis
Business listing extraction
🙌 Author

Your Name

⭐ Support

If you like this project:

Star the repo ⭐
Share feedback
Connect for freelance work
📬 Contact

"I extract valuable business data and convert it into structured formats for analysis."

Feel free to reach out for any scraping or automation projects 🚀