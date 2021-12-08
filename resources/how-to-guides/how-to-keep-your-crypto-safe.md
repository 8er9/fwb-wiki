# 🔐 How To Keep Your Crypto Safe

This article is a how-to guide for understanding how best to secure your crypto wallet. The first section contains keys terms and concepts. The second section gives steps to take to prevent getting hacked and losing your crypto.

## Getting Started

Once you've [set up your Ethereum wallet](how-to-set-up-your-first-ethereum-wallet.md), it's important to take steps to boost your security.

Owning a non-custodial wallet gives you true ownership of your assets along with the freedom to access Web3-enabled sites and dapps. This also comes with the responsibility of keeping those assets safe. In this guide, we'll discuss the basics of cryptography and best practices to keep your wallet safe.

### 🔒 **Public-Key Cryptography**

When you send a message to the blockchain, you need the ability to **prove** that the message you sent came from you and not somebody else. This proof is called a **cryptographic signature**, and takes advantage of a single 256-bit number that has a very specific mathematical relationship to your Ethereum address, called your **private key.**

Every address has a single private key that can be used to sign messages, and it is not possible to "switch out" the private key for a given address. This is made possible by "[public key cryptography](https://en.wikipedia.org/wiki/Public-key\_cryptography)".

If someone else has your private key, they have the ability to send messages as if they were you, which is why it's important to keep it secret.

### **🔍 So Then, What Is a Seed Phrase?**

A seed phrase is also known as a "secret backup phrase" or "recovery phrase". This is that series of 12 to 24 simple words that you wrote down during your initial wallet set up.

The seed phrase, combined with a set of rules (called a "derivation path"), is used to generate the private keys to **ALL of your addresses**.

You can have multiple accounts, across multiple blockchains, all stemming from the **core secret** that is your seed phrase. Anyone who gains access to your seed phrase can move the funds in **ALL** your addresses.

Attackers **LOVE** to target seed phrases for maximum gain.

{% hint style="danger" %}
#### <mark style="color:red;">**Never ever give anyone your seed phrase. There is no legitimate reason to type your seed phrase into any website ever.**</mark>
{% endhint %}

This is why it's important to use a hardware wallet to secure your funds. Your seed phrase should **never touch a computer at any point** whatsoever. The only legitimate reason to use your seed phrase is to recover your accounts into a new wallet in the event that yours gets lost or destroyed.

This also includes setting up Metamask on a new browser, but even this is a risky move since keyloggers and clipboard sniffers could be watching.

## ✋ Tips For Staying Safe

### **1. Secure Your Seed Phrase Offline (and Only Offline)**

Keeping your seed phrase offline is the most critical step to protecting your crypto. This limits the ways you can get compromised. If the only copy of your seed phrase exists offline on a piece of paper, someone would have to steal that piece of paper to gain access to all your assets.

When you store your seed phrase in a notes app, password manager, photos, or anywhere connected to the internet, you are exposed to more attack vectors and ways to get compromised. Computers are a messy place. Sophisticated attackers could be watching your screen or clipboard and waiting for you to reveal your seed phrase.

{% hint style="warning" %}
<mark style="color:orange;">**If you think your seed phrase might have been exposed, you must set up a new seed phrase and move all of your assets as soon as possible.**</mark>
{% endhint %}

### 2. Get **a Hardware Wallet**

The most secure place to store your crypto assets is in a hardware wallet. This is a physical device that keeps your seed phrase offline and off your computer.

Although hardware wallets come at a cost, you can be certain that hackers won't be able to view your seed phrase unless you intentionally give it. The only way to keep your seed phrase 100% offline and off of a computer, while still being able to transact using it, is by using a hardware wallet.

Software wallets, aka Hot Wallets (such as Metamask, Rainbow, etc.) _can_ be a relatively secure place to store some crypto assets. However because your seed phrase must be exposed to an internet-connected device in order to use these wallets, you **cannot** achieve the high levels of security that hardware wallets provide. Software wallets are the favorite target of attackers since the ability to view your seed phrase is just two clicks away, and can also be read from your hard drive using traditional computer viruses.

### **3. Have More than One Wallet Address**

You should consider having a public wallet which you use for daily transactions (such as buying NFTs, interacting with dapps, etc.) and another one specifically for holding your assets.

Don't put all your eggs in one basket. Remember that anyone with your public address can view all of your assets and transactions. Clever analysis (or just a yourname.eth ENS domain) might be able to link your real-world identity with your account, which can make you a target for phishing or worse.

### **4. Protect Your Identity Online**

Be careful about the personal information you post online.

Bragging about your assets could draw the wrong type of attention and make you an easy target for hackers. As criminals become more sophisticated in the crypto world, you may begin to wish you had kept your identity more decoupled from your crypto assets. Be smart and think about the future.

### **5. Beware of Scams**

There are a lot of phishing attempts out there- from giveaways to fake support teams offering to send you money.

The rule of thumb here is that if an offer sounds too good to be true, it probably is. Again, <mark style="color:red;">**there is no legitimate reason to type your seed phrase into any website ever**</mark>**.** Anyone asking for your seed phrase is guaranteed to be a scammer. When visiting websites, always check the URL of the site you are visiting. Be cautious when opening emails that require urgent action and don't download files from unknown senders.

### Additional Resources

{% hint style="success" %}
To learn more about keeping your crypto safe, listen to this [wallet hygiene voice chat](https://drive.google.com/file/d/1X1KLBL7Sf4t5u4tm8zoRU72pgOPg48gR/view) featuring Brian Mark, Kyle Thornton, and our friends at Ledger. Stay smart and safe out there!
{% endhint %}

{% embed url="https://medium.com/@kyle-thornton/stay-safe-out-there-friends-deb62926bd2b" %}
