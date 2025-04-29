This is a project on decentralized voting application.

To run this project, follow the below mentioned steps.

- In the root directory, run the following command:
- npm install

- Connect to Sepolia Testnet in Metamask.
- Ensure that you have some Sepolia Eth. If you don't, get it from google sepolia faucet.
- In the same browser:
  - Copy Voting.sol to RemixIDE.
  - Compile the contract.
  - Copy the ABI key and paste it into the script.js at const contractABI = <Paste-your-contract-ABI-here>;
  - Deploy it using Injected-Provider Metamask.
  - Under the Deployed Contracts tab, copy the contract address and paste it in script.js at const contractAddress = "Paste-your-contract-address-here";
- Save script.js.
- In the terminal, run npx parcel index.html.
- Now, go back to the browser at the provided url.
- Connect the wallet from the same address that you deployed the contract. You are the owner of the voting instance.
- You can start the voting, register voters using their account address, and add candidates using their names.
- Change the account in metamask to the registered voter.
- Connect the wallet. Now, you can vote for the candidate of your choice.
- Once the owner finishes the voting, the final votes can be seen.
