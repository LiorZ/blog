+++
date = '2025-04-22T10:23:24+03:00'
draft = false
title = 'Is SaaS a good business model for drug‑discovery companies?'
+++

# **Is SaaS a good business model for drug‑discovery companies?**

In 2024 the Nobel Prize in Chemistry went to **David Baker**, **Demis Hassabis**, and **John Jumper** for their groundbreaking advances in **computational protein design** and **protein‑structure prediction**. Their achievements—most famously the AlphaFold2 model—have sparked a wave of enthusiasm for applying “foundation models” to biology.

Proteins are the cell’s workhorses. They relay signals, catalyze reactions, and give each organism its unique identity. Because most drugs succeed or fail by modulating specific proteins, the ability to predict a protein’s three‑dimensional shape is enormously valuable. AlphaFold2 proved that deep learning can deliver this insight at scale, and the race to build ever‑larger “protein foundation models” began.

**EvolutionaryScale** grew out of Meta AI’s ESM project, while **Profluent** emerged from Salesforce researchers who created the ProGen series—both companies promising ever‑more‑powerful generative models for protein science. Their founders are brilliant, and their technology is impressive. Yet I argue that **licensing these models to pharma as a pure SaaS platform is a weak business model**. Here’s why.

## **Where does value accrue?**

Platform startups typically try to sell access to their AI engine: annual subscriptions plus the promise of future royalties for any drug that emerges. On paper this looks “asset‑light” and scalable; in practice pharmaceutical buyers hesitate because the platform does not attack their biggest pain point.

Drug R\&D is divided by the infamous **“Valley of Death.”**

* **Basic science**—where foundation models excel—generates promising molecules.  
* **Big Pharma** must shepherd those molecules through IND‑enabling studies, clinical trials, and regulatory hurdles.

Model builders speak the language of sequences, structures, and binding energies; drug developers speak a different language. They care about ADME – Absorption, Distribution, Metabolism, and Excretion: how the body handles a compound, PK/PD – Pharmacokinetics / Pharmacodynamics: how drug concentrations change over time (PK) and the biological response those concentrations trigger (PD). CMC – Chemistry, Manufacturing, and Controls: the regulator‑mandated documentation proving you can make a consistent, safe product at scale and more. Bridging that gap is hard. No current foundation model can reliably predict how a novel molecule will behave in the messy, chaotic reality of a human body—let alone how regulators and payers will judge it.

Take Merck’s *verubecestat* (MK‑8931) as an example (although there are many, many more): this β‑secretase (BACE‑1) inhibitor was celebrated as a textbook case of “model‑driven” drug design and delivered good [results](https://pubmed.ncbi.nlm.nih.gov/27807285/) in animal studies—yet it [crashed](https://www.bmj.com/content/356/bmj.j845) spectacularly in Phase III clinical trials. 

Setbacks like verubecestat drive home a hard lesson: great in‑silico predictions—and even flawless animal data—mean little unless they translate into human benefit. That reality has pushed AI‑first start‑ups such as Recursion and Insitro to pivot toward owning the molecules themselves. By advancing their own drugs into the clinic, they control more of the value chain and can prove their technology works, instead of waiting for partners to do it.

On a different front, open‑source models advance at lightning speed. Within weeks of Isomorphic Labs releasing AlphaFold3, researchers [replicated](https://github.com/jwohlwend/boltz) it under a permissive license on GitHub. Competing against a free alternative—especially when the scientific community continually improves it—erodes the pricing power of a SaaS license.

In short, pharma is less worried about the **cost of molecule discovery** than about the **probability of clinical success**. A SaaS fee for an upstream tool does little to de‑risk the billions spent downstream. Until AI platforms can directly shift the success rate in late‑stage development, selling access alone will remain an uphill battle.
