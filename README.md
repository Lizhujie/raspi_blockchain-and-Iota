# raspi_blockchain-and-Iota

## Blockchain Demo : 
    run blockchain.py in terminal and then start a new terminal and enter: 
    In the command line to post
    curl -X POST -H "Content-Type: application/json" -d '{
    "sender": "d4ee26eee15148ee92c6cd394edd974e",
    "recipient": "someone-other-address",
    "amount": 5
    }' "http://localhost:5000/transactions/new"       


    And then you can check the all information of block in http://localhost:5000/chain.
    In the end, the code is to realize the consistency of Blockchain.

## Iota Demo(based on: https://gist.github.com/huggre/a3044e6094867fe04096e0c64dc60f3b): 
    In that code, the address is seted for LED service(You can use some iota wallet to create, such as trinity). 
    If we want to use that service, we can use our iota account to send tokens to that address. When the transaction is authorized,
    You can see the number displayed in terminal turns to the number that you send to the iota address of LED service. And the LED would turn on. 
    And depend on your service time, the balance would decrease. When the balance becomes to zero, the LED would 
turn off. 
