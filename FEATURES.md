# 💡 MoneyForge Features

This document outlines the core features, interactive elements, and experimental scenarios built into the MoneyForge simulation.

---

## 🏗️ Core Systems

### **1. Barter → Money Evolution**

The simulation begins with a pure barter economy. Agents must find a "double coincidence of wants" to trade. As they fail, some will spontaneously adopt a common medium of exchange, leading to the organic emergence of money.

### **2. Value Construction**

Prices are not fixed. They emerge dynamically based on the total supply and demand for goods across the economy. Disasters, production changes, and shifts in agent desires will cause prices to fluctuate in real-time.

### **3. Market Dynamics**

- **Goods Market:** Agents trade `food`, `tools`, and `materials`.
- **Credit Market:** Banks lend money to agents in need, charging interest and creating money through credit.

### **4. Credit & Debt**

Agents can take on debt from banks to fund their activities. This introduces a new layer of financial complexity, allowing for faster growth but also the risk of debt spirals.

### **5. Bubbles & Crashes**

The simulation includes a simple asset market. Wealthy agents can buy and sell these assets. The price is not tied to any intrinsic value, allowing for speculative bubbles and subsequent crashes to emerge organically from agent behavior.

### **6. Inequality Dynamics**

The Lorenz curve and Gini coefficient track wealth inequality in real-time. Watch how different economic conditions, policies, and random events lead to the concentration or distribution of wealth.

---

## 🎮 Interactive Elements

### **Intervention Tools**

You are the "Economy God" and can intervene at any time:

- **Print Money:** Inject money into the economy by giving it to all money-using agents.
- **Trigger Disaster:** Cause a supply-side shock by destroying a large percentage of a random good (e.g., crop failure, mine collapse).
- **Adjust Parameters:** Use the sliders to change the agent count, production rate, trade distance, and more.

### **Observation Tools**

- **Real-Time Charts:**
  - **Wealth Distribution:** A Lorenz curve visualizes the distribution of wealth.
  - **Currency Adoption:** Tracks the percentage of agents using money over time.
  - **Market Prices:** Shows the fluctuating prices of goods.
  - **Asset Market:** Tracks the price of the speculative asset.
- **Agent Visualization:**
  - **Color:** Indicates role or wealth level.
  - **Indicators:** Rings and icons show goods inventory, asset ownership, and more.
  - **Trade Lines:** Yellow lines appear to show successful trades as they happen.

---

## 🎯 Scenarios & Experiments

The simulation includes several preset scenarios to kickstart different economic conditions:

- **Pure Barter:** The default starting state.
- **Money Seeded:** A small percentage of agents start with money to accelerate its adoption.
- **High Inequality:** A few agents start with the vast majority of the wealth.
- **Economic Crash:** Instantly destroys a large portion of all wealth in the simulation.
