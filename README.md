# CryptoFarm 2.0

**CryptoFarm 2.0** is an enhanced, object-oriented C++ console game where you start with **1500 FarmCoins** to buy planting beds, grow plants, and sell your harvest at prices dynamically tied to real-time cryptocurrency exchange rates fetched from the **Binance API**. This version emphasizes clean OOP design and was developed as a C++ exam project.

---

##  Game Concept & Mechanics

- You begin with a fixed budget of **1500 FarmCoins**.
- Purchase planting beds using numeric keys (**1**, **2**, **3**, ...).
- Nurture plants by watering and fertilizing each bed.
- Harvest and sell crops—prices change in real-time based on the selected cryptocurrency's exchange rate from Binance.
- Objective: Grow your FarmCoin balance by strategic use of beds, resources, and market timing.

---
<img width="1186" height="814" alt="image" src="https://github.com/user-attachments/assets/37daa0a9-7d51-4094-8466-9e6a156fee5d" />
---

##  Why OOP?

This version is structured around **Object-Oriented Programming (OOP)** principles to ensure clarity, modularity, and extensibility. Key design ideas include:

- **Encapsulation**: Game logic is distributed across clear classes that represent game entities and actions.
- **Reusability & Maintainability**: OOP-style components pave the way for easy extensions and future enhancements.
- C++ remains a powerful language for high-performance and structured programming, especially when embracing its OOP paradigms. :contentReference[oaicite:0]{index=0}

---

##  Features

- **Robust OOP design**: Classes for beds, plants, game controller, API fetcher, etc.
- **Binance integration**: Uses Binance’s public API to fetch live currency rates (e.g. via HTTP GET, potentially using a library like `binapi`) :contentReference[oaicite:1]{index=1}.
- **Intuitive controls**: Beds mapped to number keys; clear console-based commands for watering, fertilizing, and selling.
- **Real-time strategy loop**: Manage your resources while watching the market fluctuate.

---

##  Getting Started

### Requirements

- C++17-compatible compiler (e.g. GCC, Clang, MSVC)
- Internet connection to fetch price data from the Binance API
- A JSON parsing library such as **nlohmann/json** to handle API responses

### Build & Run

```bash
git clone https://github.com/kihaas/crypto-farm-2.0.git
cd crypto-farm-2.0

# Build (example using g++)
g++ -std=c++17 main.cpp -o CryptoFarm2

# Run
./CryptoFarm2


