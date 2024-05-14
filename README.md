# ERC-20-Backend
ERC-20 Backend

<p>This repository hosts a smart contract to create and mint a custom ERC-20 token. It works in conjuction with a <a href="https://github.com/thelearner411/ERC-20-Frontend" target="_blank">frontend application</a> that executes the relevant smart contract functions.</p>

## Instructions for running this contract
<p>Install <a href="https://metamask.io/download/" target="_blank">MetaMask</a> in your browser.</p>
<p>Install <a href="https://archive.trufflesuite.com/ganache/" target="_blank">Ganache</a>.</p>
<p>In MetaMask, import an account from your local Ganache</p>.
<p>Launch Ganache with the Quickstart option.</p>
<p>Open <a href="https://remix.ethereum.org/" target="_blank">Remix</a> in your browser. Connect to the DGIT plugin. In the GitHub settings tab, you will be required to set your GitHub email, username and token.</p> 
<p>Clone a fork of this <a href="https://github.com/thelearner411/ERC-20-Backend" target="_blank">repository</a> into your environment.</p>
<p>In Remix, set the environment to Dev - Ganache Provider. Ensure that the host and port match those of your local Ganache.</p>
<p>Compile the EthereumTrove.sol contract. If you have issues compiling the contract, you might need to change the EVM version (london might work).</p>
<p>Before deploying, set the initial contract address to that ganache account address imported into MetaMask.</p>
<p>Copy the contract address and contract ABI which you will need to execute the contract in the <a href="https://github.com/thelearner411/ERC-20-Frontend" target="_blank">frontend</a> part of this application.</p>