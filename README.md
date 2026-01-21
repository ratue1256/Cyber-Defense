🛡️ Cyber Defense: TDS ULTIMATE

Cyber Defense is a modern Tower Defense Simulator (TDS) game, inspired by Roblox classics, but designed to run entirely in a web browser. This project pushes the boundaries of a "Single File App" by integrating real-time multiplayer, a persistent economy, and advanced visual effects.

🚀 Key Features

🌐 Real P2P Multiplayer: Powered by PeerJS (WebRTC), play cooperatively with your friends without any centralized server. One player hosts, the other joins via a unique code.

💾 Progression System: Automatic browser-side profile saving (localStorage). Earn Coins in-game to unlock new troops.

🎒 Inventory & Loadout: Manage your tower collection. Strategically choose your 5 best units before starting an operation.

🛒 Lobby Shop: Purchase advanced units like the Minigunner, the DJ Booth, or the Accelerator.

⚡ Performance & VFX: 60 FPS rendering engine based on HTML5 Canvas with particle systems, projectile trails, and an ultra-smooth "Glassmorphism" interface.

🎮 Balanced Gameplay:

Separate player economies in Co-op mode.

Progressive difficulty with boss waves every 10 levels.

Varied unit types (DPS, AOE, Support/Buff, Economy).

🛠️ Installation & Usage

The game is contained in a single HTML file. No installation, Node.js server, or database is required.

Download the index.html file.

Open it in any modern browser (Chrome, Firefox, Edge).

To play with others:

Host: Click "CREATE ROOM" and share the generated code.

Guest: Enter your friend's code and click "JOIN".

🏗️ Technical Architecture

Graphics Engine: HTML5 Canvas API (Zero external libraries).

Networking: PeerJS for direct browser-to-browser communication (P2P).

Interface: Advanced CSS3 with background blurs and transition animations.

Data: JSON for the tower database and the saving system.

📋 Available Troops (Loadout)

Unit

Role

Description

Scout

Starter

Fast and inexpensive base unit.

Sniper

Long Range

Massive damage at a distance, ideal for bosses.

Minigunner

Heavy DPS

Extreme fire rate to melt through tanks.

Farm

Economy

Generates extra cash at the end of each wave.

DJ Booth

Support

Buffs the range of all nearby allied towers.

Accelerator

Laser

Devastating continuous beam (End-game unit).

Developed by Ezio Floriot - 2026 Edition
