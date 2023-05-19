# datascience-101
Unstructured testing of ideas within Data Science 

## Python data processing  

An ex-colleague decided to test a few Python data processing libraries, with a variation of data size to figure out when to use what. 
He evaluated Pandas, Apache Spark and Polars https://betterprogramming.pub/pandas-spark-and-polars-when-to-use-which-f4e85d909c6f

### Pythin libraries in a broader perspective 

```mathematica
| Library/Package      | Tool Type           | Small Data Sets    | Medium Data Sets   | Large Data Sets    |
|----------------------|---------------------|--------------------|--------------------|--------------------|
| pandas               | Data Manipulation   | ✔️                 | ✔️                 |                    |
| polars               | Data Manipulation   | ✔️                 | ✔️                 |                    |
| NumPy                | Scientific Computing| ✔️                 | ✔️                 | ✔️                 |
| Dask                 | Distributed Computing|                    | ✔️                 | ✔️                 |
| Spark (PySpark)      | Distributed Computing|                    |                    | ✔️                 |
| scikit-learn         | Machine Learning    | ✔️                 | ✔️                 | ✔️                 |
| TensorFlow           | Machine Learning    | ✔️                 | ✔️                 | ✔️                 |
| PyTorch              | Machine Learning    | ✔️                 | ✔️                 | ✔️                 |
| Keras                | Machine Learning    | ✔️                 | ✔️                 | ✔️                 |
| XGBoost              | Machine Learning    | ✔️                 | ✔️                 | ✔️                 |
| LightGBM             | Machine Learning    | ✔️                 | ✔️                 | ✔️                 |
| Matplotlib           | Data Visualization  | ✔️                 | ✔️                 |                    |
| Seaborn              | Data Visualization  | ✔️                 | ✔️                 |                    |
| Plotly               | Data Visualization  |                    | ✔️                 | ✔️                 |
| Bokeh                | Data Visualization  |                    | ✔️                 |                    |
| OpenCV               | Image/Video Processing| ✔️                 | ✔️                 |                    |
| scikit-image         | Image/Video Processing| ✔️                 | ✔️                 |                    |
| Pillow               | Image/Video Processing| ✔️                 | ✔️                 |                    |
| NLTK                 | Natural Language Processing| ✔️           | ✔️                 |                    |
| SpaCy                | Natural Language Processing| ✔️           | ✔️                 |                    |
| Gensim               | Natural Language Processing| ✔️           | ✔️                 |                    |
| Flask                | Web Development     | ✔️                 | ✔️                 | ✔️                 |
| Django               | Web Development     | ✔️                 | ✔️                 | ✔️                 |
| FastAPI              | Web Development     | ✔️                 | ✔️                 | ✔️                 |
| Requests             | Web Development     | ✔️                 | ✔️                 | ✔️                 |
| BeautifulSoup        | Data Scraping       | ✔️                 | ✔️                 |                    |
| Scrapy               | Data Scraping       | ✔️                 | ✔️                 |                    |
| Selenium             | Data Scraping       | ✔️                 | ✔️                 |                    |
| GeoPandas            | Geospatial Analysis | ✔️                 | ✔️                 | ✔️                 |
| Shapely              | Geospatial Analysis | ✔️                 | ✔️                 |                    |
| Fiona                | Geospatial Analysis | ✔️                 | ✔️                 |                    |
| statsmodels          | Time Series Analysis| ✔️                 | ✔️                 |                    |
| Prophet              | Time Series Analysis| ✔️                 | ✔️                 |                    |
| PyCaret              | Time Series Analysis| ✔️                 | ✔️                 |                    |
```


