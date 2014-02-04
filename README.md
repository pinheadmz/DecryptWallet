DecryptWallet
=============

Modifications to blockchain.info DecryptWallet.html which currently does not support 2-password encrypted wallets

Blockchain.info offline Decrypt Wallet tool does not work for 2-passwords, I made a version that does

My Solution: https://github.com/pinheadmz/DecryptWallet

(original, official Blockchain.info tool: https://blockchain.info/DecryptWallet.html)

Blockchain.info's offline wallet decryption tool was never fully updated to handle 2-password encrypted wallets. 
The second password encrypts just the private keys, after the first round of overall encryption with your main password. 
If you try the official version now, you will get 'null' for all the private keys.
Wallets with the old 1-password encryption still work fine.

I added some code to fix the problem and I sent it to Mandrik via the customer service channel, 
and he said he'd forward it to Ben (their CTO) but that it was OK for me to post on github and reddit.

I was interested in this because for me the offline decryption tool "closes the loop" of being in control of my wallet.
I have backups of my blockchain.info wallet in my physical control, 
but what good does that do me if I can't access the website for whatever reason? 
Even though there are some clients that can import encrypted blockchain.info wallets, 
I recommend that everyone who has downloaded a backup of their wallet, ALSO download a decryption tool.

Give my code a look! Feedback welcome :-)
