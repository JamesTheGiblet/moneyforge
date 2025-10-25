
# 💸 MoneyForge - Economic System Simulator

> "Money is the most successful collective fiction in human history. It only works because we all agree to pretend it works."

**What if you could SEE that fiction being constructed in real-time?** That is the purpose of MoneyForge.

MoneyForge is a browser-based simulation that models the emergence of a complex economy from a simple barter system. It demonstrates how core economic concepts like money, value, credit, and investment can arise organically from the interactions of individual agents, each with their own goals and behaviors.

---

## 🚀 How to Run

Simply open the `moneyforge.html` file in a modern web browser. The simulation will start automatically, loading any previously saved state from your browser's `localStorage`.

---

## Core Systems

### **1. Barter → Money Evolution**

The simulation begins with a pure barter economy. Agents must find a "double coincidence of wants" to trade. As they fail, frustrated agents observe the success of their money-using neighbors and may spontaneously adopt money, leading to its organic emergence as a medium of exchange.

+### **2. Dynamic Value & Pricing**
Prices for goods (`food`, `tools`, `materials`) are not fixed. They emerge dynamically based on the total supply and demand across the entire economy. Disasters, production changes, and shifts in agent desires will cause prices to fluctuate in real-time.

+### **3. Division of Labor & Agent Roles**
Agents are assigned specialized roles, creating a natural need for trade and a more complex economy:

- **🌾 Farmer:** Produces `food`.
- **⛏️ Miner:** Produces `materials`.
- **🛠️ Toolmaker:** Produces `tools`.
- **🏦 Bank:** Does not produce goods, but provides loans to other agents and earns interest.
- **🏛️ Government:** A unique agent that collects taxes and distributes a Universal Basic Income (UBI).

### **4. Credit, Debt & Banking**

Bank agents can lend money to other agents in need. This introduces a credit system, allowing agents to fund their activities but also introducing the risk of debt.

### **5. Asset Market & Speculation**

Once the economy matures, a speculative asset market emerges. The asset's price is tied to the overall economic performance (trade volume). Wealthy agents can buy and sell these assets, creating a new avenue for wealth generation and introducing the potential for market bubbles and crashes.

## 🎮 Interactive Elements

### Intervention Tools

You can intervene in the economy at any time:

- **Print Money:** Inject money into the economy by giving it to all money-using agents.
- **Trigger Disaster:** Cause a supply-side shock by destroying a large percentage of a random good (e.g., crop failure, mine collapse).
- **Adjust Parameters:** Use the sliders to change the agent count, production rate, trade distance, and more.
- **Apply Scenarios:** Instantly set up the economy for different conditions like "High Inequality" or a "Money Seeded" start.

### Observation Tools

A comprehensive dashboard provides real-time insight into the economy's health:

- **Economy Canvas:** A live view of all agents, their roles, wealth, and trade interactions.
- **Wealth Distribution:** A Lorenz curve and Gini coefficient clearly visualize wealth inequality.
- **Currency Adoption:** Tracks the percentage of agents using money over time.
- **Market Prices:** Shows the fluctuating prices of goods based on supply and demand.
- **Asset Market:** Tracks the price of the speculative asset.
- **Government Treasury:** Visualizes the government's financial state as it collects taxes and distributes UBI.
- **Event Log:** A running commentary of important economic events.
