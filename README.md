We have established a solidity contract with this code. 
Step 1: The Solidity compiler version range for this contract is set using the pragma directive pragma solidity >=0.6.12 <0.9.0. It guarantees compatibility with Solidity versions less than 0.9.0 and greater than or equal to 0.6.12. 

Step 2: Contract Declaration: We hereby declare the MyToken contract. 

Step 3: Public Variables token_name: The name of our token is kept in this variable. This string has "Sandeep" as its original value. 
token_abbrv: The abbreviation for our token is kept in this variable. The string's initial value is "SNDP". 
total_supply :The entire supply of our token is kept in this variable. This unsigned integer has a zero initialization. 

Step 4: Mapping:Token balances are linked to addresses through this mapping. Token balances are represented by unsigned integers that are mapped to addresses. 

Step 5: Mint Function (mint): This function creates fresh tokens through minting. The address to which tokens will be minted is represented by the parameter "address" in the parameters. The number of tokens to be minted is represented by uint v_value. Functionality: Adds v_value to the overall supply. raises the a_address balance by v_value. 

Step 6: Burn Function (burn): Tokens are burned, or destroyed, via this function. The address that tokens will be burned from is represented by the parameter "address" in the parameters. The number of tokens to be burned is represented by uint _value. Functionality: Verifies if v_value is more than or equal to a_address's balance. It subtract v_value from both the total supply and the balance of a_address if the balance is sufficient. 

Finally, this article has broken down a Solidity smart contract that shows how to mint and burn a token.
