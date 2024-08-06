# Proveably Random Raffle Contracts

## About

This code is to create a sample smart contract for a random lottery.

## What we want it to do?

1. Users can enter by paying for a ticket
   1. The ticket fees are going to go to the winner during the draw
2. After X period of time, a random winner is selected
   1. And this will be done programatically
3. Using Chainlink VRF and Chainlink Automation
   1. Chainlink VRF -> randomness and secure off-chain enviroment
   2. Chainlink Automation -> time-based trigger

## Tests!

1. Write some deploy scripts
2. Write some tests
   1. Work on a local chain
   2. Test on a testnet
   3. Test on a mainnet
