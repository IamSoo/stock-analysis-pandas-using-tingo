# stock-analysis-pandas-using-tingo
A small project that shows how to do a generic stock analysis using Tingo's API and Pandas. Tingo is nice SaaS service that provides trade history data.
They also have nice set of REST APIs to get the stock prices. To use tingo's api first we need to create an api key(for test and individual its free) and pass it in pandas while calling function
get_data_tiingo.

## How to run

### clone the project
```
git clone git@github.com:IamSoo/stock-analysis-pandas-using-tingo.git
cd stock-analysis-pandas-using-tingo
```
### create virtual env

```commandline
python -m venv .
source venv/bin/activate
```

```commandline
pip install -r requirements.txt
```

### Attch the venv to ipykernel

```commandline
python -m ipykernel install --user --name venv
```


### start the jupyter notebook

```jupyter notebook```




