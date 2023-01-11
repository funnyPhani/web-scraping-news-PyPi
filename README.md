# web-scraping-news-PyPi
## To install package
```python
!pip install -U scrapeDataQuotes
```
## To run our code
```python

from scrapeDataQuotes import scrape_data
scrape_data()
```
### Commands to create a package
```python
"""
Steps to install PyPI package
--------------------------------
python setup.py bdist_wheel
pip install -e .
python setup.py sdist
python setup.py bdist_wheel sdist
twine upload dist/*
"""


```
