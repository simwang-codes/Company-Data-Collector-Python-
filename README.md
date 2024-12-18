# Company Data Collector
  If you have a list of company names in an Excel file and you want to get these companies' official website URLs and their HQ addresses, the Company Data Collector can help you complete this task effectively.

  The company_data_collector_with_api.py script helps you fetch a company's official website URL and its HQ address by utilizing an API and the Google Search engine, and inputs the fetched results back into your Excel file. If no HQ address is found, the company's address will be retrieved as an alternative.

### Prerequisites
  serpapi, os, openpyxl, requests, dotenv, googlesearch, beautifulsoup4, and time libraries are needed to run this script. They can be installed using pip3 install "library name".

### How to run the script

  1. Get your API key by registering for a free account on Serpapi, save your API key in a .env file, and keep it in the same directory where you are about to run the program.
  
  2. Create a list of company names in Excel (or you can download the test sample "Account Match.xlsx" from the Excel Files folder).
  
  3. Download "company_data_collector_with_api" from the Python Scripts folder. 'cd' to the directory that contains the script, type "python3 collect_company_data_with_api", and run the script.
  
  The result you get will look similar to the processed test sample named "Account Match(Processed).xlsx" in the Excel Files folder.

  You can also try running "company_data_collector_without_api.py", which doesn't require you to use any API but will be less efficient and may exceed Google's rate limit.

## *Author Name*
[Sim Wang](https://github.com/simwang-codes)
