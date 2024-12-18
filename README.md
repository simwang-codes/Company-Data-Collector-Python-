# Company Data Collector
  The CompanyDataCollector script helps you fetch a company's official website URL and its HQ address. If no HQ address is found, the company's address will be retrieved as an alternative.

### Prerequisites
  serpapi, os, openpyxl, requests, dotenv, googlesearch, beautifulsoup4, and time libraries are needed to run this script. They can be installed using pip3 install "library name".

### How to run the script

  1. Get your API key by registering for a free account on Serpapi, save your API key in a .env file, and keep it in the same directory where you are about to run the program.
  
  2. Create a list of company names in Excel (or you can download the test sample "Account Match.xlsx" from the Excel Files folder).
  
  3. Download "collect_company_data_with_api" from the Python Scripts folder. 'cd' to the directory that contains the script, type "python3 collect_company_data_with_api", and run the script.
  
  The result you get will look similar to the processed test sample named "Account Match(Processed).xlsx" in the Excel Files folder.

  You can also try running "collect_company_data_without_api.py", which doesn't require you to use any API but will be less efficient.

## *Author Name*
[Sim Wang](https://github.com/simwang-codes)
