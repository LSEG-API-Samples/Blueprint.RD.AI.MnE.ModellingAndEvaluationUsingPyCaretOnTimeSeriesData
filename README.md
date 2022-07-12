# Modelling for Time Series Data using PyCaret


## <a id="overview"></a>Overview
This article is the second article in series of the previous one. In previous article, we performed EDA on the time series data loaded using Refinitiv Data library and PyCaret. In this article, we will make use of AutoML functionalities available in PyCaret, select best model, fine tune the selected model, make use of blended models and evaluate them.

Details and concepts are further explained in the [Modelling and Evaluation - Time Series Forecasting using PyCaret](https://developers.refinitiv.com/en/article-catalog/article/modelling-and-evaluation-using-pycaret-on-time-series-data) article published on the [Refinitiv Developer Community portal](https://developers.refinitiv.com).

## <a id="disclaimer"></a>Disclaimer
The source code presented in this project has been written by Refinitiv only for the purpose of illustrating the concepts of creating example scenarios using the Refinitiv Data Library for Python.

***Note:** To [ask questions](https://community.developers.refinitiv.com/index.html) and benefit from the learning material, I recommend you to register on the [Refinitiv Developer Community](https://developers.refinitiv.com)*

## <a name="prerequisites"></a>Prerequisites

To execute any workbook, refer to the following:

- A Refinitiv Desktop license (Refinitiv Eikon or Refinitiv Workspace) that has API access 
- Tested with Python 3.7.13
- Packages: [pandas](https://pypi.org/project/pandas/), [pycaret-ts-alpha](https://pypi.org/project/pycaret-ts-alpha/), [refinitiv.data](https://pypi.org/project/refinitiv-data/)
- RD Library for Python installation:  '**pip install refinitiv-data**'


  
## <a id="authors"></a>Authors
* **Shadab Hussain** 
* **Marios Skevofylakas**
