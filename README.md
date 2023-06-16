# SolidityAssessment
### Executing program
To run this program, you need to Remix and you can access this by searching https://remix.ethereum.org/.
you can see the Pragma Solidity which means it enable  the compiler features. 
By creating a new file, you need to click File Explorer on the side bar. Add a file with .sol extension. 
The contract will include public variables that will contain information about your token (Token Name, Token Abbrv., Total Supply).
Addresses will be mapped to balances in your contract (address => uint).
There will be a mint function with two parameters: an address and a value. 
The function then multiplies that number by the whole supply and multiplies it by the balance of the "sender" address.

### Compile Code
by compiling it, you need to click on the side bar the Solidity Compiler. Click the auto compile and click the compile Token.sol.

### Deploy & Run
Click the Deploy & Run transactions below the Solidity Compiler that you'll see on the side bar. Copy the address that you can see on account. 
At Deploy & Run transactions you'll see environment, account, gas limit, value, and the contract. 

The contract tab, you see the token.sol and deploy it. After deploying it, you can see at the output the green check means it works. 
Below is 'deployed contracts' click that and paste the address you've copied before and paste it to 'burn' and 'mint' section. You can add value and click transact.
