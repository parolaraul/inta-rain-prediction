# Rain Prediction
### Using [INTA meteorological data](http://siga2.inta.gov.ar/#/data) and Time Series Forecasting with [Keras LSTM](http://keras.io)
This is an example of predictions using time based datasets. For this case I used INTA's public data to train a model that will predict if it will rain in a near future.

## Installation

To try this example you should have python and jupyter notebook installed. I use [pip](https://pip.pypa.io/en/stable/) for installing requirements.

1. Clone the repo
2. Create virtualenv: 
```bash
~$ virtualenv .venv
```
3. Activate environment and install 
```bash
~$ source .venv/bin/activate
(venv) ~$ pip install -r requirements.txt
```
4. Run Jupyter 
```bash
(venv) ~$ jupyter notebook
```
5. Open the notebook

## Contributing
Pull requests are welcome.

## License
[MIT](https://choosealicense.com/licenses/mit/)
