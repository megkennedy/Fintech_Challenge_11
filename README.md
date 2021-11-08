# Fintech_Challenge_11

UW Fintech Bootcamp Challenge 11

For this challenge we are analyzing MercadoLibre financial and user data to see if we can predict search traffic and if that will translate into stock price changes.

## Libraries and dependencies needed

import pandas as pd
import holoviews as hv
from fbprophet import Prophet
import hvplot.pandas
import datetime as dt
from pathlib import Path
import numpy as np
%matplotlib inline

## Temporary installations

from IPython.display import clear_output
try:
  !pip install pystan
  !pip install fbprophet
  !pip install hvplot
  !pip install holoviews
except:
  print("Error installing libraries")
finally:
  clear_output()
  print('Libraries successfully installed')


## Issues

I had difficulty running the notebook in Google Colab, so I just used Jupyter Lab.

## Contributors

As always a shout out to my professer, TAs (especially Kevin who helped me sort out a mental error while trying to complete the assignment), and classmates for all their help during this process