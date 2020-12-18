# OFAT
## Long-range forecasting in feature-evolving data streams [PDF](https://doi.org/10.1016/j.knosys.2020.106405 "Downdoald the paper from here")

## Abstract
_Accurate long-range forecasting in high-dimensional feature-evolving time series is a pressing issue with multiple applications in optimal resource allocation, monitoring and budget planning. Stochastic nature of feature-evolving time series coupled with their temporal dependency pose a great challenge in their forecasting. This is because the length of input sequence (rows) may vary as data points evolve with their feature values (columns) changing. In high-dimensional feature-evolving heterogeneous time series, it is impractical to train a forecasting model per single time series across millions metrics, leave alone space required to maintain the forecasting model and evolving time series in memory for timely streaming processing. Thus this paper proposes O̲ne sketch F̲its A̲ll T̲ime series algorithm, which is a stochastic deep neural network framework to address stated problems collectively. Extensive experiments on real-life data sets and rigorous evaluation showcases that OFAT is fast, robust, accurate and superior to the state-of-the-art methods._

## ofat.py 
This file contains OFA implemetation algorithm 

## Datasets
### Check details in dataset directory
## Dependencies
1. Tensoflow 2
2. Keras 2.3.1
3. Python 3.6
4. Matplotlib 3.1.2
5. tqdm 4.44.1

# Reference
If you find this code useful in your research, please, consider citing our paper:
```
@ARTICLE{wamburakbs,
	AUTHOR = "Stephen Wambura and Jianbin Huang and He Li",
	TITLE = "Long-range Forecasting in Featute-evolving Data streams",
	JOURNAL = {Elsevier, Knowledge Based Systems},
	VOLUME = {206},
	NUMBER = {106405},
	PAGES = {},
	YEAR = {2020},
  }
```
# License
OFA is distributed under Apache 2.0 license.

Contact: Stephen Wambura (ceo@stephenwambura.com)
