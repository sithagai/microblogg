# microblogg

Intro:

The basic overview contains three critical components Smart-Contract, Front-End with Web3.js integration 
Blockchains are a unique solution which addresses these issues discussed before. The blockchain is fundamentally a way to provide reliability and safety by redundancy. A new way which can democratize the process of Social networking.

Microblog uses the ethereum address as a reference to the user much like a handle on Twitter to uniquely identify the user apart. Anyone with a ethereum account can join the network and post their thoughts. Every user joins the network by signing in using a username and password.Once registered the user must log-in before creating a post.

The posts are displayed in a simplified interface in real-time with no censorship possibility.

A Post contains:

Username,
Address of author,
Post data,
Data Time of the post.

Tech :

Solidity,
Truffle frameworks, 
Ganache (Local Deployment),
MetaMask(Web3 Injection into browser),
Web3.js (FrontEnd),
HTML & Bootstrap (Designing FrontEnd).


Steps :

git clone <>,
Open a browser and ensure MetaMask is set up to custom RPC http://localhost:8545,
Run Ganache,
truffle migrate --network ganache --reset,
truffle test,
truffle console,
In terminal run npm install ..

Cmd:
ganache-cli -p 8545,

truffle compile ,

truffle migrate ,

npm run dev,

reference:

https://truffleframework.com/
http://ethertweet.net/
https://github.com/yep/eth-tweet


error :
https://stackoverflow.com/questions/22475849/node-js-error-enospc

 npm dedupe

echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p

Who does it benefit?
Any believer of open and free media is a definite benefactor of this system. A whistleblower like Julian Assange might have greatly benefited by such system. This solution will not only provide a method of decentralized Social media Communication but also help create a similar better system for preservation of intellectual data and protection from censorship.
