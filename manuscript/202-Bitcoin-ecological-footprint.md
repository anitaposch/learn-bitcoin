### Bitcoin's ecological footprint
_Bitcoin consumes a lot of electricity, which will increase our climate crisis and is irresponsible._

![Newsweek article from 2017](resources/_Newsweek-2020-energy.png)

Above screenshot is an article from Newsweek right in the middle of the 2017-2018 bull run. It is based on the work of Alex de Vries (Digiconomist), a former data analyst for the Dutch Central Bank. Many research papers and mainstream media articles are based on his false assumptions like comparing Bitcoin transactions' energy consumption to VISA payments and calculating a carbon footprint from it. I argue a lot of this work is done to spread false claims to demonize Bitcoin. 

> "Every time we have a rally in Bitcoin we see all of this negative attention to the environmental impact of Bitcoin. Apparently it only matters when the price is high." - **Andreas M. Antonopoulos**

Let's dive into this. Bitcoin critics often mention that Bitcoin consumes more energy than the benefits it creates. It's undeniable that Bitcoin mining requires lots of electricity. It is estimated that between 80 and 118 TWh per year are used globally for mining which is the equivalent to the entire power consumption of countries like the Netherlands. 

![Country ranking, March 2021](resources/_electricity-consumption-btc.png)
[Source, March 2021](https://cbeci.org/cbeci/comparisons/)

The world wastes a lot of electricity. The amount of electricity consumed every year by always-on but inactive home devices in the USA alone could power the Bitcoin network for 1.9 years. [^^C2-4]

At the same time, two-thirds of all energy produced in the USA is lost. It's reasonable to assume that this is happening in all other parts of the world too. 

![Estimated US Energy Consumption in 2017 - Rejected Energy](resources/_Energy_US_2020.png)
[Source](https://flowcharts.llnl.gov/)

Notice that rejected energy accounts for around 62% of all electricity generation. Rejected energy is energy that is produced but ultimately does not go to useful work. To make matters worse, this number has been increasing on a relative basis over time. In 1970 Lawrence Livermore National Laboratory found our proportion of rejected energy was around 48%. [^^C2-7]

To put it in another perspective Bitcoin accounts for 0.54% of all electricity used globally. 
![The world's total electricity production, consumption and Bitcoin's share, March 2021](resources/_electricity-world-btc.png) [^^C2-8]

**Electricity consumption easy to quantify**
Bitcoin's transparency allows estimations of its energy demand quite in contrast to many other industries, where these data points are more obscure. Measured by electricity costs alone, we can assume that Bitcoin is [much more efficient](https://medium.com/@danhedl/pow-is-efficient-aa3d442754d3) than traditional banking and gold mining on a global scale.

Bitcoin mining’s estimated dollar cost per Gigajoule expended is 40 times more efficient than that of traditional banking and 10 times more efficient than that of gold mining.

![Comparing energy expenditure across monetary and banking systems](resources/_energy-efficiency-ARK.png)
[Source](https://ark-invest.com/articles/analyst-research/bitcoin-myths/)

**Why does Bitcoin need this amount of electricity?**
The Proof-of-Work mining mechanism is a fundamental feature which secures the independence, neutrality and automated integrity of the network. It's state of the art and the most secure way to prevent attacks on assets worth $ 1 trillion USD locked in the network. (BTC marketcap, April 2021)

Bitcoin can settle transactions without intermediaries because specialized, dedicated hardware proves transparently that the computer has executed a costly computation.

Proof-of-Work is anchoring the digital money in the real world. As Chaincode Labs resident Hugo Nguyen explains, "Under the hood, proof-of-work mining converts kinetic energy (electricity) into a ledger block. By attaching energy to a block, one gives it ‘form’, allowing it to have real weight and consequences in the physical world." [^^C2-3]

Proof-of-Work is also the only mechanism that allows an equally distributed, decentralized creation of coin supply, whereas other methods require initial token drops and token generation events that allow centralized actors to take advantage of pre-mined coins (Proof-of-Stake).


**Carbon emissions**
Some research has tried to assess the carbon emission flows and sustainability of Bitcoin through estimating future demand on the basis of false assumptions. One paper for instance is claiming that: "the annual energy consumption of the Bitcoin blockchain in China is expected to peak in 2024 at 296.59 Twh and generate 130.50 million metric tons of carbon emission correspondingly." [^^C2-5]

> "It’s an immediate red flag that the authors confidently declare Bitcoin’s future carbon outlay to two decimal places, when realistically the number can only be estimated to within an order of magnitude.", states **Nic Carter**. [^^C2-9]

Based on the "Cost & Sustainability of Bitcoin" report by Hass McCook (August 2018), the Bitcoin network exhales 63 million tonnes of CO2 per year - about 0,12% of global greenhouse gas emissions. Of the 160,000 TWh of energy generated globally each year, the Bitcoin Network chews through about 105 TWh/year (0.0661%). (It should be noted that all figures include the impact of the manufacture of ASIC mining equipment, which represents over 50% of all Bitcoin-related emissions generated.) 

**Assumption #1: It takes X kilowatts to do a single transaction**
This is faulty mathematics. The use of energy for bitcoin does not scale to the number of transactions. The number of transactions that happen on-chain and the number of transactions that happen off-chain - for instance, on second layer technologies like the Lightning Network or through custodial exchanges, that batch transactions - are not correlated at all to the cost of mining. Mining is driven to 80-90% by bitcoin's price and 10-20% by fees. The higher the possible profit for miners, the more miners are setting up new mining facilities and when the price crashes some have to stop their machines. In the long term, when all 21 million bitcoin have been mined, the transaction fees will drive mining. At that point, transactions intensity will be more correlated to energy usage. But not today, the last bitcoin will be mined in 2140. Mining is driven by competition in a free market where mining difficulty adjusts dynamically. It has nothing to do with how many transactions are being processed. Mining is a mechanism for security. It relates to how much security the market allocates to the system, so more energy equals more security and when the price of bitcoin goes up the amount of money allocated to protect it also increases naturally. Therefore usage and higher adoption drives additional financial motivation for miners to produce more security by consuming more energy. 

**Assumption 2: Linear extrapolation**
The second wrong assumption is to extrapolate linearly and say, if it takes X kilowatts of energy to do one transaction today and we have seven and a half billion people on the planet who will want to do one transaction per day each then bitcoin's energy consumption in the future will be Y. This is false. Bitcoin can't scale linearly in terms of transactions because of block size constraints on the base layer. To mitigate that, second layer protocols are developed like the Lightning Network or Liquid, which allow thousands of payments without the need for extra energy. The efficiency of mining equipment is rising. Miners need less power for the same amount of computing performance over time. Additionally, Bitcoin developers are improving the code, minimizing the data size of transactions so that more transactions can be mined in one block.

**Assumption 3: Comparing VISA to Bitcoin**
A Bitcoin on-chain transaction can not be compared with a VISA payment. It is not the same. In traditional banking there are various layers of settlement, meaning they differ in their level of security and finalization. Let's take the example of the US system, which is comparable globally. The baselayer are Fedwire, CHIPS and SWIFT networks, while debit card and credit card payments operate one or two levels above with many intermediaries. The baselayer of Bitcoin has to be compared with Fedwire, CHIPS and SWIFT. Layer 2 solutions like fast, micro payments on the Lightning Network can be compared with VISA. 

![False comparison between a bitcoin transaction and VISA](resources/_VISA-BTC-comparison.png) [Source](https://www.statista.com/statistics/881541/bitcoin-energy-consumption-transaction-comparison-visa/)

Let's take a look at the average transaction volume. 

![Average value of a single credit card transaction worldwide in 2012, USD](resources/_average-VISA-transaction.png) 
[Source](https://www.statista.com/statistics/279308/average-credit-card-transaction-value-worldwide/)

![Average value of a single Bitcoin transaction](resources/_average-transaction-value-bitcoin.png) [Source](https://bitinfocharts.com/comparison/bitcoin-transactionvalue.html#1y)

The average bitcoin transaction value was 258,766 USD on April 21st, 2021. While the average VISA transaction was 91 USD in 2012. Bitcoin transactions transport magnitudes more value than credit card payments. Assuming Bitcoin will gain traction then it might one day settle millions of dollars worth like the Fedwire system at very low fees compared to the banking system. 

Average transaction value per Fedwire transfer was 4,5 million USD in February, 2021. [Source](https://frbservices.org/resources/financial-services/wires/volume-value-stats/monthly-stats.html)

![Settlement of banking versus Bitcoin](resources/_settlement-compared.png)

Bitcoin transactions are settled every 10 minutes constantly, 24 hours per day, 365 days per year - all while ACH transactions can take up to two years until they are finally settled. [^^C2-12] Not to forget: Bitcoin and Lightning transactions are trustless while the traditional payment system only works because intermediaries take care of fraud and charge backs.

**Assumption 4: Equating energy consumption with pollution**
People say for example "every transaction pollutes" or "bitcoin's pollution is increasing" or "bitcoin produces pollution as a result of its energy consumption" - that's simply not true. There is no direct correlation between energy usage and pollution because it depends entirely on what type of energy is used. If you're producing energy with coal, yes that causes pollution and environmental impact. If you're producing energy with hydroelectric dams or wind or solar for example then you're not actually polluting. In fact what you're doing is you're subsidizing those energy mechanisms and the creation of more solar, wind, geothermal, off-gassing and other forms of energy through the application of bitcoin as an economic factor in the production of that energy. 

Bitcoin miners are profit driven, they will always look for the cheapest energy, which is renewable. Coal and oil will always be more expensive than hydro power, stranded gas, wind and solar. Not to forget nuclear, which is also an option that many praise as green energy. As a European who can vividly remember the Chernobyl accident in 1986, where we had to stay inside our houses, it is not my preferred option.

Indisputably, Bitcoin miners are using otherwise wasted energy. I spoke with [Sébastien Gouspillou](https://bitcoinundco.com/en/sebastien-gouspillou/) and [Philippe Bekhazi](https://bitcoinundco.com/en/philippe-bekhazi/) two miners using hydro power, confirming above statements.

**Energy mix of electricity production**
Bitcoin miners are fairly well distributed across the globe. While it is easy to quantify the electricity demand, it is more difficult to quantify the electricity sources since the Bitcoin mining industry remains a highly private and pseudonymous industry. Therefore, research estimates about the electricity use in mining from renewable energies vary from 39% (Cambridge Center) to 73% in the CoinShares Mining Whitepaper, which concludes: 

"Using a combination of estimates of global mining locations and regional renewables penetrations we again calculate the Bitcoin mining industry to be heavily renewables-driven. Our current approximate percentage of renewable power generation in the Bitcoin mining energy mix stands at 73%, around four times the global average. Overall, our findings reaffirm our view that Bitcoin mining is acting as a global electricity buyer of last resort and therefore tends to cluster around comparatively under-utilised renewables infrastructure. This could help turn loss making renewables projects profitable and in time — as the industry matures and settles as permanent in the public eye — could act as a driver of new renewables developments in locations that were previously uneconomical." [^^C2-10]

The question is not how much energy is required, but how is this electricity produced? How much CO2 is emitted? If we decide as a society that we don't want polluting energy, then we should regulate the production of energy and not allow the use of polluting systems. This is about regulating energy production and not about regulating the consumption of energy in one particular sector of the economy which happens to be Bitcoin. 

**Final assumption: Bitcoin isn't useful, therefore any use of energy for a bitcoin is wasteful**

If you decide Bitcoin isn't useful, then this is a very subjective opinion. Bitcoin might not make sense to you, but it might make sense for many other people. If you are making this argument, you must agree that there are many other forms of energy use that are prima facie useless or even damaging in their use, and they don't receive the same amount of scrutiny. 

We can light up billions of Christmas lights every year for a display of Christmas spirit, which might be completely pointless for billions of people of other beliefs. The number one use of energy for example in the United States outside of civilian markets is the Department of Defense. The US government uses enormous amounts of energy and is the largest polluter in the country, arguably for no legitimate reason other than seeking extreme control. 

![US military emits more CO2 than many nations](resources/_military-co2.png)
[Source](https://www.statista.com/chart/18359/estimated-military-carbon-dioxide-emissions/)

Which leads back to the chapter about the Petrodollar, the linkage between the US dollar and the OPEC, which makes the USA the globally dominant powerhouse and is secured by US military and wars in the Gulf region. 

Is the war machine a useful thing to have in our society? Before you scream "Whataboutism!" and say that it's comparing two different things, we should reduce the use of the war machine as well as the use of bitcoin, do not forget there's a very important link that is missing. The war machine all around the world is funded directly by debt that is produced and paid off through inflation that is enabled through the uncontrolled central bank printing of money, which in the end you, a tax payer, are fronting the bill for. Bitcoin isn't just a solution for an open economy, it's a solution that constrains government from producing currency at rates and using inflation as a hidden form of taxation to fund the war machine that pollutes and damages more than anything else in existence. Bitcoin isn't simply a substitute for general economic activity, it's also a direct control on the war machine that pollutes and uses far more energy to kill people. So in my opinion those two things are very closely tied. But that's just Andreas M. Antonopoulos' and my opinion.

**Conclusion: The benefits of Bitcoin**
It's uncensorable, incorruptible, and allows billions of people regardless of color, gender, orientation, wealth, and status open access to a global money system. Furthermore, it is our only chance to secure financial privacy in a world of digital surveillance. 

The Bitcoin network secures assets for about 100 million users globally, worth 1 trillion USD (April 2021) without any upper limit and does not rely on military power and currency wars.

Conclusion as put by ARK Invest: "Contrary to consensus thinking, we believe the environmental impact of bitcoin mining is di minimis. Renewables, particularly hydroelectric power, accounts for a large percentage of bitcoin’s energy mix. As Castle Island Ventures partner, Nic Carter, has noted, in their search for the cheapest form of electricity, miners will continue to flock to regions offering a glut of renewable electricity, unlocking stranded energy assets as “electricity buyer's of last resort, creating a highly mobile base-demand for any electricity sources able to produce at prices below current producers, regardless of location.” As a result, from a climate perspective, bitcoin mining could be a net positive." [^^C2-3]