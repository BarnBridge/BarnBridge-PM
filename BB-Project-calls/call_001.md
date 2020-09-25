# BarnBridge Project Call 001 Notes

### Meeting Date/Time: Thursday Aug 24, 2020 at 14:00 UTC
### Meeting Duration: 1 hour
### [GitHub Agenda Page](https://github.com/BarnBridge/BarnBridge-PM/issues/3)
### [Audio/Video of the meeting]()

Moderator: Troy Murray

Scribe: Dragos Rizescu

Attendees: Milad Mostavi, Dragos Rizescu, Bogdan Gheorghe, Denis Firu, Keegan Selby, EJ Rogers, Tyler Scott Ward, & Troy Murray

Intro
New people on the call
Denis Firu: Designer, he has been working DMOB for 2y now, worked on multiple projects within the space
4th Revolution Capital on the call Keegan & EJ
Keegan: with EJ Rogers, they are the two GPs of 4RC, 4th Revolution Capital, a digital asset fund focused on technology and crypto, specifically in DeFi
Long time players
In crypto sync 2011
Lead the round here with BarnBridge
Have been doing the financial modeling around the token allocation and smart yield product and getting into the volatility branch product now
Really excited, this is the bridge for TradFi and one of the true products for DeFi— participate for retail financial services.
Tyler: When everyone from the community came in and said that we need to clean the design, Denis has done that.
Tyler: 4RC have been pretty invaluable for us at BarnBridge
Dragos: +1 on Denis

Smart Contracts
https://github.com/BarnBridge/BarnBridge-YieldFarming
Milad shares the screens and presents
Milad: Finished the contracts for staking, yield farming, LP incentivization that are connect tot he community vault
The community vault very simple contract that will hold all tokens at the begning
The launch DAO at the beginning, and the BarnBridge DAO afterwards, will be able to allocate those tokens for different purposes
We have 8% for yield farming & 20% for yield farm LP incentivization which runs for 100 weeks starting for second week of yield farming because in the first week there will be no $BOND tokens. The yield farming runs for 24 weeks.
The yield farming will be connected to the staking contract and will accept USDC, SUSD and DAI— they will be added together
Since 2 weeks, we added progressive deposits
Users will be able to stake in the middle of the week and still get rewards for that
If someone add 100k USDC — they will get half the rewards for that at the end of the
We calculate how much time in the epoch and we give that amount.
Partial withdraws are supported also— you can withdrawn a specific amount which will not be rewarded because it’s not the end of the epoch
Staking contract is pretty cool— takes all the tokens in there, everything goes in there.
Next steps
Go deeper in the main DAO
Connect the UI, continue building the UI,
Do the audit
Connect the UI with the SC

Audits
Bogdan: We have been working hard on the smart contracts and finished them this week.
Right now, doing the due dillgience we are doing internal audits with the friends from Atpar
External audits done by Hacken.io— a full code and functional review with pretty much all known attacks verified, access control issues, all that stuff
Milad: Atpar is reviewing the contracts right now, they are amazing SC devs.

App Design
Bogdan: Presents the prototype of the app— Denis did a killer job, design is fire.

App Dev Updates / FE
Dragos: Killing it on the FE side, and development generally speaking.
Quick sneak peak on localhost, the barebones of the FE of what Bogdan has presented— the Connect Wallet is all done, a lot of WIP is happening right now.
Next steps,  Slava is currently working on the Pools page, connecting to the SC.
Next call we will have a lot to play with here.
Also we are setting up the infra and we will have the app live (on the dev side).
Tyler: We are getting to the point where we can demo FE on calls— the FE looks awesome from a design perspective, fast progress, pumped.
Troy: Have we come down that we are using the graph?
Bogdan: We want to get this out ASAP to start farming $BOND. Therefore we will be using the graph to show transactions and more until we build a stable backend.
Dragos: Sneak peak on the graphQL that Casian has put up.
Troy: When we do the indexing on the graph, should we have some docs for other metrics?
Bogdan: We have to built it— we only have a couple events. The subgraph is going to be public, but you won’t be able to do more with it.

DAO Research
Milad: We put most of the effort to get the SC ready for staking & yield farming, but fundamentally we want to have the main DAO very lightweight not very complex
Maybe use the diamond standard
But, re-use a lot of work used in the space
Troy: His personal philosophy with this— at the beginning is to keep it simple, maybe not use the Diamond Standard— build in complexity as we see what it works in the space. Look at Synthetix on how they are doing it. Keep our options open.
Tyler: No negative connotation, the 2 separate ideologies
Uniswap you need 10M UNI in order to submit something to the DAO— maybe is overkill, maybe not
Syntetix has a lower threshold to submit something
The new DeFi people need to remember what caused the DAO that caused the fork— it was a simple attack 
The OG Ethereum people— need to remember that back in the day the first DAO attack was done very simply.
The community is important to be involved in this, but this is still a financial institute. Simple attacking a financial took that is playing with interest rates cannot happen.
Tyler is in favor of high thresholds.
Troy: There are a lot mechanisms that you can put in place to quard those attacks.
Tyler: Someone can come in to get community support to run something up to run up their position. 
Troy: Incentives need to be aligned correctly, it will be tricky. However, we need to keep it simple at first and advance it how the space is moving. For example Synthetix will slash you if you don’t vote— more to look on what is going in here.
Milad: Starting next week we will have a better plan and next steps.
Tyler: Community involvement is very important to avoid what has happened in the crypto winter of 2018.
Milad: We need to categorize all the stake holders, know everyone and align the incentive.
Troy: Good point for the community to jump on this, R&D is happening in terms of the DAO. Community come on Discord to input your voice.

Marketing
Troy: A comment in the agenda about the marketing in github.
Tyler: This question will come every single week.
The way some marketers join projects, outbound sales strategy, say that the current marketing strategy is bad with the purpose to get hired.
We are in the phase of building and we have organic growth.
If you have ideas on marketing tactics that will work, we are all thumbs up.
However, if you come up with an influencer in crypto, we will not listen— if we ignore it, don’t take it personally.
A good idea, please share it.
Tyler runs Proof, a crypto marketing agency, so he knows all the influencers already.
The biggest thing for marketing we are doing, the yield farming is a tool for this. the people that own the token, understand how it works, vote in the DAO and tell other people about it— word to mouth strategy.
Tyler: The community has a bad vibe towards influencers, the pump and dump schemes done by influencers are short term schemes, we are looking long term for BarnBridge.
Troy: Bootstrap the community through yield farming and LP incentivization, very important.

Open floor
Milad: Also want to add that we added more people on the team: Adrian Bancu, Casian Lacatusu, Razvan Pop, Denis & Slava
Dragos: This is the Q branch office.
Tyler: Follow the Discord, talk it in there.
We are getting deeper in the Whitepaper, we will create some content that will go deeper into that.
Communication with the team— talk with us in Discord.
We will not be able to respond to everyone on Twitter, but we will try to get to them in Discord.
Conversations with us are Discord.

