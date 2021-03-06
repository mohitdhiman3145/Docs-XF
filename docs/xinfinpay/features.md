# Get Started with XinPay Crypto Asset
In this tutorial, we’ll be discussing an essential technology that correlates with the core operation of XinFin — Network transactions.

# Understanding Xinpay
XinPay is a bridge that allows you to visit the distributed web of tomorrow in your browser today. It allows you to run XinFin DApps right in your browser without running a full XinFin node.
While doing transactions on the blockchain network, it uses computing power which is called gas cost, and much like gas in real life, you have to pay for it. For you to pay that gas cost, you will need a wallet that handles your money, and that’s where XinPay comes in.
Well, I guess that’s enough information about XinPay for now. We don’t have to explore every angle of the equation. I bet you get the gist of its purpose already. Without further ado, let’s jump right into the first question!

# How can I install it?
Before you install XinPay, you have to know that XinPay only supports a couple of browsers. XinPay supports the following browsers:
 - Google Chrome (or any Chromium browsers, Brave, a DApp Chromium browser.)
 - Mozilla Firefox
 - Opera
If you already have any of the above, you can proceed, otherwise, you should download at least one of the listed browsers and you’re good to go!
For you to download XinPay, you should first go to this [link](https://chrome.google.com/webstore/detail/xinpay/bocpokimicclpaiekenaeelehdjllofo) and download it.

You can also download XinPay on your browser’s plugin extension web store, but if you want to be directed automatically to the download page dedicated for your browser, the link is the way to go. 

Once you’re inside, you should see Xinpay iconic XinFin head following your mouse direction. Under it, you should see the GET CHROME EXTENSION orange button, click that, and you’ll be automatically directed to your browser’s store.

For Google Chrome browser’s example, you should see something like this

![XinPay Home Page](/assets/Xinpay1.png)

Now after getting in, just add the plugin extension, and it will install itself on the browser after downloading. (in Chrome’s case, click the Add to Chrome button.)

Once it is installed, a new tab will suddenly pop up, it’s the Xinpay wallet’s welcome page. But you’ll get the same interface on the actual wallet so just close it. Once closed, click here:

![XinPay Home Page](/assets/Xinpay2.png)

If you click that icon, you should trigger the Metamask wallet’s user interface. This is how the wallet looks like:

![XinPay Home Page](/assets/Xinpay3.png)

Now just click continue, and you’ll be directed to creating your password. Don’t go import seed since you don’t have an existing account yet. You will use that if you want to recover your account. We'll talk about account recovery later in this article.

After creating and confirming your password, you’ll go through some terms and agreements, then you’ll be given a secret backup phrase. That phrase is the heart of your account since it is derived from a unique hash created when you created the account just now.

![XinPay Home Page](/assets/Xinpay4.png)

As said, you shouldn’t compromise the phrase to anyone, because if your wallet has XDC inside then that can be transferred to someone else. Although Xinpay is a wallet made for developers, you still have to exercise secrecy.
(The account I have shown is for demonstration purposes so it’s totally fine.)

After saving the phase, you will need to confirm it next. Then it will ask you if you want to deposit, skip, and close that for now.

![XinPay Home Page](/assets/Xinpay5.png)

Finally, you’re done! You have successfully installed Xinpay, and made your very own wallet. Yeah, we did install Xinpay, but what is the catch about that wallet? What is it capable of? This leads us to the next point:

# What can it do?
For the features of Xinpay, there’s a lot that you can do. But I’m not going to cover everything since my focus is to teach you just enough to get you ready for developing your XinFin decentralized applications.

Here are the basic features of Xinpay that you will need:

- Adding/Importing accounts
- Switching accounts
- Switching networks
- Requesting tokens (Testnet Faucet)
- Sending tokens (XDC)
- Adding/Searching for token
- Getting backup seed

Alright! That’s all you need to know about the features. Let’s now head to the next question:

# How do I use it?

To track our progress easily, let’s just learn all those listed features from top to bottom. But before that, I’m just going to show you a few helpful things:

![XinPay Home Page](/assets/Xinpay6.png)

Let’s try to look at the highlighted portion on the top side.

Below the name of the account: Account 1, you can see random-looking character string, something that looks like this - xdc607b... That is your account’s wallet address, if you click it, the address will be copied onto your clipboard.

This is very helpful since you’ll be using your account a lot on your smart contract development and your dApps as a test account.

Next is the one below it, which is your transaction history. Here you will see the state of your transactions whether or not it is finished, pending or the transaction had failed, etc.

Also, if you want to switch the value from Fiat to dx you can do that by going to the top right highlighted button, as shown here:

![XinPay Home Page](/assets/Xinpay7.png)

When clicked, a window will show up under it. From there, you can see from the bottom-most part, which is the Settings button with the gear icon. Hit that button and it should show this:

![XinPay Home Page](/assets/Xinpay8.png)

You’ll be taken to this interface, initially on the Settings tab. Without scrolling, you’ll be able to see the Primary Currency section, from the Fiat radio button, switch it to *XDC, and that’s it. If you go back to your Main interface by hitting the head button, it should change by now:

![XinPay Home Page](/assets/Xinpay9.png)

# Adding/Importing accounts

For this feature, it lets you add more than one wallet. This can be useful both in development and in real life. Since you’ll be making applications, you will need to test not only one account but will have to get your accounts to interact with each other on a smart contract. Makes sense, right?

![XinPay Home Page](/assets/Xinpay10.png)

# Adding accounts

From main, for you to add an account, just go to the highlighted top right button and click it. This will prompt a new window, showing a list of items.

On the top side of that window, it shows the list of accounts that you currently have. As of now, you only have one account which is Account 1.

To add another, just click the first option below it: + Create Account. When clicked, you’ll be directed to a very self-explanatory interface, which contains an input for the name of your account and the button Create, hit it.

When you go back, you'll have your new account waiting for you. It also has its unique address.

# Importing accounts

![XinPay Home Page](/assets/Xinpay11.png)

If you have an existing account, you can click on Import Account. You will be taken in an interface where you will have to put a secret backup phase in the private key string text input of the Private Key category. If you want to import JSON, you can do so by changing it in JSON. The last thing to do is to hit the Import button.

# Switching accounts

![XinPay Home Page](/assets/Xinpay12.png)

Since you learned how to import and add accounts, I assume you made new ones too. So, let’s learn how to switch accounts!

In the example above, you can see that I have already added 2 more accounts: Account 2 and Account 3. On the same window as before, if we want to switch to Account 2, from the list, just click it. 

# Switching networks

Switching networks is an important thing about Xinpay. As you have recently seen, we’re using the Main XinFin Network. But that’s not the development network, there’s a network for one.

![XinPay Home Page](/assets/Xinpay13.png)

As you can see in the picture above, we’re on the Main network. But underneath it is developers’ available networks. Most often, developers usually use the XinFin Apothem Network. That is if you’re using Remix directly with injected Web3 setting. Localhost:8545 however, is for your local XinFin network.

Choosing a network is a case to case basis, but for common action, let’s choose Apothem Test Network, click it and you’re in it already!

# Request tokens 

Making transactions costs gas amount, and gas costs money. So we will need tokens every time we interact with/test contracts or send tokens.

But all these are mostly used if you’re going to spend and do real transactions on Main-net. For the developers, however, if you switch to a developer network such as Apothem Network, you will see this:

![XinPay Home Page](/assets/Xinpay14.png)

You will see a Test Faucet. By clicking the XinFin Apothem Testnet Test Faucet button, you will be able to get free tokens. But these tokens have no real value since it’s a testing network. 

By just clicking the blue button, you’ll be able to request XDC. From there, for a short moment, it will take effect and give you tokens that you’ll be needing as gas for testing in development.
Here is the link of the Testnet Faucet, get yours now!

![XinPay Home Page](/assets/Xinpay15.png)

# Send tokens

Before proceeding, try getting tokens for at your one account from the Test Faucet on Apothem Network. If you already have tokens, we can now try to send tokens to another account. To see the effect, send it to your other created account.

![XinPay Home Page](/assets/Xinpay16.png)

From the Apothem Network, if you hit the Send button, you’ll be sent to this interface. In the example, Account 1 has 100 XDC, and by hitting the recipient address input text, you’ll be able to choose or pastedown an address.

In your case, use your account that has XDC, and send it to your other account. Set the amount on the Amount section, and you can set how fast the transaction will be beneath it, it’s customizable.

After you set everything, hit Next. And you’ll be sent in this interface:

# Confirmation Interface

![XinPay Home Page](/assets/Xinpay17.png)

This is the exact interface whenever you make transactions on XinFin using Xinpay. You’ll see a lot of this prompting interface once you start developing.

From here you can also edit the gas fee, to make your transaction faster. In here, we are sending 0.457 XDC to Account 1. Hit Confirm and your transaction will be processed and will also show up on your Transaction History on the main interface.

# Add/Search tokens

Aside from XDC token, there are also different kinds of tokens that you can use based on the kind of DApp you use. Usually, when you make a DApp they also make their cryptocurrency. So here, I’ll show you how to search and add your token.

# Add tokens

![XinPay Home Page](/assets/Xinpay18.png)

From the main interface, go to top left menu icon beneath the Home button. Once you hit the menu, you’ll be able to see this one slide:

From what you can see above, your token shows up, under that is a supposed list for the other tokens. Since you only have the XinFin token, you can’t notice the list.

With that said, you can add a token, it’s either you add your own made token from an ERC20 standard contract or you search someone’s token assuming that you have one already. Let’s go with adding your own first.

![XinPay Home Page](/assets/Xinpay19.png)

On the Custom Token tab is where you can add your own created token. There are 3 input fields. The last two fill in by themselves once you fill in the Token Address input text field. So the first one is the only one needed.

If you plan to make your token, you can try it on the Custom Token tab. Just hit Next and you’re good to go. It is added to the list. If you choose one from the list, you can use it for your transactions related to that token.

Now on to the searching of the token.

# Search tokens

Same as before, if you go to the menu icon again, on the Search tab, you will see this interface:

![XinPay Home Page](/assets/Xinpay20.png)

As seen above, XF is a known example of a crypto token. If in an instance, you have received XF tokens, then you can search and verify it from here, and add it to your token list.

# Get backup seed

If in case you forgot your secret backup phrase, you can get it from your settings, so go back to settings from the top-right menu button.

![XinPay Home Page](/assets/Xinpay21.png)

When you get inside Settings, and if you scroll down in the middle you will find the Reveal Seed Words section. If you hit the Reveal Seed Words button, the secret backup phrase will be shown and you can copy it. Keep it safe!

Questions? Join Telegram Channel to get answers: https://t.me/joinchat/GeOl40UaNJPlFLNwSvu9cQ

# Summary

It’s finished! That tutorial sure was a bit long but I’m pretty sure that what you learned just now, will equip you enough for your future or current developments for making your decentralized XinFin applications.

In case you forget some things you learned from here, you can always come back. It’s natural if you don’t remember everything in one go, every developer’s been there. You’ll get better soon enough!

Even these non-blockchain related Microsoft developers are happy for you:

Hope you learned a lot and good luck venturing deeper into blockchain.

Until then, signing out, and stay tuned!
































