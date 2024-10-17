### Loop to create 10 different screen sessions
sudo bash -c 'for i in {1..10}; do screen -dmS wallet_$i node test.js; echo "Started session wallet_$i"; done'
