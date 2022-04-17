# ScrapPaper

![test](/img/abstract.png)

## About this project
ScrapPaper is a web scrapping method to extract journal information from PubMed and Google Scholar using Python script.
Users need to install Python 3 and required modules (See last section of this README.md file), and run the `scrappaper.py` script. 
Refer to the published paper for detailed instruction. 
This side project was completed on March 8, 2022 by @rafsanlab. Follow me on Twitter: https://twitter.com/rafsanlab

### Paper to cite:
Rafsanjani, M. R. (2022). ScrapPaper: A web scrapping method to extract journal information from PubMed and Google Scholar search result using Python. In bioRxiv (p. 2022.03.08.483427). https://doi.org/10.1101/2022.03.08.483427

### This project was modified for MAC compatibility by a.Gabardo

## System Requirement
* Python (version 3 or above)
* The following Python modules: requests, csv, re, time, random, pandas, sys, bs4
* Operating system (current code was tested on Windows 10)
* Command prompt (if using Windows) / terminal
* Search link of the first page result from PubMed or Google Scholar
* Text editor or spreadsheet software to open the results

## Simplified instructions
1. Download the `scrappaper.py` script and `cd` terminal to the directory.
2. Copy the link from the first search results of PubMed or Google Scholar.
3. Run the code and paste the link when prompted.
4. When finished, open the results using text editor or spreadsheet. 
5. Refer to the published paper for detailed instruction.

## Disclaimer
Web scraping might get you blocked from the server, run at your own risk.

## Gabardo - MAC version
To run this script in a MAC environment first create a Python Virtual Environment using the following command

`python3 -m venv venv`

Activate your Virtual Environment with the following command

`source venv/bin/activate`

Use PIP to install the requirements found in the requirements.txt file using the following command (beware that installing Pandas can take some time)

`PIP install -r requirements.txt`

Run the script using

`python scrappaper.py`

Be happy!

### TIP to circunveint the CAPTCHA restrictions.
1. Connect your computer using the `Personal HotSpot` connection from your mobile.
2. Run the script while possible until get the CAPTCHA notice.
3. Reboot your mobile device (this will very likely grant you a new IP address).
4. Reconnect your computer to the hotspot and proceed to the next steps. 

**Note**: you may need to split your searches to complete all your queries. 