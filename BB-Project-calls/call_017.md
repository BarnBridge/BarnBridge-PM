# BarnBridge Project Call 017 Notes 

### Meeting Date/Time: Thursday 2021/5/13 at 15:00 UTC

### Meeting Duration: 34 mins

### [Github Agenda Page](https://github.com/BarnBridge/BarnBridge-PM/issues/28)

### [Audio/Video of the meeting](https://youtu.be/eBbDtDl2p3A)

### Breakdown: 

Moderator: Troy Murray

Scribe: Rayne L.

Attendees: Troy Murray, Mark Ward, Akin Sawyerr, Pavlo Bendus, Vitalik Cherniak, Milad Mostavi, EJ Rogers, Dragos Rizescu, Bogdan Gheorghe, Tyler Ward, Max Fiege

## Intro [[00:00]](https://youtu.be/eBbDtDl2p3A)

**Troy:** Welcome to BarnBridge Project Call 17!

We are going to turn it over to the tech and the devs.

Bogdan, I think...

**Tyler:** The throne is yours.

**Troy:** Yes, the throne is yours.

## Tech/Dev [[00:13]](https://youtu.be/eBbDtDl2p3A?t=13)

**Bogdan:** I was going to say. The point where my name gets called out– what I live for every couple of weeks. 

Let us go over what happened here over the past two weeks. Maybe we will give some timelines.

### Yield Farming [[00:33]](https://youtu.be/eBbDtDl2p3A?t=33)

**Bogdan:** We promised a couple of weeks ago to publish a revamped version of it. Still not out because we ended up doing more than we originally planned. We missed the once-a-week release schedule over the last few weeks. That is because of the changes that we have made– even though they are not visible– It is worth it. 

We cleaned up the code a lot. It will be valuable in the long run, even if you do not see those changes. I will include a few more updates separate from the Yield farming side. 

#### Migrations [[01:15]](https://youtu.be/eBbDtDl2p3A?t=75)

**Bogdan:** We also did an infrastructure migration which was part of the reason for those delays. It served more than one purpose.

There were discussions about this last time, I believe I forgot about it, and Tyler had to remind me about it. 

#### Testnet App

**Bogdan:** We are releasing a public testnet app next week. I am committing to that timeline. It will be up next week, and It is separate from our development environment– it mimics the production app. We had to do some contract deployments. A few changes to the front/back end were required to accommodate that. It is all looking clean, and anyone can start testing things on Kovan– next week.

Another thing, for migrations, we are going to release a public version of our APIs. We keep getting requests from third-party aggregators that would like to obtain data for BarnBridge. They typically use the graph or ask for data directly. We will set up an API for them to use. It will scrape historical data and provide any sort of data points that they would like. 

#### Governance

**Bogdan:** A Snapshot vote for the Smart Yield incentives program began. It is about how much we allocate to each pool. So, there will likely be an on-chain DAO vote for that in a few weeks. 

### Smart Yield [[03:03]](https://youtu.be/eBbDtDl2p3A?t=183)

**Bogdan:** The things you have been waiting for and the Cream and Aave integrations. You guys know that gas costs are insane. The main reason we delayed the launch is because of this. It would cost around 20ETH to launch the 50/60 or so contracts that we need for both of those. 

The good news, they will start appearing next week. I want to launch Cream and then Aave the week after. 

Cream got delayed because they do not have anything on the Kovan testnet. So, we needed to deploy a version of Cream and test everything out.

The problem we talked about for Aave– the launch of their rewards program. We figured out a solution. It will be an interesting dynamic regarding the distribution of rewards. You will all see that when it gets released.

*The other markets will launch with **USDC**, **USDT**, **DAI** and **GUSD**. Those will be the markets for **Aave**.*

*For **Cream**, it's **USDC**, **USDT** and **DAI**.* 

So, there will be some overlap between them. However, it will be interesting to see the competition between each other. Also, as a precaution, it was not needed because the changes were not very large. But, to err on the side of caution, we will also audit the integration. And publish the reports for those. 

### Smart Exposure  [[05:02]](https://youtu.be/eBbDtDl2p3A?t=302)

**Bogdan:** It is in full-blown development mode. We have passed two audits and two revisions– one for each. The results were awesome– no bugs found. We passed the audits with flying colours. 

It should be out of production soon after the Smart Yield integrations. I will not commit to timelines on that one. Although, there are more announcements for that later with the Chainlink integrations and such– probably after the Smart Yield integrations are out.


### Smart Alpha  [[05:47]](https://youtu.be/eBbDtDl2p3A?t=347)

**Bogdan:**  Still no changes here– at least no updates that we are willing to share right now.  Other than it is a work in progress on the models. I can share that we have not started the Smart contract implementation on that. It is still in modelling– going well. 

We have some questions from the community. 

Should I address those now? 

Troy, Tyler, do we want to handle those?

**Troy:** Yeah, I think you can. A lot of it is about the development stuff. And then we can do operations afterwards. 

**Bogdan:** Yeah, exactly. 


### Community Questions  [[06:23]](https://youtu.be/eBbDtDl2p3A?t=383)

**Bogdan:** The first Question;

**Question**

> "I do not understand the dev set-up. So there are two dev teams? 
One is working on SE, and one is working on SY and SA? Or are there three teams? One for SE, SY & SA?
Feel free to answer them on Discord if you do not want to answer them on the call. Great work so far!"
 
 > -**fractaldirk**-

**Answer**

**Bogdan:** We do have two dev teams. There is a core developer team. They work on the products– formally announced on the roadmap & in the whitepaper.

- __Core Devs__
    - Smart Yield 
    - Smart Alpha & Integrations
    - Front & Backend 

Then there are our advisors at Atpar who work on the Smart Exposure contracts. 

- __Advisors__
    - Smart Exposure

You can say there are two development teams. But, we have all worked closely together on both of them. Atpar has worked on the Smart Exposure contracts, and as such, the core dev team is working with them to come up with the final product. 

**Tyler:** To add to that. On the Dmob side. Back in December-November. I do not think we shared this. I put it in Discord, so it is public. 
We slightly foresaw in advance that Smart Yield was going to require a lot of integration work. And, the original million dollars that we raised– we will never stop building Smart Yield– so we raised additional capital. At least a few million dollars, which allowed the dev team to expand. 

So, we essentially have three dev teams, In terms of groups working on stuff. But, it is all under Dmobb, and the Indian chief Milad keeps an eye on everyone. Making sure it gets done– properly. 

**Bogdan:** Peacekeeping and keeping us on a short leash. We are never leaving the house. That is why you always see me with this background. 

**Question**
> "If possible, please expand on the thought process for limiting senior minting abilities. I assume it is to protect juniors. Is there something else I am missing?"
 
 > -**mike9870**-

**Answer**

**Bogdan:** We had a forum talk about this where we mentioned capping the Senior rate at 65%. The reasoning for this is because we bootstrapped the Juniors with rewards at inception. And that skewed the pool from the start– in the way you currently see. It's around 1-90 or something, the ratio between Seniors and Juniors. It's not a situation that would typically happen If we had left the product alone without incentivizing the Juniors. 

Meaning– having the pool skewed in favour of the Juniors means the next Senior can lock in a large fixed coupon. A fixed-rate with minimal slippage for a long period that's very close to the original APY. That would essentially leave the Juniors exposed to some risks– This is where some people might ask how do we get Seniors on board? Why cap the Senior rates? 

It's not part of the reason why there are not many Seniors that have joined so far. And this cap will not serve to deter them. Whoever was going to join the Senior side would have done so after the limit as well. Part of the reason is also that the Juniors act as liquidity providers for Smart Yield– in a sense. Limiting exposure means that after the rewards end, we can still attack them and keep [Pavlo's loop](https://barnburner.substack.com/p/on-pavlos-loop) going. 

That's the reasoning behind that. The rewards will end at some point, and we need to keep the Juniors with as little exposure as possible to crazy coupons and interest rates– even during times when the pool gets skewed.

Does that make sense? 

**Tyler:** I fully support and bump what Bogdan just said. 

One thing I want to add just so everyone on this call is aware. So it's publicly recorded. I was on a Clubhouse call– let's say about two months ago. And Akin, you were on it as well. 

There is a group that Aave works with that does financial modelling on all of these platforms to identify solvency risk. So Stani essentially knew the dollar amount that Ether would need to crash too– for Aave to start having solvency concerns. They're a group, and I'm unsure if it's Gauntlet. However, there is a group that can run extensive tests for us. They're more of a financial auditing firm rather than a Smart contract auditing firm. But, they can help us make decisions whether or not it's 65% or 51%. 

I know we've written a lot of our models. Although, for the same reasons, our Smart contracts get audited. It wouldn't be bad once these products are released. We start getting higher TVL. If we figure out who that is, we can pay them, and it's like a second set of eyes– Stani said he was super impressed.

**Akin:** Yeah, It's [Gauntlet](https://gauntlet.network/). They do pretty sophisticated financial modelling for both Aave and Compound– who live and die by their ability to assess the risks associated with collateral. All their collateral ratios and such are all modelled out. I believe Gauntlet runs a lot of those models for them. 

**Tyler:** Milad, we should talk to them as a second set of eyes once everything gets released. In my opinion. 

**Akin:** We've started conversations with them. We discussed with a team member about their operations– to get an idea of what they are building. There are a few things on their side that they're working on which are non-public yet. Some of the stuff is very interesting. It's on the product side, and it's occupying their time right now. It seems that over the next few weeks, more details will become public.

Over time, as we release more and more products with varying levels of complexity. Having an independent review around that could be of help– for specific products. At day's end– Smart Yield sits on top of certain products. At least currently, with Compound and Aave, we sit on top of the risk-free curves that they have in place. As we extend it further out– the risk curve– perhaps there's room or capacity to engage them to assess other risks associated with different protocols. 

**Troy:** Okay, so, I guess we finished with the questions from the community. I think we can jump into operations. 

## Operations [[14:40]](https://youtu.be/eBbDtDl2p3A?t=880)

**Troy:** Pavlo and Max, would you like to go over the Discord restructuring. 

### Pavlo & Max 

**Max:** Pavlo, do you want to take that?

**Pavlo:** Yeah, I can. 

### Discord Restructure

**Pavlo:** We set up our Discord server a while ago. We've been adding channels here and there, and now we've realized we can make it better by restructuring it. Max and I went ahead and suggested an updated structure for the Discord. 

We also went ahead and changed the structure around already. Sorry, if there were some channels you may have liked– that disappeared. We're trying to make it more organized and remove the places we are not active in or any duplicates. All the main threads are still there. We also added some emojis to make it more visual and easier to navigate through. 

**Troy:** I love that! I think that's great. 

**Tyler:** I'm not sure whose idea that was. But that was a great idea. 

**Pavlo:** That was Max's idea. 🧠

**Tyler:** Good work, Max! 🦾

### Updates [[16:14]](https://youtu.be/eBbDtDl2p3A?t=974)

**Pavlo:** Yes, I can also give an update on some of my stuff. We've finally updated the Coingecko circulating supply metric. It now displays the correct number. Also, Coinmarket Cap has placed a blue checkmark beside the circulating supply. Which means it's the real circulating supply. 

We've also submitted the information to Messari for the update to BarnBridge's profile. Our profile is now getting worked on by Messari.

### Docs

**Pavlo:** Also, an update regarding the Docs. We'll be finally releasing the docs tomorrow by the end of the day. An updated doc structure. The new guides and some new outbound materials. That will all be on the docs at [BarnBridge.com](https://barnbridge.com)– I assume that the dev docs will follow after that. Perhaps the week after or so. 

**Tyler:** What about the website?

**Pavlo:** I'll hand over to Vitalik he has the latest information on the website.

**Tyler:** Nice!

### Website [[17:44]](https://youtu.be/eBbDtDl2p3A?t=1064)

**Vitalik:** Okay, so, regarding the website. We're at a good spot. Nearly 50% of the pages get done from the dev perspective. One more page needs to be done by the designers. Wireframes get done. 

We are aiming for the end of next week. The English version got completed. For the other translations, it will be a bit later. But, otherwise, Mark is going to publish some bounties for that. 

That's pretty much it for the website.


### Bounties [[18:33]](https://youtu.be/eBbDtDl2p3A?t=1113)

**Mark:** If anyone has done any translations for us in the past. I'm going to reach out to you. I'd like to give the work to the people who last helped us out. I know some people get busy, and some are not available. 

So, if any bounties cannot get done by the people who have done them before– I'll be reaching out in Discord. Via the various language channels– to ask for help. I'll also be posting bounties again on [Gitcoin](https://gitcoin.co/barnbridge). 

Look out for those. If you are interested in helping out– reach out to me via Discord. 

**Tyler:** Mark, everyone who watches this call will ask where you got that visor...!

**Troy:** Yeah, and the shirt. 

**Mark:** Okay, so, my shirt came from the BarnBridge shop. I had a mysterious box show up on my doorstep yesterday with BarnBridge on it. It got filled with some goodies. There were shirts and gear and hoodies. So, I don't want to spoil the drop that's supposed to happen today. 

I had this visor custom-made. I needed one with– BarnBridge –kind of for my brand. My friends call me the visor guy and mess with me by calling me the "visor crypto guy." So, I figured it was ideal for my brand. It also matched my Twitter picture– I needed one.

Anyways, look out for the [BarnBridge shop](https://barnbridge.shop) tonight! Thank you, Jen, for helping us out with that! And sending me some merch– I was excited about that box yesterday.

**Tyler:** Nice! 😎

Alright, the next on the list is Akin with operations. 

## Akin [[20:46]](https://youtu.be/eBbDtDl2p3A?t=1246)

**Akin:** I'll try and go through this quickly. There is nothing too new. 

### Business Dev Talks (cyber cap, leonteq etc)

**Akin:** We are still having calls with lots of TradFi entities who are curious and are trying to understand more about BarnBridge. And different stages of how to deploy capital into our products. So, we're continuing to build out those relationships. 

### Partnerships [[21:08]](https://youtu.be/eBbDtDl2p3A?t=1268)
 
**Akin:** On the partner side.


### **Chainlink Keeper Mainnet (Launch)** [[21:12]](https://youtu.be/eBbDtDl2p3A?t=1272)

**Akin:** We are engaging with Chainlink on several things. For some of our products, we are releasing. We'll be leveraging some price feeds for some future outputs. 

Also, getting the BOND price feed out is a big priority for us. It's a prerequisite for several potential integrations that want to leverage BarnBridge. So, we are working with them to walk through that and understand their process. 

They are also helping us with financial modelling– to help us better understand deployments on certain chains like Matic. They have price feeds there as well. 

### **EEA Membership (update)** [[21:57]](https://youtu.be/eBbDtDl2p3A?t=1317)

**Akin:** We joined the Enterprise Ethereum Alliance. We'll likely be on-boarded next week. Part of the rationale behind joining the alliance– which I did not elaborate on much last week– it's one of 'the' industry groups that bridges crypto/defi and traditional finance. So, a lot of conversations have been ongoing in that forum for a couple of years. 

I think it's a place for BarnBridge to have a presence.  

For at least two reasons:
To reach the right customers/users (that should know about us)
Driving thought leadership around our concept (novel ideas)

In the next couple of weeks, we should know more about: 
- How we will participate 
- How we leverage the alliance 

### **Open Defi / Defi Alliance (updates)** [[22:53]](https://youtu.be/eBbDtDl2p3A?t=1373)

**Akin:** OpenDeFi– as some may have noticed, has transitioned into becoming a DAO If everyone can read the medium post. 

> **Incase you missed it– [Introducing: OpenDeFi DAO](https://opendefi.medium.com/introducing-the-open-defi-dao-f4bb31dae36a).

There will be some announcements once they launch and have a mainnet– it's pertinent to the community. We'll share that announcement– when it's out– in the Discord. Be on the lookout for that!

DeFi Alliance is having a 'founders series' of short talks. They'll get released under their umbrella. So, we'll be participating in that. It's nothing huge. Simply a high-level view of projects that are a part of the alliance. They're doing some marketing around that. Something should come from that over the next few weeks. 

That's pretty much it.  

## Max  [[23:49]](https://youtu.be/eBbDtDl2p3A?t=1429)

**Max:** I can follow up with that. 

Pavlo and Akin have covered most of the things that we've worked on together. But, two things I'd add. 

### China Community Management 

**Max:** On the China Community Management front– Leo is slated to attend three conferences over the next few weeks. He's been doing a lot of legwork when it comes to other projects in the crypto space as well as centralized entities. I'm looking forward to seeing how that turns out over the next few months.

### Starkware & Immutable

**Max:** The other thing I would add– for anyone interested– we've been engaging regularly with the [Starkware](https://starkware.co/) ecosystem. We've had multiple calls with Diversify. We'll be speaking with [Immutable](https://www.immutable.com/) later this week. It's been interesting to see all the different ways that layer two strategies can come about. 

We're working on Matic deployment. But, it's becoming clear to us that the future is multi-layer-2. So, we're excited to see where those conversations go over the next few months.

## Tyler  [[25:06]](https://youtu.be/eBbDtDl2p3A?t=1506)

**Tyler:** I put Layer 2 as a discussion point on the list. 

### L2 Works 

**Tyler:** It's more so about Matic/Polygon in particular. I think Bogdan and all of them will elaborate further at the right time. 

We're in a Telegram group with them. We ask questions and test everything to ensure it works everything. 

One thing I think the community needs to understand– it's been said before, I'm reiterating– for Smart Yield, we don't have control of layer two's destiny. What Aave and Compound or anything that we integrate with goes to– we are a money lego. We can't choose Optimism if no one goes there. 

For Smart Exposure and Alpha, we'll have more autonomy when they start to release. Then we'll become serious about looking into them. I think just like the rest of the industry– we are watching and seeing what works. We're all impressed by Aave's integration of Polygon. Not just us, but the entire industry is impressed. We still talk with Compound frequently to understand what they're doing. A number of us on this call still speak with Kain– so we know what they're doing. I'll say this we are monitoring it in general. And when Bogdan has solidified updates that he would like to share, we will.

### Tech integrations  [[26:45]](https://youtu.be/eBbDtDl2p3A?t=1605)

**Tyler:** My name is under tech integrations. I'm not sure what that means. However, for the basis of this call– we've spoken on topics related to integrations we are working on. I don't think I have anything to add about it.

One final thing. When we first opened up this call monologue/agenda someone had said:

> "Tyler, explain BarnBridge; Smart Alpha and Smart Yield– like I'm five."

There is a [Youtube video](https://www.youtube.com/watch?v=x8jR0AsQTPw) that dropped. I think we should post it with this when we post to Twitter. There is a guy named Mazza who started a new series and kind of pretends to be an idiot. He gets you to explain a protocol and a product. 

It's like an hour and a half. It's informative, and if you're joining right now and are at this stage of the call and you don't know what we're building– I'd invite you to watch that video. I think it's good.  

**Mark:** It's a really good video. I've sent it to some of my friends who've had troubles understanding BarnBridge– even though I've explained it multiple times. They said that video finally helped it click for them. I suppose, when you describe it, you can go over everything and explains it in full. That video does well going over it and breaking it down– as Tyler says. 

**Tyler:** Also, shoutout to that guy! He followed up with me and stayed on top of everything to do that video. He's trying to do crypto for idiots where he talks to various founders. He pretends to be an idiot for the call– but he's an intelligent guy. The format was impressive. I'd tell everyone to follow that person in general. I was very impressed by him, and I like him.

I want to give him a shoutout for staying on top of me and spend time doing that.

[TheCryptoIdiot](https://www.youtube.com/channel/UCXlobB6ZGsBXc57utGRHfjQ)


**Troy:** Cool!

Alright, is there anything else we want to go over on this call?

I think we've answered all the questions from the community.

## DAO Votes  [[29:10]](https://youtu.be/eBbDtDl2p3A?t=1750)

**Max:** One thing I would like to add. With Cream deploying next week presumably, we'll be rolling most if not all of the snapshot votes that we've been voting on the past few months into that. 

Because of the ten action limit per DAO vote, we'll have all those wrapped with the Cream deployment. When Aave deploys, we will do a vote on-chain purely for Aave rewards.

**Akin:** I want to add one thing I think would be helpful. Max has been doing a ton of research around distribution. Over the long term, part of our success will rest upon how our products get distributed in secondary markets. Whether It's an ERC-20/J-token or an NFT/Senior or whatever else we may produce down the line. 

A big part of the goal is ensuring you have liquid markets for all these assets. In some of the calls we've had with TradFi folks, that's an area they look for– the ability to turn over an asset that may not yield for a year. A liquid secondary market makes assets more attractive. 

Max has been doing a lot of research there. Not only layer twos and distribution channels. We are spending a lot of time there and seeing how things evolve. It is an ongoing area that will become more and more important as time goes on. 

I am to putting that out there. We have discussed it before. But, I would like people to be aware of that. We are actively working on a view and strategy for how we approach this moving forward.

**Max:** To that point, one of the questions we have on the agenda today. Regarding the ten weeks, for the rewards, we are voting in. The idea being– ten weeks allow us to accumulate TVL while we finalize our thinking around subsidizing junior secondary markets. Instead of staking what you already deposited in Smart Yield. Because there are a few different ways to do that, we want to ensure we do not rush any single solution above another. 

**Akin:** The core theme that max is alluding to– for a liquid secondary market to exist, you also need liquid assets. We need a TVL build-up to create the assets that can get distributed to secondary markets. To some of the comments around our approach to incentivizing the pools, we are launching. Part of the view to attain TVL is not to get a land grab, but we need it for liquidity. Which then liquifies secondary markets, and we have better distribution. And that attracts more TVL at the top. Because the more liquid the market, the easier it is to enter and exit products freely.

There is a method to the madness. Every decision has a long-term view behind it– that is a comment for those on the forum who gave push back around the rationale of the TVL strategy.

**Troy:** Go ahead, Tyler.

**Tyler:** I was going to say, if no one has anything else to say, I think we are good to break this off. 

Final thoughts, anybody?

Shoutout to Vitalik for giving away all that money: 

- [Gitcoin: MultiSig](https://etherscan.io/tx/0x2fb8b58f85ab4773da00771f7f1e1a9eacf99af0ef3310b75ebcd017099f7b3c)
- [India Covid-Crypto Relief Fund](https://etherscan.io/tx/0xb65bcbb85c1633b0ab4e4886c3cd8eeaeb63edbb39cacdb9223fdcf4454fd2c7)

**Troy:** Pretty cool move! 

**Mark:** Shoutout to Vitalik! 

**Troy:** A billion dollars!? To legitimate charities...that's pretty cool. 

**Tyler:** That was a super flex. 

Also, shoutout to the Sushi team for buying Uniswap.com– that was probably the funniest shit that I saw in years. 

Good work!

**Troy:** Also, shoutout to Satoshi. 

**Tyler:** For not coming and showing his face– after all this time.

Alright, bye, everyone. Have a wonderful week! 👋

**Everybody:** 👋👋👋👋👋👋👋👋👋


<br>

### Relevant Links

* [Website](https://www.BarnBridge.com)​
* [DOCS](https://docs.barnbridge.com/) 
* [Project Management Hub](https://github.com/BarnBridge/BarnBridge-PM)
* [Agenda](https://github.com/BarnBridge/BarnBridge-PM/issues/21) 
* [Twitter](https://twitter.com/barn_bridge​)
* [Discord](https://discord.gg/NwXHd3z)
* [Youtube](https://www.youtube.com/channel/UC4exzX_c37p2gYJK4L9nrGQ)

<br>

* [BarnBridge Shop](https://www.barnbridge.shop/)
* [Bond.Bet](https://bond.bet/)

