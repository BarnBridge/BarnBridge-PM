# BarnBridge Project Call 022 Notes 

### Meeting Date/Time: Thursday 2021/7/22 at 15:00 UTC

### Meeting Duration: 18 mins

### [Github Agenda Page](https://github.com/BarnBridge/BarnBridge-PM/issues/39)

### [Audio/Video of the meeting](https://youtu.be/jpY00FyNY5Q)

### Breakdown: 

Moderator: Troy Murray

Scribe: Rayne L.

Attendees: Keegan Selby, Troy Murray, Pavlo Bendus, Vitalik Cherniak, Milad Mostavi, Christian Crowley, Bogdan Gheorghe, Tyler Ward, Max Fiege, DeFi Dad (Travis Blane), Trevor Latson

## Intro [[00:00]](-)

**Troy:** Welcome, everyone! To BarnBridge project call 22. A small update– the majority of the dev team is at EthCC. You'll hear them, but you probably won't see them.

So, Bogdan, if you would like, I'll let you take it away from here.

## Tech/Dev [[00:23]](https://youtu.be/jpY00FyNY5Q?t=23)

**Bogdan:** Hey guys! Sorry if there is noise. We are at EthCC. 

If anyone is watching– after this gets published –ping us in Discord and say hi! 

Short updates. We launched Smart Yield/Exposure on Polygon last week. We will have updates over the next few weeks for that. It was our first try with network changes, and we need to do some polishing.

Other than that, Smart Exposure will have some updates over the next few weeks.

We started with Smart Alpha audits last week. Those are supposed to last ten days. We'll have the first preview of how those turn out next week.

The specs for the back end have also begun because the UI got finished. We are kicking off the app development for Smart Alpha. 

Those are the most critical updates– see you next week!

Again, sorry about the noise, guys!

**Troy:** No worries! I'm sure you're having a great time.

Well, those updates were awesome. I think there are a lot of things coming out over the next couple of weeks.

As Bogdan said, Polygon got launched. 

So, awesome! 

I think what we'll do now is hand it over to the operations team. 

## Operations [[01:52]](https://youtu.be/jpY00FyNY5Q?t=112)

**Troy:** Christian, If you want to give a breakdown. Then we'll go through the list of operations.

## Christian

**Christian:** Sure! Happy too. Thanks, Troy!

### Priorities

A quick note from my standpoint– our priority over the next month and a half will be;

- Launch Planning (Smart Alpha)
  - We've kicked things off, and we are looking to go forward with a fairly comprehensive plan. We're pulling different components of the ecosystem to help there.

That's a big priority for us.

- Finalizing OKR & H2 plans
  - Formalizing objectives & Key results for half two– for the team.

I think it will be a good way to help with alignment.

### Product / Feature Prioritization

I've also been working alongside Bogdan. To build out a refined way to prioritize feature requests and additions to products. It will allow us to add those more strategically to our roadmap. 

So, there is more to come from that! 

First, I'll pass it over to Pavlo to talk through marketing updates. Max will walk through integrations updates. And then, Trevor will walk through what he has been working on recently. 

So, Pavlo, take it away!

## Pavlo [[03:08]](https://youtu.be/jpY00FyNY5Q?t=188)

Hey everyone! 👋

### Website / Newsletter Updates

I'll start with a website update. 

The new website build is up and running. There is a light and dark theme. You should also have the ability to sign up for our newsletter. 

Because we navigated away from the Substack, some people could not sign up for the newsletter. However, you should be able to now. 

Substack previously had all of the newsletters listed on one page. We figured out a way to do the same thing. There will be a dedicated webpage that contains a list of all previous editions of Barn Burner. If you've missed any, you can get check them out.


### ImmuneFi bug bounty program

Secondly, we've completed the ImmuneFi questionnaire.

A point to add there– [PID-4 successfully passed and executed.](https://app.barnbridge.com/governance/proposals/4)

Now we have the allocated capital to start the bug bounty program.

### DeFi Safety Score

We paved the way for updating our DeFi safety score to the latest version. 

So, that's also coming.

### Smart Alpha Educational Materials

Also, as Christian already mentioned. We've begun focusing on Smart Alpha planning. 

Max already drafted a great beginners guide– for Smart Alpha. Along with more educational materials. 

So, we're in the process of preparing all of that and putting it together.

With that said, I'll hand it over to Max.

**Keegan:** Hey, real quick. Educational materials sound like a job for DeFi Dad. (Whose on the call today)

We'll tag you in there, Travis.

**DeFi Dad:** You rang? ☎️🤓

Hey guys! That sounds great. I'd love to speak up after the call.

## Max [[05:22]](https://youtu.be/jpY00FyNY5Q?t=322)

Cool! I don't have too many updates on my end. (No laundry list this time 🧺📝😉)

I want to talk about a couple of community snapshot votes that happened this past week.


### Leo Renewed (China Community) & Rewards Renewal (KPI options)

We received passing approval for both the renewal of Leo's role as community manager in China. 

We also received communal support for the piloting of the KPI options program– for Smart Yield. Instead of an outright $BOND incentivization method. (That was good to see)

### Nexus Mutual (Excess Sum)

Also, now referring back to the previous community vote. When we initially made the communal decision to support shield mining on Nexus Mutual. The idea was to use DAO funds to buy back $BOND on the open market– to get used for that effort.  

The funds sent over for that effort are now far more than only 10K $BOND, which means we have an excess to consider. 

I believe there are a few different routes we can take. Other insurance platforms would allow us to stake the excess USDC/USDT for BarnBridge insurance on their platform.

So, I'll bring that to the community for us all to discuss and find a consensus. I believe it's around 120-130K in extra funds.

I'll hand it over to Trevor now.

## Trevor [[07:06]](https://youtu.be/jpY00FyNY5Q?t=426)

Thanks, Max! 

### The Graph

I've been working on getting our contracts indexed on the sub-graph. 

So, currently, there are thirty-three public contracts on there. There may be a few more to add in the future. They have gotten deployed to sub-graph studio.

Now, I'm working on a few updates to the schema. 

[Technical difficulties]🤖

**Troy:** It sounds like you are running into the awesome Puerto Rican internet that we have here. 

**Trevor:** Yes, that's exactly what's happening. (Let me disconnect my VPN)

**Troy:** You broke up there for a few seconds.

**Trevor:** Alright, we're disconnected now.

Anyways, we're getting the sub-graph schemas in place. Once those are published, we'll make the repositories public so that you can see exactly what kind of data will be available for use. (What you can use complex queries for)

### Additional Tokens for Smart Yield

Other than that, we're working on getting sUSD (Synthetix USD). And RAI added to Smart Yield.

That shouldn't be a heavy lift. Since we already have the code in place for other assets on Aave. 

Finally, I'm working on building out the backend for KPI options– in a reusable way. So, It's looking like it won't be a one-off. We'll have a codebase that allows us to leverage KPI options in different scenarios in the future.

That's about it for me!


## AIP Update (Aave)


**Troy:** Cool! One thing that I do want to bring up. 

I know, we've been saying on these calls that we're pushing to get on Aave and other places. 

However, it has taken a lot longer than we initially planned. I believe I've been saying for the past four calls– It's right around the corner.

But governance in web3 is not the easiest environment to get things done. We're very close. I want the community to know that!

We are about 22K Aave short for delegated proposition power– for the AIP. But, there are things in motion that should get that figured out. (Hopefully, in the next week)

I'm pushing this for the next week, and I think it will happen. 

But, I want the community to know, there are things in motion. The AIP is ready to go. It's gotten approved by Aave to get pushed out. So, you can look forward to that!

We're all pushing hard!

I wanted to clear that up.

## Round Table [[10:17]](https://youtu.be/jpY00FyNY5Q?t=617)

**Troy:** I don't know, Tyler, did you want to say anything? 

If you have to add anything– we're at the round table now.

**Tyler:** Specifically about Aave?

**Troy:** No, I just mean in general. 

**Tyler:** Not really. 

Just that we've been busting our ass since Smart Exposure dropped. If anything, I'm slightly brain dead because it's been a blur. 

The dev team has been working very hard on Smart Alpha. And while that's coming out, we're working on specs for (without teasing) something that is a big lift. We've been working on it for months, and we're going through everything with a fine-tooth comb. Making sure there are no edge cases.

I think the entire team has been working full strength on something we haven't even talked to anybody about yet. We've only teased small things here and there. There hasn't been a ton of outward business development ploys. Or land grabs or bells whistles– where we promote a product. 

We've done a lot of due diligence, checking our P's and Qs. We're making sure that from a security standpoint, we don't release something improper. That's essentially what the last few weeks have been like for everyone on this call. 

It's not a fun, exciting thing. It's what we need to do to ensure that people don't have to worry about using the products. 

**Troy:** Yes! 100% 

It does feel like a blur, to be honest. 

Anyway, this is a somewhat short call because a lot of the dev team is in EthCC. 

And unless there is anyone on the call who would like to add or say anything. We can probably call it. 

The coming two weeks are going to be exciting! There is a lot. 

So, we'll leave it at that. 

### Introduction: [DeFi Dad (Travis Blane)](https://twitter.com/DeFi_Dad) [[12:55]](https://youtu.be/jpY00FyNY5Q?t=775)

**DeFi Dad:** Troy, just a quick note! 

Hi everyone! (This is the first time I've joined a call) 

If you see guys see any opportunity in the next week or so. (Based on what Tyler shared) If it would help at all– you can do a short live stream with me. I'd love to do that– to help communicate some of this and get it out there. 

We can do what we've done in the past. 

Again, it depends on what Pavlo is thinking. And all that hard work you are all doing, it will pay off. Once these products release. If you ever want to use my Youtube as a catalyst to communicate that. 

Otherwise, we'll be stoked to show it off– when Smart Alpha goes live.

**Troy:** We appreciate that a lot! I think we can pow-wow around that and figure out how we'll go about it. A few marketing ideas are floating around. I think Christian will likely want to provide an opinion on that. 

He schedules the majority of that. But, yeah, we greatly appreciate it, and we'll take your offer.

**DeFi Dad:** You guys know! Just call upon me. (Now that I'm on the team 🎉)

I have nothing holding me back. We could do a live stream within 24hrs if you needed. 

And also, Christian and Pavlo. If you ever wanted– I'm happy to join your brainstorming meetings, and I may have some new outside perspective or perhaps just providing fresh feedback. 

Otherwise, you are all killing it! 🦾

Just call on me whenever you need it. 😎

**Tyler:** I will add you to the internal Slack!

Now that you're in there. 

I don't think we gave DeFi Dad a proper introduction. I believe everyone in the industry knows him. 

So everyone knows, and when I say everyone on this call. Even our capital partners [4RC](https://www.fourthrevolution.capital/). (Who helped with a ton of the OG modelling for Smart Yield)

Their team has been helping us model edge cases for a few of the other products we are planning– both behind Smart Alpha and for it. 

So, I'm not sure when we started recording and if we introduced DeFi Dad properly in this context. 

**Keegan:** Yeah, DeFi Dad officially joined 4RC. He's here to support our portfolio of companies. And Barn Bridge is our favourite of all time. 

So, that means educational tutorials, live streams– that whole thing. 

He's the best in the business. He's here to support you guys. 

**DeFi Dad:** And, I cut a tight lawn. 🚜🌿

You should see what my lawn looks like right now. 

**Everyone:** 😂😂😂

**DeFi Dad:** I also put together swing sets and barbeques. 

It's good to be here, officially! I feel as if I was always a secret part of the team. (Obviously, I was a part of the DAO from the beginning)

But, anyway, I'm stoked to be here now. 

And if anyone doesn't know– my name is **Travis** –you don't need to call me dad.

**Tyler:** You have to call him Father Travis or Daddy Travis. 

**DeFi Dad:** Wait, hold on. I'm a Car collector too. 

**Keegan:** Hey, look at that! It's a Lambo. 😆

**DeFi Dad:** It's a 2012 Nissan. 😏

(In case you're wondering; it's worth 4K💰)

**Tyler:** Before moving to Puerto Rico, I had a 2003 Chevy Cavalier because I'm not a car person either.

I think we had to scrap it when I left. 

Also, yeah, DeFi Dad, we're happy to have you too man, you've been supportive from the get-go. We appreciate it. And what you've done for Ethereum in general. 

**DeFi Dad:** Thanks, guys! 

Yeah, this has been one of the most exciting projects to be a part of. 

**Tyler:** I think we can call it now. 

Alright, everyone!

**Troy:**  Yeah!

Alright, everyone, have a great rest of your day. We'll see the rest of the community!

**Everyone:** ✌️✌️✌️✌️✌️✌️✌️✌️

<br>

### Relevant Links

* [Website](https://www.BarnBridge.com)​
* [DOCS](https://docs.barnbridge.com/) 
* [Project Management Hub](https://github.com/BarnBridge/BarnBridge-PM)
* [Agenda](https://github.com/BarnBridge/BarnBridge-PM/issues/21) 
* [Twitter](https://twitter.com/barn_bridge​)
* [Discord](https://discord.gg/NwXHd3z)
* [Youtube](https://www.youtube.com/channel/UC4exzX_c37p2gYJK4L9nrGQ)

#### BarnBridge Products

* [BarnBridge Shop](https://www.barnbridge.shop/)
* [Bond.Bet](https://bond.bet/)

