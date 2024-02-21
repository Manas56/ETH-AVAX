# OwnershipContract
OwnershipContract is a simple Ethereum smart contract written in Solidity. It demonstrates ownership functionality by restricting access to certain functions based on the contract owner.

# Contract Functions
### constructor()
Initializes the contract owner to the address of the account that deployed the contract.

### onlyOwner()
Modifier function that restricts access to only the owner of the contract.
Throws a require error if the caller is not the owner.

### onwerHere()
View function that checks if the caller is the owner.
Uses the revert statement to revert the transaction if the caller is not the owner.

### Owner()
View function that checks if the caller is the owner.
Uses the assert statement to ensure that the caller is the owner.

# Usage
Deploy the contract to an Ethereum blockchain network.
The deploying account becomes the owner of the contract.
Call the onlyOwner function to verify ownership.
Call the onwerHere function to verify ownership using revert.
Call the Owner function to verify ownership using assert.

## License

This project is licensed under Manas Mamgain. Contact [mailto:manasmamgain19@gmail.com] .
