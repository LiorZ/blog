+++
date = '2025-02-27T10:55:31+02:00'
draft = true
title = 'Moneyball Moment for Bioproduction'
+++

# **Moneyball Moment for Bioproduction**

In 2003, Michael Lewis’s bestselling book *Moneyball* introduced a provocative idea to the world of baseball: data analytics could be used to identify undervalued players with the potential to deliver outsized performance. Suddenly, hidden gems were everywhere, waiting to be discovered by teams that knew how to read the stats. Two decades later, we find ourselves in a parallel revolution \- but this time, it’s within the realm of biotechnology and enzyme production. Modern computational biology tools, especially around enzyme design, are ushering in a new era in bioproduction: a *Moneyball moment* where careful data analysis and computational design are revealing opportunities for transformational leaps in profitability and sustainability.

In this post, I’ll explore how computational enzyme design \- both the stabilization of natural enzymes and the creation of completely novel ones \- opens a vast new horizon in biomanufacturing. This technology, used in conjunction with careful market analytics, can pinpoint “hidden gem” products: those small-market, high-cost items that, once the cost barrier is removed, can scale dramatically and tap into huge untapped demand.

## **Setting the Stage: Baseball, Biotech, and Data**

In the original *Moneyball* story, the Oakland A’s used data analytics to identify overlooked players whose skills \- obscured by unconventional statistics \- were priced significantly below their real value. By leveraging these insights, the team competed at a high level while spending far less than many of their rivals. The parallels to biotechnology might not seem obvious at first, but if we look closely at the dynamics of enzyme-based bioproduction, the similarities become clear.

Traditional methods of enzyme discovery and optimization have often been *ad hoc*, relying on trial-and-error experimentation, or focusing exclusively on well-known enzyme families. Now, thanks to advances in computational protein structure prediction and design, as well as machine learning, we can systematically scan a vast universe of possible enzymes (both natural and novel). Using these new tools, we can identify enzyme catalysts that have the highest potential to unlock profitable manufacturing processes.

Just as *Moneyball* used data to root out inefficiencies in the baseball recruiting marketplace, enzyme design is poised to uncover hidden opportunities in the bioproduction space. By using data on reaction thermodynamics, kinetics, protein stability, substrate specificity, market demand, and cost factors, we can determine which processes have the greatest potential for disruptive cost reduction. Let’s explore how.

## **The Power of Computational Enzyme Design**

### Stabilizing Natural Enzymes

One of the first transformative impacts of computational enzyme design lies in enhancing existing natural enzymes. Stabilizing a natural enzyme so that it can function efficiently at industrial conditions \- such as high temperatures, extreme pH, or in the presence of organic solvents \- can lead to substantial improvements in yield and cost-effectiveness.

Traditional enzyme engineering relied heavily on random mutagenesis: introducing genetic mutations randomly and testing thousands or even millions of variants in search of improvements. While this evolutionary approach has yielded many success stories over the decades, it remains a time-consuming and expensive process.

Computational protein design uses algorithms to predict how changes in amino acid residues affect enzyme structure and function. Algorithms like [ProteinMPNN](https://www.science.org/doi/10.1126/science.add2187) have been demonstrating [time](https://www.nature.com/articles/s41586-024-07601-y) and [again](https://pubs.acs.org/doi/10.1021/jacs.3c10941) how the boundaries presented by natural proteins can be pushed to their limits.

As a result, natural enzymes that previously lost activity fairly rapidly in challenging industrial conditions can be systematically re-engineered to remain stable and effective, lowering production costs and expanding the range of viable processes. In many cases, this might involve only a handful of specific mutations \- well-chosen based on computational models \- rather than an entire library of random variants. Last year we published a [paper](https://www.pnas.org/doi/abs/10.1073/pnas.2313809121) in PNAS showing how to do exactly that \- not only mutating individual positions, but also replacing whole segments of the protein to create a much more stable variant.

### Designing Novel Enzymes

Perhaps even more revolutionary is the potential to create *completely novel enzymes* that do not exist in nature at all. Nature’s repertoire, while astonishing, is bound by the constraints of evolution \- enzymes evolve to fulfill specific functions in particular organisms. Yet in industrial processes, we often need new catalytic abilities that nature did not (or could not) evolve for.

With computational design, we can *in silico* explore the enormous space of possible protein sequences, focusing on those that could catalyze desired reactions with high specificity and efficiency. Labs around the world, primarily the Baker lab from the University of Washington are pushing the boundaries of what’s possible. Only recently, the team published a [paper](https://www.science.org/doi/10.1126/science.adu2454?adobe_mc=MCMID%3D08559740651216295533130373546916921985%7CMCORGID%3D242B6472541199F70A4C98A6%2540AdobeOrg%7CTS%3D1739423946&utm_source=substack&utm_medium=email), discussing a deep neural network guided design of a serine hydrolase completely from scratch. This is a unique example, since unlike previous de-novo design enzymes, this study showed that even complex reaction dynamics, in which the protein adopts multiple conformations, can be encoded in a designed protein.

This revolution expands our toolbox far beyond the boundaries set by nature, letting us access chemistries and reaction pathways that could significantly reduce costs and allow the production of new, valuable compounds that were previously too expensive or difficult to make at scale.

## **The Commodity Challenge: Margins and Economies of Scale**

While enzyme design seems poised to reinvent manufacturing, it’s important to note that *not every process is ripe for disruption*. The viability of an enzymatic process is highly dependent on the market economics of the target product.

**Commodity products** \- large-volume industrial chemicals or materials like ethanol, methanol, or fuels \- usually compete on razor-thin margins. Even if you were to design an enzyme that makes the production process more efficient, the benefits might be limited if enzyme production itself remains expensive. Because commodity markets operate at huge volumes and require massive economies of scale to be profitable, any increase in cost \- even at a fraction of a cent per unit \- can be devastating. For an enzyme-based solution to succeed here, the cost of enzyme production must be minuscule, often not feasible until enzyme production technologies (like large-scale fermentation) are themselves extremely optimized and cheaper.

This is reminiscent of traditional scouting in baseball chasing “home run hitters.” It’s a big splash, but it may not always lead to success if the cost to procure these “heavy hitters” is too high. In other words, **if you chase the biggest, most obvious targets (giant commodity markets), you’ll be facing the toughest margins, and the cost barrier for enzyme production can significantly undercut the potential benefits.**

## **The High-Margin Challenge: Are Small Markets Lucrative Enough?**

On the other end of the market spectrum, we find **specialty chemicals** and **high-margin products** \- pharmaceuticals, fine chemicals, flavors, fragrances, and advanced materials. Here, the markets might appear small in terms of volume, but the margins are significantly higher. A single kilogram of a specialty pharmaceutical intermediate, for example, can be worth orders of magnitude more than a kilogram of a commodity chemical. 

Those products however, tend to be biochemically complex, which means that their production requires many biochemical steps (which are catalyzed by enzymes), making their development long and costly. Terpenes for example are a class of molecules that are extremely prevalent in many markets \- from fragrances to biopesticides. Those compounds are usually sourced from plants, where they can be found in trace amounts. A synthetic production method can be extremely lucrative from an environmental perspective too, since the production of many plants (e.g. lavender plants) for the sole purpose of obtaining those molecules requires many acres of arable land and water. The market for individual molecules however is not huge. For example, the market size for linalool \- one of the key molecules obtained from lavender \- is only a [few hundreds of millions of dollars](https://www.alliedmarketresearch.com/press-release/linalool-market.html). Those markets aren’t small for established companies to pursue, but startups usually seek to disrupt multi-billion dollar markets. Therefore, investing time and effort to craft a synthetic enzymatic production method for linalool may not have the best ROI.

Another example is nootkatone \- a compound obtained from grapefruits which is used as an artificial flavor in many products. Around 400 tonnes of grapefruits are [needed](https://www.ox.ac.uk/research/research-impact/turning-orange-grapefruit) to produce just one kilogram of nootkatone, limiting its availability and significantly increasing its price (it is [considered](https://www.ox.ac.uk/research/research-impact/turning-orange-grapefruit) one of the most expensive flavour ingredients in the world). Its market size is valued in the tens to a few hundreds of millions USD according to [some](https://www.reportprime.com/nootkatone-cas-4674-50-4-r823) [estimates](https://www.sphericalinsights.com/reports/nootkatone-market#:~:text=Free%20Sample%20PDF-,The%20Global%20Nootkatone%20Market%20size%20was%20estimated%20at%20USD%20110,10.55%25%20from%202023%20to%202033.), however, in 2020, the US EPA registered nootkatone for use as an insecticide and insect repellent. The market for biopesticides is a significantly growing market, with 15.2% CAGR, expected to reach $15.66 billion by 2029 , according to some [estimates](https://www.marketsandmarkets.com/Market-Reports/biopesticides-267.html). This is an indication that Nootkatone might have much greater revenue potential, it might be a “hidden gem”, since its market might increase if the price will be significantly lower, capturing some portion of the already big and rapidly expanding bio-pesticide market.

Startups have already identified this opportunity. Oxford Biotrans, a spinout from the lab of Luet Wong from Oxford which uses one enzyme to convert valencene to nootkatone and Evolva Bio which produces this compound through fermentation are both such examples.

## **Identifying the “Hidden Gems”**

Beyond simply stabilizing existing processes in high-margin markets, the most lucrative category of opportunities that truly encapsulates the “Moneyball moment” for bioproduction is the one of the **hidden gems**.

A hidden gem is a product or process that appears to have a limited market, but in reality, that limitation is a direct result of its high cost. In other words, the reason we consider the market “small” is that there has never been a cost-competitive way to produce the product at scale. If a novel enzyme (or a significantly improved natural enzyme) could reduce the cost of production by several orders of magnitude, the price could drop enough to unleash a massive, *previously unserved* demand.

### The Price-Demand Cascade

Economists often point to the concept of *price elasticity of demand*, which suggests that as the price of a product decreases, demand increases \- sometimes exponentially, depending on how integral that product is to downstream applications. Think about how digital technologies drastically lowered the cost of communication, leading to an explosion in global internet usage and entirely new business models. 

In biomanufacturing, hidden gems follow a similar pattern. A product that is too expensive for broad consumer use may be relegated to niche applications or limited to small-scale use by research laboratories. However, if an enzyme could be designed that drastically reduces the production costs, demand might balloon across multiple industries. More consumers can afford it, new applications arise, and a virtuous cycle emerges.

### From Niche to Mainstream

Once the improved enzyme-based process scales, that formerly niche product gains mainstream acceptance. This transition yields a magnified economic opportunity for the producer. This is where the *Moneyball* parallel is strongest: you’re not just looking for a single advantage in a crowded marketplace. Instead, you’re identifying that special “player” with unique traits (the enzyme) that can radically alter the entire dynamic of the game (the market).

It takes a combination of careful market research \- understanding cost drivers, supply chain constraints, potential use cases, and the elasticity of demand alongside deep understanding of the capabilities of computational protein design and biochemistry. The synergy of these two leads to rational investment decisions and innovation in product lines that might otherwise remain overlooked.

## **The Role of AI**

### AI in Enzyme Design

The rise of machine learning tools, combined with increasingly accessible genomic and proteomic data, together with the gigantic protein dataset predicted by Alphafold and donated by DeepMind has created a data-rich environment for enzyme design. With hundreds of millions of  structures now publicly available, computational protein design algorithms are now more than ever, demonstrating their capabilities in increasingly difficult design tasks. 

### Cost-Benefit Analysis and Market Insights

On the business side, clever analytics guided by LLMs and Retrival-Augmented-Generation (RAG) databases can be leveraged to run models that compare current manufacturing costs to potential enzyme-based improvements. *Scenario planning* can show how dropping the price of a product by 10%, 50%, or 90% might open up new markets. This is especially crucial for discovering those hidden gems: If you do not model how market demand could shift with a new price point, you might never realize the potential for a “niche” product to become a massive revenue driver.

By combining computational enzyme design with robust techno-economic analysis, companies can build a sophisticated pipeline for discovering and prioritizing opportunities for enzyme-driven disruption. This process is reminiscent of how baseball teams combine on-base percentage, slugging percentage, and other advanced statistics to rank player value.

---

## **Charting the Path Forward**

### 1\. Collaborate Across Disciplines

Breakthroughs in enzyme engineering rarely happen in isolation. Effective projects require collaborations among protein chemists, data scientists, process engineers, and market analysts. This cross-functional approach ensures that promising enzyme designs don’t languish in the lab but get integrated quickly into manufacturing pipelines that can scale and prove their commercial viability.

### 2\. Start with the Right Targets

A frequent mistake is to start by aiming for the biggest commodity markets, imagining that if you can capture even a fraction of those immense markets, you’ll win big. As we’ve discussed, commodity markets are tough because of narrow margins. Instead, a strategic approach is to identify those with potential elasticity where designed enzymes can deliver a step change in efficiency or open up new demand segments.

### 3\. Perform Rigorous Market Discovery

Spotting hidden gems requires a solid understanding of the cost structure and the elasticity of demand for specific products. Companies should invest in **market discovery** strategies: interviews with potential customers, focus groups, and scenario modeling. In some cases, a product’s demand is pinned down not just by cost, but also by regulatory, environmental, or consumer preference factors. That said, cost often remains one of the biggest levers for market expansion.

### 4\. Use Pilot Projects as Proof of Concept

One of the most important aspects of making an internal case for novel enzyme design is piloting. Select a few target molecules or processes that have shown strong computational feasibility and run pilot-scale trials. Demonstrating success at the pilot stage \- both in terms of technical feasibility and cost savings \- builds confidence, attracts investment, and paves the way for full-scale industrial adoption.

## **Some Concluding Remarks**

We are living at a critical juncture in biotechnology. The advanced computational tools that have been refined in fields like AI, data science, and structural biology are converging with powerful enzyme production methods. This convergence is the catalyst for a new era of biomanufacturing \- one that, much like the *Moneyball* revolution in baseball, hinges on data-driven insights to ferret out undervalued or overlooked opportunities.

Whether it’s stabilizing an enzyme so it can survive in harsh industrial conditions or crafting a completely new enzyme from scratch, the potential for cost savings, efficiency gains, and new product avenues is enormous. But it’s not a blanket strategy for all industrial processes \- commodity markets, with razor-thin margins, are harder to disrupt because the cost of enzyme production can be a limiting factor. Instead, the sweet spot often lies in specialty or niche products, where the market is high-margin or artificially capped by expensive and inefficient current production methods.

Within that space, hidden gems abound. These are the products that, on paper, seem like small markets, but whose true potential is concealed by prohibitively high production costs. By deploying modern computational enzyme design and supporting it with strategic market analytics, companies can transform these hidden gems into blockbuster opportunities \- tapping entirely new demand once costs fall and new uses become viable.

That’s the heart of the *Moneyball moment for bioproduction*: using better, smarter data and next-generation computational techniques to spot the unsung heroes of biomanufacturing, betting on them, and reaping the rewards of efficient, scalable, and immensely profitable industrial processes. The game has begun \- now is the time to step up to the plate.

