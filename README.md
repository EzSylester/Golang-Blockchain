<h1 align="center">Welcome to Go Building a Blockchain in Go tutorial Walkthrough 👋</h1>

<p>

  <img alt="Part" src="https://img.shields.io/badge/version-01-blue.svg?cacheSeconds=2592000" />

</p>

### 🏠 [Homepage](https://www.youtube.com/watch?v=mYlHT9bB6OE&t=759s)

## Author
👤 ** Tensor Programming **

## Reviewer
👤 ** monkrus **

## Show your support

Give a ⭐️ if this project helped you!
***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_


## Part 1
```sh

1. go mod init github.com/monkrus/golang-blockchain.git 

2. Create a Block struct (Hash, Data, PrevHash)

3. Write a method to create a hash based on the previous hash.

3. We join the 2-dimensional array into one

4. Create an actual hash on info

5. Take created hash and push it into the hash field of the block
   NOTE! [:] is a slice referencing to the whole array)

6. NOTE! SHA256 is really simple comparing to the real way to calculate a hash in the blockchain 

7. Write a function to create an actual block

8. Create a blockchain type

9. Write a method to add block to the chain
- create a previous block
- create a new block
- append new block

10. Write a function to create a genesis block

11. Write a function to initialize blockchain 
- create an array of blocks using genesis block

12. Put functions into the main function
- intialization, adding blocks etc.

13. Run a for loop to see the blockchain

13. RUN go run main.go

```
## Part 2
```sh

1. Clean up: 
- create  `blockchain` folder with `block.go` inside of it
- rename `package main` into `package blockchain`
- make `blocks` field public by replacing it with `Blocks`
- add `github.com/monkrus/golang-blockchain` to import in `main.go`
- please note `main.go` will now have less lines of code

2. Create proof.go

3. Set up difficulty

4. Create ProofOfWork struct

5. Create function NewProof
- create a target 
- NOTE!  One of our hashes has 256 bytes 
- NOTE! left shift is the same as multiplication by 2
- << is used for "times two" and >> is for "divided by two"

6. Create a ToHex utility function

7. Modify CreateBlock function

8. Delete DeriveHash function

9. Create Validate method

10. Add POW to main.go
```

