# BarnBridge Project Call 016 Notes 
### Meeting Date/Time: Thursday 2021/4/29 at 15:00 UTC
### Meeting Duration: 36 mins.
### [Github Agenda Page](https://github.com/BarnBridge/BarnBridge-PM/issues/27)
### [Audio/Video of the meeting](https://youtu.be/DgTUvvK4vt0)
### Breakdown: 

Moderator: Troy Murray

Scribe: Rayne L.

Attendees: Troy Murray, Mark Ward, Akin Sawyerr, Pavlo Bendus, Vitalik Cherniak, Milad Mostavi, EJ Rogers, Dragos Rizescu, Bogdan Gheorghe, Tyler Ward, Max Fiege

## Intro [[00:00]](https://youtu.be/DgTUvvK4vt0)

**Troy:** Welcome, everyone! To BarnBridge Call 16!

Big day today. I'm going to hand it over to Bogdan G. for the updates.

## Tech/Dev [[00:14]](https://youtu.be/DgTUvvK4vt0?t=14)

**Bogdan:** Let me get my glasses on. 

These are much, much better. 😎

So, the overall team updates. We have had some delays. The delay brought both good and bad news. But, all in all, everything is going as planned. We may also have a couple of surprises. 

### Website UI Update [[00:49]](https://youtu.be/DgTUvvK4vt0?t=49)

**Bogdan:** For the Yield Farming, It was the first thing we launched– so it's now the oldest. So, we are giving it a new skin. We are also polishing it to make it more in tune with the rest of the app. No one requested it, but we are going ahead with it. 

We have seen a few requests for reworking the deposit and input forms across the app. Since we are doing the polishes, we will also make the other adjustments. Meaning we'll allow users to simulate inputs– with different balances– without enabling a token or without having a token balance. 

Think of it like Uniswap. You can adjust the amount in a trade field to see what would happen– without having the balance on hand. 

We should all be familiar with that UX, and if it's good enough for Uniswap, it's good enough for us. 

These are the cosmetic changes.

#### Governance (Still-unchanged)

**Bogdan:** There are plans for the future, but they're not in stone. We want to add distinct pages that display each address. So you can see certain users voting history and whom they delegate to, and so forth, sort of a user history page– similar to [Compounds](https://compound.finance/governance).

Some of you might know what that already looks like.

### AAVE Smart Yield [[2:47]](https://youtu.be/DgTUvvK4vt0?t=167)

**Bogdan:** Well, here comes the bad news. 

Aave ninja-released a liquidity mining program. Meaning, the working version of Smart Yield that we had running on the testnet. We need to adjust to account for that. Unfortunately, that also means we are back to where we were a couple of weeks ago. 

I have to repeat what I said before– Smart Yield for Aave is coming soon!

That's about it for the bad news. 

#### Polygon [[03:25]](https://youtu.be/DgTUvvK4vt0?t=205)

**Bogdan:** Now we have the good news. A two-prong for delivery:

We have a solution for the Aave liquidity mining, and we are already working on the changes to implement the solution.

With that, we can look into another request; a layer '2' implementation of Smart Yield– in this case, Polygon for Aave.

So, we are going to make good use of the delays and extra time. All of the changes will take place in parallel. These changes have their challenges.

For some insight: One of the challenges– bridging governance proposals. 

Whenever the mainnet DAO needs to change a parameter with the Polygon Aave Smart Yield– we would need to bridge them. A second challenge is claiming the fees that accrue on the Polygon bridge and moving them back to the mainnet. So, we are in contact with the Polygon team. We are getting advice on how to deal with this. We are confident that this delay will boost our timeline for layer '2' deployment.  

### CREAM Smart Yield [[04:54]](https://youtu.be/DgTUvvK4vt0?t=294)

**Bogdan:** Good news, number two! Even more use of the delay– with the whole Aave thing. We had a productive call with the [Cream Finance] team. So, we are planning on releasing a Cream integration with Smart Yield. It will also likely happen before the Aave rolls out. 

**TLDR;**

Aave Smart Yield got delayed. However, we hope to have a Cream and Aave L2 solution along with an Ethereum mainnet solution. Maybe that sweetens the deal and makes you guys forgive us for the delays. 


### Smart EXPOSURE [[05:45]](https://youtu.be/DgTUvvK4vt0?t=345)

**Bogdan:** This is the secret ninja that we have not released any specs for yet. We'll keep to the spirit of previously unplanned surprises. I hope we can keep it undercover at least for a couple of weeks still. 

On the last call, I believe we mentioned we were doing a round of feedback for the UI. I'll update that. We received the feedback and started on the development– It's going well. The front end is close to the finish line, and we should be connecting the front end to the contracts– sometime next week. 

### Smart Alpha [[06:40]](https://youtu.be/DgTUvvK4vt0?t=400)

**Bogdan:** The crowned jewel. Not a lot of updates. At least, not ones that I want to spoil. It's still a work in progress, and things are going well. I could say we are thinking of good use cases for it. I hope we get to plan some partnerships and integrations for that early on. So we can roll it out in style. 

I think that's everything. Did I miss anything from the Agenda?

**Troy:** The only thing would be the public testnet.

**Bogdan:** Oh, right. As I asked that question, the public testnet came to mind.

### Public Testnet [[07:23]](https://youtu.be/DgTUvvK4vt0?t=443)

**Bogdan:** Also, something that everyone asked for, I should have started with this first before telling people they can play with the inputs. 

We will have a public testnet implementation with a separate deployment for the contracts. Everyone will be able to play with those. It's also separated from the dev environment that we use. 

Probably the best way to understand Smart Yield and Smart Exposure is by playing around with it and seeing how it works. We are going to have faucets for the tokens. The Yield Farming portion will not be released on the testnet because it is redundant. So, we will only have Governance and Smart Yield. 

To get BOND tokens for the governance proposals. There will be a Kovan Uniswap: kETH -> BOND market.

For those that want to implement proposals and for some reason want a fair amount of BOND tokens– those will be mintable. There will also be a specific forum category for those that can provide good reasons for needing the tokens. 

Then we may just mint those tokens so that they can create the proposal and pass it. 

I believe that covers it for the testnet. I don't want to give any timelines, but it's all coming pretty soon, days on some and weeks for some. I don't believe we are talking about months for anything. 

**Troy:** Are you making a Joe Lubin joke?

**Bogdan:** Exactly! Few know about those. 😂

**Troy:** Very, nice! 😂

Alright, with that. 

That was an awesome update on the tech side, thank you– let's turn it over to operations. 

## Operations [[09:35]](https://youtu.be/DgTUvvK4vt0?t=575)

**Troy:** Let's start it off with Pavlo. Can you give an update on your stuff, please?

### Pavlo [[09:43]](https://youtu.be/DgTUvvK4vt0?t=583)

**Pavlo:** Hi, everyone! 

I'll start with the docs. 

#### Docs Update 

**Pavlo:** The docs v2 are coming along. We have covered a lot, the new guides for the Smart Yield and the governance. We are working on the Smart Exposure guide right now. 

Other than that, Vitalik has designed an introduction to Smart Yield. It's a PDF with some modelling. That's also being revealed and will be available for download. 


#### Website v2 dev update

**Pavlo:** Now, we have not announced it yet, but we have been quietly working on a Website revamp. Denis and the dev team put together some amazing designs. We are currently working on the development part. So, this is, moving along as well. In a short time, we can share the new style and feel of the website with you.

That's about it for the operation side. 

#### Integrations Team [[11:05]](https://youtu.be/DgTUvvK4vt0?t=665)

**Pavlo:** There are a few updates about the integration team. So, our primary focus, in the past, was working on the flow and getting documentation for the developers. And for the teams that potentially want to integrate with us, this is still being worked on. 

We are talking to Coingecko to get the junior yield farming APY pool listed on the DeFi farms page. Also, we worked with the dev team to get the DeFi llama adapter fixed. The adapter now displays the correct TVL number– which gets used by Coingecko. So the TVL is accurate now. 

We've also been closely monitoring the community intake form. (not a lot of the more recent applications) 

We are looking forward to those If anyone from the community has any ideas or suggestions. Feel free to fill this out, and we'll make sure to review it. 

[Community Intake Form](https://docs.google.com/forms/d/e/1FAIpQLSftA8dem1TfkzT4rK71pHzTNXxYJwX-BMITLcOoP_WQF8fteQ/viewform)

**Troy:** Awesome. Thank you, Pavlo. 

Can we get an update from Akin, please?

### Akin [[12:43]](https://youtu.be/DgTUvvK4vt0?t=764)

**Akin:** Sure, this will be short and sweet.

#### OpenDeFi / DeFi Alliance

**Akin:** I spoke a bit about this on the last call. We had an AMA with DeFi Alliance. I also published the answers to the AMA in our Discord. For those who didn't see it. You can go to our announcements channel, and then you can review what we talked about there. There could be interesting added information that you can leverage. Nothing should be too brand new. But, there may be some questions answered there that are new.

OpenDeFi– there are some changes with their organization. They'll get announced in the next few weeks. It will have a positive impact on the BarnBridge community, so look out for that. We'll likely publish an announcement after they do. Just a heads up, over the next couple of weeks, you'll see something in that regard.

#### EEA Application

**Akin:** We applied to join the Enterprise Ethereum Alliance. Based on advice from a few of the partners we've been conversing with

For those that don't know, the EEA is a forum where a few traditional financial entities– like banks and institutions –engage the Ethereum ecosystem. We thought it would make sense for us to be a part of that group. It's a way to leverage a networking organization to further the goals of BarnBridge within that community.

It's relatively straightforward we applied. We only need to pay the annual fee, and ideally, we'll have a host of forums and events that we have access to, so that should be good from a biz-dev/marketing perspective. 

#### Data and Disclosure 

**Akin:** The last thing. We've been having some internal discussions around data and disclosure– that we can provide via the UI– as we continue to expand implementations with different entities. So, look out for that– as we update the UI. There may be some integrations included that provide further information about the counterparties we are working with. So, we can give the users all the information possible to make the best investment decisions. 

That's pretty much it. 

### Max [[15:24]](https://youtu.be/DgTUvvK4vt0?t=924)

#### China feeling the Barn

**Max:** I'll follow up with Akin here. By updating everyone that our China community management program is up and running. Leo started earlier this week. 

He is in the process of building out various channels and letting people know that he is on behalf of BarnBridge. I'm looking forward to what comes of that in May.

**Troy:** Very cool! The final stuff– I'll hand it over to Tyler to give a synopsis on it. 

### Gemini Listing [[16:04]](https://youtu.be/DgTUvvK4vt0?t=963)

**Tyler:** Obviously, we got listed on Aave. 

**Troy:** Gemini**

**Tyler:** I'm sorry, Gemini. 

I was going to tweet about this in the morning. We are working with a couple of different exchanges. I don't want to put a target on our back by saying this. At least in this form, I think it's appropriate. 

The biggest thing about the Gemini listing isn't like "number go up." and everyone asking in the Discord, "When listings?",  "When exchanges?"

It's more than that– Gemini is a New York regulated financial institution. So, naturally, they have higher scrutiny on the things they list vs. other exchanges. 

In other countries, there are fewer regulatory concerns. That's why Gemini only has 40 coins listed. They scrutinize the hardest. 

Other exchanges operating in the United States may not get scrutinized as much as Gemini– they get regulated by New York– The fact they listed BOND. And we fit the security parameters– it's a big tip of the hat to the team and others in this space for a long time. It's also a tip of the hat to the process in which we rolled things out. 

From the perspective of DAO first– it should be a green light for the industry. At least for a few American people in DeFi who want to create a project with a DAO first approach. Also, we are almost obsessive with the decentralized aspect of this project. And, so the community has more tokens in their hands as we rolled out the products– instead of the original investors in the seed round or even the team– we took substantially less of a stake than other projects in this space that came before us. 

People need their legal advice. However, it's a strong signal for the DAO first approach. I think it's mixed with our obsession with decentralizing the project– and our roll-out, not talking about price, not talking about listings, just focusing on the technology and what we are building. 

I think that people need to review our videos and how we've been doing everything so transparent– in the eyes of the community –you can see how we've rolled things out. Look at our Medium articles because I believe going forward– and it's not perfect– but things get done well, and the institutions looking our way prove that.

**Troy:** Yes, I agree. 

## Round Table [[20:30]](ttps://youtu.be/DgTUvvK4vt0?t=1230)

**Troy:** There is also a question that we have noticed has come up a lot. I'm going to add this to the round table, and then we can talk about this. 

People have asked us if we want to take the rewards (fees) and buy Smart Yield somewhere, to procure a runway. 

I'm not sure what our opinions are on that. But, if anyone has any thoughts on that. 

**Tyler:** I can explain how that mechanism works whether it goes into one bucket or a treasury. (where all the BOND tokens are)

I guess that is a little irrelevant. There have been a few teams that have started looking at the Senior side of Smart Yield. As a way to lock up some of their fees to the treasury. A lot of treasuries are in their tokens. 

Like BarnBridge, for instance, we have a large treasury, but it's in our token. And, even when we do get listed on these platforms like Aave, the spread won't remain the same long term– compared to stablecoin, because that's what people use when borrowing/lending in traditional markets. I think a lot of treasuries that plug into these platforms– whether it be Yearn. 

> [A good example of a group that is generating a lot of stablecoin to their treasury.](https://yearn.finance/vaults) 

A lot of stable coin projects have reached out to us with a similar mindset.  We did deposit into the Senior side originally– via our treasury management. (the core team) 

I believe doing it in a public way is a concrete signal to others that we are willing to eat our dog food. It shows other projects what we are doing. When I talk to different projects about this, they are extremely receptive. I conversed with the Olympus DAO team yesterday about this. Their main thing was the lack of a deep enough DAI pool. 

When we incentivize our pools, and we move to Aave and Cream. We will need to incentivize pools other than USDC. But that's an example of a group that benefits from locking in a stable yield on our platform. 

Pool together has also spoken to us about integrations to stabilize their platform. We'll be focusing on TradFi to get our stablecoin yield higher. My point is there are massive treasuries within DeFi right now that can utilize our protocol. 

I think us using it is a massive signal to the industry. I don't know if anyone else has thoughts. But, that's my opinion on it. 

**Troy:** I like the idea of being the model for it, especially through the DAO. And allowing other projects to see how to use it is very strong. Even though we did that through the multisig. 

**Tyler:** We didn't tell anyone about that. Doing it with the multisig vs. doing it the community– it's substantially more powerful– because it's more than a couple of people making a decision, it's the entire community.  

**Troy:** It also brings the community conversation into it. I think it's a really good idea personally. It would be amazing if we can get the MakerFoundation to use it. That's what this instrument gets used for. 

I suppose we are in a bull market. But in a bear market, something like this is quite powerful. It gives you a guarantee. 

**Tyler:** I think it can signal the industry in a bull market too.

**Troy:** Yeah, but the industry tends to be full of degens. 

**Tyler:** Yes, but with the DAO. At the individual level, they are all degens. But if you view the aggregate– it's as if when 10,000 people make decisions, they are more responsible than every individual who makes high-risk decisions. 

Like Synthetix has had this problem with sUSD shorts and not having anyone that takes the other side of the trade. 

There is a big part of it which is that. We are in a bull market, and a ton of people are full risk-on. When we hit a downturn, people will understand how much more superior BarnBridges coding and strategies are in a downside environment. Compared to other groups working on similar tech. We'll have to let everyone find that out when it happens. 

With that said, the big piece is– if these DAOs are almost functioning as companies or partnerships/collectives that generate fees. You can't do legitimate financial planning without fixed income. So, these DAOs should be looking at BarnBridge. However, their treasuries are in different things, and that's my point. We likely need to get the TVL across a basket of stablecoins. Instead of only incentivizing USDC. 

I agree the industry is risk-on. But that doesn't mean Aave is taking its tokens and apeing into shitcoin farms. They are conservative with those bags. 

**Troy:** Yeah, I agree. 

**Akin:** Just to chime in on that. I think the use case for having other treasuries leverage Smart yield is clear. There would be a benefit to them doing that. I think on our end, putting our capital into the product as an example– makes sense. Although, over the long term, we will need to reconcile that with other use cases, whether it's expenditures for building out new teams and the DAO. 

Also, there are other aspects of leveraging our BOND tokens to build/influence other strategic projects. So, some of the conversations around seeding the Bancor pool with BOND. That's an example of creating liquidity for BOND with another pool. But also, earning governance tokens from Bancor. Which gives us a level of agency within our network, like voting for proposals– that we may want to put forth –they are beneficial to us. I think we've been having ongoing conversations around how to deploy capital. 

**Troy:** This is around using the fees accrued by the products, not the BOND token. 

**Tyler:** That's what I didn't know at the beginning. Are those fees converted into BOND when you hit the transfer? Or are stablecoins transferred into the treasury?

**Troy:** It's stablecoins directly into the treasury. 

**Tyler:** Well, then we are talking about different things. We are wondering what we do with the stablecoins? 

**Akin:** I understand that. I mean, it's all value that is within the treasury. So the question becomes, would you put that stablecoin in Smart Yield to earn passive yield or would you use it as a capital expenditure– to fund a team that builds value for the network. That's still a capital outlay. 

**Troy:** You could also do a buyback and seed the BOND into Bancor.

**Akin:** Yes, potentially. The point I was trying to make was, there is a broader conversation around how to deploy. Whether it's fees or BOND tokens, What are the most effective activities to deploy that too? 

I believe, in the nascent stage of a network, In my view– capital expenditure should get used to build things that bring long-term value. I would default to that.

It's a matter of quantum. Are we talking a few hundred thousand or a few million into Smart Yield? That's one thing. 

However, if we discuss how to deploy large amounts of our fees, we should think about how we use them and deploy them as a building expenditure– opposed to passive income in the short term. 


**Tyler:** I suppose it depends on the amount. Let's say BarnBridge's treasury is 100 million dollars, and we throw off 20 million in fees a year. Well, we don't operate at a 2 million dollar burn rate. You can use the BOND token in that scenario to help with some of that. It's a no-brainer, and some of it comes back to the treasury. 

However, if you have a ten percent interest rate on Aave, you can lock in that annual ten percent interest rate with 20 million. And with the burn rate kept under 2 million. In that scenario, you have an evergreen platform that is cash flowing– with higher numbers, it starts to come into effect. That's how real-world CFOs do financial planning. They lock in their annual expenses with fixed-income products. And then, the excess is used to take bets on longer-term plays. However, year to year, you know if we deposit this here: we have 20 million in cash, but we also generate 2 million. 

That's what you would do with your responsible capital. And the delta between the locked runway and your excess. It becomes a conversation that the CFO thinks about– Are there some things that can get invested in? or are there other ways to distribute this?

I think we are not there yet. However, a lot of protocols are. Synthetix is cash flow positive. Yearn is throwing off insane revenue. I believe they did better last month than all of 2020. I think that us talking about it and showing the industry how to do financial planning like that. It's a step in the right direction that will get us where we need to be– more than seeding a Bancor pool, in my opinion. 


**Troy:** It's such a powerful instrument. And we have not seen anything like it yet. We also haven't seen a project in the ecosystem use it in that form. It's pretty wild when you use it that way. Because you have entire independent organizations built into web3– operating –that's the future and its galaxy brain stuff. It's wild to think about it. 


So I agree, showcasing it ourselves is worth it– especially in a public way. 

I think we had a good conversation about that. I look forward to hearing what the community has to say about all of that. I don't think there is anything else that we need to go over– If there is anything that anybody would like to bring up, go for it! Or forever hold your peace.


**Pavlo:** I want to shout Ser Wright Ward because he is always trying to use some new !FAQ comment in the Discord. It's exciting. 

I promise you we will update it. The only reason we haven't yet is that we have not released the docs v2. There will be some links from the FAQ to the v2 version. That's the only reason we have not done it yet.

**Mark:** We need Pavlos loop. 

**Pavlo:** Yes, he does that each day!

Shoutout and respect! 

**Troy:** Tyler, want to give a shoutout to your Bucs? Before we end this.

**Tyler:**  I don't know. We just gave one to my older brother. I think that's good enough. I'll send Wright some BOND as a tip. He's been hustling for us, and he doesn't get paid anything.

**Troy:** Good man! 

Alright, with that, we'll see everyone in two weeks. 

Sayonara! ✌️

**Everyone:** 👋👋👋👋  


<br>

### Relevant Links

* [Website](https://www.BarnBridge.com)​
* [DOCS](https://docs.barnbridge.com/) 
* [Project Mangement Hub](https://github.com/BarnBridge/BarnBridge-PM)
* [Agenda](https://github.com/BarnBridge/BarnBridge-PM/issues/21) 
* [Twitter](https://twitter.com/barn_bridge​)
* [Discord](https://discord.gg/NwXHd3z)
* [Youtube](https://www.youtube.com/channel/UC4exzX_c37p2gYJK4L9nrGQ)

* [Bond.Bet](https://bond.bet/)
