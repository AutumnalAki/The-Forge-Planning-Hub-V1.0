# The-Forge-Planning-Hub-V1.0
Planning Hub and Calculator for The Forge

📸 Smart Inventory System
OCR Scanning Engine: Upload screenshots of your in-game inventory. The app uses Tesseract OCR with spatial analysis to detect ore names and quantities automatically.

Fuzzy Logic Correction: Includes a "Typo Fixer" (Levenshtein Distance) to correct scanning errors (e.g., reading "lceite" as "Iceite").

Manual Override: Users can manually adjust quantities for precision.

⛔ Exclusion System ("Ban List"): Right-click any ore to mark it as Excluded. Banned ores turn red and are completely ignored by the calculator algorithms—perfect for saving high-tier materials for personal use.

🧠 Optimization Engine ("The Brain")
Clicking Calculate Best Recipes triggers three advanced simulation algorithms:

1. 💰 Money Farm Strategy
Max Single Sale: Identifies the single most valuable item you can craft right now.

Max Profit Run (Chain): Simulates a full crafting sequence to drain your inventory. It tells you exactly what to craft in what order to maximize total cumulative profit.

Profit Ranges: Displays value as a range (e.g., $1,000 - $5,000) to account for guaranteed base values vs. lucky variant drops (e.g., Wolf Armor).

2. ⚔️ Weapon Specialist
Damage Maximizer: specific algorithm that finds the ore combination yielding the highest raw Damage (DMG) stat.

3. 🛡️ Tank/Armor Architect (Dual-Mode)
Max Stats Mode: Uses any ore (even weapon-specific ones like Iceite) to achieve the highest possible raw Defense (DEF) number.

Trait Set Mode: Intelligently filters out ores that provide weapon traits, ensuring recommendations create valid, synergistic Armor Trait Sets.

💎 The Ore Vault
Complete Database: Includes data for all 4 regions: Stonewake, Frostpire, Forgotten Kingdom, and The Peak.

Visual Rarity: Color-coded borders and text (Common to Mythic) for instant recognition.

Live Scaling: A UI slider to zoom ore icons in or out for better visibility.

Filtering: Filter the view by specific islands/regions.

⚗️ The Crucible (Manual Simulation)
Drag-and-Drop Crafting: Test custom recipes manually.

Live Probability: Real-time calculation of crafting success rates (e.g., "85% chance for Heavy Chestplate").

Stat Preview: A "Quality Slider" (0-100%) simulates the forging minigame performance to predict final item stats.

Inventory	Right-Click	Toggle Exclusion: Bans/Unbans an ore from calculations (Visual: Red Border).
Inventory	Left-Click	Does nothing (Selects item).
Inventory	"Scan Image" Btn	Opens file picker to upload a screenshot for auto-detection.
Vault	Left-Click	Adds 1 unit of that ore to the Crucible (Manual Recipe).
Crucible	Left-Click	Removes the item from the current recipe.
General	"Mode" Button	Switches logic between ⚔️ Weapon Mode and 🛡️ Armor Mode.
Results	"USE" Button	Automatically loads the recommended recipe into the Crucible for manual tweaking.
