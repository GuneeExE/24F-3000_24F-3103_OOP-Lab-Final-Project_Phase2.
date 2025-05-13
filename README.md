# oop-Stronghold-game
My semester project game for object oriented programming
Here’s a complete **README.md text** for your GitHub repository. You can directly **copy-paste this** into your README.md file:

---

# 🏰 Stronghold Kingdom Management Simulator

A C++ console simulation game where you govern a medieval kingdom, manage resources, conduct diplomacy, maintain your army, and handle politics, corruption, economy, and more.

---

## 📦 Project Overview

Stronghold is a turn-based kingdom management simulator where players take turns to expand their realm, train armies, manage finances, and outmaneuver rival kingdoms through diplomacy, espionage, and warfare.

---

## 📁 Project Structure

```
├── Main.cpp          # Game loop and user interface
├── Stronghold.cpp    # Implementation of kingdom mechanics and subsystems
├── Stronghold.h      # Class declarations, constants, utilities
├── README.md         # Project documentation (this file)
```

---

## 🛠️ Technologies Used

| Library       | Purpose                                    |
| ------------- | ------------------------------------------ |
| `<iostream>`  | Console input/output                       |
| `<string>`    | String operations                          |
| `<ctime>`     | Random number generation                   |
| `<cstdlib>`   | Random utilities (`rand()`)                |
| `<thread>`    | Simulate delays (e.g., building, training) |
| `<chrono>`    | Timing operations for delays               |
| `<fstream>`   | File I/O (saving/loading game state)       |
| `<memory>`    | Smart pointers (`unique_ptr`)              |
| `<exception>` | Custom exception handling                  |

---

## 🔧 Features Implemented

* 🏦 **Economy Management** (Taxes, Loans, Debt)
* 🛡️ **Army Training, Morale, & Combat**
* 👑 **Political System** (Elections, Bribes, Rebellions)
* 🏘️ **Population Management & Class Satisfaction**
* 🧱 **Infrastructure Development** (Barracks, Blacksmiths, Healthcare)
* 🌦️ **Dynamic Weather Effects**
* 🏬 **Market with Dynamic Prices, Inflation, Guild Demands**
* 🕵️ **Espionage Missions** (Spy, Sabotage, Theft)
* 🚛 **Smuggling & Diplomacy**
* ⚠️ **Corruption & Audit System**
* 🗺️ **Map Control & Enemy Attacks**
* 💾 **Save/Load Game States**
* 🏆 **Scoring System with Leaderboard**

---

## ⚙️ How to Compile & Run

```bash
g++ Main.cpp Stronghold.cpp -o StrongholdGame
./StrongholdGame
```

---

## ✅ Functions & Their Purpose

### Utility Functions

* `getValidInt(prompt)`: Safe integer input with validation.
* `getValidString(prompt)`: Safe string input.
* `clearInputBuffer()`: Clears input stream after invalid input.
* `getValidChoice(min, max, prompt)`: Ensures choice within range.

### Core Gameplay (Kingdom Class)

* `playTurn()`: Executes one kingdom turn (updates, events).
* `trainArmy(count)`: Train soldiers using resources.
* `holdElection()`: Conduct political elections.
* `manageLoanOrAudit(choice, amount)`: Loans, repayments, corruption audits.
* `buyResource(resource, amount)`: Buy resources from the market.
* `manageDiplomacy(kingdom, choice)`: Form alliances, trade routes, etc.
* `bribeOrBlackmail(choice, candidate)`: Influence politics.
* `sendMessage(recipient, message)`: Diplomatic communication.
* `sendFakeTradeRequest(recipient)`: Fake trade to deceive rivals.
* `produceWeapons(count)`: Weapon production.
* `conductEspionage(action, target)`: Spy, sabotage, steal gold.
* `conductSmuggling(target)`: Smuggle goods using alliances.
* `manageHealthcare(choice)`: Build hospitals, improve morale.
* `manageBuildings(choice)`: Expand barracks.
* `saveState(filename)`: Save game progress.
* `loadState(filename)`: Load saved game.
* `saveScore()`: Save player's score.
* `printStatus()`: Display current kingdom status.

---

## 🏅 Example Game Flow

1. Start a new game as Player 1 & Player 2.
2. Take turns managing kingdom affairs via a menu-driven interface.
3. Handle economy, train army, engage in diplomacy, espionage.
4. Survive random events & disasters.
5. Save/load progress and compete for high scores.

---

## 📊 Sample Save File

```
Kingdom: Ironhold
Population: 1000
Morale: 0.85
Gold: 1200
Loan: 500
LandSeized: 0
Army: 150
Weapons: 80
Food: 900
Iron: 450
Wood: 700
Stone: 600
BlacksmithLevel: 3
King: Arthur
Tax: Progressive
HealthcareLevel: 2
BarracksLevel: 1
Inflation: 1.2
```

---

## ✍️ Author

24f-3000 Usman Ghani
24f-33103 Faizan Waseem

---

## ⭐ Bonus

Feel free to fork, modify, and add more features like:

* Multiplayer over network
* AI opponent
* More detailed warfare mechanics
* Advanced trade & economy system

---


