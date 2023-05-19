# datascience-101
Unstructured testing of ideas within Data Science 

## Python data processing  

An ex-colleague decided to test a few Python data processing libraries, with a variation of data size to figure out when to use what. 
He evaluated Pandas, Apache Spark and Polars https://betterprogramming.pub/pandas-spark-and-polars-when-to-use-which-f4e85d909c6f

### Pythin libraries in a broader perspective 

```less
| Library/Package      | Tool Type             | Small Data Sets    | Medium Data Sets   | Large Data Sets    |
|----------------------|-----------------------|--------------------|--------------------|--------------------|
| pandas               | Data Manipulation     | &#10004;           | &#10004;           |                    |
| polars               | Data Manipulation     | &#10004;           | &#10004;           |                    |
| NumPy                | Scientific Computing  | &#10004;           | &#10004;           | &#10004;           |
| Dask                 | Distributed Computing |                    | &#10004;           | &#10004;           |
| Spark (PySpark)      | Distributed Computing |                    |                    | &#10004;           |
| scikit-learn         | Machine Learning      | &#10004;           | &#10004;           | &#10004;           |
| TensorFlow           | Machine Learning      | &#10004;           | &#10004;           | &#10004;           |
| PyTorch              | Machine Learning      | &#10004;           | &#10004;           | &#10004;           |
| Keras                | Machine Learning      | &#10004;           | &#10004;           | &#10004;           |
| XGBoost              | Machine Learning      | &#10004;           | &#10004;           | &#10004;           |
| LightGBM             | Machine Learning      | &#10004;           | &#10004;           | &#10004;           |
| Matplotlib           | Data Visualization    | &#10004;           | &#10004;           |                    |
| Seaborn              | Data Visualization    | &#10004;           | &#10004;           |                    |
| Plotly               | Data Visualization    |                    | &#10004;           | &#10004;           |
| Bokeh                | Data Visualization    |                    | &#10004;           |                    |
| OpenCV               | Image/Video Processing| &#10004;           | &#10004;           |                    |
| scikit-image         | Image/Video Processing| &#10004;           | &#10004;           |                    |
| Pillow               | Image/Video Processing| &#10004;           | &#10004;           |                    |
| NLTK                 | Natural Language Processing| &#10004;     | &#10004;           |                    |
| SpaCy                | Natural Language Processing| &#10004;     | &#10004;           |                    |
| Gensim               | Natural Language Processing| &#10004;     | &#10004;           |                    |
| Flask                | Web Development       | &#10004;           | &#10004;           | &#10004;           |
| Django               | Web Development       | &#10004;           | &#10004;           | &#10004;           |
| FastAPI              | Web Development       | &#10004;           | &#10004;           | &#10004;           |
| Requests             | Web Development       | &#10004;           | &#10004;           | &#10004;           |
| BeautifulSoup        | Data Scraping         | &#10004;           | &#10004;           |                    |
| Scrapy               | Data Scraping         | &#10004;           | &#10004;           |                    |
| Selenium             | Data Scraping         | &#10004;           | &#10004;           |                    |
| GeoPandas            | Geospatial Analysis   | &#10004;           | &#10004;

```


