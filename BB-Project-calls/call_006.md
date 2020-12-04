# BarnBridge Project Call 006 Notes 
### Meeting Date/Time: Thursday 2020/12/3 at 15:00 UTC
### Meeting Duration: 30 mins - 1 hour
### [Github Agenda Page](https://github.com/BarnBridge/BarnBridge-PM/issues/8)
### [Audio/Video of the meeting](https://youtu.be/-skbfvP8S8s)
### Breakdown:

Moderator: Troy Murray

Scribe: Dragos Rizescu or Rayne L.

Attendees: Keegan Selby, Vitaliy Chernyak, Pavlo Bendus, Troy Murray, Milad Mostavi, Dragos Rizescu, Bogdan Gheorghe, Tyler Ward, Akin Sawyer, EJ Rogers, Mark Ward
## Intro

**Troy:** Welcome everyone to the BarnBridge project call 006, we are going to start the agenda off with Dragos himself.

**Dragos:** Thank you, Troy.

## Tech/Dev

### BarnBridge App

#### Yield Farming

**Dragos:** Hello, everyone. The first thing we are talking about is the BarnBridge App— Yield Farming.

Monday last week, there was a front end bug. Luckily we solved it quickly. The bug was caused by a list of transactions received from the sub-graph. It was saved in the session storage, the session storage filled up and resulted in a front end crash for a lot of user browsers. Not that bad of a problem— too many transactions.

We addressed it by not saving the session storage in the same way as before. The result is a not so good user experience when currently navigating the app.

With our goal of a better user experience. We started moving away from the graph. We started implementing our packing component, added some UI updates— epoch graphs are being updated.

Here is a sneak peek, and we will soon roll a release for these updates. Either later in the day today or tomorrow. The updates allow the graphs and transaction lists to load a lot quicker. Creating a better user experience.

#### BBDAO

**Bogdan:** Smart contracts are now 100% done. We are working on improving test coverage, doing some internal reviews. As far as design goes, a third of it has already been implemented in the front end. We are just connecting it to the test net contracts.

Shout out to Slava he's been killing it with the front end work on both the Yield Farming and the DAO at the same time.

**Dragos:** I think we can show the community a bit of what this is going to look like. I don't think that's going to be a problem. Let me share my screen.

**Bogdan:** Small spoiler. 😎

**Dragos:** This is how the DAO overview page will look, Denis killed it with the UI once again— shoutout to Denis. This is going to be the list of proposals, when you click a proposal you will get something like this. I'm going to stop showing this now, that's the sneak peek.

Back to you Bogdan.

**Bogdan:** Gracias, ignore the top-secret part, that was just Denis messing with us. Just for authenticity.

Back end work is in progress, there is a data pipeline working that will replace the old graphs. We are slowly feeding data to the front end, internal reviews are in progress.

All of our smart contract developers plus, our advisors at ___ are looking at the smart contracts to make sure that everything is in order and works as it should. We have ___ audits already booked with contracts signed. 

The first one starts next week and the other one later in the month or early 2021.

That's pretty much it for the DAO.

#### Smart Yield

**Bogdan:** We had two competing models. Essentially those two models competed until one of them wore out and borrowed the best features from the other. So the smart contract development is moving along nicely with the winning model. Implementation should be done in time for the winter holidays.

The UI being worked on by Denis— the largest emphasis of this being on UX and having the smoothest possible experience. Every step of the way, getting a bit of hand-holding, plenty of disclaimers along the way so you know what you are getting into.

The back end specs also being worked on at the same time, this will include the debut of the in-app notification system.

Also, two audits are booked for the smart yield, both kicking off in early 2021.

#### Smart Alpha

**Bogdan:** Working the zero spec, if we could call it that. Almost completed, with major help from Atpar. There is a kicker to that— there will be two different smart alpha flavours getting worked on at the same time.

We are probably going to have to edit the whitepaper and all the docs out there to include both versions. You will get a feel for what those are soon. Our plan is for at least two separate audits for Smart Alpha. We will announce more on that soon.

There is an overall focus and a very huge emphasis on security, we have a pretty large in-house team doing the internal reviews. Atpar has been helping a lot with external audits, with all of the biggest companies in the space to be honest. Double the audits for all of the products, the reports will be published, so you guys can take a look at them. The repos will be made public in due time.

A bug bounty program, Mark will talk more about later and some other interesting lines of defence that we are going to use to keep funds safe, which are all going to be announced later.

**Troy:** Awesome, update there. Thank you, Bogdan. That was like...

**Tyler:** That was like a mic drop dev update.

**Troy:** Yeah.

**Bogdan:** My mouth is dry.

**Troy:** I hope the community understands, there is a lot of information there, a lot to digest. But we are all excited.

### DeFi Standards

**Troy:** There have been internal conversations around these ideas, and we have had talks with external teams. About this idea— the standards inside of this ecosystem. I want to turn it over to Akin who has really been spearheading a lot of these conversations.

**Akin:** We talked a bit about this last call. The idea that— because of the nature of the products we are creating, we need to build some clarity as to, what the risks were around the products.

But, also just naming conventions;

 * *What are they called?*

 * *What would a senior tranche look like?*

Just to create some real uniformity. Because, as we put products out there we want to make sure that it's easy for customers to be able to understand what each product is and be able to identify them. So, we have been having those conversations but we've also sort of expanded a little bit to also— think a little more broadly around disclosures.

With most financial assets in the real world, you tend to have these very long disclosures. That kind of tell you what they are and what the risks are. We think that we need something similar. But maybe not as onerous, in our space.

To create standards around how we disclose information around the risks so that sophisticated users can see that and understand what they are. Because they are used to financial disclosures in the real world.

But we also want to make it accessible enough for new users, who are in the DeFi space and the Crypto space. So they know what questions to ask.

At least a base level of disclosures that let you know;
 
 * *What's important to ask?*
 * *What's important information you should know about these assets?*

**Akin:** Something that gives you the full sense of the risks you're buying into. So, we want to publish that and create a standard around that. We are talking with some of the partners who have been engaging around this idea, and the hope is to be able to publish a list of disclosures, nomenclatures— things that people can easily find and reference as they buy and sell out products.

Another thing, we have also started thinking about some ideas around being able to verify proofs of liquidity in our assets. Because we are partnering with third parties and we are tranching debt products that already exist from our partners. Over time, as we get more and more partners and products, we can see how it can get relatively complex. In terms of whos originating debt and what are we tranching, and what are the various tranches.

We've begun to think upfront now as to how we can make it easier for users and customers to easily verify that everything we are putting out there has or is meeting the standard of liquidity or the collateral backing of all these assets.

We are in some conversations to explore those ideas, and might not necessarily make it through the first round of disclosures list, but we might it depends on how quickly those conversations happen.

But, we are definitely entertaining some ideas that will make it easy for anyone to verify on-chain the level of liquidity that's backing all the assets we're put out there. Essentially so it's easier to measure, ultimately this fits into a sort of credit rating system.

Where you will be able to understand what the rating of an asset is and then verify the validity of the ratings, and if it's constant. And if it's not then you can see that maybe the collateral backing it has moved in a negative way and has affected the rating of the product.

Ultimately, in steady-state, we want to make sure that it's easy for people to understand what these assets are and the risks. And also easy for people to verify that these assets are behaving as they should be, and then price them accordingly. In steady-state, we want to make sure that information is easily accessible and dynamic.

Just to make that clear, I think that would be a pretty market innovation in our space. Because, in traditional finance, it's hard to verify on an on-going basis that a pool of assets is actually behaving like it's supposed to. So the feedback loops in traditional finance are a little slower, but in crypto and DeFi we think we think we have the technology and the tools to make it a lot more dynamic.

It will be easier for market participants to enter the markets, exit the markets with assurance that product ratings are what they should be and what they are. And you can track that dynamically over time.

That's the long term goal, and we're trying to build the standards, the rules, the conventions, with the hope our partners will adopt them. But, over the long term that those become the standards in the DeFi space that provide some level of self-regulation and self-disclosure, that we think will be beneficial to the whole ecosystem.

**Troy:** Yeah, personally I find it really exciting what's going on with all that. Especially the outside conversations we've been having with other teams, and the input they have provided. I expect a lot of growth in that area in the next couple of months.

### Bounties

**Mark:** A small update from last week about the bounty programs. We have launched them— there are a few up on Github & Gitcoin already. 

You can find them in the [BarnBridge bounty program repo.](https://github.com/BarnBridge/Bounty-Program)

We also have a separate one for [project calls](https://github.com/BarnBridge/Project-Call-Notes-) because we are going to continue to host project call notes. We have already chosen someone for this week.  

There are three bounties out right now; 

 * [Japanese translation of Whitepaper and Website](https://github.com/BarnBridge/Bounty-Program/issues/2)
 * [Spanish translation of Whitepaper and Website](https://github.com/BarnBridge/Bounty-Program/issues/3)
 * [BarnBridge Meme Competition (November)](https://gitcoin.co/issue/BarnBridge/Meme-Competitions/1/100024202)
 
We actually have nine applications for the Spanish translation and we will be narrowing down those this week. But we currently have zero applications for Japanese. So if anyone knows Japanese, or is willing to help us out with that. Please reach out to us or apply for our gitcoin bounty so we can get that rolling.

As mentioned last week, we really want to be community-driven and offer as much as we can to the community to help with us. So, make a Gitcoin account if you don't have one and make a Github account if you don't have one because you will need a Github account in order to have a Gitcoin account.

If you have any questions about this and you are in our Discord you can always reach out to me and I can try to help out, get you started.

Really, same as last week, we have got them going they're started, just keep an eye peeled for more bounties.

They will be announced via Twitter & Discord.

If you are on Gitcoin or Github you might see them a bit faster than others before they are posted to Twitter or Discord.

**Troy:** Right on. I'm excited to see what happens with the call notes on this one, that should be an interesting experiment. Last but not least I think we'll hand it off to Tyler.

### Operations/Marketing Rundown

**Tyler:** Alright, it seems like for the next call I'm being asked to wear a Santa costume— we are going to need to vote on that next week.

*Technical Difficulties...*

#### Operations

**Tyler:** What I was going to say was, what are there around three thousand people in the Discord? If we can get a rough 20% consensus with upvotes or a poll. I'll buy a Santa suit, it has to be next week so Amazon can get it here on time. Shoutout to EJ for the idea.

Alright, just a quick rundown on operations and marketing. Some people were asking us in discord, about official partnerships.

So I think that the partnership concept was so abused in the ICO days. So now we have moved to DeFi calling actual partnerships acquisitions. I know why the community is asking about partnerships, and essentially as far as what Akin is doing, I don't know how official you want to call a partnership.

But we are working with Aave while on this call just launched the v2 of their protocol. We are also working with the Opium team on this general idea of standards. We also talked to ChainLink yesterday, about standards in particular, and how you verify on-chain assets and how oracles would be a player that could work with that.

The community can think of this as— we have all of these new on-chain tokenized representations of debt and derivatives off of those debts. Assets, how they're read on-chain will become somewhat of a cluster for the ecosystem, and we are trying to get out in front of it, to work with the community on some of those.

We'll probably reach out to Maker and Compound, once we start to solidify some of the things with the other players that I'm mentioning. I don't want to make it sound like we are not working with the entire ecosystem. I put a long-form response to everybody in general chat on discord.

For the people who are not keeping up with that. Like on the oracle side we are talking to pretty much everyone, like ChainLink, UMA reached out at one point asking us to look at their feeds. I know we are looking at the ___ feeds. Obviously, we are going to use ChainLink everywhere that we can, because it's like an industry standard, and there's a reason why ChainLink is as successful as they are because their team is pretty awesome.

In terms of actual, ink to paper partnerships, it's a lot more boring. But I'll explain to the community, so everybody knows what's going on. We are talking to two relatively large exchanges. Both are under NDA(non-disclosure agreements) we cannot announce anything, we do not want people front running. Those conversations are progressing. I'm assuming they will really progress when we have live products.

We've solidified, at least on our end, some aspect of legal council. As you know you got $200 million in TVL, meaning we are responsible for those assets and it's a big responsibility. As well as the general growth of BarnBridge from inception. Obviously, we just need to figure out what we can and can't say, and what we should and shouldn't be doing. To make sure everything is done properly so things don't get pulled down.

Bogdan alluded to audits. I think we've officially inked Haechi and I believe Quantstamp, but I don't know if we have signed with them, we are more working on timing but that's for the DAO. We will probably do a Hacken audit for Smart Yield. But more importantly is OpenZeppelin, since that's going to be the big product that we launch originally, which fortunately will be followed up quickly by Smart Alpha. I think some of those original timelines of development have overlapped a little bit.

All of those audit firms are signed deals that we are progressing forward. Also, as Bogdan alluded to, we very well may be working with one of our partners who helped scope out Smart Alpha, to help push some of that forward. That's unofficial but you could call that a real partnership.

So, just basically want to explain to the community, that we are talking to just about everyone in the ecosystem. I think it's a forgone conclusion that we will integrate with Aave and Synthetix. Those teams have been nothing but helpful, and honestly, kicked BarnBridge off from the get-go.

In terms of official partnerships, we are talking to just about everyone in the space in some capacity or another. We just don't want to go around name dropping unofficial partnerships, and the actual ink to paper stuff is very boring. But, hopefully, that gives everybody an idea of the boring behind the scenes stuff, that we are all working on.

#### Marketing updates

**Tyler:** We've been slowly rolling out Medium articles, more kind of housekeeping— who the team is, getting the team opened up on GitHub so everybody can see what they're doing. Mark has been doing a hell of a job on the bounty stuff. We have some articles that basically the whole team has been working on. Everybody from Akin-Pablo-Vitaly and Troy as well.

There is a DAO article coming out, it's actually kind of done, but we're having internal conversations about one feature of the DAO that I think we need to hammer out before we share it with the community. And then there will also be articles coming out about some of the deeper specs around Smart Yield and Smart Alpha.

As we started building these products the whitepaper is now not 100% accurate, because the devil is in the details on how you build these things. In broad strokes it's accurate but in the finite details, it's less so.

There's a lot of stuff we've been working on. When Coinbase was looking at us for custody they linked to our BOND token page, which was outdated— we've updated that. We probably need to update the Smart Alpha and Smart Yield sections of the site, there are some typos in some graphics that we know about.

There's just a whole bunch of little things happening behind the scenes that are boring. But I think that come January and February we are going to be shipping so fast, that people aren't going to be requesting unofficial partnerships because we'll be at the point we are moving into official partnerships.

Hopefully, that gives everyone an idea of what we've been doing. I think we're kind of all busting ass & hustling, and I think you can expect to continue to see that. Albeit, the Christmas blip will slow us down a little bit.

## Round Table

**Troy:** The Christmas blip, that's an interesting way of putting it.

**Tyler:** Well I'm a workaholic. So personally, you know. I don't have downtime on Christmas, but all ya'll can enjoy it. 🎅

**Mark:** Yeah, Tyler, for the last four years would come to Christmas, and then would open his computer while everyone was opening presents. Christmas and Thanksgiving, he'd say " oh my ___ have a black Friday sale, I have to do this!" he always had something open on his computer to do.

**Tyler:** Well...

**Mark:** It's alright Tyler, we'll always love you.

**Troy:** Inside family information there.

**Mark:** I just want to add one more thing, because I had people talk about it in their applications— for the meme competition guys, it's in our discord. You do not have a limit on how many memes you can submit. You can submit as many memes as you want, we love the memes. Your memes might get featured on one of Tyler's tweets or BarnBridge's tweets.

You may not win but keep trying next week. November's competition just ended so we'll be selecting someone this week. Then we'll put the bounty up for December, so holiday memes, whatever you guys want. Post as many memes as you want, there's no limit.

**Troy:** Keep the memes coming, keep the memes coming.

**Tyler:** I want more Amish memes. I love them. I'm almost liking those more than the James Bond ones.

**Troy:** Okay, well the last thing is the Round Table. Is there anything that anybody wants to talk about that wasn't on the agenda?

Usually, this is where we have the question section from the community, but there was none this week. Is there anyone on here that wants to say anything go ahead now?

**Mark:** Can you guys give us some questions next week? I don't think we have had one yet and this is project call 006.

**Troy:** We've had multiple.

**Tyler:** I think the epic Q bot on discord destroyed the questions.

**Troy:** I think there will probably be a lot more questions once the products start shipping. Especially the DAO and everything.

**Pavlo:** We were seeing some questions about a telegram drop. We are not doing any airdrops on Telegram. We just have one Telegram group and the only point of that group is to forward everybody to discord. Everything official has been on Discord and Twitter. Do not send your private keys, do not send your money anywhere. Just follow the official threads.

**Troy:** Yes.

**Tyler:** Honestly, just ignore anything about BarnBridge on Telegram. We literally only have a group to push everybody to discord. We have been reporting these Telegram groups. I have no idea what the scam is. It's some random bot, as soon as we pull it down, it just gets put right back up again. Some people in the community are saying we are responsible for it. Saying we need to talk to Telegram, I don't know anyone at Telegram.

Just ignore it, it looks like a scam and it feels like a scam. It's your guy's fault if you do something on there because we literally have nothing to do with that thing. So just, do your own research there. We'll keep reporting it, but I'm not going to officially reach out to Telegram to stop it, because it seems like whack-a-mole where you drop one and another pops up.

**Troy:** Yeah, definitely.

**Akin:** I'll add a couple of lines. There were some conversations around governance that we've had over the last couple of days on the platform. I just want to talk a little about that. Part of what we are trying to do is ensure that we have a really fair governance process, that balances expediency with participation from the community. As anyone who has been in the DeFi ecosystem, there's a lot of conversation and experiments around governance.

A part of what we are trying to do is make sure that we are taking the best of what we've seen out there, and incorporating it into what we are doing. But also, ensuring that it aligns with our philosophy and our goals of making sure that this is a community-owned project, and the community ultimately would have the power to drive decisions.

We're being deliberate over the next couple of weeks, to make sure we are dotting all the i's and crossing the t's. I think a lot of the conversations we've been having on the discord have been very helpful because I think we have been leveraging people's thoughts, and just having these discussions openly are helpful.

Just to tell the community, that governance for us is really at the top of the list. We want to make sure we roll out a process that has incorporated the best ideas out there but also takes into consideration some of the conversations that have already started happening on our discord. So, hopefully, when we launch it, it'll look a lot like a lot of the conversations that we have been having, and it shouldn't be too much of a surprise to too many people.

The hope is that we launch a governance process that is as good as we can when we start, and as we hand it over to the community, the community ultimately will drive how the process evolves over time.

**Troy:** I definitely think the conversation that's been going on in the discord is really great, and hopefully that will just expand as we keep rolling out these modules.

So, if there is nothing else, I think we will call this.

We will have one more project call before the end of the year.

If everyone's good, I think we're going to sign off and see you all on discord.

**Everyone:** Bye!👋
