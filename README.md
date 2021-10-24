# GydeDAO Contracts with Tally and ERC20

This DAO is dedicated to minimizing time poor folks spend in poverty through accurate referrals.

## Inspiration
 
The tldr; When I was going to my favorite coffeeshop, they had a lot of people who would come in and request free food, which was normal. I would buy folks food and sit and talk with them about their lives and generally get to know them. I quickly realized that there was no way to google or find reliable, actionable information as a member of the general public about how to level up and spend less time in poverty. It seemed there were no incentives to accelerate individuals up and out. So, I started thinking why not build the platform cooperative for poor people to interact with and be heard; it would save time and help the community of people who find themselves stuck in situations that could be temporary. People were asked to go to places they had never been before and trust them with their lives, which were often exploited by intrusive questions about their private lives. This was the currency through which they accessed services. 

## What it does

Helps connect those who need help with reliable, trustworthy solutions, starting in Baltimore City, including reviews of free and low-cost services, intuitive search, and more.  

## How we built it

- Used Tally to setup analytics for the GydeDAO
- Used Remix to deploy OpenZeppelin Governor and TimelockController smart contracts for Tally, as well as an ERC20 token for voting on proposals. 
- Used my iPad app, Notability and Invision to create an interactive low fi/medium-fi prototype,
- Used React to create an SPA and wrote copy for the landing page. 
- Used DAOHaus to launch a MolochDAO on Rinkeby called "GydeDAO". 
- Used Snapshot to setup an off-chain voting process with quadratic voting for gydedao.eth. 
- Used batchgeo.com to create the mapping prototype/store locator demo

## Challenges we ran into

- NFT gated links didn't work with mintgate.io. 
- Figuring out how Tally worked with the OpenZeppelin Governor contracts. 

## Accomplishments that we're proud of

- Improving the quality of information available and the user experience of the application. Simple one click solution with actionable information. 

## What we learned

- How to use Tally. 
- How to qualify fields of data for BatchGeo.com. 
- How to deploy your own NFT on Mintgate.io and token-gate content. 
- How to deploy and use a Governor contract to hook up to Tally. 
- How to create a space on Snapshot to do off-chain quadratic voting for token holders of the ERC20 that I made for the DAO ($GYDE) on rinkeby. 
- That snapshot does not allow testnet ENS domains for creating spaces. That Tally does not provide native support for NFT-gating communities. 

## What's next for Gyde

See the living product roadmap: gyde.community. 

### ETHLisbon: Low-fi web app prototyping; SPA, DAO, and ERC20 launch, then...

### User research, Low-Fi prototyping iteration, then...

###  High-Fidelity UX/UI Sprints and Brand Palette, then ...

###  Building App with Engineering Sprints, then...

### Building App, then...

### Launch 1.0
