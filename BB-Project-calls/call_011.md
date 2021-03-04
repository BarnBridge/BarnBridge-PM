# BarnBridge Project Call 011 Notes 
### Meeting Date/Time: Thursday 2021/2/18 at 15:00 UTC
### Meeting Duration: 38 mins
### [Github Agenda Page](https://github.com/BarnBridge/BarnBridge-PM/issues/17)
### [Audio/Video of the meeting](https://youtu.be/ZTXCwv5D0IU)
### Breakdown: 

Moderator: Troy Murray

Scribe: Rayne L.

Attendees: Keegan Selby, Troy Murray, Mark Ward, Akin Sawyerr, Pavlo Bendus, Vitalik Cherniak, Milad Mostavi, EJ Rogers, Danijel Gornjaković, Dragos Rizescu, Bogdan Gheorghe

## Intro [[00:00]](https://youtu.be/ZTXCwv5D0IU)

**Troy:** Welcome to Project Call 011

Dragos is lighting a candle! 🕯️

Let's start with the tech update! I'll pass it to Bogdan. 

# Tech/Dev [[00:10]](https://youtu.be/ZTXCwv5D0IU?t=10)

**Bogdan:** Thank you, Troy. Yes, the usual– I'll start with all the bits and pieces. And some small updates for each. 😎

## Yield Farming [[00:10]](https://www.youtube.com/watch?v=ZTXCwv5D0IU&t=10s)

**Bogdan:** Yield farming, we sunsetted pool three about a week and a half ago. Around 95% of the BOND tokens have been withdrawn and moved to the DAO. 

To add to that. There are a few thousand tokens (40-39K) still in pool 3, whoever has left those– I hope you see, hear or read this. Just withdraw those, don't wait for the gas fee. Withdraw those tokens and move them over to the DAO and continue staking there. That's essentially it for yield farming. There are no new updates since the end of pool three.

## BBDAO [[01:16]](https://www.youtube.com/watch?v=ZTXCwv5D0IU&t=76s)

**Bogdan:** The BarnBridge DAO has successfully launched. The DAO has almost absorbed the deposits of pool three. As far as token supply, around 50% of the circulating supply is staked– which is good news. 

We met the activation threshold within a week. The DAO is activated, and anyone with over 10% of the total BOND staked can make proposals. We also encourage you to do so. 

Whoever is interested in doing that, we have two venues to discuss this– before adding it to the actual DAO. There is a signal vote (via Snapshot) this uses signatures. Signing allows for a gasless Vote & we have forums. The forums are where you can have more long-form discussions. And the Snapshot allows for a mock vote.

About the Snapshot, Dragos will give some details about it,  because we have had some problems with it.

**Dragos:** The Snapshot is [signal.barnbridge.com](https://signal.barnbridge.com). We have an issue with it. It only allows members to post proposals. Everyone can create them, but it won't display until your address gets added to the 'member' list. I've tried to diagnose this, but I cannot figure out the solution to the problem. 

Nonetheless, if you do post a proposal and you are having problems with it. Then link to it in the Discord, and we will get your address added to the list and have the proposal displayed. That's the workaround I have found for now.

There's an active proposal right now. For [Smart Yield Junior Tranches on SushiSwap](https://snapshot.page/#/barnbridge.eth/proposal/Qmf6HKkRMvY8cANPcCnKrHyqBL9bftS3xVjSSWuKAPWEJR)

Alright, Bogdan. I believe that is all I have to say about Snapshot.

**Bogdan:** Besides that, we still have a couple more releases planned with some polishes and minor improvements. Those should come in the next few days or so. 

### Forum Launch

**Troy:** We also launched the forum.

**Bogdan:** Right, I touched on the forum. I'm not sure what else to add other than the [link](https://forum.barnbridge.com). You can use this space to engage the community and obtain a mock vote useable for Snapshot. The forum is where you can engage in more long-form discussions. Please be respectful. 

There is a proposals category. So you can discuss the material, get a mock vote, link it to the Snapshot, see how the Vote goes and then it's added to the DAO. That should be your process for launching proposals.

### UI updates

**Dragos:** One more thing. I am not sure if you touched on some of the other releases that happened over the last few weeks– after the DAO launch. We have made quite a few small UX and UI improvements and have pushed a couple of releases. Just some minor changes I felt like I should mention that in case you forgot. 

**Bogdan:** Yes, we will have a couple more releases after the DAO. But all of it is minor, just some small bugs and UI polishes, that kind of stuff.

## Smart YIELD [[05:35]](https://www.youtube.com/watch?v=ZTXCwv5D0IU&t=335s)

**Bogdan:** Let's go step by step through this. Everything that I mention are all happening in parallel. So we are back to full-on launch mode. We have contracts deployed on the test-net. We are just making sure they do what they are supposed to do. We have set up a two-week deadline for ourselves until launch. So we have been busy coming up with a bulletproof test for this and go through every possible scenario for the contract.

### Audit Updates & Launch Dates

**Bogdan:** For a launch date– we have it set for the first week of March, but that is tentative pending the audits. They could push us past this date a bit. The worst case is mid-March, dependent on the audits. Both audits are in progress, and we have been in touch with the auditors. We're confident and believe we are awaiting good news.

The primary focus right now is connecting the front end to the back end to the testing contracts. Then we can run through the process of the front end and see how everything works. When the time comes, we plug into the mainnet contracts. And then we can release everything into the wild–hopefully around March-ish. Fingers crossed! 🤞😎

## Smart ALPHA [[07:21]](https://www.youtube.com/watch?v=ZTXCwv5D0IU&t=441s)

**Bogdan:** The same as last call. The contracts are in full-blown development mode, and there have been six different models at this point. All of them had strong points and weak points. We initially had decided on a model, but after further testing, we realized and were inspired to create more possibilities for future iterations of Smart Alpha. 

Future versions may sound weird because we have not launched the base yet. But that's how far we are trying to think about this. There is some more cool stuff planned. 

I think that about covers it!

**Troy:** Cool! 

Also, something that was not on the Agenda. But that has been going on in regards to Smart Yield and Alpha's long-term plan. We have had a few concrete conversations around Layer 2 options with Optimistic and Kain at synthetix. I know plenty of people in our Discord ask us this constantly and understand there is a lot of work going into that. But, we are a team that is at the forefront of this, and we will get access when the time comes. And I'll leave it at that. I've been told I really shouldn't talk too much about it.

So, know there is work getting done!  

We also want to say welcome to Danijel– who is our bot master on Discord. Maybe some of you have seen him before. This guy is pretty much the central nervous system for the entire Discord DeFi ecosystem. If you're in a server with price bots or anything, this is your guy. He pretty much runs DeFi's entire Discord bot infrastructure. 

He has been working on a bot for us. It's modelled slightly after our DAOFirst mechanism and how we orientated a multisig that the team runs. I'll be passing it off to Danijel– he has a demo for us. This bot will be a project that we giveaway to the ecosystem. Projects or teams with a DAO and a Discord can use this to organize others inside their Discord. We look at it as a quasi-reputation layer inside the ecosystem. Where people can bubble up, and this helps to arrange that.

So, Danijel, if you are there, you can introduce yourself and go ahead.

## DAOFirst Bot

**Danijel:** Thanks, man! I don't mind showing my face. 

**Dragos:** Nice background! 

**Danijel:** Ah yes, I had a joke for it. I am in my daughter's room. It is the quietest place to have this call. 

Thank you for the awesome introduction, Troy. I have done plenty of Discord bots and probably in the range of hundreds by now. This one so far has been one of the more challenging projects I've done. I got quite excited about it when we started talking and rushed to deliver something as soon as possible. 

It's nowhere near the final version. So this is an early demo– I'll gather some feedback and see how we move forward. I'm excited to show it. 

### Demo [[08:57]](https://www.youtube.com/watch?v=ZTXCwv5D0IU&t=537s)

**Danijel:** So here is the bot. I'll pull up the list of commands. Troy made a bit of an intro for the bot– it's for making a mini DAO inside a Discord server.

> **!help** brings up the command list

You use your Discord handle because everyone most likely knows you by that name.

*Here is the list of commands*

* !createSquad (creates team, assigns channel, role. Adds creators as members)
* !addMember (adds tagged user to the team)
* !setWallet (assigns a wallet address to Discord user)
* !setConsensus (sets team consensus for multisig)
* !initSafe (preps txn to create Gnosis safe for team members)
* !setSafe (replace team safe address)
* !squad (Details of the team) 

Currently, it's a bit trivial. But there is a lot of work going into it. The safe creation is a feature of Its own, and it uses Gnosis multisig safes.

**How to create a squad:**
* !createSquad BarnBridgeDemoSquad
  - Alright. So a channel is automatically created, and I was granted a role there as a squad member. Since I am the creator, I am also a member by default. Anyone can easily create their squad, and they receive a channel.

  - After I enter the '#barnbridgedemosquad' channel, I am in the context of my squad. And the bot automatically knows that. 

**Adding members:**
* !addMember @DanijelsTestUser
  - The bot replies with an alert. The bot tells me that the server member I have selected has been added and automatically assigned the 'squad' role. 

**Squad Overview:**
* !squad
  - From there, I can see the name, number of members, the consensus value. At the moment, my consensus is one, and there are two members, and ideally, you would want everyone to sign. Right now, you only need one signature to pass any transaction. In general, we would prefer at least 3/4 or more to sign off on the transactions. 

**Setting consensus:**
* !setConsensus 2
  - I did set a bunch of validations as well. So if you try and make the consensus higher than your members, the bot will return a prompt telling you to add members. 
  - For example, if I have two members and try to set consensus to three, the bot will say– there are not enough members in the squad. 

**Setting a wallet address:**
* !setWallet 0x0000...0000
  - You can see that I can change my address to whatever It needs to be. It's worth mentioning the additional validations that prevent other Discord users from making commands and affecting another squad.

**To create a safe:**
* !initSafe
  - The bot will send you a message about a prepared transaction with a link to follow. I still need to build a front end for this. And note I'm not a front-end developer. I will probably need some help from some people who like to do the CSS and beautify. 

  - As you can see, I connect to my Metamask. On this screen, I can see the squad name, the consensus rules and the signers. I can create the transaction from this screen. You receive an alert telling you your transaction hash. And telling you to go back to Discord, and the DAOFirst bot will let you know once the safe initializes. 

  - You can go back to the Discord and see that the bot is listening to the safe creation and following the transaction hash. The bot will also send a message once the transaction has initialized– you will then see your new safe and the address. We can navigate to the Gnosis Safe app from this reply. From there, we can load the safe with the address provided by the bot. You can verify that the member addresses match and can go from there.

There are many different things you can do with a bot like this. I'm still working on doing Gitcoin transactions with this. Interactions with Gitcoin, like starting and finishing bounties, that pay directly to a treasury. After that, I think all that's left is a feedback round with Troy and Mark. And of course, whoever else would like to provide some feedback for this. Whatever can help make this a fully functional mini-DAO bot. 

**Troy:** That's awesome, Danijel. You rocked this out in a matter of days. I'm incredibly impressed.

**Mark:** Yeah, you've blown us away, man. This bot is a lot more than we were expecting in the time frame you had.  

**Danijel:** Thanks, guys!

**Troy:** Totally!

**Mark:** We appreciate it, man! You kick ass.

**Danijel:** You know what took the most time? This UI. 😂

You can't be good at everything in life, and you have to accept that.

**Mark:** Well, better than some!

**Danijel:** It will be open-source eventually so anyone can take it and beautify it. 

**Troy:** Just to let the community know. The nice things about using the Gnosis Safe. If you have a squad inside of a DAO and you receive capital to do stuff. You can take that capital and use the products already integrated with the Gnosis Safe to create yield and generate more runway for yourself. That's the idea behind it– leveraging the systems that are already out there.

I'm excited to see this in action. I hope other projects integrate this as well. We will be giving it away. It interacts very well with our DAO and how we created it. You will be able to form mini-teams. 

I think that's about it. Thank you so much, Danijel!

**Danijel:** You're welcome! 

**Everyone:** 👏👏👏👏

# Operations [[21:56]](https://youtu.be/ZTXCwv5D0IU?t=1316s)

**Troy:** Now for operations! Akin, do you have anything you would like to comment on regarding the DeFi Alliance?

## DeFi Alliance [[21:56]](https://www.youtube.com/watch?v=ZTXCwv5D0IU&t=1316s)

**Akin:** Things are going as they were before. Lots of conversations with liquidity providers. That has been the best return of value so far, getting them understanding what's going on with BarnBridge and hopefully setting them up to ape into Smart Yield and then eventually Smart Alpha.

That's going pretty well. We still have a few weeks to go to continue building relationships. And hopefully, they will help us down the line. Some of those conversations are leading into interesting directions about partnerships. That focus on both our products but also the long-term opportunities and relationships for BarnBridge. Those conversations have been good. 

Other than that, we have been continuing conversations in the community around proposals. As we approach the launch of Smart Yield, some of my focus will be thinking about proposals. To get people to think about ways to leverage the DAO. Trying to help give structure for people and showing them how to play a role. I think a lot of attention will be around that. I'll be helping the community and looking for a way to gauge the sentiment for what needs building and how we can add value. 

That's pretty much it!

**Troy:** Cool! 

Alright now moving on. Mark, I think you have some updates on the bounties. We have not been able to update them because of the gas fees. But I'll let Mark give an update on those.

## Bounties [[24:13]](https://www.youtube.com/watch?v=ZTXCwv5D0IU&t=1453s)

**Mark:** That is the update. Let me start with the translations. I know I've talked a lot about this. Just bear with us because we need to update the site and have all the languages update together. There is a lot of new things, and we have products coming out soon. So, we have slowly been releasing the spec for Smart Yield. So a page will be up for that. We are just getting that caught up with the new translations. 

Also, we have not been posting a lot of bounties. The gas fees are kind of out of hand to be posting 50 dollar bounties. Because It's around $20 to pay it out, and another $20 or sometimes 100 dollars– to post it. And that is not practical for us. 

We are still going to be having bounties. And they'll be posted in the repository so people can still submit a pull request. But for the moment, we are taking a break from Gitcoin. To save a little bit of crypto so we can continue on these programs. We don't want to be wasting any funds that do not need wasting. 

**Troy:** Cool! Yeah, It makes total sense. I know you can use layer 2 for payments on Gitcoin, but you cannot currently post bounties this way as it's just a payment solution. 

**Mark:** That's the most expensive part. Paying out the bounty is cheap, but listing it is costly.

**Troy:** Yeah, because it's going on-chain. And with all these people putting NFTs literally into the chain...we've got problems. ☕🐸

Anyways, last but not least, we will turn to Pavlo for an update on the website and the Discord.

## Website/Discord Community Update [[26:57]](https://www.youtube.com/watch?v=ZTXCwv5D0IU&t=1617s)

**Pavlo:** As we are getting closer to the Smart Yield launch, we have been updating more things on the website. We recently updated the old pages about Smart Yield and added the latest information. 

We have also been working on the documentation for BarnBridge. Also, there was a Twitter poll, and most people seem pretty impressed by the DAO. They also love the little tutorials, so we will continue doing that. Everything is coming together and will be available soon! 

**Troy:** Okay, cool! Thank you for the update. A lot is going on in the Discord, and I think as we get closer and closer to launch, I think we all expect a lot more will be going on. And I think the more, the merrier.

Moving on to the Round Table!

# Round Table [[28:30]](https://www.youtube.com/watch?v=ZTXCwv5D0IU&t=1710s)

**Troy:** As the community and Discord have grown, we have gotten more and more questions in the comments. There are four or five questions. 

The first one is for Tyler, but he is not here, so we will have to skip that one. 

Question (1)
* From: **Amishmanish**
  - For devs: If you can share briefly; in terms of coding and algorithm-deployment, what are the steps involved in building out the Yield and Alpha products?


Answer (1)
* From: **Milad**
  - Smart Yield development started based on a model that Keegan shared with us. We iterated on that and developed a spec from it. From there, we started building it out and writing code in solidity. We ran some tests against it. Then we started targeting Compound so that the current yield is gets generated there. After that, we tranched the rate into two different tokens.

  - Smart Alpha started similarly, but it's still in the early coding stages. The spec took a bit longer there. It may evolve from here. That's the process, and the teams involved with each product are not very big.

Question (2)
* From: **Amishmanish**
  - How are devs looking to reduce computational steps (gas costs) for complicated on-chain derivatives? Could you share any examples

Answer (2)
* From: **Milad**
  - One of the things about solidity is you can't loop indefinitely. If there's a set of items that require action, they need to remain small. And not grow constant. For example, with Smart Yield, we came up with a way to represent the senior bonds in a small structure. We call it A-BOND or aggregate-bond. They kind of represent all the BONDS that currently exist. We then use that as a baseline. It's not necessarily cheap all the time. But we do know how long it takes and how much gas it uses. And as the number of BONDS grow, the gas used remains the same.

Question (3)
* From: **Mike9870**
  - Is it possible for the team to discuss the project decentralization goals? Specifically surrounding BOND and its products not being classified as a security.

Answer (3)
* From: **Troy**
  - From the get-go, we intended this project to be decentralized from the start– to the point that we never created a legal entity. We started from a DAO. All the founders and feeders were involved in the launchDAO, and that DAO seeded the main BarnBridge DAO. It's always decentralized and always will be. If you look at the token distribution, the community holds the majority and not the people on this call.

  - That's all I am going to say on this topic. And I will not answer the other part of that question, Mike9870, because that get's a little dubious for us. 

Question (4)
* From: **ObiStanKenobi**
  - What aspects of the products will be up to the community/DAO to decide? How will this process impact the release timelines?

Answer (4)
* From: **Troy**
  - This won't affect the release timelines at all. The products will be out. But the timeline for updating parameters inside the products is different. We will go over the parameters in a Medium article. The current things the DAO can control are the fee structures– how much gets taken from a Junior or a Senior BOND– and the maximum duration of the bond.

* From: **Milad:** 
  - Those are the main things. There are two pluggable components for the Smart Yield that the DAO can change. 
1. The Oracle: Calculates the yield generated by the pool (3-day avg.)
2. The algorithm/formula that offers the Senior Bond a yield can change

Right now, the formula reflects the pool composition. More Junior vs Senior Bonds means a better rate for the Senior Bonds.

**Troy:** Awesome, look for a Medium article closer to launch. There will be more details on that. We are just working through specifics. But everything will become very clear. 

I think we are done with project call #011. Unless anything else has anything to say?

**Akin:** Yes, I have something to add for the last couple of questions. I think, ultimately, it's whatever we make it to be– when it comes to participation with the DAO. I have spoken recently to a few people on the Discord, with people asking questions about how they can contribute. I think within those discussions. We can find more ways and add more structure. 

I've had thoughts about putting out proposals to add more clarity and structure– around how people can participate. I think there will be a lot to do on the operational side to decentralize that. Everything from partnerships to marketing. Anything where organizations could use that type of structure to add value. We should continue those conversations, and as more discussions happen, it will provide more insights into what needs more structure. As it makes sense– and adds value. We don't want this to be overly bureaucratic. However, I think that anywhere that we can add direction, provide structure and value should be the focus.

**Troy:** Yeah, I look forward to seeing this. Kind of like Synthetix, you have the protocol and then there are projects getting built on top of that. Those are then taken over by community members. Which was the idea behind getting Danijel to make that bot. A way to streamline the ability for the community to decide who gets allocated capital. Then the team can control that capital. And the community can still monitor it in a way. Teams also have an easy way to manage that capital if need be. That's the reasoning behind the Gnosis Safe. We are working on ways to streamline the organization and turn it over 100% to the community.

I look forward to seeing what happens from this. So look for more structure– it's coming. And watch out for the products being launched and what ends up getting built on top of this. It's going to be very exciting.

I think we are there, that's project call #011 in the books. We'll see everyone in two weeks!

**Everyone:** 👋👋👋
