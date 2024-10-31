### Loop to create 10 different screen sessions and perform 1000k trxs
```
git clone https://github.com/prettyanita348/unitszero_bot.git
```
for 1k trx on multiple screens
```
sudo bash -c 'for i in {1..10}; do screen -dmS wallet_$i node test.js; echo "Started session wallet_$i"; done'
```
for 100 trx across all privatekeys
```
sudo bash -c 'for i in {1..10}; do screen -dmS wallet_$i node multiple.js; echo "Started session wallet_$i"; done'
