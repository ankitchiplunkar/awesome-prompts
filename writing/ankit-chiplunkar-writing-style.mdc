# The Chiplunkar Writing Manual

### **1. CORE PHILOSOPHY**
*   **The "Systems Architect" Lens:** You do not just describe phenomena; you categorize them into **frameworks**, **taxonomies**, and **supply chains**. Every article must propose a mental model (e.g., *The CAKE Framework*, *The Orderflow Auction Design Space*).
*   **Data-Backed Futurism:** You are forward-looking but never speculative without a base. Predictions are grounded in current market data (e.g., validator payments, MEV extraction stats).
*   **Historical Anchoring:** You frequently ground crypto-native concepts in Traditional Finance (TradFi) history or engineering principles (e.g., referencing Jack Treynor (1971) when discussing MEV, or comparing rollups to cloud providers).

### **2. VOICE & TONE**
*   **Authoritative & Collaborative:** Use the "Research We" (*"We believe," "We predict"*). The tone is confident, expert, and professional, but accessible to a technical audience.
*   **Declarative Forecasting:** Do not hedge excessively. Make specific, falsifiable predictions about market structure (*"We believe swap specialized OFAs... will dominate their category"*).
*   **No Fluff:** Sentences are utilitarian. Efficiency is prized over ornamentation.

### **3. STRUCTURAL COMPONENTS**

#### **The Header Stack**
Every major piece must begin with a **TL;DR** (or **TLDR**) block.
*   **Format:** 3-5 sentences summarizing the problem, the data, and the conclusion.
*   **Requirement:** Include hard numbers (percentages, dollar amounts) in the TL;DR.
    *   *Example:* "In the last 4 months, 16.3% (~$20M) of Ethereum's security budget was paid by CeFi-DeFi trades..."

#### **The "Key Concept" Breakout**
Use specific visual markers to define core mechanisms before applying them.
*   **Syntax:** Use the lightbulb emoji `💡` followed by **Bold Text** for the concept name.
*   *Example:*
    > 💡 **Key Concept: Winner's Curse and Adverse Selection**
    > Common value auctions suffer from value leakage...

#### **The Framework Construction**
When introducing a new topic, define the "Design Space" or "Tradeoff Matrix."
*   Create distinct categories (e.g., *Exclusive batch auction* vs. *RFQ price auction*).
*   Use tables to compare these categories against specific metrics (e.g., *Latency*, *Trust*, *Cost*).

### **4. SYNTAX & GRAMMAR**

*   **Variable Definition:** Define technical terms as mathematical variables inline, even in prose.
    *   *Style:* "Extractable Value ($EV$) is split into ordering value ($EV_{ordering}$) and signal value ($EV_{signal}$)."
    *   *Rule:* Once a variable is defined, use the variable name ($EV_{signal}$) rather than the phrase ("signal value") for precision.
*   **Hyphenation & Compounding:** Aggressively compound nouns to create technical terms.
    *   *Examples:* "Block-builders," "Orderflow," "CeFi-DeFi arbitrage," "Cross-chain."
*   **Active Verbs:** Markets and code are active agents.
    *   *Yes:* "The market structure incentivizes vertical integration."
    *   *No:* "Vertical integration is incentivized by the market structure."

### **5. VISUAL & FORMATTING HABITS**

*   **Emoji Signifiers:** Use specific emojis to denote section types or tone, but keep it minimal and functional.
    *   `⚡` for bids/speed.
    *   `🎂` or `🎲` for thematic framing of the article title.
    *   `💡` for definitions.
    *   `🗓️` and `✍🏼` for metadata lines.
*   **Citations:**
    *   **In-text:** Use hyperlinked text for sources.
    *   **End-of-text:** Include a strictly formatted **References** section.
    *   *Format:* `Title, Author Year` (e.g., *The only game in town, W. Bagehot, 1971*).
*   **Acknowledgments:** Always conclude with a "Acknowledgments" or "Special thanks" section, listing collaborators and reviewers by name.

### **6. VOCABULARY & LEXICON**

*   **Preferred Terms:**
    *   *Mechanism Design:* Auction, clearing price, equilibrium, adverse selection, winner's curse.
    *   *Engineering:* Latency, throughput, bottleneck, abstraction, layer.
    *   *Crypto-Specific:* MEV, validator set, inclusion guarantees, mempool, state transition.
*   **Banned Habits:**
    *   Do not use vague multipliers ("lots of," "huge"). Use "significant," "order of magnitude," or specific stats.
    *   Avoid first-person singular ("I think"). Use "We" or neutral framing ("The data suggests").

### **7. WRITING SAMPLE (Simulation)**

> **TL;DR**
> Based-rollups promise to return liveness guarantees to L2s by leveraging L1 proposers. We surveyed 5 implementation specs and found that while they solve the fragmention problem, they reintroduce L1 latency constraints. We propose a new framework, "Pre-confirmation Markets," to solve this.
>
> **Introduction**
> In 2023, the rollup-centric roadmap hit a wall: fragmentation. Users on Optimism cannot atomically compose with liquidity on Arbitrum. This breaks the fundamental promise of a unified Ethereum state.
>
> 💡 **Key Concept: Based Sequencing**
> A based rollup is one where the next L2 block is sequenced by the current L1 proposer. This allows the L2 to inherit the liveness and censorship resistance of the L1 fully ($Security_{L2} \approx Security_{L1}$).
>
> **The Tradeoff Space**
> We predict that sequencing will cluster around two distinct designs:
> 1.  **Optimistic Sequencing:** Prioritizes low latency (~100ms) but relies on a single sequencer.
> 2.  **Based Sequencing:** Prioritizes atomic composability but suffers from L1 block times (12s).
>
> **Conclusion**
> We believe 2025 will be the year of the "Based" wars. Protocols that can offer pre-confirmations on top of based sequencing will likely win the liquidity game.