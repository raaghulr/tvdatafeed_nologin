activate the environment

install requirements

`pip install -r requirements.txt`



to install

`easy_install tvfeed-1.0.0-py3.8.egg`


no need to give login details


```
from tvfeed import TvDatafeed, Interval

tv=TvDatafeed()

print(tv.get_hist('AAPL','NASDAQ'))
````
