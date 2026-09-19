# Friend Arena

- **Project name:** Friend Arena
- **Builder / contact:** [@JojoCE1177](https://x.com/JojoCE1177) · [Vladdtest/friends-arena](https://github.com/Vladdtest/friends-arena)
- **Category:** Token Activity
- **SDK:** FriendSDK v0.1

## What did you build?

A 1v1 garden arena where your Rare Friend buys a ticket, fights a same-generation rival over several hits, and every ticket is a simulated $RAREFRIENDS spend that the UI splits into burn + active-weight rewards.

## How does it use Rare Friends?

You play as your own hardwired Generations NFT. The SDK verifies the wallet and Friend. The original walking sprite is the fighter; the rival is the same canonical art, mirrored, matched by generation and nearby tier/weight.

## Source

https://github.com/Vladdtest/friends-arena · FriendSDK v0.1

## Playable demo / how to run

No hosted demo. Node.js 22+:

```sh
git clone https://github.com/spokesz/friendsdk.git
cd friendsdk
git clone https://github.com/Vladdtest/friends-arena.git games/friend-arena
npm ci
npm run dev:game -- games/friend-arena
