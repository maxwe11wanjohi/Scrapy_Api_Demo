# Scrapy_Api_Demo
This repository demonstrates how to combine Scrapy and Playwright to scrape and extract data from a website, specifically focusing on obtaining product information.


To run the code and obtain the final output using Scrapy and the provided spider "pwspider", follow these steps:

Set up a virtual environment:

For Mac:
Open a terminal.
Install the virtualenv package if you haven't already: pip install virtualenv.
Create a new virtual environment: python3 -m venv myenv.
Activate the virtual environment: source myenv/bin/activate.
For Windows:
Open Command Prompt or PowerShell.
Install the virtualenv package if you haven't already: pip install virtualenv.
Create a new virtual environment: python -m venv myenv.
Activate the virtual environment: .\myenv\Scripts\activate.
Install dependencies:

Ensure your virtual environment is activated.
Change to the directory where your code is located: cd /path/to/code.
Install the required packages: pip install scrapy scrapy-playwright.
Run the spider:

While in the same directory where your code is located, execute the following command:
scrapy crawl pwspider -o product.json
This command runs the "pwspider" spider defined in your code and saves the scraped data to a JSON file named "product.json". You can replace "product.json" with a different filename if desired.

Wait for the spider to finish:

The spider will start sending requests, scraping data, and storing it in the specified output file.
Once the spider completes its execution, the terminal/command prompt will display relevant logs and notifications.
The generated "product.json" file will contain the scraped data in JSON format.
By following these steps, you can set up a virtual environment, install dependencies, and run the provided code to scrape data using Scrapy and the "pwspider" spider. The final output will be stored in the "product.json" file.
