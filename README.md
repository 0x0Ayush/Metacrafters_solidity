# BabyDoge Token Contract [this is just for Project not affilated with real baby doge] 

#This contract represents the BabyDoge token, an ERC-20 compatible token deployed on the EVM blockchain. It allows minting and burning of tokens.

**Public Variables**

`tokenName`: A string variable representing the name of the token.
`tokenAbbrv`: A string variable representing the symbol or abbreviation of the token.
`totalSupply`: An unsigned integer variable representing the maximum supply of the token.

**Mapping Variable**

`balances:` A mapping variable that maps addresses to their respective token balances.

**Functions**

`mint` : function mint(address _address, uint _value) public;

This function allows the contract owner to mint new tokens and assign them to a specified address. It takes two parameters:

`_address:` The address to which the minted tokens will be assigned.
`_value:` The amount of tokens to be minted and assigned.
The function increases the totalSupply by the specified `_value` and updates the balance of the `_address` by adding the minted tokens.

`burn` : function burn(address _address, uint _value) public;

This function allows the contract owner to burn existing tokens from a specified address. It takes two parameters:

`_address:` The address from which tokens will be burned.
`_value:` The amount of tokens to be burned.

The function checks if the _address has a sufficient balance of tokens to burn. If so, it decreases the totalSupply by the specified `_value` and updates the balance of the `_address` by subtracting the burned tokens.

**Once Done :** Deploy it though : https://remix.ethereum.org/

To verify contract address head over to Explorer of that chain in this case its : https://goerli.etherscan.io/

Also We can add the token to metamask ! wallet and use it as We want Thanks :)

