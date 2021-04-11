The objective of this program is to web scrape data from https://www.zalora.com
for ALDO shoe brands. The data is then outputted into a .json file.

Follow the instructions below to get the application running: -

1. cd to the folder directory (e.g. 'path'/zaloraaldowebscraper)

2. Run the following command: 'docker build -t python-zaws .'

3. Run the following command: 'docker run --name my-container -v ${pwd}:/mydata python-zaws

4. A data.json file should be outputted into the same directory
