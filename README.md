### Loop to create 10 different screen sessions and perform 1000k trxs
sudo bash -c 'for i in {1..10}; do screen -dmS wallet_$i node test.js; echo "Started session wallet_$i"; done'
```
sudo bash -c 'for i in {1..10}; do screen -dmS wallet_$i node multiple.js; echo "Started session wallet_$i"; done'
