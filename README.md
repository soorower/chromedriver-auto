### Auto Installs Chrome-webdriver for use with selenium

## Install pip/pip3
```
pip install chromedriver-auto
pip install selenium
pip install requests
```

## This package works for Chrome version >= 115.0.5790.102
Recently(24 July 2023) Google published a new website for providing Chromedriver for more recent versions of CHROME BROWSER.
Details: https://googlechromelabs.github.io/chrome-for-testing/ 

first, it checks whether a Chrome driver is already there. If no Chrome driver or version mismatch is found, it will download Chromedriver automatically from the official website.

Use Code:


```
from chromedriver_auto.driver_ready import *
driver.get('https://www.google.com')
```
