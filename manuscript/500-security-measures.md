# Storing Coins Safely

## Safety Measures
All databases can get hacked. Search your email on https://haveibeenpwned.com/ - if you're lucky you have not been pwned, but billions of other accounts have. Therefore, it is important to follow general security measures that apply even more while using Bitcoin.

### Hardware and Software Setup
You can use popular browsers such as Firefox, Opera, Brave or Chrome. Browser extensions that block Javascript and Cookies are recommended. Ghostery, NoScript and ScriptSafe are the kind of extensions you can add to your browser. "HTTPS everywhere" enforces an SSL connection to all websites, including those that do not yet offer SSL.

Be aware that some online stores do not work properly with those extensions turned on, so you have to disable them manually.

It is important that you keep your devices safe.

### Updates
This advice applies to all your devices: perform all suggested software updates. For your computer's operating system as well as for your smartphone. Always use the latest version of your wallet and firmware software on your hardware wallet.

### Email Addresses
Do not use one email address for everything. Get yourself disposable email addresses that you only use one time. You can also buy a domain that you only use for fake email addresses that you forward to your main address.

### Secure Passwords
Use secure passwords for all online services. Your birthday, place of residence, the name of your cat or 1234567 are not secure passwords. Whole sentences with digits, spaces, upper and lower case letters and special characters are strong passwords.

Use a different password for each website on which you log in. Otherwise, a hacker with only one password can enter all the services you are registered with. Do not store these passwords in a Word file or anything like that on your computer. A Word document is easy for hackers to steal and read.

You can use software like 1Password, Bitwarden or KeePass (free and open source). These are encrypted password databases, where you can generate and store all your passwords and you only need to remember one password to open it.

### PIN
Set up a PIN for your wallet software so that no one can easily open your wallet on your device.

### 2FA
Use a 2 factor authentication method to secure your accounts. Do not use SMS / text as the 2 factor authentication method because of SIM swapping attacks. Instead, install an authenticator app like and OTP or TOTP on your phone.

### SIM Swapping
SIM swapping is when someone hijacks your SIM and telephone number. They can then use your phone number to login to all connected accounts where you activated 2 factor authentication with text/SMS. SIM swapping is an attack to get into your primary email account. If the attackers can access the primary email account that is associated with 2FA to your phone number, they can find all the Bitcoin exchange accounts you are using with 2FA and wipe them out.

The attack is often started by calling customer services at your telecom provider (Verizon, Vodafone, AT & T, Magenta,...). They say something along the lines of "I am the owner of the phone number, I lost my phone please transfer my number to my new SIM". The customer services person will ask for a piece of personal information to verify your identity. The attackers will then try a lot of tricks. They badger the support person to get small bits of information from them, hang up and call someone else and use that snippet of information to build to the next level. They then get more information and keep building until they have enough information to persuade the last person that they are the account owner and get the SIM transferred.

They will go after all crypto exchanges where you might have set up an account with your email address and phone number.

When they know your email, they will try to change your account password with the "forgot password" functionality. Good sites will not tell them if the account exists. The attackers will try to do a password reset or try to get a text message verification.

**What You Can Do - Gmail Example**
Lock down your primary email account and remove your phone number from your email account (such as a Gmail account). Here is how it's done: [https://anita.link/removegmail](https://anita.link/removegmail). Use a different password for every account on every website or service. As a Gmail user, you can enroll in the Google Advanced Protection Program, which defends against targeted online attacks.

## Phishing Attacks
In 2020, the marketing database of the French hardware manufacturer Ledger was hacked. The devices are safe, but thousands of email addresses, phone numbers and even home addresses of customers were leaked and can be found by anyone on the internet. This is an absolute disaster because there's a high chance that people ordering a hardware wallet own bitcoin too. In the worst case, you will be "visited" at home. Most likely are threats via email and phishing attacks. To prevent this, keep in mind that you may never need to use your physical address for delivery of a Bitcoin related product such as a hardware wallet. You could organize a postbox for yourself. In the US there are services that can receive mail for you (CMRAs). If possible, do not even use your real name when ordering. Get yourself a second phone number and use this in case the vendor requests one. Give them a disposable email address that you only use for this specific order.

Phishing attacks are attempts to scare or manipulate you so that you enter your seed words on the attacker's website. For instance, you could receive an email saying: "Your ledger device has been corrupted or deactivated, visit this link and enter your 12 seed words to save your funds." or "We have detected a large withdrawal from your Ledger. You have 24 hours to respond to make this transaction valid. We are sorry, we can not reach your Ledger it seems to be corrupted. We are going to authorize the withdrawal unless you start the recovery process, give us your 24 seed words." or "you have received an airdrop. Money is coming into your account, all we need is a verification, please start your recovery process and give us your 24 seed words."
![Phishing mail](assets/_phishing-mail-ledger.png) [^70]
The attackers try to make you act fast without thinking. If you receive such a mail. Stop. Do not do anything. Because no one can seize your money, no one can remotely disable your hardware wallet. That is the whole point of a decentralized currency like bitcoin.

Never trust email! Especially: never click on the links attached.

Bookmark the real websites of official sites of Ledger, Shift Crypto, Trezor etc. or type the domain name yourself in the browser address bar and look up the SSL authentication certificate. The attackers will send you to a fake website that looks the same as the real one. The only difference is the URL. One of the new tricks is to use domains with Unicode characters that look the same as the real domain. For instance, can you notice the stain underneath the l of electrum? If you open that URL you see electrum.org, but are visiting xn--eectrum-9hb.org instead.

![](assets/_phishing.png) [^71]

Browsers like Opera and Chrome will warn you, but Firefox doesn't do this by default. You can change that by enabling "punycode" in Firefox, see [anita.link/puny](https://anita.link/puny).

## 3-2-1 Rule for Storing Your Seed
The seed consists of 12 - 24 English words. Nowadays, more wallets use 12 words instead of 24 because they provide a high enough level of security and are easier to remember and store.

Write the seed on a piece of paper by hand when you first initialize your wallet. Make sure that the order is correct and check the written words multiple times. Note the vendor, model and the wallet software too. You might need this information in case you want to recover your funds.

If you set up a hardware wallet you should send a small amount of bitcoin to it to make sure that everything works. After receiving the small amount, delete the software from the device and restore it with the words you have written down previously. This is an important step that you should not skip.

After that, it is advisable to take the following security measures to prevent you from losing your seed. When people lose access to their funds it's more often because they have lost their seed or made a mistake writing it down and not because their devices have been hacked.

**3**: Write down the seed three times

**2**: On at least two different media (laminated paper, engraved or stamped on steel) and store it in a safe place for protection against fire, loss and theft.

**1**: additionally, store a backup in a different location, preferably at least 100 kilometres away.

Jameson Lopp, one of my podcast guests, is testing steel plates that can be used to secure the seed for the long term. He exposes them to fire and pressure to check longevity. Not all products are made of steel or titanium, which is why they melt in fire. The tests can be found here: [anita.link/metalseed](https://anita.link/metalseed)

Don't get creative! Dividing the words into two or more parts and storing them in different locations is a common mistake. You only need to lose one part and you will no longer be able to access your coins.

* Never give the seed to someone you don't trust with your money!
* Do not enter the seed on any websites or electronic devices!
* The seed is not required to send or receive bitcoin.
* No credible individual or entity would ask for your seed.
* Check the storage locations of your seed words regularly!
* Set up an inheritance plan - worst cases do happen and if you do not instruct your beneficiaries correctly, your bitcoin are lost. I recommend Pamela Morgan's book on "Cryptoasset Inheritance Planning".

### Passphrase
A passphrase is an additional way to secure your funds on top of the seed. If you add a passphrase, the software creates an additional wallet that you can use to protect yourself from physical attacks. If someone gets hold of your seed, they still can not access your funds because they do not have the passphrase.

Example: You might want to leave the minority of your funds in the basic “non-passphrase” wallet and move the majority of your funds to a passphrase-protected wallet. The idea behind this is that if you ever find yourself in a situation where somebody is trying to extort a ransom from you or puts you under duress, you can safely unlock your wallet and only give the attacker access to the normal wallet (which only contains a small amount of funds).

This sounds great, but there are also risks involved.

1. Because the passphrase is not stored anywhere automatically, you need to take **all necessary precautions** in order to make sure that the passphrase stays safe and accessible e.g. by making a physical backup.
2. If the passphrase is lost, you **will not be able to access that wallet** anymore and any coins stored in that wallet will become inaccessible.

With a passphrase, you do not only need to store your seed but the passphrase too. Now you have to find long term secure storage for the seed AND the passphrase, which makes it a more complicated process. Be aware: In order to restore a wallet of this type, you would need your seed AND the passphrase you used for that wallet to restore access to the funds.

Since physical attacks happen rather rarely, storing the seed with the 3-2-1 method should be sufficient.

### Alternative Backups
Some wallets use different mechanisms for the backup. For instance, the Muun wallet uses a combination of recovery code - that you need to write down like a seed - and an emergency kit.

## Learning by Doing
It can be intimidating to start using Bitcoin because it's real money. That is why it is a good practice to start with very small amounts.

For your first attempts, install a wallet on your phone, search for a [Bitcoin ATM](https://anita.link/atm) close to you or attend a local Bitcoin meet-up and exchange a small amount. Get a wallet for your computer and send bitcoin in between your two wallets to different addresses.

The best time to do this is usually on the weekend when the Mempool is not packed with transactions and the fees are lower.

Use different wallet software, reinstall the wallet seed from wallet A to B, use the seed on different devices. You will feel more and more secure maintaining the skills.

### Test Receive Address
Before you send a large amount for the first time, make sure that the address is really from the receiver and perform a small test transaction. Always check the Bitcoin address two or three times before sending the transaction. Compare the first and last digits of the address. Bitcoin that you send to an incorrect address are lost.

### Test Your Hardware Wallet

Before you save large amounts on a new hardware wallet, you should check the functionality and the seed.

When you set up the device initially, it creates the seed for you that you write down by hand (additionally the vendor, model and software version). Afterwards, you use the vendor software (or another software such as Electrum) and create the first Bitcoin address in your hardware wallet by clicking on "Receive". Then send a small amount to it from your previously installed smartphone wallet. If the amount on the hardware wallet has arrived as confirmed, the first test was successful.

Also, try sending from your hardware wallet to another wallet. For example, you can send a small amount to your smartphone wallet or another address of your hardware wallet. It doesn't particularly matter. The main thing is that you are testing a payment from the hardware wallet too. To do this you must check the receiving address on the hardware wallet and confirm sending with one or more clicks directly on the hardware wallet. This manual confirmation on the device makes hardware wallets secure as only you can press the buttons and no one can hit the buttons virtually over the internet.

**Restore Your Wallet**
Then make sure that you have your backup/seed! Afterwards, delete all data on your hardware wallet. Some vendors call it "factory reset", "wipe" or "reset the device". Your wallet is empty. Now restore your funds and wallet with the seed. This is called "Restore from recovery word", "Restore wallet", or "Import seed". Then enter your seed phrase on the hardware device. If everything is correct, the wallet is restored and you can see your previous transactions and balance.

**Upgrade Firmware and Software**
Don't just lock the device away. You should look for updates to the software or for firmware upgrades at least every 6 months. The crypto space is fast moving and new developments are integrated into wallet software on a regular basis.

## Smartphone Lost? Computer Stolen?

### Loss, Theft, or Malfunctioning of Your Device

If your device gets stolen, remember that your bitcoin are still listed on the blockchain under your private key. Since you set an access PIN for the wallet, the thief cannot open it. However, they will still try to find a way to crack your PIN.

You should immediately install a new wallet and import the seed that you kept safe to regain access to your funds (see "restore your wallet"). Then, move the coins from your stolen wallet to a new Bitcoin address in your new wallet as soon as you can, repeating the same security setup procedures for the new wallet.

If your device gets corrupted, you follow the same steps, but there is no need to rush to move the coins. Just restore the software wallet and you're done.

[^70]: Anita Posch
[^71]: [Source @ElectrumWallet](https://twitter.com/ElectrumWallet/status/1144678604523147265?s=20)
