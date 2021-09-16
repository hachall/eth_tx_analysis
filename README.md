## Crypto Transaction Analysis
Transaction analysis of crypto economic systems using Graph Neural Networks, particularly for classifying fraudulent activity amongst a sea of innocuous transactions.

### Requirements
 - DGL: https://www.dgl.ai
 - Pytorch Geometric: https://pytorch-geometric.readthedocs.io/en/latest/
 - NetworkX
 - MatplotLib
 - Numpy
 - Pandas
 - Python standard library (csv, dateutil etc.)

### Data
- **Labelled Ethereum Addresses**:
for a comprehensive set of 20,000 labelled Ethereum addresses labelled by illicit/licit, by address type (Wallet vs Smart Contract) and for entities (Exchanges, miners, tokens etc.) visit https://www.kaggle.com/hamishhall/labelled-ethereum-addresses.
- **Bitcoin Transactions**:
Get the elliptic dataset from here: https://www.kaggle.com/ellipticco/elliptic-data-set/. This is a feature rich dataset of fraudulent, verified and unfledged Bitcoin transactions.
- **Ethereum Transactions**:
Run eth/tx_by_block.ipynb to gather  and save to csv all transactions between a *start* and *end* date
Or run eth/tx_by_neighborhood.ipynb to gather a focused set of transactions around a central set of nodes.
- **EOS Transactions**:
The EOS transactions and labels come from a private dataset of ERC20 token transfers, available on request.

### Toolkit
