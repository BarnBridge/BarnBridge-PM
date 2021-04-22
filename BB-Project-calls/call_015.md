# BarnBridge Project Call 015 Notes 
### Meeting Date/Time: Thursday 2021/4/15 at 15:00 UTC
### Meeting Duration: 18 mins
### [Github Agenda Page](https://github.com/BarnBridge/BarnBridge-PM/issues/25)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=_QIrenVqreo)
### Breakdown: 

Moderator: Troy Murray

Scribe: Rayne L.

Attendees: Troy Murray, Mark Ward, Akin Sawyerr, Pavlo Bendus, Vitalik Cherniak, Milad Mostavi, Dragos Rizescu, Bogdan Gheorghe, Max Fiege, Tyler Ward

## Intro [[00:00]](https://www.youtube.com/watch?v=_QIrenVqreo)

**Troy:** Alright, everyone. Welcome to BarnBridge project call 15. 

I'll be turning it over to Bogdan. I hope everyone is doing alright.

A lot of tech updates and cool stuff came out this week.

Let's get to it.


## Tech/Dev [[00:16]](https://youtu.be/_QIrenVqreo?t=16)

**Bogdan:** Yes, lots of tech updates. I have to scroll through my Agenda– it's now scrollable. 

We've had multiple releases over the last few weeks. Some minor, some patches. A bunch of good stuff. We are in a good cadence with those. So, we hope to keep going like that– at least trying to do one per week– for the foreseeable future. We've had some notification updates (we are constantly adding them), and eventually, we will stop mentioning those because they will be in the release notes.

I'm starting with the boring stuff right now. We've upgraded our infrastructure for the community– for better monitoring. 

That's it for the boring. 😎


### Yield Farming [[01:08]](https://youtu.be/_QIrenVqreo?t=68)

**Bogdan:** An end of an era– or one end. Most of the funds have already got withdrawn. Some have moved onto Smart Yield, and we've updated the app to reflect those changes. There were some problems with withdrawals. So, we've had to fix those as well.

### Governance — Treasury Tab [[01:33]](https://youtu.be/_QIrenVqreo?t=92)

**Bogdan:** The treasury tab. This one we released this week. Anyone can check the holdings of the DAO treasury. It also shows the fees that the product Smart Yield has accrued– so far. There is a bunch of BOND in there and a bunch of USDC from the Smart Yield. Anyone can transfer the fees for that, from products to the DAO treasury. However, there is no incentive for that. So, whoever feels like a good samaritan and wants to spend gas to do that. Be our guest. 

However, usually, it would be the first step of the proposal plan when the DAO/community wants to use those funds. Collecting the fees can and should be the first step in a proposal. The funds will have to move from the fees section to the DAO holdings section– if they need to get used.


### Smart Yield — AAVE Integration & Compound DAI [[02:28]](https://youtu.be/_QIrenVqreo?t=148)

**Bogdan:** We ninja launched DAI for Compound. We didn't make that big of a deal about it. We announced it after it was available in the app. Nothing new or exciting about that. We need to make decisions about the Junior side incentives. There will be more updates on that, and a lengthy community discussion will take place. Max can talk more about that later on this call. 

Everyone is waiting on this– we'll have Aave integration soon. We finished the Smart contracts. We have some testing left to do, and even though they are simple– compared to the Compound contracts. We want them audited to be sure. That will take a couple of weeks. Although, we won't delay the launch. They are simple enough, and everything works as intended.

Also, as requested by the community– the Smart Yield section, work is ongoing for a stats dashboard. It will be released next week. We released it ten minutes ago for internal feedback. Everyone kept asking for more details about what the A-Bond is, the state of the senior bonds and a few other things. So, there will be a stats page dedicated for each market on Smart Yield. 

### Smart Exposure [[03:58]](https://youtu.be/_QIrenVqreo?t=238)

**Bond:** We mentioned this before. However, we did not go into much detail about it. We slightly stumbled upon it while researching various models for Smart Alpha. So, we set on a version for that. We are having Smart contracts audited starting tomorrow. They got tested– I think it's 99% test coverage or some large number like that. Everything is looking good. 

The UI is getting a round of feedback tomorrow. I've heard only good stuff so far. You guys are likely going to like this one. It bases on Smart Yield, so, It will look familiar. It should be useable by May or the end of the month. So, we are a couple of weeks out with that.

Next. Further down our timeline. Smart Alpha.

### Smart Alpha [[05:05]](https://youtu.be/_QIrenVqreo?t=305)

**Bogdan:** The spec is working and done– vetted by everyone. We are working on a simulation with data, and a goal-line implementation is deep in the works. After we are happy with where that is going, turning it into Smart contracts shouldn't take Casian too long. He works fast and well. Then we have to start booking audits for those. That should happen soon. 

I think I've touched on everything. 

Hopefully, If not, bring me back. 

**Troy:** I think you did touch on everything. That was a pretty concise rundown about everything that has happened over the last couple of weeks. A lot of good stuff is happening right now. I think we are excited about the Aave integration coming up and the Smart Exposure launching. Which, as Bogdan said, we accidentally discovered it and then said, let's do it.


## Operations [[06:10]](https://youtu.be/_QIrenVqreo?t=370)

**Troy:** Moving on, let's jump into Operations. I think the first update will come from Akin. It's around the Teams and everything going on with that. So, Akin, if you would like. 

### "Teams" Updates [[06:22]](https://youtu.be/_QIrenVqreo?t=382)

**Akin:** A few buckets of things we are working on— The integrations team has already been working. We've built a few things regarding the intake of ideas and proposals for third parties. Who is trying to integrate and work with us. There have been a few conversations with several projects– about potential integrations –at various stages of interest. It's going well. I'll leave max to fill in some details. 

I'll focus more on outward-looking partnerships. As Troy said, over the next couple of weeks, we'll be launching with Aave. So, I've been having conversations with them about other areas like TradFi– building relationships on that end. So, we will see where that goes. We've been conversing. And there are multiple things that we can do with Aave going forward– not only the product side –we can potentially partner & leverage their onramps to traditional finance. That should be interesting over time. 

Along with Smart Exposure, we've been talking to Chainlink for the last few weeks. Around using their keeper network (which they will be launching soon) for the Smart Exposure product. Over time there will be other use cases with Chainlink as we roll out other projects– that will need to leverage price feeds. Those conversations have been going well. Over the next couple of weeks, there should be announcements regarding our relationships with them and what we are doing heading forward.

We'll continue to talk to onramps. There are several emerging onramps. A lot of TradFi funds have been coming on board. We've been engaging them and having conversations. 

For one, to build relationships and understand their structure. How they work, what their goals are and what they see coming.  And how we might collaborate going forward. Certain usual suspects– Fireblocks, Copper, Fiat of Europe, SwissBorg and Crest Finance. We are talking to everyone– I think we are still in a norming stage of learning. And we are trying to build relationships. Hopefully, in the coming months. Substantial things will come out of those conversations and relationships.

I'm also doing an AMA later today with the DeFi alliance community. At 1 PM eastern. It's a follow-up to the DeFi demo day. They are having each of the teams do AMA's within the community. It's another opportunity to have a slightly longer Q&A session. 

As some have heard, Coinbase has joined the DeFi alliance as of last week. I think the DeFi alliance is growing and becoming a stronger convener of projects and partners that get indexed into DeFi. So, we will continue to spend time and build relationships there. 

We've also continued to work with OpenDeFi, which is another alliance, but it's more bet towards Asia. However, they are global as well. So, we are continuing to engage them, and we'll seek leverage opportunities with them. For partnership onramps– it will help us understand what is happening in Asia. As we launch an Asia team, some of the roles within OpenDeFi may transition over there. I look ahead to building more inroads to Asia and understanding the market– to learn how BarnBridge can serve clients there. 

I'll leave it at that, and I'll transfer it to Max to talk more about what we've been doing on the integrations side. 

**Max:** I think the main news, this week, on that front, we currently have the China community management squad vote wrapping up. It's been a unanimous success. And so, I'm looking forward to getting that ball rolling with Leo from the Discord. 

We also have another snapshot going for the next few days. It's for seeding the Bancor Bond BNT/BOND pool with DAO funds. I've been pleased with the turnout for Snapshot votes. Both are 70-90 thousand BOND showing up, without us having to court folks into participating. I think in tomorrow's issue of Barn Burner. I'll outline our thoughts around Snapshots and DAO governance votes. There will be a back and forth on how to figure out a community consensus in the early days– while things are considered informal.  

As far as the integrations team goes, I can write up an update for that. Akin has touched on a few of the conversations we've been having. Between myself, Akin, Pavlo and the community members on the integrations team. So, I'm super thankful for the Snapshot participation and the submissions we've received for the intake form. 

**Troy:** Awesome. That stuff seems like it's going well. 

I've been following it, and I'm pleasantly surprised while watching from afar.

So, good work on all of that, guys. 

Let's hop over to Mark– on the bounties. 

Mark, can you give an update on what's going on with you?

### Bounties [[12:39]](https://youtu.be/_QIrenVqreo?t=759)

**Mark:** We've been working on some of the bounties– I think I made this point on the last project call. We are eventually going to redo the website, and right now, we are currently going over all of the translations to get some of the new text done. We are also translating some new languages into our slimmer whitepaper– we are calling it a lite paper. It's only three pages. Max shortened it. We recently got Arabic translated, and we are going to translate it into Czech. 

Essentially, we are getting new translations that we did not have before– for audiences we did not reach prior– which is cool. Ideally, we can get the lite paper translated into every language so that everyone can read the digestible version– in case the thirteen-page whitepaper is too long. 

**Troy:** Nice! When is the lite paper coming out?

**Mark:** It's out in English. It's unpublished. I can send it along to you and Tyler to read it, and then we can okay it– and get it published. 

I read it a few times. It's really good. I don't think there is anything that needs to get added. I'll send it over to you guys. 

**Tyler:** I have a quick question. 

What's going on with that thing that Emilio had put together? With those models that we wanted to turn into a PDF for TradFi.

It's more of a Mark and Pavlo thing. It may have gotten lost in translation over the week. I think I went into that last night, and Max had made a few comments. 

Do we know who was going on that?

If it's no one, then I can. 

**Mark:** Pavlo, do you know anything about that? I didn't work on that document. 

**Pavlo:** I think, as you said, Tyler. Max commented, and I've seen some comments from Akin too. So, with those comments, we need Emilio to go through it again. Then we will move forward with the doc. 

**Tyler:** Okay, that sounds good. 

**Troy:** Cool! 

Pavlo, would you like to give updates on the community and the website and all of that?


### Website/Discord Community Update [[15:33]](https://youtu.be/_QIrenVqreo?t=933)


**Pavlo:** The Discord has been active. A lot of meaningful conversations are happening in there– as well as the forum. I'm excited to see that happening and the participation. A lot of stuff is going on under the hood. 

So, we've been getting some suggestions to improve the documentation. We need to make the guides more simple/user-friendly. We are working on that– we call it docs v2. So, a lot is going on there. 

Other than that, we have started working on the developer docs for the integrations team. It will get used by the teams and individual developers that want to integrate with us– this is a big chunk of work. Bogdan is helping us there. 

Last but not least. We are talking to Coingecko to get our API listed on their forums page. So, we are doing some work there. 

That's about it. 

**Troy:** Okay, that sounds good.


## Round Table [[17:18]](https://youtu.be/_QIrenVqreo?t=1039)

**Troy:** We don't have anything from the community this week. 

Tyler, do you have anything you would like to say?

**Tyler:** No. 

**Troy:** I think we are good. Everything is moving forward pretty quickly. I'm excited to see what happens in the next couple of weeks. I think things are going to be really, really interesting. 

I'll leave it at that. 

Unless anything else has anything they would like to add, I think we can sign off and whip this out to the community. 

**Everyone:** 👍👍👍

**Troy:** Alright, sounds good.

Thanks, everyone!

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
