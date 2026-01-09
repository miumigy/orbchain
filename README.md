# 🪐 Orbit Chain

**Interstellar Supply Chain Manager**

**Orbit Chain** is a **3D interstellar supply chain simulation game** that runs entirely in a single browser file.
As the CEO of an interstellar logistics company, your mission is to build a network of mining, production, and sales to become the Universe's Logistics Emperor.

## ✨ Features

* **Single-File Architecture**: The entire game runs on a single `index.html` file. No build tools or local server required.
* **Rich 3D Visuals**: Beautiful space environment and particle effects powered by [Three.js](https://threejs.org/).
* **Real-Time Economy**:
    * **3-Tier Supply Chain**: Raw Material (Miner) → Processing (Factory) → Market.
    * **Cost Management**: Balance transport costs (Variable) against facility upkeep (Fixed).
    * **Dynamic Demand**: Manage risks associated with price fluctuations due to events and inventory levels.
* **Strategic Fleet Management**:
    * **Scout**: Fast, small capacity, high cost (Ideal for urgent demand).
    * **Hauler**: Slow, large capacity, low cost (Ideal for bulk transport).
* **Smooth Gameplay**:
    * **Time Warp**: Pause and Speed Up (Fast Forward) controls.
    * **Responsive Design**: Glassmorphism UI optimized for both mobile (portrait) and desktop.
    * **Short Session**: Time-attack style gameplay with a speed bonus for fast clears.

## 🎮 How to Play

1.  **Deploy Fleet**
    * Purchase transport ships from the bottom-right panel to start automatic deliveries.
    * Use **Haulers** to build a cost-effective foundation, and **Scouts** for urgent deliveries.
2.  **Upgrade Facilities**
    * Click on a planet to open the details panel.
    * You can upgrade **Flow Speed** and **Capacity**.
    * ⚠️ **Warning**: Higher levels increase **Upkeep** costs. Reckless investment will lead to bankruptcy.
3.  **Maximize Profit**
    * Delivering goods to Markets (Green planets) generates cash.
    * Optimize your supply chain to prevent **Stockouts** (missed opportunities) and **Overstock** (waste).
4.  **Game Clear**
    * Survive and increase your Corporate Rank until you achieve the title of "**Emperor**".
    * Faster clear times award a significant **Speed Bonus**.

## 🚀 Installation & Usage

No special environment setup is required.

1.  Clone or download this repository.
2.  Simply open `index.html` in any modern web browser (Chrome, Safari, Edge, Firefox, etc.).

```bash
# Clone the repository
git clone [https://github.com/your-username/orbit-chain.git](https://github.com/your-username/orbit-chain.git)
cd orbit-chain

# Open index.html directly in your browser
# (or double-click the file in your file explorer)
```

## 🛠️ Tech Stack
- Core: HTML5, CSS3, JavaScript (ES6+, Worker API)
- Rendering: Three.js (via CDN / ES Modules)
- Build Tool: None (Pure Vanilla JS implementation)

## 📂 Directory Structure
```
orbit-chain/
├── index.html      # Complete source code (Logic, Styles, 3D Rendering)
├── README.md       # Project documentation
└── LICENSE         # License file
```

## 🤝 Contribution
Bug reports, feature suggestions, and Pull Requests are welcome! Although the code is contained in a single file, it is structured into Web Worker, Main Thread, and CSS sections for readability.

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
