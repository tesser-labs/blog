---
title: In Math we trust. Transitioning from "Code is law" to "Math is Law"
description: The decentralized computing and blockchain space is on the cusp of one of its biggest paradigm shifts, transitioning from "Code is Law" to "Math is Law."
keywords: [ZK, Verifiable Computing, Proof Carrying Data]
slug: ./math_is_law
published: true
author: Hamid Alipour
date: 2024-08-16
hero_image: ../assets/MathIsLaw.png
---

The decentralized computing and blockchain space is on the cusp of one of its biggest paradigm shifts: transitioning from "Code is Law" to "Math is Law." This shift promises to revolutionize the industry by leveraging advancements in technologies like Zero Knowledge Proofs (ZKPs) and Verifiable Computing. These advancements enable the creation of robust mathematical proofs for the correctness of computations and the soundness of their outcomes. This transition opens up a vast domain of possibilities that were not traditionally feasible, bringing a whole new realm of applications and use cases to the blockchain.

"Code is Law" was originally coined by Lawrence Lessig in the early 2000s to highlight the power computer programs give their creators and the profound impact they can have on societal governance. In his book "Code and Other Laws of Cyberspace," Lessig argued that as internet interactions become more dominant in real life, code would effectively govern cyberspace and, by extension, real-world societies. It was not until the introduction of Ethereum in 2014 as the 'World's Computer', and the advent of smart contracts as self-executing agreements with terms directly written into code, that 'Code is Law' gained its literal meaning as a slogan.
The main challenge with 'Code is Law' up until that time was that code execution required trusted runtime environments, making it difficult for code alone to serve as the ultimate arbiter without any guarantees of correct execution. The invention of blockchain technologies like Ethereum made it possible, for the first time, to provide these execution guarantees by having an incentivized set of validators redundantly run computations to reach a consensus on the correctness of the results. This consensus mechanism ensures that program code can be treated as law, as it is guaranteed to execute correctly, making 'Code is Law' a reality.

### The Shift to "Math is Law"

Recent technological advancements have paved the way for a new paradigm in verifying the correct execution of program code. This alternative approach is primarily driven by the development of verifiable computing and cryptographic techniques, such as succinct non-interactive arguments of knowledge (SNARKs) and zero-knowledge proofs (ZKPs). These techniques allow verifiers to check the correctness of computations without redoing them, using shorter and quicker-to-verify proofs based on cryptographic and mathematical principles. This represents a shift from 'Code is Law' to 'Math is Law.'

These verifiable computing techniques have their roots in theoretical computer science, dating back to the 1980s. The concept was introduced by Shafi Goldwasser, Silvio Micali, and Charles Rackoff, who demonstrated the feasibility of proving statements in a zero-knowledge manner. Early work focused on interactive proof systems and probabilistically checkable proofs (PCPs), where a verifier could check the correctness of a computation with high probability by examining only a small portion of the proof. Building on these ideas, SNARKs advanced the field by allowing the creation of succinct proofs that could be efficiently verified. These concepts laid the groundwork for verifiable computing by establishing the theoretical underpinnings for efficient verification processes.

The main characteristic of verifiable computing is that the mathematical primitives and theories underpinning SNARKs and verifiable computing come with strong proofs that can be trusted regardless of the origin, execution environment, or any other external factors. This enables the provision of robust mathematical constraints that, when satisfied, offer easily verifiable guarantees of correct computation. These capabilities can open a range of new possibilities for blockchain applications, including enhanced scalability and improved interoperability between on-chain and off-chain data.

### Real-World Applications

One of the most exciting developments in the verifiable computing space is the emergence of Proof-Carrying Data (PCD) technology. In a PCD-enabled system, any information flowing through a network carries a proof of its correct computation, regardless of its origin. This approach could revolutionize blockchain consensus systems by only relying on consensus for transaction ordering and data availability, allowing computations to be performed off-chain. While the technology is still in its early days, its development is progressing rapidly. This would significantly enhance blockchain scalability, facilitate seamless cross-consensus messaging, and improve light client interactions.
Zero-knowledge proof (ZKP) technology, on the other hand, allows users to selectively reveal information as needed, ensuring that sensitive data remains private while still enabling essential information to be securely moved on-chain.
The combination of verifiable computing, proof-carrying data, and zero-knowledge proofs offers robust security and privacy assurances. It can effectively bridge the gap between off-chain and on-chain workflows by ensuring that correct computations are performed off-chain, and data is revealed on-chain only when necessary. It enables to enhance scalability while maintaining privacy.

This transition from "Code is Law" to "Math is Law" can unlock significant advantages:

1. **Enhanced Scalability**: By moving computations off-chain, blockchain networks can process significantly more transactions per second, alleviating the current scalability bottlenecks.
2. **Improved Interoperability**: PCD enables seamless interaction between on-chain and off-chain data, bridging the gap between blockchain and real-world applications.
3. **Increased Efficiency**: Light clients can operate more efficiently by relying on proofs of correctness rather than executing full computations, making blockchain technology more accessible to a broader range of devices and applications.
4. **Simplified Cross-Consensus Messaging**: Cross-chain interactions and communications can be streamlined, enabling more robust and versatile blockchain ecosystems.

However, this shift also comes with its own challenges, such as the need for widespread understanding and adoption of new cryptographic techniques, the potential complexity of integrating these technologies into existing systems, and the significant computational overhead associated with generating verifiable proofs, which can add multiple orders of magnitude in computational cost. The good news is that many of these challenges are either being actively addressed or are expected to see promising solutions in the coming years, thanks to the rapid progress in the field.

The bottom line is that the transition from "Code is Law" to "Math is Law" marks a significant evolution in the blockchain and decentralized computing space. By leveraging advancements in cryptographic and mathematical techniques, we can create systems that are more secure, transparent, and scalable. As we embark on this journey, the potential for innovation and transformation is immense, promising a future where trust is mathematically guaranteed, the boundaries between different trust domains—whether on-chain or off-chain—are blurred, and Proof-Carrying Data can flow seamlessly across these boundaries, with verifiable computation being performed by private or public actors who have access to the data.
