# rankwatch17_py_scraping
## **Assignment**:
To write a python script to scrape https://www.babynamesdirect.com to get all baby names for
boys and girls both. Store the names in a comma-separated format in names.csv with two
fields: name, gender. The first column will contain all names and second column will contain
either boy or girl.

## **Prerequisite:**
* Python should be installed
* Install pip and psutil(Cross-platform lib for process and system monitoring in Python) 
* To install pip, securely download get-pip.py 
* Then run the following: "python get-pip.py"

### Import these libraries

```python
import urllib2
from bs4 import BeautifulSoup
import csv
```

### Built with
Used Notepad++ for writing the script.
