# Witless
A token system based on proof of transport.

## What is Witless?
Architectured by the visionary mind of William Fields[^1], **Witless** is a token system unlike anything else on the market today. Rather than use a system that will destroy our planet (proof of work), or one that will help the rich to be even richer (proof of stake), **Witless** is the first token backed by the new *proof of transport* system.

## Proof of Transport
Proof of Transport (also known as *PoT*) enables peer-to-peer transfers of tokens without a central authority by forcing the parties involved in the transaction to solve a transportation challenge to execute the transaction.

The difficulty of a *PoT* challenge correlates mostly with the physical distance between the peers[^2] and is solved by all the peers meeting at a single location. After the *PoT* challenge is solved, peers can send and receive **Witless** tokens with no restrictions.

## The Witless token

Solving the *PoT* challenge is only half of the work needed to execute a **Witless** transaction, the other half is making sure the **Witless** tokens are valid. To solve this problem, **Witless** leverages the *United States Dollar* coin for the validation process.

### Why USD?

*USD* is a coin created in 1792 with a market cap of 2.1 trillion [^3] of itself, and each *USD* unit is worth 1 of itself[^4]. *USD* is the most popular coin for reserve currency and is the only coin accepted by the United States government for tax payments. 

On top of all of these benefits, two aspects of *USD* are fundamental for the **Witless** system:

#### World-class counterfeit prevention systems

*USD* bills, in special the 100 *USD* bill, have many mechanisms which prevent a malicious party from creating counterfeit versions of it. **Witless** leverage these fraud prevention systems by using 100 *USD* bills to represent 1 **Witless** token. 

#### Guarantee value

Because 1 **Witless** token is also a 100 *USD* bill, a **Witless** token will always be worth at least 100 *USD*.

### Process

All **Witless** tokens are 100 *USD* bills, but not all the 100 *USD* bills are **Witless** tokens. To figure out if a 100 *USD* bill is a **Witless** token or not, one should check if the serial number of the bill is included in the [list of **Witless** serials](files/witless-serials.txt.asc). This list is also signed by the [**Witless** official public key](files/public.key) for extra security.

## Transaction example

Suppose Bob embezzled royalties fees which he was supposed to share with Alice. After years of litigation, a court order forced Bob to compensate Alice, and they agreed to use **Witless** tokens because they are better than money. They also agreed 5 **Witless** tokens would be a fair compensation.

1. Since Bob is on house arrest, Alice solves the *PoT* challenge by driving to his house.
2. Bob gives Alice 5 100 *USD* bills.
3. For each bill, Alice checks if the serial number is included in the [**Witless** list of serial numbers](files/witless-serials.txt.asc).
    * For extra security, Alice double checks if the list she is using is signed by the [**Witless** public key](files/public.key).
4. Since all the bill serial numbers are included in the **Witless** list, they are valid **Witless** tokens.
5. Alice accepts Bob's transfer and now she owns 5 **Witless** tokens.

## NTF support

As is expected from any modern token system, **Witless** supports NTFs. Users of **Witless** can include several types of data in their **Witless** token:

* Text messages.
* QR codes.
* URL (both Web classic, Web 2.0, and Web 3.0 supported).
* Drawings of a monkey humanoid.

### NTF limitations

* NTF data must fit inside the 100 *USD* bill.
* When writing the NTF data, the data should not override the *USD* counterfeit prevention systems.

## FAQ

#### Is this a joke?

Is [Brainfuck](https://en.wikipedia.org/wiki/Brainfuck) a joke? **Witless** is meant to be a fully functional token system.

#### Can the Witless list of serials be updated?

Yes, it can. Adding new serials to the official **Witless** list is called *creating a new wave*, and each wave must follow these rules:

* The list can only the appended, existing information cannot be changed.
* Every wave must be numbered as `N+1`, where `N` is the last wave number, and timestamp.
* New serials are always associated with the current wave.
    * Meaning that is not possible to add (or remove) serials from previous waves.

#### Won't adding new serials to the Witless list devalue the Witless token?

The invisible hand of the market works in mysterious ways, it is not possible to tell what exactly will happen, but **Witless** has a couple of systems to prevent the devaluation:

* No matter how many tokens are, a **Witless** token is always worth *at least* 100 *USD*.
* Because **Witless** updates happen on waves, the fungibility of tokens of the same wave is high, but tokens from different waves may not be as fungible. Even if new tokens are created, the market may choose to value original wave tokens higher than newly added tokens.

#### What would happen if the person holding the private key for the Witless list "go rogue"?

If a new **Witless** list is created and correctly signed by the official **Witless** private key, but this new list is not updated following the **Witless** rules, **Witless** users must ignore the new version.

If multiple **Witless** lists are correctly formatted and signed, but the lists contract each other (for example multiple valid lists with different definitions for the last wave), it is up to the peers involved in the transaction to agree on which list they should use. Older and well-known lists are more likely to be trusted, but at the end of the day, any list is as valid as the peers involved in the transaction believe it to be.

## ICO

![Witless ICO $100 bills](/files/ico.jpg)

All the 15 initial **Witless** tokens have been already secured and the ICO is scheduled for Q1/2022 and soon we will share more details about the bidding process. If you want to hear more about **Witless** ICO, [consider signing up for updates](https://www.signupanywhere.com/signup/lwzsnswq).

[^1]: This statement is not an admission of responsibility.
[^2]: Geography and access to public and private transportation also play a role in the difficulty. 
[^3]: As in February of 2021.
[^4]: As in December of 2021.