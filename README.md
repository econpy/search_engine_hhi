## About ##
The `analysis.py` script takes data on market share downloaded from [http://gs.statcounter.com/](http://gs.statcounter.com/) to compute the [Herfindahl index](http://en.wikipedia.org/wiki/Herfindahl_index) for the search engine market across countries and time.

## Running ##
Assuming [pandas](http://github.com/pydata/pandas) is installed, simply run:

```bash
python analysis.py
```

which will make a DataFrame of the data, and from that, the following line chart:
![HHI across Countries and Time](http://s3.amazonaws.com/econpy/hhi.png)
