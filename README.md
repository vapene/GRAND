# grand
This is a Pytorch implementation of paper: Graph Random Neural Network

## Requirements
* Python 3.7.3
* Please install other pakeages by 
``` pip install -r requirements.txt```

## Usage Example
* Running one trial on Cora:
```sh run_cora.sh ```
* Running 100 trials with random initializations on Cora:
```sh run100_cora.sh ```
* Calculating the average accuracy of 100 trails on Cora:
```python result_100run.py --cora ```
