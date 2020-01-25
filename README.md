# n26-csv2ofx-ynab
Convert [N26](https://n26.com) CSV to OFX for [YNAB](https://www.youneedabudget.com)

### Setup
```
pip install notebook meza csv2ofx
```

### Usage
Place `n26-csv-transactions.csv` in your working directory and run:

```
jupyter nbconvert --to notebook --inplace --execute convert.ipynb
```

### Acknowledgements
This is a fork of the GitHub Gist [ofxconverter.ipynb](https://gist.github.com/josephfinlayson/068691178b4441c6276bec014bbdb926) by [Joseph Finlayson](https://gist.github.com/josephfinlayson) adapted to my needs for N26 Germany.