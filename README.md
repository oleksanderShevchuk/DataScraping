### Smartphone Price Comparison

#### Overview
This application automates scraping smartphone information from three different online stores (Comfy, Foxtrot, Rozetka), comparing their prices, and emailing the results.

#### 1st Process: Data Scraping
1. **Websites Scraped:** Comfy, Foxtrot, Rozetka
   - Navigate to each website.
   - Go to the "Samsung smartphones" section.
   - Extract information for each smartphone: Name, Price, Product URL, and Website URL.
   - Save the collected data into an Excel file for each website.

#### 2nd Process: Data Comparison
1. **Comparison of Scraped Data:**
   - Compare data obtained from the three websites.
   - Identify smartphones that are listed on all three websites.
   - Compare prices of identical smartphone models and determine the lowest price among them.
   - Save this information into a new Excel file named "Minimum Prices".
   - Save other records into another Excel file with an arbitrary name.
   - Send the Excel files generated (Minimum Prices and UniqueModels) via email.

#### Instructions for Running the Application
1. **Setup Requirements:**
   - Ensure .NET Framework is installed on your machine.
   - Install UiPath Studio for automation workflow editing (optional).
   
2. **Running the Application:**
   - Open the UiPath project in UiPath Studio (if using).
   - Execute the workflow for the first process (Data Scraping).
   - Execute the workflow for the second process (Data Comparison).
   - Put your specified email address for the sent Excel files.

#### Troubleshooting
- Ensure all dependencies are installed and configured correctly.
- Check network connectivity and access to the specified websites.
- Verify email server settings if there are issues with sending emails.
