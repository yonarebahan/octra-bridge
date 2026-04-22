# bridge oct to woct

**clone**
```
git clone https://github.com/yonarebahan/octra-bridge.git
```
```
cd bridge-oct
```
**install**
```
pip3 install web3 requests eth-abi pynacl
```
**Mainkan**
```
python3 octra_bridge_woct.py --amount 10 --lock-only --env-file .env
```
```
python3 octra_bridge_woct.py --tx (TXHASH) --env-file .env
```
```
python3 octra_bridge_woct.py --tx (TXHASH) --send --env-file .env
```
