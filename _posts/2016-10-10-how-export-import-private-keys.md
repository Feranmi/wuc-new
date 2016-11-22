---

layout: post
title: How To Export and Import Private Keys
author: Trace Mayer
authorurl: /
description: How to export and import private keys.
published: true
---

<p>Exporting and importing private keys is very important to keep your cryptocurrency safe. <a href="/what-is-a-private-key">What is a private key?</a>
<center><iframe width="700" height="394" src="https://www.youtube.com/embed/TevLN_k-GWA" frameborder="0" allowfullscreen></iframe></center>
<p>TRANSCRIPT
<p>Just a quick note before we get started.  If you do not already know what a private key is then it is highly recommended that you watch this video here where we discuss exactly that.  
<p>Now, there are a number of reasons one would want to export a private key.  Most notably being to transfer your balance from one device on to another and in this case a paper wallet on to a hardware wallet.  Here, I've gone ahead and loaded a paper wallet from Liteaddress.org with one Litecoin.  Now, in order to import its balance on to my PC, I need to know a private key, which you may find printed on the wallet alongside of its public key.  All I need to do is scan this code with a QR reader and it will reveal the private key to me just like that.
<p>We are going to present this process both on Electrum and Litecoin Core.  So at this point, feel free to skip ahead to the wallet of your choosing and I will see you there.  And if for any reason you are having trouble choosing, here is some smooth jazz while you mull it over.
<p>Electrum is by far the simplest way to do this.  Start by opening it up, navigate into your wallet, private keys, then import.  Here, you will be asked for the wallet passphrase.  Simply enter it and press Enter.  A notice will then pop up warning us that private keys are not recoverable from seed.  Just click Confirm, and now a new box will appear where you can enter your private key.  Go ahead and enter your key and press enter.  It will then inform us that we are about to import the following Litecoin address.  This looks good to me so click Confirm and now we can see that what we have the balance of one Litecoin ready to be spent.  As for exporting, that is just as easy.  Right click the address that you want to find the key of and select private key.  Again, just enter your wallet passphrase and press Enter, and there it is.
<p>For the core wallet, we're going to start by opening it up, navigating to Help.  Then the import console.  Then under the console tab if your wallet is encrypted with a passphrase, you will need to enter the following before you can go any further.  You can do so by typing in wallet passphrase followed by your passphrase and the number 60 to gain access.  Now, we can type import, proof key, followed by our private key that we have just scanned from the paper wallet.  If we want to label it, say, Paper Wallet, we can do so by writing this after the private key.  Otherwise, just leave it blank.  Now, hit Enter and the key showing us green letting us know that it has successfully been imported.
<p>Now, if like me you close and reopen the wallet and notice your balance has not actually changed which I am going to assume will be most of you, don't panic.  We just need to use a rescan function to, well, as it sounds rescan to try and find the missing transactions.  So close the wallet and with our desktop shortcut, right click and go to properties.  Now, in the target path we are going to add space, hyphen, rescan.  And then click Apply.
<p>Exit out of this and reopen the wallet via the shortcut.  And you should now notice it say rescanning.  This process can be quite timely.  As of right now it currently takes me roughly 10 minutes to complete.  But for you it may take even longer especially as small transactions are recorded over time.  Once it is finally done, we should finally see our balance of one Litecoin successfully imported and ready to be spent.
<p>One last thing, we can now go back into the properties of the shortcut and remove hyphen rescan.  As it is no longer necessary, we may not want to be rescanning every single time we start up the wallet.
<p>In order to export a key for the core wallet, again, we need to go to help, then the export console.  Now, if your wallet is encrypted with a passphrase you will need to enter the following under the console tap before we can go any further.  We can do so by typing wallet passphrase followed by our passphrase and the number 60 to gain access.  Now, in the console we can type dumpprivkey followed by the Litecoin address that we want to find the key of.  In turn, this will then bring up that specific wallet's private key.
<p>If you have any questions or suggestions for what should cover next, feel free to leave a comment.  And if you want to get involved, you can find us over at litecointalk.com and on Reddit @r/litecoin.  So drop by and say hello and until next time, farewell.