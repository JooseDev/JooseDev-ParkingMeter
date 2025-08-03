# JooseDev-ParkingMeter
Immersive QBCore parking meter break-in script with a custom lockpicking minigame, difficulty levels, animations, progress bar, and coin drop effects. Features random loot, global cooldowns, and server-side checks for a balanced, fun criminal activity. FULLY OPEN SOURCE

🚗 Parking Meter Lockpicking for QBCore
A fully immersive FiveM resource that lets players break into parking meters using a custom lockpicking minigame. Features difficulty levels, animations, a progress bar, and a satisfying falling coin effect on success.

Features:

🎯 Custom Minigame with easy/medium/hard difficulty options.

⏳ Global Cooldown to prevent repeated farming.

💰 Random Loot System that drops quarters or other items from a configurable loot table.

🎬 Immersive Animations for lockpicking and collecting coins.

🪙 Coin Drop Effect on successful break-ins.

🛡 Server-Side Checks to prevent abuse.

🔧 Configurable Settings for cooldown time, loot, and difficulty.

Perfect for adding a fun, risk/reward criminal activity to your RP server while maintaining balance and immersion.

## 📥 Installation Steps
1. **Download** or **clone** this repository into your FiveM `resources` folder.  
2. Rename the folder to `joosedev-parkingmeter` (or keep your preferred name).  
3. Add the following line to your `server.cfg`:
   ```
   ensure joosedev-parkingmeter
   ```
4. Place the `quarter.png` image in your inventory images folder (e.g., `qb-inventory/html/images/`).  
5. Add the `quarter` item to your QBCore shared items file:
   ```lua
   ['quarter'] = {['name'] = 'quarter', ['label'] = 'Quarter', ['weight'] = 0, ['type'] = 'item', ['image'] = 'quarter.png', ['unique'] = false, ['useable'] = false, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = 'A shiny quarter.'},
   ```

## 📦 Dependencies
- [QBCore Framework](https://github.com/qbcore-framework/qb-core)  
- [qb-target](https://github.com/qbcore-framework/qb-target)  
- [progressbar](https://github.com/qbcore-framework/progressbar)  
- Lockpicking Minigame Resource (included or replace with your own)
