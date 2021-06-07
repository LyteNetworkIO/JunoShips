# Bitcoinships

A peer-to-peer monetized multiplayer online Battleship game

## Hello, Judges!

Thank you for considering this entry!

First things first, connectivity with peers across the web was inconsistent in my test. 

However, I did manage to get the app to run on two different computers side by side. 

Here's a demo:

TODO: Add video demo

It does work through websockets locally. You can test it by opening two browser windows on your computer.

And you can play with a peer, by using two screens and sitting across from each other... 

...or by placing a visual barrier such as a piece of cardboard between two web browser tabs on one screen! :D

At first I thought it was unfortunate that my newness to working with websockets or whatever the connectivity issue is, prohibited the unleashing of gameplay on the World Wide Web immediately following the hackathon.

But then I realized that it would be irresponsible of me to release Bitcoinships to the public without a security audit, or at least a code review by someone experienced with websockets and multiplayer JavaScript games.

Because there are 5 judges, I created 5 separate deployments for you to test the gameplay while I work out the above-mentioned WWW connection issues. 

- for Brenton: 
- for Joshua:
- for Jack:
- for Mystery Judge #1:
- for Mystery Judge #2:

Here are my thoughts on how Bitcoinships measures up to the evaluation criteria:

## Creativity

The original idea was: What if you were playing Battleship online with a friend... and you could bet 50 cents and a friend could bet 50 cents, and the winner gets the dollar? (minus fees)

As much as we see in the BSV ecosystem great one-player plus leaderboard profit sharing games such as Haste in BSV... 

...and the multiple bets on a game of chance as in PeerGame...

And although there are some multiplayer games in the sense of social media or other sites and apps, such as PowPing, Twetch and Bitstagram...

...and most notably CryptoFights...

Two-player games of skill, especially classic board or tabletop games, is relatively untapped realm for BSV, as far as I know.

There are many possibilities for this model, including 

-literally sending players the game jig, wallet permitting
-allowing players to create their own "partially signed" game contract for another peer to join
-tournament play, leaderboards and more.

In some situations, a server-client flow makes sense, and in others, two or more clients interacting will be best.

Regardless of the flavor, a reliable Bitcoin-powered gameplay and state recording engine underpins it all.

If what's missing is peer-to-peer tabletop games monetized online...

Then what's different about this version than any other game, that makes my version of Battleships so original?

**Well, I've got dark mode!

TODO: Screen shot of dark mode

Another creative thing I did while testing is that you'll notice if you disconnect from the server by refreshing the page, you automatically get refunded in your Money Button or RelayX wallet.

If the game looks promising to the hackathon judges, I'll devote resources to making the game persist its state using cookies and local storage once I figure out the websoc. 

Frankly part of 


