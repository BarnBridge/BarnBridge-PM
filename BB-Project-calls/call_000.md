# BarnBridge Project Call 000 Notes

### Meeting Date/Time: Thursday Aug 10, 2020 at 15:00 GMT
### Meeting Duration: 1 hour
### [GitHub Agenda Page](https://github.com/BarnBridge/BarnBridge-PM/issues/1)
### [Audio/Video of the meeting](https://youtu.be/Q3N1o2W6-CM)

Moderator: Troy Murray

Scribe: Dragos Rizescu

Attendees: Milad Mostavi, Dragos Rizescu, Daniel Luca, Bogdan Gheorghe, Casian Lacatusu, Tyler Scott Ward, & Troy Murray

## Intros
- Tyler Scott Ward— the idea builder
- Milad Mostavi— the architect, the DMOB
- Dragos, Dragos Rizescu— just Dragos & product dev
- Daniel Luca— DeFi lead dev & secutiry
- Bogdan G—  DeFi nerd, product & data dev
- Casian Lacatusu— DeFi dev
- Troy Murray - anon

**https://barnbridge.io/team/**


## Tech

### DAO First Approach
Tyler: inspired to just have this built by anyone because it’s a product he wanted to use for a long time
YFI came out with the fair launch concept— distribute governance and have it community run through a DAO
Kain said from the beginning that the one thing he would have done differently with Synthetix at start would have been to go DAO first because going the other way around creates a mess.

=> Roll this out as a DAO first

More fair and distributed launch because of it

Be able to distribute the governance to a degree that allows us to have a community to decide on the platform, not us making the decisions
Long term, the types of things that we are dealing with internationally from a regulatory perspective, it helps if a lot of the governance is driven from a community perspective
VCs, money people, didn’t like it, however we can be an example of how and why this would work, DAO first, so more companies do how we are doing => inspire a generation of new decentralized companies

Troy: We are completely transparent from the get go, from the start— you can see all it going

Tyler: This method allows people to stick true their guts and not change because of money
We could have raised more money since it was a lot of interest in this, but we stopped— we don’t need this much money
Therefore this kept us honest because we have to report everything to the community

Dragos & Troy: It’s been a wild ride and we are just starting.

### Yield Farming
BBIP-002: https://github.com/BarnBridge/BBIP/blob/bbip-002-YieldFarming/bbips/002-YieldFarming.md

Daniel: With the Yield farming, we are thinking of a fair way to distribute some of the tokens w/o selling the tokens to the people— no money from this to us
People will add DAI, USDC & sUSD to the Yield Farming stacking pools
They will be able to extract those yields whenever they want and the tokens
We want to do it for 24 weeks, split into epochs— 1 week = 1 epoch
The more you stay, the more rewards you get
We distribute 8% of the total token supply => 33,333.33 tokens per epoch
Who stakes the most in an epoch, they will get more tokens

Troy: Reason we are using USDC, DAI, sUSD in the yield farming in staking is because those are the first assets that will be used in the first product— Yield Bonds 

Tyler: To clarify to the community, when we are not making any money— means that we are not making an ICO— selling this tokens into the market.
However, are we not taking some aspect of a small fee of the curve pool? That would go to the foundation. Like a nominal fee.

Troy: We are not setting up a pool.

Milad: We are not— we can choose to sell some of the tokens to the uniswap pool from the treasury— only if the DAO decides to do so.
Something that is not visible in this specification
The $BOND/yCRV pair which gets highly rewarded in the first 24 weeks, bonus— next 100 weeks after that we have incentivisation plan running for that LP token from uniswap

Troy: By staking the LP token you get 2.5x $BOND on that in the current specification— exciting.

Milad: 2.5x in the first 24 weeks and 100 weeks, but we don’t know exactly the amount of tokens.

Troy: We are bootstrapping liquidity in the network now basically.

### Diamond Standard
BBIP-001: https://github.com/BarnBridge/BBIP/blob/bbip-001-BarnBridgeDAO/bbips/001-BarnBridgeDAO.md

Troy: Daniel proposed Diamond Standard

Daniel: Because we need to do everything DAO first & decentralized everything, Diamond Standards fits pretty well here.
One of the biggest problem in the Ethereum ecosystem is contract upgradability— one option is to have a proxy contract with an owner that can do that.
What we wanted to do is to have the DAO be itself if each choses so— people can vote, add or remove functionality.
=> The DAO can do everything with this standard.

Daniel: This is not battle tested yet, few projects have started to use, but we think it’s in a pretty good shape right now.

Troy: You don’t have to remove everyone and add everyone— that is the problem.

Plus, new governance systems that can be added to the standard. Like cold storage voting.

### BBIPs
BarnBridge Improvement Proposals: https://github.com/BarnBridge/BBIP/

Daniel: Everything is open and everyone can come on it and comment on them.

BBI-001— the DAO
BBI-002— Yield Farming
BBI—003— The $BOND token, which is an accepted state.

Troy: For community, please add to this, you will be invited to the call and the conversations will be better— this is community driven.

## Marketing
Troy: A lot of opinions in Discord on how we should market this— Tyler, take it away.

Tyler: Regarding Discord discussions, we are not going to do a lot of advertising.
Because of what BarnBridge is doing from a financial instrument component, BarnBridge is banned from any big marketing platform such as Google, Twitter, Facebook
It is good that we jump start the community, but we don’t have any major reason to use the main 3 digital marketing platform
Also, the tokens are allocated, we will not be giving influencer incentivisation

Tyler: We did allocate some capital from the seed to markerting
To get the domain— barnbridge.com was $5k but needed long term
Get the banners on ethtrader
Plus a lot of marketing will be done out of pocket, not from the funds— everything from seed will go to development

Tyler: From community updates
Organically, it’s a lot a buzz, and growth is here
Therefore, the organic growth will be enough
Plus the yield farming will help to build a community

Tyler: We haven’t thought a lot on how we will do community management or BD— because we are focusing on developing
