## Unit 3: Ethereum | Remix IDE -English Version- 🚀

### What's this project about?

This Smart Contract contains a simple approach to read/write functions. 

Main Goal: This smart contract will allow you to store an array of Person and their favorite number. Also, to recover and search for a specific favorite number.

#### Write Functions: 

- Store: Receives as parameter the person's name and his/her favorite number. Parameters: tuple(string,uint256 

![image](https://user-images.githubusercontent.com/60369910/185639835-af995cce-4819-41be-8de3-7df79c096238.png)

#### Read Functions: 

- Retrieve: Each of the person you have entered in the Store method are saved in an array. With this method, you can enter the position of the person you need to recover. For instance, if you enter 0, you will recover the first person you entered. Then, 1 is going to be the second and so on. Return Type: tuple(string,uint256)

- SearchFavoriteNumberPerPerson: You can enter the person name you need to recover his/her favorite number. Parameters: name of the person (string). Return Type:  tuple(string,uint256)

Test Network: I used a connection to my Metamask provider. The network selected was Ropsten. 

Contract was deployed at : https://ropsten.etherscan.io/address/0x4e1b0353157700252f95b5c20d990f4a3ba71760#readContract . I have decompiled the deployed contract so you can see the full code and interact with it. 


![image](https://user-images.githubusercontent.com/60369910/185641812-2e439b60-0951-4543-af20-8d80cadf11c8.png)
