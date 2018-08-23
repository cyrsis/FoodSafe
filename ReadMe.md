
## food safe demo


## End to end Food Safe demo

Goal
how to keep secret in the blockchain

Actor:
Producer
Supplier
Store 

1. Create a  new contract
2. Write information
3. Read Informaiton

`npm install`
`npm run dev`


# Security
read the password if you have secret phase


# Note
1. Create a new Contract for every new patch of the goods
2. Able to write information in the contract
3. Reading informaiton from blockchain

# Testing
`truffle console --network ganache`

# Javascript
`var ss`

`FoodSafe.deployed().then(function(deployed){s = deployed;});`

`ss.AddNewLocation(1000,"The productor","123")`
`ss.AddNewLocation(2000,"The supplier","123")`
`ss.AddNewLocation(3000,"The store","123")`

# Check the getter function
`ss.getLocation.call(1).then(function(retval){console.log(retval)})`
`ss.getLocation.call(2).then(function(retval){console.log(retval)})`
`ss.getLocation.call(3).then(function(retval){console.log(retval)})`

# Compile the contract in the Server (Advance userage)
``



Probably only work in private chain

since the create the new contract from the client side is not easy

Have to install solc in the server from azure

## Compile and deply contract in the server
`ssh ` from Azure
enter password
`sudo add-apt-repository ppa:ethereum/ethereum -y`

`sudo apt-get update`
`sudo apt-get install solc -y`

