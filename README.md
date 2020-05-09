# Blockchain-Testnet

# Homework Responses 

### 1. I started the network by launching puppeth in my terminal.  Once you launching puppeth, you are required to set a network name.  In this case tbank.  The major difference between setting up this network and the ones we did in class, was our network was a Proof of Authority network.  This was different than class as 1. We had to set up the nodes prior to the network.  2. Calling the nodes were different as it required a rpc flag, address as well as password to access the node.  Unlike the proof of network we ran in class, this took much longer to mine the blocks on the blockhain.  

### 2. As mentioned above accessing the node was very different from a proof of work network vs. a proof od authority.  Whereas with a proof of network you only had to use the following command: ./geth --datadir node1 --mine --minerthreads 1.  Whereas with a proof of authority it is more complex as it adds an unlock, password and an allow insecure unlock as follows: ./geth --datadir node1 --rpc --mine --unlock "Address" --password "Password File" --allow-insecure-unlock. 

### 3. What is a Proof of Authority network? 
### A proof of authority network is a consensus algorithm which leverages the value of an identity.  While this is probably the best of the three consensus algorithms, the drawback is it takes longer to mine the block as it requires more energy.  We see this as it took longer to run our proof of authority algorithm than it did our proof of work during class. 

### As mentioned above, the proof of authority algorithm was slightly different as it require the public key, and password to access the block in the CL function.  

### 4. I connected to MyCrypto Wallet at the end.  Once the two nodes were interacting with one another you would connect back to the MyCypto Wallet by adding a new custom node.  Through that, you would call the Node by the network system name, set the currency to custom and input the chain id.  Once you did that, you would go back to the keystore file and access the new mined ETH through the keystore files saved in each node.  Once you got into the wallet you would have to add the address of the second node to begin transacting between the two nodes.  Unfortauntely I developed issues as it said my internet connection was poor.  please find the screenshot to see such evidence.  However, you can see under the wallet address that it did mine properly as there was plenty of ETH in the wallet.   