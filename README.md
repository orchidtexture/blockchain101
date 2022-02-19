# Blockchain 101

Blockchain learning material and resources for friends and family.

## Introduction

First of all, don't get frustrated if you don't understand some concepts the first, 
second or third time you read them, some topics took me several attempts to understand, 
some others I haven't completely grasped what they're all about and still, I'm effectively
building products around them. This is a journey full of new knowledge about an exciting, 
revolutionary piece of tech. _Learn, build, and repeat_. Also, don't forget to enjoy the ride.

## Background knowledge

How comfortable are you with the following concepts?
+ **Proof of work:** It is an _incentive mechanism_ as well as a _consensus protocol_ 
where nodes work in unison to solve a globally distributed cryptographic challenge.
> It is computationally intensive and also guarantees that any solution or proof
> is genuine and that the solver can prove that they indeed solve the challenge
> so that they can receive the reward.
+ **Cryptography:** (TODO)

Some resources for amping up your core blockchain concepts:

### Proof of work (PoW)

> [Mining simulator](https://blockchain-academy.hs-mittweida.de/2021/05/proof-of-work-simulator/)  
> [Proof of Work network simulator](src/pow-simulator.md)  

### Cryptography

> url 1  
> url 2

## Blockchain. What is it?

In 2008 the [Bitcoin whitepaper](https://bitcoin.org/bitcoin.pdf) was released by Satoshi Nakamoto and
on January 2009 the Genesis Block was minted, bringing the Bitcoin network into existence, eventually becoming
a cornerstone towards the evolution of world's financial systems. Since that day, many different blockchains have
emerged, some of them adding functionality and innovating with state-of-the-art consensus protocols, but lets
start with the basics and you'll find that once falling down the rabbit hole there's no way back.

In order to understand blockchain fundamentals, you'll have to understand it's first use case, cryptocurrencies,
the digital money.

### What gives cryptocurrencies their value?

Lets imagine you wake up to a world where economy has collapsed overnight, 
banks and every trustworthy finantial institution has dissapeared. How will you be able to 
buy a morning espresso from your local coffee shop? 

Well, there are a couple of different possible answers to that, you may be able to give
something in exchange for that fresh cup of coffee, but what if there are
ten people behind you expecting to trade some goods as well. Eventually, the coffee shop owner
will run out of space for storing those items or will cover all their immediate needs, it is not scalable.
You will also run with some problems regarding valuation and matching of trading assets. You may expect
a hot beverage will cost you about 30 pickles, but coffee shop personnel may value it closer to 50
pickles, or maybe they believe there aren't enough pickles in the world that can buy you an espresso
because they are asking for doritos' bags instead.

Suddenly, you come up with this great idea, living the digitally enhanced life you live it only makes sense
for you to try and trade one of your precious digital assets, and you pay with your recently aquired PDF of a teen vampire 
best seller novel, you email it to the coffee shop and wait still in front of the line, grinning from ear to ear and 
dreaming about that morning elixir you're about to get ☕️. What do you think the cashier will tell you? Will they just accept 
it and provide you with your desired product? Most certainly not! How many people you think owns a copy of that PDF book? 
If everyone's aware it is a best seller, and probably, a lot of copies circulate out there, demand for that particular 
file decreases, price goes down to the point that it's worth nothing.

This lead us to some fundamental problems when using digital assets as means for storing value: 
+ **Infinite production:** Zero cost for producing an asset allows plenty of assets to exist and circulate,
meaning, there's no real value in something that everyone can potentially own for free.
+ **Double spend:** The same digital asset can be sent to multiple parties, two unaware people could be receiving
the same picture of your dog 🐶 in exchange for a product or service.

Lets see how this two problems could be solved. First, in order to prevent double spend, every participant in 
this new digital economic system (we'll call it a network) should know who owns each asset. If everyone sees 
how you payed your coffee with a digital file, then you cannot reuse that same file with someone else.
Now we are left with the infinite production problem. We'll need to put some work on it, imagine this file contains
a poem you wrote, how much time did it took to create it? lets say you spent 4 hours writing it, so you are able to
produce 2 **unique** poems for each 8 hour shift. Now each of those poems start becoming valuable assets, since some
work hours were needed in order to generate them. Another important aspect is verification, it may take several
hours to create a poem, but verifying its uniqueness should be a quick task, you can run some anti-plagiarism 
software and get it veryfied in minutes, if not seconds. Four hours to create it, a few seconds to verify is the
asymmetrical relationship we're looking for.

After we've come up with this solutions we're still missing two fundamental components: trust and decentralization.
I know, big words, but while **trust** refers in some sense to the reputation of the party providing the asset as 
payment (maybe known as a honest individual and prolific writer), **decentralization** simply assures that there 
is no central owner of all these digital assets in circulation.

After you succesfully trade your first poem for another good, the whole system starts to make sense and people begin
transacting digital assets here and there. 
Same thing happened with Bitcoin on May 22, 2010, when an individual succesfully purchased two pizzas paying the 
modest quantity of 10,000 BTC, that day Bitcoin as a real world currency became a thing.

In conclusion:
> Double spend solved + Infinite production solved + Trust + Decentralization = **Blockchain** 


### Sources:

1. [Blockchain 101 lecture from blockchain101.com](https://blockchain101.com/courses/)
2. [Research showcase: Proof-of-Work Network Simulator for Blockchain and Cryptocurrency Research](https://www.youtube.com/watch?v=kYQBPAZRYlc)
3. [Bitcoin Wiki](https://en.bitcoin.it/wiki/Main_Page)
