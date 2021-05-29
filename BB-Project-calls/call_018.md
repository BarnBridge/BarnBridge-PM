# BarnBridge Project Call 018 Notes 
### Meeting Date/Time: Thursday 2021/5/27 at 15:00 UTC
### Meeting Duration: 17 mins
### [Github Agenda Page](https://github.com/BarnBridge/BarnBridge-PM/issues/31)
### [Audio/Video of the meeting](https://youtu.be/5GkPZjRZOAE)
### Breakdown: 

Moderator: Troy Murray

Scribe: Rayne L.

Attendees: Troy Murray, Mark Ward, Pavlo Bendus, Vitalik Cherniak, Milad Mostavi, Dragos Rizescu, Bogdan Gheorghe, Tyler Ward, Max Fiege

## Intro [[00:00]](https://youtu.be/5GkPZjRZOAE)

**Troy:** Alright, everyone! 

Welcome to BarnBridge Project Call 18!

There have been a lot of changes around here. What we're going to do is jump into the dev and tech side. I'm going to hand it off to Bogdan without his cool sunglasses on. 

**Bogdan:** Oh, give me a second.

The most important part. 🕶️

## Tech/Dev [[00:28]](https://youtu.be/5GkPZjRZOAE?t=28)

**Bogdan:** Okay, then. 😎

I'll keep it shorter this week. We've finally caught up with the promised released schedule. For a couple of weeks, we missed– we pushed around three major improvements in one week. So, we made up for the lost time. 

We have almost the same bullet points as last time. They are follow-ups for anyone keeping track. 

### Yield Farming [[01:02]](https://youtu.be/5GkPZjRZOAE?t=62)

**Bogdan:** We published the new UI, and it's now consistent with what the Smart Yield reward pools have. So, you've probably noticed that. 

We've released the public testnet app. It has faucets, and anything you need to know about it is in the docs– and the UI. Anyone can use it now. They can start playing with the DAO and using Smart Yield without being on the mainnet. 

We also talked about a public API. It's not a public API– a single third party is using it. They are trying to aggregate some data that we offer. We keep getting requests for data in the community. So once we have the chance to spin up proper docs for those, we will have a public API. Anyone who wants to pull BarnBridge data can start using that API. 

### Governance [[02:01]](https://youtu.be/5GkPZjRZOAE?t=121)

**Bogdan:** I think we passed the proposals during the queue period. We are kicking off the Cream & Aave rewards with those. We are also seeding the Bancor BOND/BNT pool and some other tactical administrative spending with the second proposal.

1. [Incentives for AAVE and CREAM SY junior tranches](https://signal.barnbridge.com/#/barnbridge.eth/proposal/QmW8armbvxmwFCD5GpCkrQcTBReYFSbnf8Hp3uFHBfzaRT)
2. [Seeding the BOND/BNT Bancor Pool](https://signal.barnbridge.com/#/barnbridge.eth/proposal/QmNNk4sn56SjudokxwZ6C3W2ALZRTAfDaUL9eVmUSJfYKY)

Those get done in three days. So, anyone looking to get those early juicy APYs in the Aave and Cream pools– get your stablecoins early and warm up your left mouse click.  🖱️💥🦍

### Smart Yield [[02:38]](https://youtu.be/5GkPZjRZOAE?t=158)

**Bogdan:** Pretty obvious, anyone listening to this call knows that we launched the Cream and Aave integrations. We still haven't started the rewards pool. So, not a lot of TVL has gathered in those. But, they are working as intended. We had audits done for them. They should get published in the same repo as the community call Agenda– I think. You can find them somewhere on the BarnBridge Github.

[All of the audits](https://github.com/BarnBridge/BarnBridge-PM/tree/master/audits). Including the [Aave & Cream](https://github.com/BarnBridge/BarnBridge-PM/blob/master/audits/BarnBridge%20SMART%20Yield%20(aave%2Bcream)%20audit%20by%20Hacken.pdf) ones.

The integration with Aave + Polygon is nearly complete. Mainly the front-end needs to be adjusted to allow for users to switch networks seamlessly. Then it should go up. So, that's exciting. 

### Smart Exposure [[03:41]](https://youtu.be/5GkPZjRZOAE?t=221)

**Bogdan:** Final steps with this. We are also releasing a Polygon version of this after the release on the mainnet. We'll have two products on Polygon at nearly the same time. 

### Smart Alpha [[03:59]](https://youtu.be/5GkPZjRZOAE?t=239)

**Bogdan:** There are no critical follow-ups here. Sorry, everyone. It's a work in progress, not a lot I can share at this point. 

That's essentially it. There are tons of other stuff– tons of third-party integrations in the pipeline. Tyler might say more about those– he may say more about some and less about others– we have multiple deployments planned. The one I talked about, and we are also looking into [Arbitrum](https://arbitrum.io/). 

So, yeah, aside from that. There are tons of new product ideas to start working with– we have a fun summer ahead of us. 

**Tyler:** Troy and I muted ourselves and started talking about Arbitrum. I think the whole industry will be talking about them soon. It's a one-click EVM optimistic roll-up solution– so it's more technically sound than Polygon or Binance Smart Chain. 

What Uniswap did yesterday. (with Hayden) He has been working his ass off with Kain. And the fact their community passed that unanimously– [they said that they're immediately going to deploy resources into looking at using Arbitrum](https://twitter.com/haydenzadams/status/1397675094001045508)– I would be quite surprised that within a month, the whole industry will be on there.

I also posted in the forum. I'm not going to dox who it is. But, one of the founders of the three integrations we are on: 
- [Cream](https://cream.finance/)
- [Compound](https://compound.finance/)
- [Aave](https://aave.com/) 

One of them told us they are also building to Arbitrum. Last week the Arbitrum team and we are super impressed. We should be taking that seriously and looking into it. However, we have to wait for it to play out. We can't just deploy Smart Yield to Arbitrum. Someone– either Compound, Cream, or Aave has to go there first. We have a bit more autonomy with Smart Exposure and Smart Alpha. With those products, we slightly control our layer two destiny. 

The short answer is, I think we'll be looking into Arbitrum. And we'll be taking them extremely seriously– like the rest of the industry. I'm super impressed by what [Mariano Conti](https://twitter.com/nanexcool) from [MakerDAO](https://makerdao.com/en/) said. He was playing around with their testnet, and he was blown away by Arbitrum. If they are that good then everybody's going to find out soon enough. 

**Troy:** That's his TedTalk. (TylerTalk 😋) 

Cool, there is a lot of stuff going on with the tech and dev side. A lot of the exciting stuff, honestly. I'm pumped to see how this all plays out. And I think it launched today. 

**Tyler:** I think the 27th. Is it the 27th?

**Troy:** Yes, it's the 27th, so it launches today.

So, maybe we'll have an explosion of news coming out later.

Let's move onto operations. 


## Operations [[07:27]](https://youtu.be/5GkPZjRZOAE?t=447)

**Troy:** I'm going to hand it off to Pavlo, who has been working tirelessly with Vitaly, Max and Mark– around all of this.

Pavlo, I'll let you take it away.

### Pavlo  [[07:40]](https://youtu.be/5GkPZjRZOAE?t=460)

**Pavlo:** Thanks, Troy.

### Website

**Pavlo:** First of all. Website v2. It took a bit longer to make because of all the little things around adjusting the media elements. We've been doing a lot of slight polishes. We completed the English version of the [website v2](https://github.com/BarnBridge/barnbridge-frontend/releases). It's ready and uploaded to Github. We're only working on the deployment. It either comes today or tomorrow. 

So, that's good news. 

Other than that, we got the profile on Messari updated. We submitted the information for that a couple of weeks ago, and they've finally updated it. So, all of the available information about the protocol and the recent events, roadmap milestones have been updated.

[Messari BarnBridge Profile](https://messari.io/asset/barnbridge/profile)


### Developer Docs [[08:37]](https://youtu.be/5GkPZjRZOAE?t=517)

**Pavlo:** On the Integration team side. We've made great progress on the developer docs. These will also get released in the coming days. So, we'll put out the developer docs on Gitbook and updated readme files for the Github repos– for the actual products and Smart contracts.


### Chainlink Price Feeds [[09:06]](https://youtu.be/5GkPZjRZOAE?t=546)

**Pavlo:** Another important milestone has been reached– [we co-announced it with Chainlink yesterday](https://twitter.com/Barn_Bridge/status/1397554847352827908) –a Chainlink price feed for BOND/ETH & BOND/USDC got launched.

[ChainLink Tweet](https://twitter.com/chainlink/status/1397553276388786176)

BOND/ETH got launched on the mainnet, and BOND/USDC got released on Polygon. That's goods news because it opens up the doors for further integrations with other products and teams. 

Also, we've been talking (especially Tyler) about insurance protocols.  

Tyler may cover this later. There is a lot of stuff going on there. 

A lot of stuff is happening. I'm excited about this. 

**Troy:** Cool. 

Then Max, do you want to talk about Cream France and MAI France?

### Max [[10:23]](https://youtu.be/5GkPZjRZOAE?t=623)

**Max:** Adding onto Pavlos updates. We will be engaging with a few other communities– trying to pass proposals relevant to BOND.

### Cream France / MAI France

**Max:**  So, we'll be trying to get collateral approved for BOND on [Cream finance](https://cream.finance/). It will allow users to borrow against their BOND. As opposed to lending it out– this is the case currently. 

Secondly, we'll be working with [MAI finance](https://www.mai.finance/). And their Qi DAO platform they're currently deployed on Polygon, and you can think of them as a federated single-collateral debt platform. 

What that all means is: If we get approved by their community governance– you could mint synthetix tokens against your BOND on their Polygon-based platform.  

Similar to how you might be minting DAI against ETH in the MakerDAO ecosystem. 

I'll be writing a community representative post on their forum. Ideally, we get through their governance process. 

Lastly, after passing the third DAO vote, we'll have 50,000 BOND deposited in the Bancor BOND/BNT pool. Hopefully, that will be quite the splash as to where we can discuss the potential of BNT liquidity mining rewards– for participating in that pool. 

**Tyler:** One final thing– so the community knows. 

I've been talking with Stani, Jordan (Aave) and Santiago ([ParaFi](https://www.parafi.capital/)). Once these rewards go live, and we do have reasonable TVL on Aave. We'll submit a vote– actually, ParaFi will likely create an AIP for us to get listed on Aave. 

So, based on the timing of that. We'll all work together to engage the communities. It's a timing thing. But, we are coordinating the best times to do this. Let's say it will probably happen in about two weeks. 

**Troy:** That's pretty cool. 

That's a slight alpha leak. 😉

Did you want to talk about the insurance stuff?

**Tyler:** So, the insurance stuff in general– I've been quite public going back to October. I'm very interested in insurance for crypto. And I review every single protocol in-depth and how they work. I've invested in quite a few of them personally. BarnBridge has not invested in them. However, that was intentional. Because I was a seed round investor, I advise on these projects and help them. 

Other than Nexus because that existed before BarnBridge– I talk with [Ricky](https://twitter.com/rkstan) a lot because I'm interested in insurance. So, Nexus is working on whitelisting us. It'll happen next week. Bridge Mutual launches in early June they will be listing us.

Some of this will have to go through a DAO vote, and I'll organize it with Max. Some of these things we'll have to see. I talked with DeFi Ted, and we are already on Cover. But, we need to figure out what is happening with Cover v2 and find out how safe everything is. But, Nexus, Bridge Mutual and [Risk Harbor](https://www.riskharbor.com/). (another insurance protocol I'm excited about) 

Risk Harbor has already written a bunch of code for BOND. When they launch, they're launching with BOND– mostly the Junior side, because Seniors are NFTs so they have to prepare code for that. They are trying to make it to the mainnet.

Finally, I invested in a company called [Evertas](https://www.evertas.com/). They do off-chain insurance for on-chain contracts. And I've kept in close contact with Kain and Jordan from Synthetix. They invested in a group called [Nayms](https://nayms.io/). They are doing the same thing. Both groups are out of Bermuda, where the majority of the re-insurance for the world funnels through. 

When off-chain insurance comes on for on-chain contracts– I'm talking with all those companies. I'm trying to lock up as much insurance for BarnBridge as possible. Because that essentially makes or breaks it for TradFI. So far, we've only had on-chain contracts. And I've said before it's the spiderman meme of him pointing at himself. 

> You are insuring Smart contracts with Smart contracts.

So, we do need off-chain primitives to come into our space. But, that means someone has to build a legit (off-chain) insurance company, and that's what [Naymes](https://nayms.io/) and [Evertas](https://www.evertas.com/) are. So, they are coming into the market, but they are not here yet. For now, we have to deal with on-chain insurance protocols. Which are all the over groups I covered.

**Troy:** Another fascinating thing that Max brought up in a private chat. 

It goes back to the seeding of these things. We could use the fees that get generated in the first couple of months as a way to backstop. To insure these by the people who've used the products. 

I thought that was a good idea. It still needs to be fleshed out. But, I think it's a good use of the initial fees– IMO.

With that said, we don't have any questions on the Round Table.

I'm sure there are questions that the community may want to get answered. But, I think we leave it at this. 

Unless there is anything else that anyone on the call would like to go over?

**Everyone:**  🦗🦗🦗

**Troy:** Alright! Cool. 

Okay, everyone, we'll see you in two weeks. 

A lot of stuff is coming out, so there should be several updates in the next two weeks. 

Anyway, have a great two weeks! 🖖

**Everyone:** ✌️✌️✌️✌️✌️✌️✌️


<br>

### Relevant Links

* [Website](https://www.BarnBridge.com)
* [DOCS](https://docs.barnbridge.com/) 
* [Project Management Hub](https://github.com/BarnBridge/BarnBridge-PM)
* [Agenda](https://github.com/BarnBridge/BarnBridge-PM/issues/21) 
* [Twitter](https://twitter.com/barn_bridge)
* [Discord](https://discord.gg/NwXHd3z)
* [Youtube](https://www.youtube.com/channel/UC4exzX_c37p2gYJK4L9nrGQ)

<br>

* [BarnBridge Shop](https://www.barnbridge.shop/)
* [Bond.Bet](https://bond.bet/)

