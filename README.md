# Specie whitepaper

           Specie, An Impermanent Loss Solution Framework					    Speciecoin@protonmail.com

Alpha V1 ; Abstract 

Current Liquidity Pools determine the balance of the pools value based on predetermined algorithms. These predetermined algorithms however have become notorious for causing “Impermanent Loss”.
o	“a 1.25x price change results in a 0.6% loss relative to HODL”
o	“a 1.50x price change results in a 2.0% loss relative to HODL”
o	“a 1.75x price change results in a 3.8% loss relative to HODL”
o	“a 2x price change results in a 5.7% loss relative to HODL”
o	“a 3x price change results in a 13.4% loss relative to HODL”
o	“a 4x price change results in a 20.0% loss relative to HODL”
o	“a 5x price change results in a 25.5% loss relative to HODL”
•	“N.B. The loss is the same whichever direction the price change occurs in (i.e. a doubling in price results in the same loss as a halving).” - https://uniswap.org/docs/v2/advanced-topics/understanding-returns/  (Uniswap, 2020)

Uniswap, the leader of Liquidity Providing on Ethereum’s decentralized exchange ecosystem, was the eye grabbing start of issue notice for this problem. Specie aims to prevent centralized impermanent loss, by applying decentralization of the logic to AMM methods.

Content Structure 

1.	Current Liquidity Pool’s Logic Problem
2.	Interconnected
3.	Automated User Logic
4.	Liquidity Pool’s Asset Management Pods 











1.	Current Liquidity Pool’s Logic Problem 
Right now, liquidity pools are isolated and use few logic commands to speak to each other. “Swap Asset, Send Asset, Provide Asset Liquidity, Remove Asset Liquidity”. These functions have done their diligence for becoming the secure standard for interfacing with liquidity pools on Decentralized Exchanges. This limited logic can cause reliance on centralized infrastructure or result in high gas fees for an implementation of complex on-chain logic usage of the DEX. 


![image](https://user-images.githubusercontent.com/69151655/116327466-6fed1300-a78c-11eb-8342-bf6a057fbac2.png)

                       Current Liquidity Pools Smart Contract Logic







2.	Interconnected 
     Implementing Interconnected Liquidity Pools will allow dynamic logic use cases across the DEX market. As pools become interconnected liquidity can rapidly and cheaply move into different assets. Moving liquidity between a vast amount of assets across a wide range of connections can allow more arbitrage across protocols. 

![image](https://user-images.githubusercontent.com/69151655/116327654-e4c04d00-a78c-11eb-94f6-45ea08900b7f.png)


	                 Interconnected Liquidity Pool Logic


3.	Automated User Logic
    Users can set preferences for automated market making positions within smart contracts with interconnected LPs (iLPs). Allowing more control of the automated market making and more control of impermanent loss. As assets appreciate, they can be balanced in a way that accrues in value instead of lessening. Users can make certain AMM preferences for smart contracts to act at certain times. An example would be an RSI threshold id applied by the user to each asset in the iLPs. Such that when certain assets cross an RSI threshold it begins rebalancing.  Rebalances can be automated based on a system of preset User Logic conditions over any set time interval. 
			                       
                             
![image](https://user-images.githubusercontent.com/69151655/116327668-f0137880-a78c-11eb-907f-d6ac8e5d1e76.png)
                             
                             
                            iLPs User preference AMM logic


4.	Liquidity Pool’s Asset Management Pods
Users will now have the ability to govern an automated ecosystem of assets based on their own intuition of the market. This introduces a new concept of Asset Management pods that allow arbitrage strategies. Liquidity Pools benefit from being in on-chain Asset Management pods because it reduce losses even in assets that decrease in value. An example would be in AMPs that move value around in between low correlated and high correlated AMPs. If you know AMP A will go down in value every time AMP B goes up in value. The experienced user can train his Automated Logic Algorithms to adjust to selling and buying pressure in the overall market now. 
			Asset Management Pods with Interconnected User AMM Logic Liquidity Pools


![image](https://user-images.githubusercontent.com/69151655/116327732-0cafb080-a78d-11eb-93f4-e2ceadc2280d.png)


		Asset Management Pods with Interconnected User AMM Logic Liquidity Pools

