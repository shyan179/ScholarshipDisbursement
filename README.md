# ScholarshipDisbursement

### Wallet used
We are using web wallet - Metamask for this project. For this particular project version, we are using Ganache for the deployment and testing. There are 2 more versions using different testnets in other repository folders (Rinkeby and Goerli).

For more information
1. Metamask refer to this link: https://metamask.io/
2. Ganache refer to this link: https://trufflesuite.com/ganache/

### Solidity contracts
There are 3 smart contracts on this project and all of them are deployed using ganache via Remix IDE, you can use the "ScholarshipDisbursement.sol" if you want to deploy the solidity contratcs to different blockchain via remix IDE. Or you can use the addresses below on remix IDE to look at the functions.

1. Student Smart Contract Addrress: 
```
0x933d60E5F1AEff1f37Dd5792Db0cd2E0fd9157d1
```
2. Scholarship Provider Smart Contract Addrress: 
```
0x967B23d6e0DD4170ecAeA46c1Fe92D94B11F1016
```
3. University Staff Smart Contract Addrress: 
```
0xfBf63710005a304556802b4bffC018585E041cf1
```

### Run the front end in local node

##### Visual Studio Code
I use Visual Studio Code to create and edit my project. You need also need Visual Studio Code to run the local web server. You can find the latest version here: https://code.visualstudio.com/

Then download all the files in this repository and unzip any zip file and put them into a single folder in your local drive

Open the folder using visual studio code.

##### Node.js and NPM (Node Package Manager)
You need to have Node.js and NPM, which come together.

NB: Check if Node and NPM are already installed by inputting the following commands in the terminal:

```
node --version
npm --version
```
If they are installed, you will see something like this

![image](https://user-images.githubusercontent.com/99839809/192103013-2ff52a46-abe6-47dc-86f9-e581609d542b.png)

Else go to https://nodejs.org/en/ if you need to install it.

##### Running the local server
To execute the local web server. Type the below in the terminal:
```
node server.js
```

![image](https://user-images.githubusercontent.com/99839809/192103554-575e6ce7-400d-4410-acb8-58b6245d597a.png)


In your browser, go to the link below to access the frontend

http://localhost:3300




