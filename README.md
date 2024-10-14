# Metacrfters Solidity Project 1
 A Submission for the Metacrafters Solidity Module Project
 # Description
 This project is a sample demonstration of the basics of developing a smart contract using solidity. This smart contract is a basic contract that demonstrates the usage of variables, mapping, and functions. The basic contract has three variables. A variable string for "tokenName", which is the name of a sample cryptocurrency token. In my case, I used "ACoin" as the name here. Next is the variable string for the abbreviation variable "tokenAbbrv" which is "ACN" here. Finally, there is a variable for the total supply of the given sample coin denoted as "totalSupply". 
 There is also a mapping that connects an ETH Address to an unsigned integer variable, which is then treated as the balance of that address. It is also called "balances".
 # Functions
  The smart contract has two functions. mint() and burn(). Mint and Burn are simple functions that take two parameters. The first parameter is the ETH Address of the requesting individual, and the amount being requested by that address.
  mint() adds the amount of tokens requested by the user and adds it to both the totalSupply, and the balances variable of that user. burn() on the other hand takes away the input amount from the address' balance, and also removes the same from the totalSupply.
