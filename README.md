# Bitcoinships

A peer-to-peer monetized multiplayer online Battleship game

## Hello, Judges!

Thank you for considering this entry for the first ever RUN Hackathon!

First things first, connectivity with peers across the web was inconsistent in my test. 

However, I did manage to get the app to run on two different computers side by side. 

My internet started getting really slow right before the deadline, so I was not able to record a gameplay demo exposing the many bugs and flaws in the game.

It does work through websockets locally. You can test it by opening two browser windows on your computer.

And you can play with a peer, but you may want to have a chat open as well to test whether you see each other connecting or disconnecting with a little flicker in the player info at the top of the screen. 

If you refresh and disconnect, you get a full refund of the 1 MILLI you pay to play.

At first I thought it was unfortunate that the game still has bugs, such as invalid tx hashes being emitted from serverside bsv txs, janky back-and-forth gameplay, only 2 server slots (so to scale I'd deploy multiple servers. 

But I now realize it would be irresponsible to release such a high-value game as this to the public without proper security auditing and/or testing.

Anyway, it's up at https://bitcoinships.herokuapp.com/

Enjoy!

Here are my thoughts on how Bitcoinships measures up to the evaluation criteria:

## Creativity

The original idea was: What if you were playing Battleship online with a friend... and you could bet 50 cents and a friend could bet 50 cents, and the winner gets the dollar? (minus fees)

As much as we see in the BSV ecosystem great one-player plus leaderboard profit sharing games such as Haste in BSV... 

...and the multiple bets on a game of chance as in PeerGame...

And although there are some multiplayer games in the sense of social media or other sites and apps, such as PowPing, Twetch and Bitstagram...

...and most notably CryptoFights...

Two-player games of skill, especially classic board or tabletop games, is a relatively untapped realm for BSV, as far as I know.

There are many possibilities for this model, including 

- literally sending players the game jig, wallet permitting
- allowing players to create their own "partially signed" game contract for another peer to join
- tournament play, leaderboards and more.

In some situations, a server-client flow makes sense, and in others, two or more clients interacting may be best.

Regardless of the flavor, a reliable Bitcoin-powered gameplay and state recording engine underpins it all.

## Interoperability

Interoperates with RelayX, MoneyButton, RUN, and could interoperate with more wallets if I replace TwetchPay.

I'm out of time, gotta stop here.

THANK YOU!!!
