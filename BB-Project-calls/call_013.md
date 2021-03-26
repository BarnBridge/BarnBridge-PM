# BarnBridge Project Call 013 Notes 
### Meeting Date/Time: Thursday 2021/3/18 at 15:00 UTC
### Meeting Duration: 40 mins
### [Github Agenda Page](https://github.com/BarnBridge/BarnBridge-PM/issues/21)
### [Audio/Video of the meeting](https://youtu.be/ZyrHf_VIygA)
### Breakdown: 

Moderator: Troy Murray

Scribe: Rayne L.

Attendees: Keegan Selby, Troy Murray, Mark Ward, Akin Sawyerr, Pavlo Bendus, Vitalik Cherniak, Milad Mostavi, EJ Rogers, Dragos Rizescu, Bogdan Gheorghe, Tyler Ward


## Intro [[00:00]](https://www.youtube.com/watch?v=ZyrHf_VIygA&t=0s)

**Troy:** Welcome to Project call 013– for BarnBridge. 

We will get started, and I will hand it over to Bogdan. 


## Tech/Dev [[00:08]](https://www.youtube.com/watch?v=ZyrHf_VIygA&t=8s)

**Bogdan:** Everyone is aware that we have launched Smart Yield. Everything went perfectly– at least in our opinion. We have seen some discussions in Discord, so we would like to clear some things up. 😎


### Smart Yield Launch (Update) [[00:28]](https://youtu.be/ZyrHf_VIygA?t=28)

**Bogdan:** As far as we are concerned, this is a soft launch. It's a way to make sure everything works on the mainnet, letting the baby stretch its legs, and it works as intended. 

As far as plans go, everyone is more confident about how the products have gone thus far. The only issue that has been on everyone's mind is; How do we get some of the TVL from pool 1 to move over and bootstrap the product?

Tyler put out a proposal for discussion on the forum. Junior tranches have to be competitive because of their variable APY. There needs to be more than the original APY to incentivize Juniors.

In the forum discussion, there have been quite a few replies and overall positive feedback. The plan is to incentivize Junior tranches via more BOND rewards. (a token reward pool)

Also, this proposal will increase the Senior maturity dates. All of this discussion will get done through a post on the forum. Afterwards, to the main DAO so everyone can vote on that. The proposal should get posted today or tomorrow. 

**Tyler:** To clarify, do you mean to put into a proposal for the DAO– today or tomorrow?

**Bogdan:** Yes, as soon as possible. I was aiming for Monday at the latest for the DAO proposal. Is that doable?

**Tyler:** Actually, I was going to bring that up. 

Is there any pushback? Based on the replies to this, the only actual pushback this thing got was; 

> **"Why are there not more incentives than the DAO and the farming pools?"**

The reason is that the Junior interest rate gets included. So, there does not need to be as many incentives. We are not giving away BOND tokens as a 'proof of capital' to distribute BOND. This product has additional yield components on top of it.

That's the only thing I feel we will get pushback on. I have a strong feeling this will get passed. Since the DAO proposals take about twelve days to process– if there are no concerns –we should have it going as soon as possible. As a cleanup, we can go through all the other proposals, see which ones have support and which ones need to see the DAO. 

None of them seem to have anything major regarding additional code. However, the council stuff we have been working on needs included. And other proposals should be consolidated and categorized as grants and so forth. 

As far as this proposal goes, are they any concerns?


### Incentivization [[04:20]](https://youtu.be/ZyrHf_VIygA?t=260)

**Troy:** The only concern that I have had within the last 24 hours– if we are incentivizing at six months (Junior Tokens) and let's say there is a gap and someone pulls out– what about the people in a year-long maturity?  

Are we incentivizing people getting rekt on the Junior side if someone pulls out, in any way?

**Milad:** Some Senior Bonds stretch to one year. Not all the Juniors are stuck to one year. There is a weighted average duration to the entire aggregation of Bonds. So, many people need to have the max duration– for everyone to be stuck with a one-year maturity. It will be less than one year. 

To add– I'm expecting this to happen. We have been testing with a modified farming contract for about two weeks. That's why I say give it until Monday until we add the proposal. The difference between the new contracts and the old ones is it's continuous, can change the rates and durations for the farms via the DAO. 

**Troy:** So while we are in operation, we can make changes? 

**Milad:** Yes, exactly. Every six months, the DAO can make adjustments.

**Troy:** And it's continuous, so there are no Epochs, correct?

**Milad:** Yep! 

**Tyler:** Should we make this proposal and then only do this for some time, say a month? Test it, then in about a month, we test it out?

**Milad:** I think it should be six months because if it's one month and we need an extension, we will still have to submit another proposal, and there are 12 days for that. Then we will be rushed.

**Troy:** At six months, that gives us enough time to let it run and enough time to prepare. If it's too short, it will get rushed, and if it's too long, we might forget.

I think six months is the sweet spot. 

**Milad:** We have the luxury of time to make decisions.

**Tyler:** We need 12 days from Monday to finish that staking contract. And that's why we are posting it on Monday?

**Milad:** The staking contract is complete– we need to review it a bit more. It's very similar to the DAO rewards contract– It's slightly modified. The completed audit is still valid. We have to deploy it and make the proposal and all the actions. 

It's doable by tomorrow. 

**Tyler:** I understand now. 

**Milad:** And in the 12 days it takes for the proposal to execute, we can create the front-end and do any other back-end work required before the yield farms for the Junior tokens are ready.

**Tyler:** Do we talk to Aave before or after that front-end/staking stuff?

**Milad:** It's going to be alongside it. As the front end gets done, don't worry about that too much. We will build all the components. 

**Tyler:** Alright, that sounds awesome. 

**Troy:** Yeah, it does!

Alright, so I think that's a pretty good update regarding all the incentives for everything. 


### Smart Exposure/Leverage [[08:41]](https://www.youtube.com/watch?v=ZyrHf_VIygA&t=521s)

**Troy:** I do want to say– we are working on another product. It's called Smart Exposure– more information about that on the next call. 

But, so you know, there will likely be a product in between Smart Yield and Smart Alpha. 


### Smart ALPHA [[09:03]](https://www.youtube.com/watch?v=ZyrHf_VIygA&t=543s)

**Troy:** Another thing we should give an update on is Smart Alpha. Where we are with it and what we are thinking. 

Milad, can you give a quick update on that?

**Milad:** We have an updated Smart Alpha model that will work well– based on the Smart Yield contracts. So, there is not a ton to do from the ground up. Ultimately they are different products just using similar concepts. That's about all I can say. There is internal testing to do still. 

**Troy:** Yeah, we don't need to go too deep into it. We are letting the community know the progress, there is a new model, and we are working around it. Smart Yield is out, and we are adding to it. (additional pools etc.)

Smart Alpha is still very much happening. 

With that, I think we will jump over to Operations. 


## Operations [[10:00]](https://www.youtube.com/watch?v=ZyrHf_VIygA&t=600s)

**Troy:** Akin, give a slight update on the DeFi Alliance? I have a feeling that's pretty much coming to an end now.

What is the timeline for that?


### DeFi Alliance [[10:19]](https://youtu.be/ZyrHf_VIygA?t=619)

**Akin:** Yeah, DeFi Alliance– the main program is pretty much over. The remaining portion is demo day, on the 31st of March. That's where you present your project and where you are at and what it is.  

On the last demo day, there were around 250-300 people. The liquidity providers and the investors get to see the product at this point. I think it's great timing for us because Smart Yield is in the wild. 

**Troy:** Do we have a plan for all that?

**Akin:** Yeah, I just received the information yesterday about it. You present a 4-5 minute video outlining the project and the details of your products. Then there are around 4 minutes of Q&A. 

The way it's structured favours pre-recorded video, so the time slots fit nicely with one another. You can fix your time and move slowly. Then the teams go one after another, then the Q&As. The liquidity providers will follow up with the presenters they are interested in after the presentations.

So, for example, in the past, early-stage teams that are fundraising– have those conversations. For us, it is different because it will be mainly talking with liquidity providers.

**Troy:** I'm excited for all those people to see what we did. 

Fixed-rate for all of DeFi. What's up? 🎉 🦾😎

**Akin:** Yeah, I think having the product live and working and the TVL running, it's the time to present that. 

I have a few other things to report!


#### OpenDeFi [[12:20]](https://youtu.be/ZyrHf_VIygA?t=740)

**Akin:** Open DeFi got together a standard and disclosure group. We are trying to create a framework– a questionnaire –it would cover areas that teams and users should consider and think through. We believe that the teams will benefit by having a template for their standards. It's also great for users and helps them by having sets of questions for them to answer. 

We have a team together from several different projects, and it will likely take about 4-6 weeks to develop the questionnaire. It will get published under the auspices of Open DeFi. Through the network, hopefully, we get plenty of projects to sign on to the idea. This way different teams can start to build personal documents about standards and disclosures for their projects.

Several teams have internal risk management and disclosures that they have and use. It's been a good process unearthing that information and finding the crosses with projects that share our views and values. Creating a single questionnaire would be ideal, and we anticipate it being significant for DeFi projects to leverage. 

That would be our first step, and following that would hopefully be some sort of repository or a library that other teams have as a one-stop-shop to see how everyone is doing and what's getting worked on.

Should we talk about the Bancor thing?

**Troy:** Yeah, go ahead. 

**Akin:** A Discord community member submitted a proposal to Bancor. About building a BOND pool on Bancor. Subsequently, we had a conversation with the team about this. We align on the value of BOND getting listed there. 

They are in the process of moving from on-chain voting to off-chain because of the associated costs of gas. (Platform like Snapshot)

Once that's alive– we will enable our proposal for voting. However, we are confident in the consensus about the value of BOND getting listed. Eventually, once we build liquidity for Junior tokens, we can look closer at getting them listed. We have already had some conversations about this– after an initial discussion, it appears there is some long-term future with Bancor and BarnBridge. And that's where I look forward to bringing value to BarnBridge.


**Troy:** I think we can move onto Bounties now.


### Bounties [[16:02]](https://www.youtube.com/watch?v=ZyrHf_VIygA&t=962s)

**Troy:** Mark, do you have updates on the bounty situation.

I don't know who does the call notes– but you're amazing. 👌

> Thank you kind ser's  🙏😉

**Mark:** That's [Knowledgeable Idiot](https://twitter.com/raynemang)!

**Troy:** Oh really? That guy's awesome.

**Mark:** Yeah, he wrote the original call notes and did such a great job. I've used him for all the notes since. So, yeah, shoutout to Knowledgeable Idiot! We appreciate you. 🙌

**Mark:** I made a slight change on the last project call. I said I would relaunch the meme competition bounty permanently on Gitcoin. My theory was correct, and we started getting a ton more memes in the Discord. More people are coming into the competition. 

*I'll pay everyone out via my Metamask wallet– **I'm selecting a winner every week still!***

I would love it if someone from the Discord could reach out to me– I have a bounty up for a Japanese translation and some proof-reading. I've been struggling to find a translator, I had one, but now the person is not responding. I've had another that responded but never got back to me. 

So, if you have any experience speaking Japanese, please reach out. It's a more technical translation, so you need to be at a more advanced level. If you are fluent in Japanese, it will be no problem. That bounty is on Gitcoin, and I've been looking for a while now– nearly two months or so. We want to get it published ASAP. 

If anyone knows anyone who can do that, please reach out or refer us to another person. We need to get it done and pushed out. So our Japanese readers have the same resources as everyone else. 

**Troy:** Cool, right on. 

Pavlo, can we get an update from you on the Discord and the website and all of that. A lot is going on with that. 


### Website/Discord Community Update [[18:30]](https://www.youtube.com/watch?v=ZyrHf_VIygA&t=1110s)

**Pavlo:** From the Discord, we have seen a lot more activity lately– related to the Smart Yield launch. We are trying to keep up with everything and be as active as possible. Also, we've added updates to the [documents and FAQ.](https://docs.barnbridge.com/)

**Tyler:** Pavlo has done some pretty extensive documentation on the Smart Yield product, and Pavlo and Vitalik also posted a ton about Bond.Bet, which we never fully announced the launch on a call. It got overshadowed by the Smart Yield launch because that is far more exciting. I will at least say we have been talking with PoolTogether on where we take that. 

So, if you wanted to learn more about [Smart Yield](https://docs.barnbridge.com/faq/products) and [Bond.Bet](https://bond.bet/) Pavlo did a ton of documentation on that.

**Mark:** There is a ton of new information, new FAQs and videos for Smart Yield and Bond.Bet, so make sure to go check those out in the FAQ section.

**Tyler:** I can also loosely answer all the odd questions right now about listings, what's going on with other projects like Aave, DeFi pulse etc.

A lot of that, I have to say– It's coming. We had to launch Smart Yield first, and as Bogdan mentioned earlier, it needed to be a soft launch. I would say we are humming over the next few weeks. The proposal needs to go out, and the TVL needs to increase. A lot of that will naturally take care of itself. 

However, I've actively told major exchanges not to list us until we have launched Smart Alpha. I think we are working on their timelines. The same thing goes with Aave– we need to integrate still. I don't think I've given any non-public information. We are talking to everyone. I need to reiterate that we are working towards the integrations. Our timeline relies on the partners as well.

I think within the next few months, questions we receive about integrations/partners will get answers, and there won't be any more questions about it.

Is there anything else we need to go over about the community? May hash out councils real quick?

**Troy:** You can just jump into that. 


### Council [[22:10]](https://www.youtube.com/watch?v=ZyrHf_VIygA&t=1330s)

**Tyler:** We've talked at length in the Discord about Councils. If anyone does not know what they are because they see it via email or on social media. We purposely did not talk too publicly about Councils outside of the Discord. We want to incubate it via our Discord– similar to the SquadDAO. A ton of the conversations about these concepts takes place in Discord because that is where the community is most active.

Discord and forum are probably the best places to keep up with what's happening. Email and Twitter are more for announcements, and we are not trying to announce a council for the people that are active on Discord and have an army of people ape in from Twitter. We very much want people to rise from within, and we want to empower the community. 

If someone doesn't know what councils are, you should get involved in the Discord, and then you will see what we are talking about. Realistically we are going to be putting in a proposal– with around three council members– that help with integrations (not necessarily protocol level) but the user interface and other similar permissionless integrations.

> **For example: Max from our Discord submitted a proposal for onsen at Sushiswap.**

*Requiring me to reach out and figure out the logistics:*

* What is required? 
* How does this work?
* What are the incentives?
* Do we need any tech?

Some of that stuff needs to get run by the community because they are making the decisions. But none of this will get done without some sort of Council that can push these proposals. And do all the additional work involved. 

Essentially we put out a call for help on the more technical integration side. Synthetix does some of this stuff. The generalized update for the Council– we believe we have found three exceptional candidates that we will recommend (it's ultimately not up to us)

At the end of our day, it's still up to the community. And for the management of the Council, we offered. And we added a new developer, Alex. We also extended a role to another person– who has another job right now, so I won't mention whom. That person will be working with Akin. To help manage the Council and other internal logistics to make these situations happen. 

What Akin did with the member of the Discord and Bancor was quite impressive. Both us and Bancor were impressed. Shoutout to you guys for pushing it through. When that person joins, they will help with these instances for the Council. The Sushi Onsen and the Bancor integration requires zero dev work, and it's somewhat of a political/lobbying instance. 

Something like integrating with Aave is different that requires code work which wouldn't be up to the Council, as much because it affects timelines. Say we need to integrate into a protocol of some sort, and it's a complicated thing– it could affect layer two scaling solutions. I wrote a Medium article, and it's a long time coming. 

*The buckets are as follows:*

* Protocol level decisions (Must be done according to whitepaper)
  - Aave, Compound etc.

* Interface level discussions (Coming up from the SquadDAO facilitated with the Council)
  - Cent bridge/Bond.Bet
  - Grants and things of that nature
  - Matching funding rounds etc.

* Permissions integrations (Council + Core team)
  - Keeps the values of the project & timelines intact

That's the long version update on the Council. It will be posted in the [forum](https://forum.barnbridge.com/) as well– in a few days or so. We have to get the Smart Yield stuff rolled out because it has a higher time-sensitivity than the Council at the moment. But it's coming, and we worked a lot on it.  

**Troy:** A lot is going on, and it's exciting. 

 Milad, do you want to cover the risks of Smart Yield?


## What is the risk associated with Smart Yield? [[29:13]](https://www.youtube.com/watch?v=ZyrHf_VIygA&t=1753s)

**Milad:** The way Smart Yield works– at the core level, Seniors set some of the risks for Juniors. Meaning, that for the duration of the Senior BONDs, the Juniors that enter that trade remain locked until the maturity date. 

To exit the pool you have two options:
You leave the pool and take a haircut pro-rata– based on locked funds on the Junior side
You wait until the aggregate BOND duration has ended

So there is a lock-up period if you don't want to lose any funds. 

The second risk is that the fixed rate inherited by Seniors gets backed by the Junior side. Any surplus that the Senior funds make goes to Junior. The Juniors make money as long as the provider rate (Compound) is above the Senior rate that the pool gives. The pool provides a dynamic-fixed rate to Seniors depending on the composition and the moving average. Which in our case, Compound provides the rate. It's well balanced to prevent overpaying the Seniors.

*After Seniors get their BONDs, and the APY of Compound goes well below the aggregate BOND APY, the Juniors take the additional risk by covering the difference.*

The third risk is basically like any other smart contract. As time goes on, it becomes battle-tested. We have done two audits, and we are confident, but time is the best. That's also why we soft-launched. We didn't want a massive TVL on the first day so we can see how it behaves. Those are the risks associated with Smart Yield. 

**Keegan:** I want to reiterate, thanks, Milad. 

Guys, this product isn't like the other yield products on the market like Aave– where you deposit and withdraw collateral, no problem. As Troy alluded to, we were the first team to ship a fixed-income product. With that, the mechanisms are different. You all know that 'read the docs' and 'do your research' is a bit of a meme in the crypto space. 

But actually, this is a unique product, a first of its kind. Special risks are associated with it. Your collateral can get locked up. You can take a haircut on your collateral if you want to pull out early. The secondary markets are not entirely liquid yet. The rates quoted are not necessarily guaranteed in perpetuity. 

Thanks for covering that, Milad. 

I wanted to say that. I know someone is going to deposit some collateral. It gets locked up, didn't read the docs, and now they're pissed about it. 

*So, this is our warning to everyone– please, understand the risks and move accordingly* 


**Tyler:** Let me also address some things from the community. 

To tack on to this. First of all, the chance of losing all of your collateral is most likely from a different level. Not from BarnBridge. It will likely come from the integrated protocol level, such as Aave or Compound. It's much more likely it's solvency issues of some sort. When I say lose money, we mean that the variable rate on Junior BONDs fluctuates. When you talk about stablecoins and the tokens with less interest rate volatility, you are more talking about the pool taking a haircut if the Juniors outperform. 

However, it's like a see-saw or a war. Both sides are competing for the best yield. Which will be affected by interest rate fluctuations– and interest changes are quicker in crypto than in other markets. So when we say losing money, if you see the rate posted at thirty percent, that's what you get right now. If someone pulls out of the Junior side– then you won't get the same rate. On the inverse, someone apes into the Senior side, the Junior side could potentially get a higher interest rate. 

But, if interest rates on Compound pick up and go to eighty percent and someone locks in for a long term, then you have increased downside potential. That's why we started with short maturities because you should not be able to ape into a BOND with a 15-year maturity and artificially inflated prices. 

So, that is something vital to know. In those scenarios, the most likely situation is Junior's taking a haircut– not getting liquidated. 

I want to be clear about that. Also, at the end of the day and with everything at scale with a long enough time frame and enough integrations, people will get liquidated at some point. That's what happens in traditional finance, and it is what it is. There is no question– that's the way traditional finance works. And that will not be a hack, but a function, of you, took the wrong side of a bet. 

In the same way, if I bet on the Chiefs at the Superbowl– like Troy –I wouldn't have made my money.  

**Troy:** 😂😂😂

**Tyler:** Okay, and the next thing. 

People have brought up how it's a fixed interest rate? When it's different every time I log into the website? 

What's very important for people to understand is that you are locking in a fixed interest rate at issuance. Similarly, in traditional markets, there are BOND markets, and issuance happens every single day. The interest rate consistently fluctuates. It's typically packed into the federal allowance, and this changes on an ongoing basis. So, the way it works is the fixed rate you get quoted is the fixed rate on the platform. But, if you ape in more than what the Juniors side gets valued at– you won't get the quoted rate. 

For example, the Junior side has USD 2M, and you put USD 10M into the Senior side.

You enable the token, you can then enter your amount and see how it affects your fixed interest rate, and that's what you get locked in. However, it's a changing rate at issuance. The actual rate isn't variable once you lock it in, but it's variable until you do so. That is the difference between issuance, and holding a BOND that was already sold.

If you buy one of these from the secondary market, then it's no longer variable. That's paying out the Senior's rate. The printer price affects the way the interface may show it. That's just a quick BOND lesson for everybody. It's working properly– it's the issuance. 

**Milad:** You're getting a different rate because you're changing the composition of the pool. The interest rate for the Seniors gets based on a provider. (Compound) And the makeup of the pool. If there is 2M on the Junior side and 10M gets put on the Senior side. The composition moves greatly– you have massive slippage. On the Senior side, you have the slippage.  


**Tyler:** And once there is a lot of liquidity in the pool, that will reduce. But the interest rate will still be variable until you lock it in at a fixed rate because it changes on Compound. (integration) And the Junior side changes. So, it's this ongoing market-driven pricing that is always going to exist. 

And that's a feature, not a bug.


**Troy:** I think that's good coverage on everything. I know it's a different product than most degens are using. But it's pretty exciting because it's radically better than anything out there for any of this stuff. We look forward to opening the floodgates on this in the next couple of weeks– once the DAO proposal goes through. 

**Tyler:** I have one final thing to say– Shoutout to Milad and the team. Stani looked through all of the contracts when they published. Because he wants to integrate BarnBridge with Aave– quickly. And verbatim, he said that he has looked at a lot of tranching solutions and people trying to do what we are trying to do. Because obviously, Aave wants to have this for their institutional level people that they are in talks with. He straight up said it was the best way he has seen this built, ideated and that the code is clean and flawless. So, getting that shoutout from Stani is a big up!

So, again, shoutout to the dev team!

**Milad:**  Thank you! Shoutout to the dev team. An amazing job. 

**Tyler:** Alright, I'm done talking.

**Troy:** Okay, so with that, I think we will call it. We will see you all in two weeks there is a lot of stuff coming. So pay attention. Within that time, the DAO proposal should pass. So, we look forward to talking to all of you in Discord. 

And, if you have any questions about any of this stuff, hit us up. We are around. We look forward to showing you what's coming next.

Alright, everyone! 👋

**Everyone:** ✌️✌️✌️✌️✌️✌️✌️✌️✌️✌️✌️


<br>

### Relevant Links

* [Website](https://www.BarnBridge.com)
* [DOCS](https://docs.barnbridge.com/) 
* [Project Mangement Hub](https://github.com/BarnBridge/BarnBridge-PM)
* [Agenda](https://github.com/BarnBridge/BarnBridge-PM/issues/21) 
* [Twitter](https://twitter.com/barn_bridge)
* [Discord](https://discord.gg/NwXHd3z)
* [Youtube](https://www.youtube.com/channel/UC4exzX_c37p2gYJK4L9nrGQ)
