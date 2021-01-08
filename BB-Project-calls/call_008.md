# BarnBridge Project Call 008 Notes 
### Meeting Date/Time: Thursday 2021/1/7 at 15:00 UTC
### Meeting Duration: 25 mins
### [Github Agenda Page](https://github.com/BarnBridge/BarnBridge-PM/issues/11)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=MZsCqMeeWaM)
### Breakdown:

Moderator: Troy Murray

Scribe: Rayne L.

Attendees: Vitalik Chernyak, Milad Mostavi, Pavlo Bendus, Troy Murray, Bogdan Gheorghe, Tyler Ward, Dragos Rizescu, Akin Sawyer, Vlad Suciu, EJ Rogers, Keegan Selby, Mark Ward

## Intro

**Troy:** Welcome to project call 008! It's the new year 2021 has started. We are full steam ahead with product launching and the DAO. Based on the roadmap, we are looking at the end of January. Mid-late February for the smart yield product.

I'll be passing it on to Bogdan for updates on the products.

# Tech/Dev
## BarnBridge App

**Bogdan:** Hello people, Happy New Year. 👋😎🥳

As usual, I'll go through each product. Smart contracts, the front and back end development.  One after another. 

Yield farming, we've had people in discord and on social media asking about POOL 3 and what happens when the pool ends. The answer to that is **POOL 3 will end on February 7th.** After that, only withdrawals will be available with POOL 3. 

There will be no more deposits into POOL 3 after the end of the epochs. However, staking BOND for BOND will remain available, but it moves to the DAO, where there will be a similar but different distribution mechanism. 

### BBDAO

**Bogdan:** Smart contracts and audits, code is finished but still undergoing audits. Unfortunately, even auditors need their holidays. 😅          But good news, we are going to have them done by the end of the month. That's going to give us plenty of time to address changes. That puts the DAO launch around the 2nd week of February. We want to have the audits finished and incorporate any changes that may come from those. We also have POOL 3 migration— a smooth transition to the DAO staking.

After some more internal reviews about the DAO code, we found an unusual quark. It's nothing even remotely dangerous or critical. But it will be interesting to see if it comes up in the external audits.  We will let you know what it is at a later date.

We have deployed some versions of the contracts on Rinkeby. One of them is a short duration. We can test everything and put proposals through in a shorter time. Because if we used the main contract, we would only fit in a single proposal before the launch. We want to examine everything. We're testing multiple scenarios. So far, everything looks good and is working as intended. Proposals are passing, they're getting executed, changes made are working and taking place. So the smart contract is doing what it is supposed to.

Backend— not so glamourous. We've deployed the final version, everything is working. The frontend is in a great place. There are only a few things left. We are just making sure everything has been covered— for example, button functionality. We could do a demo because we have enough to show, but I did not prepare for that. 

So, next call— that's a promise to walk you through the product and have a look around the features.
 
That's it for the DAO.

### Smart Yield BOND

**Bogdan:** Smart contracts, audits, and development are in progress. We are just writing tests for the code. Wrapping up the final steps. The code will be opened up for auditors starting next week. This will be the first time outside eyes get to look at the code.

Backend— not too exciting. Specs are in progress, and everything is going to plan. Frontend, we just had a walkthrough for the UI. We are walking through it with the team and making sure we are not missing anything. Ensuring the whole experience looks and feels like it's supposed to. The same as last time, the frontend work is not yet started because we are still on the UI— the difficult part is the user interface and the user experience.

### Smart Alpha BOND

**Bogdan:** Smart contracts and audits, our friends and advisors at Atpar are working on the framework for both versions of the SMART ALPHA contracts that we will rely on. It's all going well. No unsolvable problems, just unsolved problems— it's looking good. We have seen cool models.

As promised, last time we talked, we were discussing which version to release first. We've decided on the variants, and soon we will most likely announce which version, the differences and when to expect them. Most-likely after the SMART YIELD launches.

We've also started looking into audits, booking slots. Perhaps around late March. Just making sure we have some good names behind the audits. 

Frontend and UI— no work is happening yet, but some wireframes are in progress. We can say for now that it will be heavily based on the SMART YIELD UI. 

I believe that's it! 😎👌

**Troy:** Cool! Thank you, Bodgan, for the update.

I just want to add, Tyler and I are focused heavily on the audits. We want to make sure that they happen promptly. But so the community knows, audits are hard to come by right now. Things can get slowed down. We give a timeline, but we are still controlled by other teams that need to do audits. Even if we book them, sometimes things happen. I just want to manage people's expectations. 

I also want to add— what's been going on with standards. This will be a pretty big initiative in Q1 & Q2 that rolls into something bigger. I don't want to talk about it yet, because I can't. Can't alpha leak. I want to turn it over to Akin for an update on DeFi standards.

## DeFi Standards

**Akin:** Happy New Year, everybody! 🎊🎉

So from where we left off last time, we pretty much have an internal draft for DeFi standards. We are just passing it around and making sure that everyone has input and that the first versions are robust enough to encompass our first two products. We have external reviews with some of our partners helping create these standards. We are getting their inputs to help make adjustments and potentially improve them. 

Conservatively over the next two weeks, we should have the documents finalized and published in a blog post or something similar and incorporate it into the BarnBridge website. This also feeds into our broader discussions with other partners around extending our standards forward— within two to four weeks, we should expand more on that and share meaningful information.

The other point to note is that it will accelerate more conversations with potential partners that would appreciate being involved in this initiative. Also, it will extend into additional partnerships with teams that would want to leverage the BarnBridge platform. I'm beginning to have those conversations as we get close to launch. So at least they're already in the pipeline, and there are discussions around that. So people can understand how to interact with our platform right away and get things going relatively quickly once we have launched the governance and our initial products. 

That's pretty much it.

**Troy:** I think that's a good primer for what we are preparing to do with standards and our products.

Mark will give an update on the bounties!

## Bounties

**Mark:** Hey everyone, my name is Mark. I'm going to update you all on the bounties.

I just recently put up all the meme bounties for the competition again. I've had questions regarding them, and we still are doing the meme comps! Keep em' coming in the discord. We love your memes. I know Tyler's been missing some of the Amish memes a little bit— those are his favourite. 

So, bring some Amish meme's to start the 2021 year.👨‍🌾🚜

Also, a project that I will need help with within the next week or two. I'll need someone from Messari to help build a profile for BarnBridge on their platform. I'll be setting up the bounty today. So if anyone from Messari is watching or knows how to create profiles. Please reach out to me in the discord on how to do this. Or reach out on Gitcoin, and I can approve you for the bounty. We can discuss it in DM's.

We are looking for new ways to allow dev bug bounties.

**Tyler:** One quick thing. Sorry for interrupting. About Messari, I've gone through that process with Andrew for Dharma Captial, so I have a list of emails for this. Reach out to me, and we can get this done.

**Mark:** Okay, cool. 

**Keegan:** We'll get into it with Jack Purdy at Messari. He's a close friend of ours.

**Mark:** Great, that will be easily handled. We'll set up a bounty for that and have someone from their team help us out.

**Troy:** Was Ser M handling that?

**Tyler:** Yeah, he can help out. We will take this offline and coordinate with everybody. It sounds as if a few of us know people at Messari.

**Troy:** What about the translations? How are those going? 

**Mark:** We have just recently translated Portuguese, European-Spanish. And Japanese just finished— we are just ironing out the details. Pablo and Vitalik are launching updates to the Russian, Spanish and Portuguese languages on the website. So look forward to the new translations of the website and the whitepaper. We have not changed the UI of any of the apps to other languages. We are still deciding when to do that.

We are making progress on the bounties and translating our project into more languages so that everyone can learn.

**Troy:** That's a good update for 2021. Where it's going and what we're doing. We should be expanding because I expect more Gitcoin integrations in the future, just based on conversations I've had with people. So look forward to that, everyone!

I'll hand it over to Tyler for an update on operations and marketing.

## Operations/Marketing Run down

**Tyler:** I'll just start with— we have a lot of updates coming out. 

As far as [Bond.Bet](https://bond.bet/) I'll approach first because I started a channel in the discord. If everyone would look at the website and provide feedback for that, we just started the smart contract work to do the integrations with pool together. It's coming along, and it should be done soon. We could launch some of the integrations with pool together before the DAO. But because of some of the DAO's staking mechanisms, we have to wait. We are holding off on announcing it for a bit until I can flesh out the best way to do that. That will just take me a bit of time over the weekend to write a Medium article about it. 

We owe everyone an updated roadmap. We'll do a rudimentary one running into the end of SMART YIELD. Then we can re-group as a team and consider the path forward. Once we launch Bond.Bet we will be launching the DAO. I assume we will play around with the DAO for a few weeks before-hand. By the time we are done playing around with that, I expect SMART YIELD to launch. 

We're also working with our investors on how to approach partnerships. I know Akin has been doing a ton of work on keeping a loose CRM of potential partnerships as we get closer and closer. Most connections will come from the SMART ALPHA product because of all the different advantages and use cases. Whether you are putting insurance products into it or an automated market maker. Providing liquidity tokens to it to compensate for impermanent loss. 

Not theoretical, but practical use cases are the areas where large partnerships will come from. Like ETH staking, but that won't come out until V1 of SMART ALPHA. The highest demand at the end of the day will likely be in ETH/DAI and WBTC/DAI. We need to get those up and running before worrying about the down-funnel. But just as a heads up, let's say SMART ALPHA comes out in March, then the collaborations and use cases that come with a launch will naturally happen after that.

There is another update I would like to give right now, but there is another sizeable Medium article that I need to finish first. 

So, I'll hold up, and everybody can just follow: 
* [Twitter](https://twitter.com/barn_bridge) 
* [Discord](https://discord.gg/bGEqrNdckT)
* [Medium](https://medium.com/barnbridge) 

We've been pretty heads down on getting shit done.

**Troy:** I'd just like to add, there's been a lot of exciting talk around what's possible with SMART ALPHA. I would like to push the community to keep expanding on different use cases. One of the recent ones we heard about was juicing AAVE yield— which I thought was an interesting idea. That came from Santiago over at ParaFi. There's a lot of different things we can do with SMART ALPHA. Again I just want to encourage the community to push innovation because it will help us determine what to focus on when we launch.

**Tyler:** Actually, and not to derail this, but I heard a cool one yesterday. I was in an interview with Constantine, Keegan you introduced me to him. He said, "If this is SMART ALPHA, what's SMART BETA?" I had never thought about that before. But once he asked me, I thought about it, and I realized that's a good idea. Because you could take our SMART ALPHA technology, and you could take an index like DPI. Because everything inside the SMART ALPHA will have a peg like DAI or USDC. So if you used Synthetix DPI as the peg or vice-versa, you could judge the performance of assets against a particular index. You would have the option to buy an overcollateralized position or an undercollateralized position. 

For example: 

1. *I'm bullish DPI, and long on the assets in the index. But I'm impartial to a specific asset in the basket—* **you buy the undercollateralized position.**

2. *I want to own all of DPI, but I'm really bullish on Synthetix—* **you buy a 70% price tranche for it.**

We could make SMART BETA with ease using the technology of SMART ALPHA. The problem with indexes is liquidity. You need liquidity for all the assets in an index & the inverse. We may want to create our own index of three assets to start with. SMART BETA is a cool concept as long as we can get liquidity right. I don't think it's a technical uplift, just a liquidity uplift.

**Troy:** Alright, cool. We can turn it over to the round table.

# Round Table
