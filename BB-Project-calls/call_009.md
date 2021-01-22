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

* https://signal.barnbridge.com/
* https://snapshot.page/#/barnbridge.eth

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

***Note***- *you cannot partially delegate your votes.*  

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

**Bogdan:** We are in the final stages. There is a big update coming. Frontend work is beginning next week. We have the UI– I feel as if I should have shown at spoiler for that. But, it's better off if we leave that for the next call. I gave a DAO spoiler this call, and we can have a Smart Yield UI teaser next call. 

Frontend work starts next week. Smart contracts audits are in the first week of February. We are just writing tests, and so far, everything is running smoothly.

### Smart Alpha BOND

**Bogdan:** We've made similar progress on the Smart Alpha BOND. We have started the wireframes, and our advisors at Atpar will be doing a lot of the development. There are two versions. We keep adding stuff and moving things around so the end product will be cool.

**Troy:** Right on. Thank you for the update on that.

 **Tyler:** You are doing a great job! I know you hate doing this, but you did awesome! The DAO looks awesome.

**Bogdan:** I don't hate it. It's just my bi-weekly dose of cringe. I'm not a public speaking type of guy.

That's why I hide my eyes...😎 so you can't see the tears. 💧

**Everyone:** Chuckles! 😂

**Troy:** Solid. I think we can move onto operations.

# Operations

### Coinbase Custody

> [Update](https://twitter.com/CoinbaseCustody/status/1348739247277268997?s=20)- In case you missed it.

**Troy:** Just to give a quick update. A lot of the community probably noticed we were added to [Coinbase Custody](https://custody.coinbase.com/assets)— which was a long time coming. A lot of hard work went into getting that done. There was a large amount of support from the team on that.

### AAVE Support

**Troy:** Another noticeable thing we did– we submitted to Aave to get BOND listed on the collateral list used for their lending protocol. It's currently under review by their risk-team. 

So the protocol is:

* You submit the [AIP](https://aave.github.io/aip/)- (Aave Improvement Proposal)
* The risk-team looks at the AIP, and you receive a grade
* The proposal's put on-chain (Usually two-weeks)

I'm hoping the risk-team stays on top of things. Apparently, they are very busy. Fingers crossed there is news on that by the next time we talk. We should be hearing positive movements there by next week.

**Tyler:** I want to add some things about listings. So that everyone in the community knows. Sorry for interrupting you, Troy. 

We get a ton of questions about when we are listing with major exchanges. I want everyone to know that the reason why large North American exchanges won't list you for retail customers until you have a live product with utility— there are regulatory reasons. And for those same reasons, we shouldn't be pushing for listing on any major exchanges. At the least until the DAO launches and most likely not until Smart Yield goes live. 

For every one that asks: Wen this exchange? Wen that exchange?

Other than Binance because they have a different set of rules in Asia. The legit exchanges are not going to list us. For the same reasons, we should not be trying to get listed. Without products, anyone acquiring BOND right now is purely speculating. When there is actual utility, then that gives everyone a reason to want to obtain BOND. 

I want the community to know that. So the community stops asking about listings. It's not like we are slacking or not doing our jobs. We should wait until we have released products before making pushes towards those things. 

Troy, you can go back to what you were saying. 

**Troy:** Okay, so I was going to segway into bounties. So I'll pass it to Mark to give an update about that and the Bitcoin talk post. 

## Bounties/Bitcoin Talk

**Mark:** We had someone reach out to us on Discord– we were looking for someone to help us with a Bitcoin talk post. We were not necessarily sure if us posting directly was going to be enough. Someone was nice enough to reach out to give us the ability to post from an aged account. We are working on that post now, and it should be up within the next two days. If any of you are apart of the Bitcoin talk platform, look for that post it'll be in the alt-coin section. I know sometimes things get hidden in that section, but that's where we were recommended to post it. So if you look for it, that's where it will be. 

One major thing we are looking for help within the bounty programs. We need some people who can proof-read Japanese. I've had a lot of trouble finding proofreaders. We've translated the website and the whitepaper, but there hasn't been a way to proof-read it. 

**Tyler:** Mark, I can help with that. Follow up with me after the call. The Centrality team that invested in BarnBridge during the seed round has a lot of Japanese connections. I know a few Japanese people as well. They told me – the translation cost per-word in crypto that we offered was below the typical threshold, and there are pretty strict standards already.

I have people in my DM's that can take care of this. So let's take this offline, and I can take care of it with you. 

**Mark:** Cool. Then for right now, we do not have a lot of bounties active outside of those. We are working on getting more bounties for the community. Right now, the main thing is the meme competition. Tyler has been enjoying and using quite a few of those memes. 

One request from Tyler this past week– we've had plenty of memes about price, and although they are funny, they are not as useful– because Tyler cannot post the memes about the price. Price memes are fun and all, but those memes are not as valuable. The meaning of the memes are for us to have some ammunition, and everyone can have some fun. We certainly appreciate it, but I say hold off on the price memes. Because they are most likely never going to be used officially by BarnBridge.

**Tyler:** Yeah, with official BarnBridge things, we cannot comment on the price. No-one on this call can talk about the price of BarnBridge, because it was a valueless governance token when we launched it. The community can say whatever they would like. We won't censor your freedom of speech. But we cannot use those memes for anything official. 

**Mark:** Yeah, I was putting that out there. We may pick it as a winner, but there's practically no chance we ever use it officially.

**Troy:** If anyone is going to Bitcoin week in Miami. In two weeks?

**Mark:** I believe it's next week.

**Troy:** Next week, our own Mark Ward will be there. So, be on the lookout for Mark. 

**Mark:** I will be speaking about Blockchain and doing a panel on basic DeFi and what's been going on this year. If anyone is going down there– please, do not be afraid to come up and talk to me. I love meeting new people and talking, so come up and introduce yourself to me. I'm excited to meet new people and people in the blockchain space.    

I'm quite excited to be talking. If you are down there next Wednesday for the Blockchain center, look for a BarnBridge panel. I'll be speaking there for about 20-25 minutes about BarnBridge and what our goals are in the space. 

So if you see me, pull me aside, introduce yourself and say what's up! I'm looking forward to meeting everyone.

**Troy:** Right on. Okay, I want to hand it over to Pavlo for an update on Discord, the community and the website.

## Website/Discord Community Update

## Operations/Marketing Rundown

# Round Table
