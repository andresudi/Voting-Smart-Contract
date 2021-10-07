# Voting System Smart Contract
Electronic voting systems have replaced paper-based systems, but even now, people doubt the
voting system’s ability to secure the data and defend against any attacks. The blockchain-based
system can ensure transparent and publicly verifiable elections in the country. If implemented
successfully, voting can be done using a mobile application that is attached to a blockchain
system.

## Features
```
● The owner of the contract can input one or more choices to be voted by people.
● The owner of the contract can specify the start time and end time for the voting period.
● A voter can vote for any choices set by the contract owner during the voting period.
● A voter can only vote once during the voting period.
● The smart contract can return the number of votes for each choice.
● Anyone can set up a voting system through the same smart contract.
```

## Tools
```
Remix IDE 
https://remix.ethereum.org/
```
## How To Deploy

1. Compile the code 
    ![compile](https://github.com/andresudi/Voting-Smart-Contract/blob/master/assets/compile.png)

2. Select the smart contract owner address
    ![select owner](https://github.com/andresudi/Voting-Smart-Contract/blob/master/assets/select-owner-address.png)

3. Input candidates in Deploy button and then pressed Deploy
    ```
    The owner of the contract can input one or more choices to be voted by people.
    ```
    ![deploy](https://github.com/andresudi/Voting-Smart-Contract/blob/master/assets/deploy.png)

## How To Test 

1. After deploy the smart contract pressed startVote button 
    ```
    The owner of the contract can specify the start time and end time for the voting period.
    ```
    ![startVote](https://github.com/andresudi/Voting-Smart-Contract/blob/master/assets/owner-pressed-startvote.png)

2. Change to another address, and copy it into giveRightToVote button
    ```
    ● A voter can vote for any choices set by the contract owner during the voting period.
    ● A voter can only vote once during the voting period.
    ```
    ![otherAddress](https://github.com/andresudi/Voting-Smart-Contract/blob/master/assets/changer-address.png)

3. Change back to owner address to give the right vote to other account
    ```
    notes: only owner of the contract can give right to vote
    ```
    ![giveRight](https://github.com/andresudi/Voting-Smart-Contract/blob/master/assets/giveRighttoVote-to-other-account.png)

4. Change back to address that already have right to vote
    ![otherAcc](https://github.com/andresudi/Voting-Smart-Contract/blob/master/assets/chnageback-to-RightAddress-to-vote.png)

5. Input index of candidate and click vote
    ![vote](https://github.com/andresudi/Voting-Smart-Contract/blob/master/assets/input-index-in-vote-func.png)

6. Repeat step from 2-5 to give other account to have right and vote
    ![o](https://github.com/andresudi/Voting-Smart-Contract/blob/master/assets/create-another-candidate-from-other-account.png)

7. Change back to owner address to end the voting period
    ![end](https://github.com/andresudi/Voting-Smart-Contract/blob/master/assets/changebackto-owner-account-pressed-endVote.png)

8. Pressed WinningCandidate button 
    ![winner](https://github.com/andresudi/Voting-Smart-Contract/blob/master/assets/pressedWinningCandidate.png)

9. Input index in candidates button to check the score
    ```
    ● The smart contract can return the number of votes for each choice.
    ```
    ![checkWinner](https://github.com/andresudi/Voting-Smart-Contract/blob/master/assets/input-index-candidate-to-see-the-score.png)

10. Change to other account so anyone can set up a voting system through the same smart contract.
    ![anyone](https://github.com/andresudi/Voting-Smart-Contract/blob/master/assets/change-account-if-another-user-want-to-create-another-proposal.png)

11. Input candidates in addCandidates button
