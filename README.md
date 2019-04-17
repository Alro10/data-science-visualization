# data-science-visualization
In order to become a Data Scientist, plot and visualize data from files such as csv, txt, etc, turn important and also really cool. How do you infer about some data? If you do not see on ```XYZ```, using awesome packages running on G colab, jupyter or script form.

under developing!


## Matplotlib

Famous and well-known python package, for beginners is very common use it.



```python
pip install matplotlib # python 2.7
pip3 install matplotlib # python 3.5
```

```
import matplotlib.pyplot as plt
```

## Seaborn

[Seaborn](https://seaborn.pydata.org/) is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

```python
pip install seaborn # python 2.7
pip3 install seaborn  # python 3.5
```

```
import seaborn as sns
```



## Plotly

An open-source, interactive graphing library for Python, [Plotly](https://plot.ly/python/)


```python
pip install plotly  # python 2.7
pip3 install plotly   # python 3.5
```
```
import plotly.plotly as py
```

*Function for using plotly on G colab*

```python
def configure_plotly_browser_state():
  import IPython
  display(IPython.core.display.HTML('''
        <script src="/static/components/requirejs/require.js"></script>
        <script>
          requirejs.config({
            paths: {
              base: '/static/base',
              plotly: 'https://cdn.plot.ly/plotly-1.5.1.min.js?noext',
            },
          });
        </script>
        ''')) # python 3.5
```


*Collaborations and contributions are very welcome!* :+1:
