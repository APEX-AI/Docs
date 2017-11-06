
APEX - Technical Whitepaper

# An intelligent system for creating distributed applications
Bitcoin and Ethereum mark an important evolution in computer science.  You wouldn't say this five years ago, but today it's not hard to imagine blockchain technology being just as transformative as the internet itself.  Decentralized computing made possible by distributed consensus will propel nacient systems to evolve at an exponential pace.  

APEX represents an evolution in the blockchain ecosystem whereby a present and evolving intelligence system will determine the best course for creation, distribution and redemption of smart tokens.  In practice, APEX is an extension to a smart contract that adds protocols for introspection into token economies for the purpose of creating intelligent systems.

In addition to protocols, the APEX AI known as Xepa combines NLP, machine learning and deep learning to enable the creation of smart contracts and the transfer and redemption of tokens through text and voice.  

"Xepa, I'd like a create a contract for Katy Perry to offer merchandise to her fans." 
- Xepa replies "Great!, how many fans does Katy Perry have on Instagram?". 

"Xepa, I'd like to create a conract for my office to pool money for lunch."  
- Xepa replies - "Great, how many people are hungry and how much does everyone spend on lunch?"  

Eventually, Xepa could be used for transactions "Xepa, please send 20 BTC to Satoshi Nakamoto as a thank you for creating the blockchain."

The rest of this document assumes a working knowledge of blockchain, cryptocurrency, artificial intelligence including subsets of AI such as NLP, machine-learning and deep-learning.

## Technology

If you were to design an AI system that created smart contracts it would probably consider previous uses of AI's that...
- Write software
- Transact assets in finance
- Optimize marketplaces

### Blockchain
Smart contracts were originally proposed by Nick Szabo in 1996 when the Internet was gaining mass adoption. [Smart contracts](https://en.wikipedia.org/wiki/Smart_contract) are a set of promises, specified in digital form, that include protocols within which parties perform on these promises [<sup>[1]</sup>](https://en.wikipedia.org/wiki/Smart_contract#cite_note-:2-1) [Ethereum](https://github.com/ethereum/wiki/wiki/White-Paper) uses smart contracts as instructions for creating decentralized applications. 

On stage at [Techcrunch Disrupt](https://techcrunch.com/2017/09/18/ethereum-will-replace-visa-in-a-couple-of-years-says-founder/) the founder of Ethereum Vitalik Buteri recently said "Ethereum will match Visa in scale in a couple of years".

### Artificial Intelligence
[Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence) as a science dates back to 1956 with a multitude of disciplines spawning in thousands of directions since then.  

The promise of AI is out of this world and yet hardly recognizable.  Most systems have yet to capture value from machine learning, deep learning, NLP and the like.  Cryptocurrency has shown to be effetive in capturing value for open source projects specificially Bitcoin and Ethereum.  APEX will take this knowledge and apply it in a specific manner.

Defining the problem.  Where Ethereum is solving a technical problem known as "distributed consensus" most AI systems don't have a technical problem.  Consider an autonomous driving car.  The problem is the car doesn't know how do anything to start with.  The solution is clear as day.  Get from point A to point B, stay on the road, don't hit anyone.  AI in this case is coming up with a technical answer to a non-technical challenge.

Scientists who develop AI are providing a valuable resource from which value can be extracted.

[Andrew Ng comment]


### Modeling and Deep Learning

[Modeling strategies]

[APEX Modeling strategy]


### Philosophy
We are well beyond questioning if a machine can [act intelligently] (https://en.wikipedia.org/wiki/Philosophy_of_artificial_intelligence). Our intent of introducing philosophy is to take into account a deeper examination of our humanity to establish rules that govern a system that creates another system.

Our first rule is empathy.  Here's why.


#### Empathy
Empathy is a relatively new development in AI as stated by the Kairos article by Gabriella Leone [What is Empathy?] (https://www.kairos.com/blog/empathy-in-ai-series-part-1-what-is-empathy).  Aside from the buisiness application such as for chat bots for Mental Health, empathy is of far greater importance to an application tasked at creating other applications.  An average application would resemble something like Wall-e from Disney and at the extereme an empathetic terminator would be more like Dexter.  It is our position that all AI systems should employ empathy so they take into account the positive and potentially adverse effects of their actions.


# Types of Smart Contract Applcations

### Marketplaces
The most common use of APEX will be to create token systems that exchange goods and/or services for consideration. They are very easy to implement and increasingly valueable after deep-leaning optimization.  

def create(name, symbol, amount, [item:value], for_whom)
def send(to, value, from_who, for_what)

The main takeaway that we're extending the Ethereum send() function to include actors and consideration.  Because Ethereum addresses the underlying protocol for sending including accounting and trustworthyness our goals are introspective to "understand" what is being traded for what by whom. 

### Identity and Scoring
You can create naming and scoring systems using a public database alongside other data. Other use cases include email authentication and potentially more advanced reputation systems. Here is the basic contract to provide a Namecoin-like name registration system on Ethereum.

def register(name, value, profile)

Again, we're looking to extend the functionality of Ethereum with introspection.  Identity systems can provide functions like  reputation.  APEX provides a service of identity matching that allows actor profiles to be combined and used throughout the APEX ecosystem.  

### Decentralized Organizations
A smart contract for an organization where members get rights to spend entity funds and agree on projects.  The big idea is that generally every rule of governance can be articulated in a smart contract and whatever procedures that can go into a smart contract can be included in a Xepa algorythm.

DAO's are becoming quite popular.  [What is Empathy?] (https://en.wikipedia.org/wiki/Decentralized_autonomous_organization)

### Wallets

Applications for wallets with holding and annunity functions.  For instance setting the maximum withdrawl limit per day or having a joint set of instructions that allow the release of funds. to withdraw.

### Multisignature Escrow

A contract can be created where several parties agree to the release of funds, similar to a DAO.  

### Gambling

An application can create gambling services with near zero fees with no room for cheating.

### Other Uses

Blockchain appliations actually have the ability to execute any code with the caveat that each node will have to execute the same code everytime the chain is traversed.  This creates an interesting dillema for smart contracts architects.  Providing answers to singleton functions is one of the many rewards awaiting algorithm architects.

# APEX Overview
APEX looks to add introspection to the blockchain specifically to the distribution and redemption of digital tokens where the actors exchange value for consideration.

### Scope of Operations

Xepa is a protocol on top of blockchain technology, it is not looking to recommend changes to the underlying blockchain consensus algorythm or any other inner-workings of the blockchain itself.

### A Hybrid System

There are a number of functions performed by APEX that don't lend to decentralization.  Number one is that maintaining a database isn't a good use of decentralized computing.

### Discovery

APEX allows deep discovery of actors and consideration.  When looking for token placement Xepa will identify potential token buyers and call their redeem() method. The redeem function will notify the app that there is an item available for redemption.  The app can do nothing, save the items in the call for use later, and/or respond with a purchase through the send() protocol.

# Xepa - The smart contract bot

### Xepa Techniques
#### NLP
Given specific inputs Xepa can perform basic actions.  Like most bots, Xepa will ask questions to fill in holes.

#### Deep reinforcement learning


#### Algorithm Injection
The APEX AI known as Xepa is a shell that accepts protocols injections from algorithm architects.  In laymans terms XEPA can be thought of as an algorythm choosing mechanism that is loosely coupled to the algorithm itself.  Any particular algorythm can be injected into any smart contract at the time of creation or later on.

#### Model Determination
A contract model is a fully-formed set of protocol paramaters with a given orientation.  An algorithm match is made when an algorythm with a simulation score of 78 or better matches the input paramaters for a new smart contract.  A "parameter" match will always be selected before a "close" match because it's impossible to weight the missing paramater given a particual ecosystem.

#### Model Evolution
A model may evolve over time and in a fashion similar to git-hub may be rolled backwards or forwards.  This is different than remodeling.  Remodeling occurs when a system consistently fails to uphold model standards or thresholds.

#### Algorithm Architects
Architects are paid in AIT when their algorythms match a set of inputs to create a smart contract.  This "match" is the output of the algorythm in the form of a smart contract with accompanying protocols.


# Protocols

### create(name, sym, amount, for_what, for_whom)
Recommend smart contracts based on capital needs & market demand

'''
create({'actor':{'name':'Katy Perry', 'aid':'kDy4Yu7rBwhmWFpuk6CFBbjPjFa2', 'audience_size': 100000000, 'vibrancy':23, 'engagement':78}, 'consideration': 'Merchandise', 'volume': 200000, 'platform': 'Ethereum' })
'''

Output will result in a smart contract that implements the send() and redeem() protocols

### send(to, value, to_whom, from_whom, for_what)
Optimize placement opportunities for token distribution

### redeem()
Accept tokens in return for some consideration

# Protocol Parameters
All protocol parameters come in the form of an array

for_what: [aic] - Array of consideration and/or consideration group Id's
for_whom: [aid] - Array of actor and/or actor group Id's
to_whom: [aid] - Array of actor and/or actor group Id's
from_whom: [aid] - Array of actor and/or actor group Id's


# Actors (aid - APEX Identity)

Protocols can combine identities cross-sandbox through the use of a aid.  Specific identities can be useful when identifying identity groups, brands and tastemakers.  APEX will assign aid's to actors when available. 

Usually a protocol will reference an identity group.  The group has it's own unique AID.  Multiple AID's can be used as parameters without exception.  XEPA will define a subset of identity groups to start with.  [Identity Groups](https://www.doapex.com)

New actors can be added through the add_actor() protocol


# Consideration (aic - APEX Consideration)

Protocols will always have a reference to consideration.  Consideration is the actual item or service being exchanged for a token.  

Similar to identities, considerations can be grouped.  The group has it's own unique AIC.  Multiple AIC's can be used as parameters without exception.  XEPA will define a subset of consideration groups to start with.  [Consideration Groups](https://www.doapex.com)

New consideration can be added through the add_consideration() protocol


# Actual Value (aiv - APEX Value)

Protocols will contain references to an actual value for an item of consideration in any fiat or token currency.  The value at the time of a transaction will change overtime thus it's important to perform any fiat exchange operations and store them at the time of transaction.

Similar to identities, considerations can be grouped. Usually a protocol will reference an identity group.  The group has it's own unique AID.  Multiple AID's can be used as parameters without exception.  

New values can be added through the add_value() protocol



# Roadmap

### Xepa Bot (web, ios, android)
### AIX (APEX influencer exchange)

## Stretch Goals

### 20m - Xepa Spoken Interface
Xepa will adopt the a spoken voice voice of a young british lady.
### 35m - APEX Marketplaces
APEX will open 3 marketplaces  
- Entertainment
- Travel & Recreation
- Virtual Goods
### 50m - APEX Exchange & Wallet
Xepa will become an exchange similar to coinbase with a spoken interface.  "Xepa, please send 10 Ether to John for lunch."
### 60m - VR & Augmented Reality Connectors
APEX will design a series of protocols to create smart contracts in VR.  
### 70m - Robotics Connectors
Xepa will gain the ability to natively communicate with popular robotics platforms.
### 80m - IoT connectors
Xepa will connect to your toaster and fridge.  "You may have your coffee when 75% of you are thirsty."
### 90m - Creativity Connectors
Xepa will get her groove on with vision, music, art and dance protocols.  You could organize a flash mob or a nationwide art project.
### 100m - APEX Marketplaces
APEX will open 5 more marketplaces  
- Finance
- Pharma
- AI
- Entertainment
- Jobs
### 125m - Self Driving Car Connectors
Xepa will get behind the wheel.  One use could be to create an Uber competitor.
### 150m - Real Estate
APEX will design a series of protocols for buying and transfering physical property.
### 175m - Physical Space Connectors
APEX will design a series of protocols that describe the physical world.  Practical applications maybe a preservation system for a wildlife refuge.
### 200m - Physical Space Connectors
APEX will design a series of protocols that describe the physical world.  Practical applications maybe a preservation system for a wildlife refuge.
### 250m - Distributed deep-learning computing platform (Ethereum for deep-learning)
We will build a blockchain where miners earn gas for performing deep-learning processes.



### References
1. Smart Contracts: Building Blocks for Digital Markets http://www.fon.hum.uva.nl/rob/Courses/InformationInSpeech/CDROM/Literature/LOTwinterschool2006/szabo.best.vwh.net/smart_contracts_2.html
2.
3.



