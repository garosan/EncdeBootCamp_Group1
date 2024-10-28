
@Munzy 3.0, @mitzsuyi, @alienrobot, @codewiz42 

https://sepolia.etherscan.io/address/0xe718a71af928cfcba89552699eb69f40da94a43c

Contract Address - 0xe718a71af928cfcba89552699eb69f40da94a43c

- Initial HelloWorld text change to “Hello from Munaiz”
- Initial HelloWorld text change to “Hello from Ty”
- Initial HelloWorld text change to “Transferring to Rodolphe”
- Initial HelloWorld text change to “Hello from Rodolphe”
- Initial HelloWorld text change to “update from mitzsuyi”


** We found that whenever a non-owner tried to make changes to the state, Remix ID just froze and started to hang. We never received an require Error “Caller is not the owner” in remix ID. 

## Personal Submission by @garosan

So I wasn't able to jump on the call with the guys but spoke to them later, unfortunately I wasn't able to change the contract owner of course, so **I deployed my own contract**:

[Contract deployed by Garosan link](https://sepolia.etherscan.io/address/0xb8ed2f351e74ec64e35cefb4e3465ed41e1e47e3)

- Then I changed the text to 'Hello from Garo Sanchez wallet 1'
- Then I transfered ownership to my wallet #2
- Then I changed the text to 'Hello from Garo Sanchez wallet 2'

Things I learned:

- If I try to call setText() or transferOwnership() without being the owner the transactions just hangs there
- For some reason when I deployed my contract it got verified automatically, my colleagues' contract didn't.
- I learned that to interact with a deployed contract I need the ABI or the exact source code.
