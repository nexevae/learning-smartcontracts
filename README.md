Hello and welcome to my repository for all of my smart contracts I will be writing while going through the 
Learn Solidity, Blockchain Development, & Smart Contracts | Powered By AI - Full Course by Patrick Collins.

The first video (lessons 0-6) can be found here: 
https://www.youtube.com/watch?v=umepbfKp5rI&list=PLmgt1IrTPD0vQuG7c4wUQp_RxyRkDVvC1&index=5&t=33s

This repo is for my beginner / practice contracts I am going to do throughout the course. I will try to keep
this as updated as possible as my goal is to log the contracts I write in an effort to apply what I learned in the 
lessons with little help; kind of a knowledge check, if you will.

Enjoy!

1.a. Counter.sol
- a simple counter contract, increase/decrease by 1

1.b. CounterCondition.sol
- a "counter version 2", if you will; increase by 1, but on decreasing, it checks the count first: if 0, then you get an error

2.a. MySimpleStorage.sol
- trying my hand at writing a simple storage contract. This one had an addition/modification as I got a little comfortable with the functions and data types (uint and string); I commented out the "modification".
- First, simply wanted to store a number. After that, I figured I would play around with the string type. I quickly remembered there are additional parameters when working with strings: calldata and memory.

2.b. SimpleStorageV2.sol
- I tried my hand with mapping on this one. I wanted to take my number and person functions from the previous contract, and be able to assign them an index number, then look them up by their number (like my version of the lesson's simple storage contract).
- I had to go back over the mapping info for this one (the proper syntax for it, which parameters go where, and so on).

2.c. CryptoInvestmentStorage.sol
- this one was straight up from ChatGPT; I wanted to take the storage concept and apply it to somehing. Off the top of my head, I decided to have a crypto investment "tracker", where I can store each crypto I buy and how much my initial investment was (fake numbers, btw). This is more of a concept idea and I wanted to see how itlooked as a smart contract.
