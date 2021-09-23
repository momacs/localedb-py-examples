# localedb-py Examples

Usage examples for the [localedb-py package](https://github.com/momacs/localedb_py).


## Notebooks

The following computational notebooks demonstrate the usage and capabilities of the package:
- [Data Access](https://github.com/momacs/localedb-py/blob/master/notebooks/01-data-access.ipynb)
- [Multivariate Time Series Clustering](https://github.com/momacs/localedb-py/blob/master/notebooks/02-mvts-cluster.ipynb)
- [Multivariate Time Series Clustering (Continuous Wavelet Transform)](https://github.com/momacs/localedb-py/blob/master/notebooks/03-mvts-cluster-cwt.ipynb)
- [Multivariate Time Series Clustering (Mapping)](https://github.com/momacs/localedb-py/blob/master/notebooks/04-mvts-cluster-map.ipynb)
- [Multivariate Time Series Clustering (Distance Matrices)](https://github.com/momacs/localedb-py/blob/master/notebooks/05-mvts-cluster-dist-mat.ipynb)
- [Multivariate Time Series Clustering (Performance Evaluation)](https://github.com/momacs/localedb-py/blob/master/notebooks/06-mvts-cluster-perf-eval.ipynb)


## Multivariate Time Series Clustering of Covid-19 Disease Dynamics

Below is a brief narrative that offers a quick look at a few results we discuss in some of the notebooks listed above.

#### 1. We cluster the 67 counties of the state of Pennsylvania by Covid-19 disease dynamics (specifically, the number of confirmed cases and the number of deaths, smoothed and standardized)

![Alt text](brief-narrative/01-c19-mvts-cluster-pa.png?raw=true)

#### 2. We keep the same cluster assignments, but plot differenced dynamics (also smoothed)

![Alt text](brief-narrative/02-c19-mvts-cluster-diff-pa.png?raw=true)

#### 3. We map the clusters

![Alt text](brief-narrative/03-c19-mvts-cluster-pa-map.png?raw=true)

#### 4. We compute the Continuous Wavelet Transform (CWT) of the standardized number of confirmed Covid-19 cases in the Allegheny County, PA

![Alt text](brief-narrative/04-c19-cwt.png?raw=true)

#### 5. We visualize distance matrices computed using five different distance measures; the distances are among multivariate disease dynamics in counties of five states

![Alt text](brief-narrative/05-c19-dist-mat-5-states.png?raw=true)

#### 6. We plot histograms of those distances

![Alt text](brief-narrative/06-c19-dist-mat-hist-5-states.png?raw=true)

#### 7. We evaluate clustering performance across several distance measures, clustering algorithms, and datasets using the adjusted Rand index (ARI)

![Alt text](brief-narrative/07-cluster-perf-eval.png?raw=true)


## License

This project is licensed under the [BSD License](LICENSE.md).
