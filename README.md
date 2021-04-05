# Bitcoin_Rasomware

This project is aim to classify if a bitcoin transaction belongs to a family of Ransomware or not, by using the following dataset. The EDA and model classification is done using R (bitcoin_r.Rmd)

## Dataset

https://archive.ics.uci.edu/ml/datasets/BitcoinHeistRansomwareAddressDataset

The dataset shows daily transaction of Bitcoin from 2009 January to 2018 December.

Features
address: Bitcoin address.
Date data is given by year and day of the year 
length: quantifies mixing rounds on Bitcoin
weight: quantifies the merge behaviour 
count: quantifies the merge pattern
looped: count how many transaction split their coins, move these coins in the network by using different paths or merge them in a single address.
neighbors:
income: Integer. Satoshi amount (1 bitcoin = 100 million satoshis).
label:Name of the ransomware family or white if it's not related to a ransomware

