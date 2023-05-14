# Fitcoin


Developed a Blockchain terminal application using GoLang and BadgerDB.


### Transactions and UTXO's

A transaction is made from one address to another, and it consists of inputs and outputs. If you are making a transaction to a friend, the input addresses are of yours, meaning you own the private keys associated with those addresses, and are able to sign the transaction with it. Each input is a reference to a previous transaction where you have received your current funds, they are known as unspent transaction outputs, UTXOs for short. Once they are used as input to a transaction, they can no longer be spent again.

The outputs are your friend’s address, and possibly your own address to receive change, as UTXO inputs has to be spent in its entirety, think of each UTXO as a piece of cash, to spend it you need to give the cashier the entire cash and receive change for it.

Steps:

1. Clone Repo

2.
```
go run main.go
```
This will display menu of commands!
![preview](Capture.JPG)
