# Assessment 2

In this Assessment, I was asked to create the following :

1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)

2. Your contract will have a mapping of addresses to balances (address => uint)

3. You will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance 
       of the “sender” address by that amount
    
4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
       It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
       and from the balance of the “sender”.
    
 5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
       to the amount that is supposed to be burned.

## Description

This smart contract contains the following :

Public Variables: These store information about the token, including its name, abbreviation, and total supply.

Mapping: This links addresses (of token holders) to their corresponding token balances.

Mint Function (mint): This function allows authorized users (who needs to be defined in a future update) to create new tokens and credit them to a specified address.

Burn Function (burn): This function enables authorized users to destroy existing tokens, reducing the total supply and their own balance.


## Authors
Bora Yaswanth Reddy
