# APEX - Technical Whitepaper

# Abstract
Bitcoin and Ethereum mark an important evolution in computer science.  Blockchain technology and decentralized computing could potentially be more transformative than the internet itself.  Decentralized computing and value transfer allow nacient systems to evolve at an exponentail pace.  We must build systems to manage this process.

APEX represents an evolution in the blockchain ecosystem whereby a present and evolving intelligence system will determine the best course for creation, distribution and redemption of smart tokens.  

APEX does not claim to have the best algorythm by which systems can design other systems.  Rather, APEX is an ecosystem that accepts inputs from the human scientific community in the form of XEPA protocols and pays those creators accordingly.  Similar to the system of "mining", the APEX ecosystem's use of "gas" is paid to the creators of algorythms in the form of AIT tokens.


# Philosophy
In basketball, the triangle offence is an intentionally boring system where the goal is to allow for freedom of an individual actor to exploit weaknesses in the defense.  Phil Jackson, coach of Michael Jordan and the championship Bulls was a huge believer in the triangle.  We are too.

APEX has a strict set of protocols to allow for freedom of action from individual actors to identify opportunities, spot weaknesses, and improve inefficiencies in a token based ecosystem.  The protocols themselves are loosely coupled to allow for variations of implementation.  send() doesn't know about redeem() and vice versa.


# Overview
The APEX AI known as Xepa is a shell that accepts protocols injections from algorythm creators.  In laymans terms XEPA can be thought of as an algorythm choosing mechanism that is loosely coupled to the algorythm itself.  Any particular algorythm can be injected into any smart contract at the time of creation or later on.


## Core Concepts

### Model Determination
A contract model is a fully-formed set of protocol paramaters with a given orientation.  An algorythm match is made when an algorythm with a simulation score of 78 or better matches the input paramaters for a new smart contract.  A "parameter" match will always be selected before a "close" match because it's impossible to weight the missing paramater given a particual ecosystem.

### Model Evolution
A model may evolve over time and in a fashion similar to git-hub may be rolled backwards or forwards.  This is different than remodeling.  Remodeling occurs when a system consistently fails to uphold model standards or thresholds.

### Algorythm Injection
Xepa performs algorythm injection.  An algo will create a model in a XEPA simulation.  When a new smart contract selects a particular model that algorythm is injected into the newly created smart contract.

### Algorythm Creators
Algorythm creators are paid in AIT when their algorythms match a set of inputs to create a smart contract.  This "match" is the output of the algorythm in the form of a smart contract with accompanying protocols.


# Protocols

### create()
Recommend smart contracts based on capital needs & market demand

### send()
Optimize placement opportunities for token distribution

### redeem()
Maximize token economics through token consideration introspection


# Protocol Paramaters

Protocol paramaters are an array of key-value pairs.
[{key:value}]


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

