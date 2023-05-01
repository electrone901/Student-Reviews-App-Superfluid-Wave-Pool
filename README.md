## Project Name:`Rate My Professor Web 3`

<br/>
![HomePage](https://raw.githubusercontent.com/marcialarturo/Student-Reviews-App/main/preview.png)

# Project Description:

Rate My Professor Web 3 is an educational site where students evaluate, rate, and review teachers and courses. It allows users to send and receive stream payments and donations.

It allows students to create payment streams for the class during the semester instead of paying upfront the whole amount. With Rate My Professor Web 3 students can cancel their Superfluid stream during the semester if they no longer like the direction of the class or if they want to drop out or something changed. The benefit of this is that professors are kept accountable and students have more control over their money and education.

Students can rate their professor in the following categories:

- Effective
- Integrity
- Empathy
- Respect
- Determination
- Homework

This rating system keeps accountable professors and documents them on the chain.


Students can also learn and read more about classes before they commit or register. This will help students save thousands of dollars and time.

Furthermore, students can share class notes, labs, terms reviews, and more. Class notes creators can get tips from sharing their notes and students can add a new class that doesn’t exist on the app or rate one that already exists for a chance of winning NFTs.

Users can search for teachers by name or choose a department and rate its teachers or read reviews left by other students.
If you have ever attended a class taught by a difficult teacher, you know that his personality and skills can impact your school performance. But, by doing some research, you can set yourself up for success and increase your odds of getting a good grade before you ever start.

In the future, we would like to add functionality for these NFTs to be used as a credit to take a class for free and more ways for students to work together. As well as chat functionality for the class to communicate with other students and the instructor.

<br/>

# How Rate My Professor App uses IPFS

Rate My Professor App uses IPFS NFTStorage to store Professors’ names, job positions, and professors' past performance. IPFS is also used to store class NFTs, names, class details, class events, and class materials and notes. For reviews, IPFS saves all the reviews, tags, class difficulty, class quality, and ratings in a decentralized way.

For every single endpoint, we return an NFTStorage hash that gets appended to the next IPFS object and it is saved on the smart contract. Then we populate our front end by calling our contract that returns all IPFS cids, and all data needed.

IPFS makes our app a fully decentralized app with an immutable chain of events that allows public and accessible data to the masses.

# Live Demo

### It is responsive website, for best view use a large monitor

https://student-reviews.netlify.app/#/

# Video Link
https://youtu.be/MpmFhDF15fI


# How It's Made

This app makes use of the following software:

- `Polygon Network` enables our application to be a scalable and secure platform with light-speed transactions. We have successfully deployed to the Polygon Test Network at contract address:`0xB61B5Ff6930EB40734d480C4e0b5312702673ED0`

- `Skale Network` enables our application to be a scalable and secure platform with light-speed transactions. We have successfully deployed to the Skale Network at contract address: `0x15036E33e8E8f706fd77A1aC550d28FD58432c1B`

- `IPFS NFTStorage`facilitated the storage of NFTS, details of the class, and metadata of every event class. We are also, saving all the reviews, tags, class difficulty, class quality, and ratings.

* `SuperFluid` enables stream payment for donations and rewards for our application

* `WorldCoin` makes sure users create only one event for a class per person to avoid any scams.

* `Xmtp` allows donators to chat with organizers and members of the groups.

* `Livepeer` facilitated the process of meeting other students from a specific class and questions about lectures.

* `Ethereum Name Service (ENS)` allows donators to look up Ethereum Name Service and convert them to wallet addresses.

- `NFTPort` smooths the path of the minting and donating process and eliminates the high transaction fees. Our users will not pay anything for donating NFTs or minting.
- `Solidity` for the smart contract.
- `OpenZeppelin ERC721` we use the ERC721 template for faster development of our smart contract.
- `Hardhat` for local blockchain development.
- `React Js, Material-ui, Web3` React Js for the frontend, Material-ui, and Web3 to connect to the blockchain.

- `Mumbai Polygon Network` enables our application to be a scalable platform with fast transactions. We deployed our app on the Mumbai Network. Contract Address: `0x2DD669b696Eb8B9D13151517ffb1acCBc88dCFC8`
  <br/><br/>

## Challenges we ran into

We run into some complications with the Smart contracts and the Safe SDK it took us longer than expected. Especially, creating Superfluis streams.

Accomplishments that we're proud of
We are proud of the final MVP and how our project went from an idea to a demo

What we learned
We learned to work with the Safe SDK

What's next
Post updates Upon registration, add a point system for users.

# Deployed Address

Contract Deployed Matic: 0x2DD669b696Eb8B9D13151517ffb1acCBc88dCFC8
Contract Deployed Skale: 0x15036E33e8E8f706fd77A1aC550d28FD58432c1B

Dashboard for streams: https://app.superfluid.finance/
