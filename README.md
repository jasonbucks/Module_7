# Module_7 - ETF Analyzer

   ![Charts Picture](Images/7-4-challenge-image.png)

Finance has had an explosion in passive investing in recent years.  Passive investing means that you invest in a basket of assets that's called an exchange-traded fund (ETF).  This way, you don't spend time researching individual stocks or companies or take the risk of investing in a single stock.  ETFs offer more diversification.

---

## Technologies

This project builds a financial database and web application using SQL, Python, and the Voila library to analyze the performance of a hypothetical fintech ETF.  This project leverages python 3.7.11 with the following packages:

* [pandas](https://pandas.pydata.org) - Use the Pandas library, along with JupyterLab, to collect, prepare and analyze data.

* [sqlalchemy](https://sqlalchemy.org) - The Python SQL Toolkit and Object Relational Mapper.

* [voila](https://voila.readthedocs.io/en/stable/using.html) - This library allows you to convert a Jupyter Notebook into an interactive dashboard that can be shared with others.

* [HoloViz (formerly PyViz)](https://holoviz.org) - Data visualization tool hvPlot.

---

## Installation Guide

Before running the application first import the following libraries:

```python
  import pandas as pd
  import hvplot.pandas
  import sqlalchemy
```

Before running, make sure that SQLAlchemy and Voila are installed on your machine by running:
  conda list sqlalchemy
  conda list voila
  
If either are not installed, install them while in the Conda dev environment:
  pip install SQLAlchemy
  conda install -c conda-forge voila

---

## Usage

The Jupyter notebook containing both my analysis of the ETF data stored in a SQL database as well as the interactive visualizations is included.  A video summarizing this Jupyter notebook deployed as a web application via the Voila library can be found below:

https://user-images.githubusercontent.com/102486437/178110644-434bcab0-d137-43fd-9e00-55d9891b1ddc.mp4

---

## Contributors

Starter code was provided by UW Fintech Bootcamp.  Updates and analysis by Jason Buckholt.  

---

## License

MIT License

Copyright (c) 2022 Jason Buckholt

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
