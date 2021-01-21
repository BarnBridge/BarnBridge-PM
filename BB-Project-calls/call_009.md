# BarnBridge Project Call 009 Notes 
### Meeting Date/Time: Thursday 2021/1/21 at 15:00 UTC
### Meeting Duration: 29 mins
### [Github Agenda Page](https://github.com/BarnBridge/BarnBridge-PM/issues/13)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=qP4SSKuDFOs)
### Breakdown: 

Moderator: Troy Murray

Scribe: Rayne L.

Attendees: Mark Ward, Akin Sawyer, EJ Rodgers, Troy Murray, Vitalk Chernyak, Pavlo Bendus, Milad Mostavi, Dragos Rizescu, Tyler Ward, Bodgan Gheorghe, Keegan Selby

## Intro

**Troy:** Welcome to project call 009! We are very close to the release of the DAO. I'll be handing it over to Akin. For an update on the news this week covering DeFi Alliance & Standards. Then he will have to hop off.

## DeFi Alliance / Standards 
> [Update](https://twitter.com/qwqiao/status/1351172408963719169?s=21)– In case you missed it

**Akin:** With standards, we are pretty much done. We are just doing some final reviews. We should have something to publish in the next couple of days. There should be something available for the community to engage with and provide feedback.

We joined a Defi Alliance accelerator program.  It starts this week. A lot of it is building relationships with MM's(Market makers), LP's(Liquidity providers) and other projects in the DeFi ecosystem. The alliance will help us engage various stakeholders who may have an interest in BarnBridge. What their needs are. What frictions there may be. And how we can support them from a product and UI/UX perspective.

That's about it. Short and sweet.

**Troy:** Yep, short and sweet. Very nice. 

Alright, we're going to let you hop off because you have some stuff to do with the DeFi Alliance. So we will see you later ser! Good luck with everything over there.

Hopping into the tech and dev side, we will be handing it off to Dragos–the one and only! For an update on what is going on. 

Please ser. 

# Tech/Dev

## BarnBridge– Snapshot

**Dragos:** I'm just going to start it off and then hand it over to Bogdan. I'm going to mention this one thing I'll share on my screen in a second– if I can find the correct one!   

> **Sharing Screen** [[2:00]](https://youtu.be/qP4SSKuDFOs?t=120)

We have the BarnBridge snapshot up. You can now search up BarnBridge, where you will find our page and proposals.

You can use two links to get there:
https://signal.barnbridge.com/
https://snapshot.page/#/barnbridge.eth

All the discussions will take place on Github. We are still tweaking things, but we will be ready for the DAO launch.

With that said, I'm going to stop sharing my screen.

> **Screen Sharing Ends** [[2:35]](https://youtu.be/qP4SSKuDFOs?t=155)

I'm going to hand it off to Mr. Bogdan G. You all know him. You all love him.

Bogdan G. 😎

## BarnBridge App

**Bogdan:** Alrighty, thank you for the intro. Same old. I'll take you through the products and then updates on the dev side. First off, yield-farming, nothing has changed. The three pools have continued, and there have not been any issues reported. We've made some polishes but have not released them yet. You will see them in a couple of weeks when the DAO launches.  

### BBDAO

**Bogdan:** The audits should be finished by the end of next week. We've spoken with the auditors, we have only heard good news so far. There are no known issues. It should be a smooth ride on the smart contract side. 

We've deployed the final version of the backend. We kept adding and polishing things as needed by the ongoing frontend work. And with that, I can give you a quick demo of the frontend.

#### UI Walkthrough
> **Screen Sharing** [[3:52]](https://youtu.be/qP4SSKuDFOs?t=230)  – the promised teaser from the last call.

Here it is– this is how the DAO will look. The overview page is a similar layout to the yield-farming page on the app. We will display stats about the BOND locks and the dispersion of votes. I'll show you the wallet, where you will stake BOND in the DAO. Really similar to the layout and structure of the yield farming app. But keep in mind there are quite a few things to tweak and add. 

We have the base functionalities so far: Enabling tokens, deposits, staking in the DAO, withdrawals, delegating etc.

You will see a change from my wallet balance to my staking balance and how it reflects my voting power. As you can see, I now have the same total voting power as I have staked. I can delegate my votes to another address/someone else. 

You can see my status changed from total voting power — total delegated voting power. I can also pull up a window to get an overview of my BOND balances. 

*Note- you cannot partially delegate your votes.*  

When you delegate, you give up control of your votes. So your total voting power is now zero. 

**Troy:** Will there be a way to denote where votes get delegated? Have we discussed that? Similar to Compound.

**Bogdan:** Like a list of how many votes get delegated? 

**Troy:** Like whose wallet, similar to Compound, they have labels that say you're delegating to Consensus or A-16C.

**Bogdan:** Delegate addresses will show in the wallet overview– in the delegate section. And in the detailed view of your voting power balance.

When I have not delegated my votes, I can also lock my staked balance for a set period to obtain a bonus. There will also be a chart that will display the decay over time. However, that is not working at this moment. The bonus multiplies your voting power based on a set period. 

For example, with a one month lock and I get a 1.08x multiplier. A full year would net me double the power, but my balance is locked for the foreseeable future as withdrawals are now disabled.

So that's how the wallet section of the DAO will work. Where you can deposit, stake, lock and withdraw your BOND.  

The proposal section is where we will create suggestions and vote on them. We have some examples here of tests. There are still some tweaks to be made. But the functionality is there, and it's linked to our rinkeby test net contracts.  The discussions tab will connect to the BarnBridge snapshot page.

That's pretty much it for the DAO

### Smart Yield BOND

### Smart Alpha BOND

# Operations

## Coinbase Custody

## AAVE Support

## Bounties/Bitcoin Talk

## Website/Discord Community Update

## Operations/Marketing Rundown

# Round Table