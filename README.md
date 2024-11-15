# NiftyStockCharts
Charts of normalized return of stocks listed on Nifty using Jupyter Notebook

## Installation
### Create a virtual environment

```python -m virtualenv venv```

### Activate environment

```source venv/bin/activate```

### Install dependencies

```pip install -r requirements.txt```

### Run Jupyter Notebook (jupyter needs to be installed globally)

```jupyter notebook```

## Chart 
The following chart is generated using matplotlib

![Chart Image](/images/StockCharts.png)

## Chart with Plotly
The following chart is generated using plotly. In addition to the chart, plotly also provides a dashboard to interact with the chart. The widget controls allow you to select the stocks to display,  the dropdown allows you to select the time period as well as add the held positions. Highlighting held positions is WIP

![Chart Image Plotly](/images/StockChartsPlotly.png)
