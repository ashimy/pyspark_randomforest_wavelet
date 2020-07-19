# pyspark_randomforest_wavelet

wavelet tranformation and　anomaly detection by pyspark randomforest


1. install pyspark env by docker


```{#lst:id sh caption="実行結果"}
$ docker pull jupyter/pyspark-notebook
```

2.processing flow

-acceleration wavelet transformation（acceleration frequency_wavelet trans form.ipynb）

-separate frequency band to create feature(acceleration frequency_wavelet trans form.ipynb)

-anomalydetection by randomforest pyspark (randamforest_pyspark.ipynb)

  -pipeline (feature create →standalization　→randomfforest ) (randamforest_pyspark.ipynb)


<wavelet transformation image>
![wavelet transform](https://github.com/ashimy/pyspark_randomforest_wavelet/blob/master/wavelet%20transform.png "sample")
