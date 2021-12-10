# TECH / DEV


## INFRA & BACKEND


- smart alpha update/upkeep bots for all the networks we are deployed on, alternative to expensive chainlink keepers - these will make sure that all upkeep transactions happen on time, especially SMART Alpha epoch advancements, which can’t happen without an on chain transaction
- general upkeep of cluster and services together with extra monitoring and alerting for the health of the services and databases
- db optimizations for heavy load caused by calculating junior/senior 30day avg apy figures - all of these optimizations are made to ensure these figures are correct
- cleanup and removed resources to decrease hosting costs
- trying to keep arbitrum and bsc up as node providers were flaky, especially bsc - working with teams and RPC providers to ensure everything stays up to date
- api enhancements for pulling NAV data for funds - TBD when included in app - this will allow users to pull junior/senior SMART Alpha token prices for any timestamp
- prepared and open sourced the backend - scraper, indexer, api and dependencies - everyone can now spin up a full version of the BarnBridge app, backend included. Open source fans encouraged to contribute!

## L2s


### Optimism
- deployed on kovan OE - currently in testing on our dev environment
- will work with chainlink to get feeds up for more pools, in order to move some of the less used mainnet ones there, to decrease gas costs
- will get the mainnet SA factory whitelisted soon after we wrap up testing - which means SA will be deployed on OE very soon

### Plans for SA L2 deployments
- work on cleaning up unused ones, and target specific project treasuries on each of these L2’s

## CURRENT PRODUCTS

### general FRONTEND UPDATES
- repo cleanup and code refactoring, modify the FE to be dynamic in its configs, for easier L2 deployment and config updates
- mobile connectivity and UI - proper mobile version design done, to be implemented - mobile users will be able to use the app from their devices

### community proposal

SY (DEPLOYED)
- Added links on the token names in transactions tables and portfolios in both SY and SA
- Added BE support for the 30d avg APY, and added it below the originator rates on the SY homepage!
- jToken conversion rates column has now been replaced by 2 new columns (only when connected with a wallet) - Junior Positions Balance and Senior Positions balance - by aggregating the balances you have in your portfolio
- Renamed Junior APY & Senior APY columns to Junior (Variable) / 30d avg APY & Senior (Fixed) APY
- Within Smart Yield replace “Originator APY” with the direct market name. Ex. “Compound APY”
- Change SY pool rows to same design as SA pool rows (clickable, with the arrow button at the right)

SA (TBD, implemented and currently in testing)
- Show underlying dollar price for juniors on the pool card where the leverage drops - users will be able to visually compare the current price of the SA pool’s underlying asset - and the price point after which downside leverage resets to 1
- Smart Alpha pool list should display the estimated upcoming epoch details and not the current pool - there will be a toggle allowing users to switch from current epoch numbers to futute epoch estimates based on entry and exit queues

plans for SA UI
- turn this from a SA explorer into a proper SA tool - SA is now built to match the structure of the smart contracts - which means it’s rigid, and appeal less to the average user
- it will appeal to the UX, and show more figures relevant to user portfolio performance - like APRs
- change the simulator to include better scenario management - to allow people to model specific scenarios to a more granular degree - essentially backtesting where they can see how their positions would have performed at different entry points in different epochs based on recorded data
- change the portfolio to be more similar to a portfolio management app, where users see how their positions performed
- this is part of the v2 of the design system - which will result in a complete overhaul of the entire app, not just SA

plans for SA treasury
- experiment with a separate SA for proj treasuries page - where projects can leverage SA by entering on the senior side, and communities on the junior side. This way, the project will be there for its users to collateralize their leverages, and the community will be there for the project to cover the treasury for potential price downsides

## NEW PRODUCTS


### new product 1
- overwhelmingly good feedback (details soon, a version of the spec that doesn’t leak to much alpha)
- spec is finalized - which is by far the most time consuming step in the dev process
- looking to book audits

### SY2

- addresses all of the painpoints we had before
    - senior and junior ERC20
    - seniors can exit before maturity
    - less gas intensive
    - better yield oracle
    - applicable to more than just lending protocols
- spec is final
- smart contract work started
- looking to book audits

### Timelines
- product 1: Q2
- SY v2: soon after product, in Q2 

##FEEDBACK


### 4RC, Dragonfly, Parafi
- feedback is overwhelmingly positive for the first product, they are very interested in long term fixed rate products, to a degree that exceeds our expectations
- same response for SY v2, as everyone agrees that it seems to be addressing all of the painpoints from v1
- We will continue to hold these feedback sessions on a more regular basis going forward & will look to talk to additional funds as well

# Operations


### Christian
- Business development
    - continued outreach to funds & other key partners to garner interest in current & forthcoming products; more to come soon
- Layer 2 planning
    - continued partnership outreach as we look to narrow our focus on one or two Layer 2's
### Pavlo
- Cream donations distribution (completed)
- UMA KPI Options post-note (completed)
- Olympus Pro bonding program progress
    - at the moment, 95% of LP shares have been purchased, now as a DAO, we have been able to obtain around $280k of LP shares
    - There have been some discussions in discord around what options we have to extend the program; we will continue to engage the community on this
- EntropyFi $BOND game
    - They announced they are going to launch a game for BOND holders -
    - they will snapshot bond holders & open up access to their game
- Outstanding Forum proposals for adding new Smart Alpha Pools
    - Looking to work on these as a part of the smart alpha revamp program; also looking at improving process to make pools more straightforward & an easier
    - for any smart alpha pool, we need 1) reliable chainlink oracle & 2) deep liquidity

### Tyler


- Ongoing cadence of AMA’s & communication
    - Will hold an AMA at 6 pm ET tonight (12/9) to address questions posed in discord & other topics that come up
    - Tyler will start doing more frequent AMAs (weekly, biweekly, TBC) now that Max is working full time on FIAT; we can figure out the exact cadence during our AMA today
- Smart Alpha Pool Deployments
    - We’re working through how to ensure Smart Alpha pools are cost effective. Each rebalance for pools deployed on Main-net is quite expensive, depending on gas fees. We are considering which Layer 2 we should focus on to 1) reduce the cost of each rebalance & 2) avoid fragmenting liquidity across to many layer 2’s
    - We want community feedback on this
    - We will likely keep the large pools (WETH, WTBC) on main-net & look to move smaller pools to a Layer 2



