# blockchain2john

This python 3 script convert wallet file into supported crypto wallet HEX string wallet.aes.json (blockchain.info v1,v2,v3 wallet backup) / wallet.dat (Bitcoin Core wallet)

```python
# convert wallet.aes.json (blockchain.info v1,v2,v3 wallet backup) or wallet.dat (Bitcoin Core wallet) into hash value for safe delivery
python blockchain2john.py --base64 wallet.aes.json > wallet.hash
```
