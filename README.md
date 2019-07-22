# dork-scanner
dork scanning tool built in python. It scrapes web search engines with dorks you provide in order to find vulnerable urls. This tool supports google, yahoo, bing and baidu search engines
 Usage:
        dork-scanner.py <search> <engine> <pages> <processes>
            <search>          String to be searched for 
            <engine>          Search engine to be used
            <pages>           Number of pages to search in
            <processes>       Number of parallel processes

# dork-scanner
This script is an automated tool to parse search engines with provided dorks in order to find vulnerable urls. This tool supports google, bing and baidu.
## Requirements
- Python 3
- Packages in requirements.txt
## Setup
Refer to these steps to install the tool on a linux distribution
```
git clone https://github.com/GuestGuri/dork-scanner.git
pip3 install -r requirements.txt
```
## Usage
``` python3 dork-scanner.py <search> <engine> <pages> <processes> ```
-            <search>          String to be searched for 
-            <engine>          Search engine to be used
-            <pages>           Number of pages to search in
-            <processes>       Number of parallel processes"""
## Examples
``` python3 dork-scanner.py inurl:php?=id1 google 3 3 ```
search for inurl:php?=id1 in 3 pages of google using 3 processes
## Author
Author: Mohamed Ghassen Gargouri 
