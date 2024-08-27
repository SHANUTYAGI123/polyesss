
# Polyess

Polyess is one stop for all chess lovers and web3 enthusiasts. It is a combination of decentralized gaming, NFT marketplaces, and the classic and one of the oldest games, "Chess". It gives anyone a platform to not only get interested in chess but also blockchain and Web3. Our tech stack is so extensive that users have everything they could wish for in one site.

## Features
- 💸 **In-Game Currency**: Polyess is a play-to-earn game, so we created an in-game currency, HT token, which you can buy and exchange for Matic.
- 📈📉 **NFT-Marketplace**: We built an NFT marketplace and handcrafted 35 awesome NFTs of legendary and famous chess players. (Marketplace is available on App and Web)
- ⚔️🗡 **Visual NFT Battle**: Those NFTs are not just art; they are avatars in games of NFT staking, where you can use them as the king, giving you the personalized experience you always wanted.
- ♟♟ **3 Game Modes**: Free-to-play, Token Betting, and NFT Staking. Bet on your wits with your Hess tokens or NFTs. The winner takes all tokens or NFTs. Stake NFTs and take part in exclusive NFT battles with your friends' NFTs too.
- 🪧🎯 **Leaderboard**: It promotes higher engagement because the more games you play, the better you get, and the higher your rank.
- 👨🏼‍⚕️🧑🏽‍🎓 **User Profile**: You get a user profile with all the stats like games won, lost, NFTs owned, Hess Tokens in your account, and your username.
- 📹🕹 **Video Chat**: While playing, you can video chat with your opponent, which makes it more fun and gives a better experience.

And we haven't even talked about the user experience and graphic experience of the website and Android app.


## Installation

### 1.Run the development console

```bash
truffle develop
```
### 2.Compile and migrate the smart contracts. Note inside the development console we don't preface commands with truffle.

```bash
compile
migrate
```

### 3.In the client directory, we run the React app. Smart contract changes must be manually recompiled and migrated.
```bash
// in another terminal (i.e. not in the truffle develop prompt)
cd client
npm run start
```
### 4.Truffle can run tests written in Solidity or JavaScript against your smart contracts. Note the command varies slightly if you're in or outside of the development console.
```bash
// inside the development console.
test

// outside the development console..
truffle test
```

### 5.Jest is included for testing React components. Compile your contracts before running Jest, or you may receive some file not found errors.
```bash
// ensure you are inside the client directory when running this
npm run test
```
### 6.To build the application for production, use the build script. A production build will be in the client/build folder.
```bash
// ensure you are inside the client directory when running this
npm run build
```


