# Dave Gibbons' Bluesky Network Analysis

## 🕵️‍♂️ Who Watches the Watchmen? A Social Network Analysis of Influence and Echo Chambers

### **What This Project is About**
Ever since I read *Watchmen*, I’ve been fascinated by the question: **Who truly holds power? And who watches those in power?** 

From **Plato** to **Foucault** to **Orwell**, thinkers have debated power structures and surveillance. But today, power isn’t just in governments or superheroes, it’s in **social media, algorithms, and online influence**. 

That’s why, for my **Network Analysis** course, I didn’t analyze a political figure or an athlete. Instead, I turned to **Dave Gibbons**, co-creator of *Watchmen*, to see **how an artist interacts in a new, decentralized, "left-leaning" social media like Bluesky**. 

Does Bluesky really provide **algorithmic freedom**? Or does it just create another ideological echo chamber, reacting against X’s (Twitter’s) political leanings at the time? **Who controls influence in this space and are we actually shaping our own digital reality?** 

---

## 🔬 **How I Analyzed the Network**
Using **Social Network Analysis (SNA)** and tools like **Gephi**, I explored:
- **Community Structure**: Do users cluster around ideology, profession, or something else? *(Modularity, Louvain Method)*
- **Influence & Gatekeeping**: Who spreads information, and who controls the bridges between communities? *(Betweenness, Closeness, PageRank)*
- **Echo Chambers & Free Speech**: Is Bluesky **truly decentralized**, or do users still form ideological silos? *(Graph Theory, Network Density)*

### 📊 **The Dataset**
- **19,242 nodes** (users)
- **29,211 edges** (connections)
- Data collected using **Gephi's Bluesky plugin**
- Expanded **n+1 degree** network (followers of followers)
- **Historical Snapshot:** This analysis reflects the **state of the network at the time of data collection** and does not necessarily represent its current structure.
- **Dataset Available:** The raw data is available in the `/data` folder:
  - `dave_follows` – Accounts followed by Dave Gibbons
  - `dave_followers` – Accounts following Dave Gibbons
  - Files with `_crawl` in their names indicate datasets **limited by Gephi's crawling constraints**

---

## 🔥 **Key Findings**
🎭 **Community Clusters Exist**: Groups form around **independent artists, UK creators, and industry professionals**—but also around **ideological leanings**.  
🌉 **Bridging Nodes Shape Discourse**: Some users (even with **low follower counts**) act as crucial connectors between communities.  
🔁 **Echo Chambers Are Real—But Not Just Algorithmic**: Users naturally form ideological bubbles, even on a platform that **claims to let us control our own algorithm**.  

---

## ⚙️ **How to Use This Data**
This repository contains **processed data from my analysis**, but it is not set up for re-running the analysis programmatically. However, you can:
1. **Load the dataset into Gephi** to explore the network visually.
2. **Examine the raw data** in the `/data` folder.
3. **Refer to my full project PDF** for a detailed explanation of methods and findings.

---

## 🛠️ **Future Research Directions**
🔍 **How do these dynamics change over time?** (Temporal Analysis)
🔍 **Do influencers on Bluesky behave differently than on X (Twitter)?** (Comparative Analysis)
🔍 **Can we design algorithms to **break** echo chambers rather than reinforce them? And would people actually *want* that?**

---

## 📖 **Conclusion**
Dave Gibbons' Bluesky network is a **living, breathing online ecosystem**. While it reflects the power of digital communities, it also highlights the risks of ideological silos,even in “decentralized” platforms. 

Ultimately, this project doesn’t just analyze **one creator’s network**. It challenges us to ask: **Are we truly shaping our own digital spaces, or are we just reinforcing the bubbles we want to live in?**
