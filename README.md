# 🚔 Kris Jail System

A full prison system for FiveM with jail commands, prison jobs, progression, contraband, searching, commissary, escape gameplay, inventory handling, and framework support for Qbox, QBCore, and ESX.

This script is built to give jail actual gameplay instead of just waiting out a timer. Prisoners can work time off, earn prison resources, level jobs, buy contraband, search for materials, craft escape tools, and attempt a tunnel escape.

---

# ✨ Features

### 🔒 Full Jail / Unjail System

* Supports Qbox, QBCore, and ESX
* Uses ox_lib menus and notifications
* Uses ox_inventory
* Persistent jail state with database saving
* Handles script restarts much better while players are online
* Prison-earned items are kept after release
* Automatic prison clothing support
* Configurable prison locations, guards, peds, jobs, stations, search spots, and escape points

---

# ⚖️ Jail System

### Commands

* `/jail <id> <minutes>`
* `/unjail <id>`
* `/jailtime`

### Features

* Police job restriction support
* Optional distance check for jailing
* Sentence time is saved
* Jail state is restored after reconnect / restart
* Inventory is confiscated on jail and returned on release
* Items earned inside prison are preserved when released

---

# 🛠️ Prison Job System

Prisoners can interact with the guard and open an ox_lib job board.

### Included Jobs

* 🍽️ Wash Dishes
* 🧹 Sweep Floors
* 🪣 Mop Floor
* 🍃 Leaf Blower
* 🧽 Wash Walls
* ⚡ Electrical Job
* 🚧 Construction Job

### Job System Features

* Assignable prison jobs
* Job-specific stations
* Work blips
* Work animations / emotes
* Time reduction rewards
* 🚬 Cigbutt rewards
* 💵 Cash rewards
* 📦 Bonus item rewards
* Configurable assigned limit per job

---

# 📈 Progression System

* Job progression with levels
* Max level: 10
* Different jobs can track their own progress
* XP requirement curve gets harder as levels go up
* Level bonuses can improve item reward chances
* Progress is saved

---

# 🚬 Contraband / Prison Economy

### 🕴️ Contraband Dealer

Prisoners can buy contraband using cigbutts.

#### Default Dealer Items

* 📱 Smuggled Phone (`phone`)
* 🔪 Shiv (`weapon_knife`)

### 🏪 Commissary

Built-in commissary support with ox_inventory shop registration.

---

# 🔍 Search Spots

Prisoners can search configured prison spots for rewards such as:

* 💵 Cash
* 🧴 Plastic
* 🔩 Metal
* 🎁 Rare contraband items

---

# 🚨 Escape System

A tunnel-based prison escape system.

### Features

* ⛏️ Shovel crafting system
* Configurable crafting cost
* Dig tunnel interaction
* Escape route objective
* Alarm system
* Police dispatch / escape alerts
* Escape release handling

---

# 🎯 Extra Details

* 👮 Guard peds
* 🏪 Commissary peds
* 🕴️ Dealer peds
* 🗺️ Public prison blip
* 📍 Job guard blips
* 🔊 Prison sound effects
* 🧹 Clean config structure
* 📖 Prison guide item support on jail

---

# 📋 Requirements

* ox_lib
* ox_inventory
* A MySQL resource compatible with `MySQL.query.await`

### Supported Frameworks

* ✅ Qbox
* ✅ QBCore
* ✅ ESX

---

# ⚙️ Configurable

You can configure:

* Prison locations
* Entry / release / reclaim positions
* Guard locations
* Dealer locations
* Commissary locations
* Search spots
* Work stations
* Blips
* Rewards
* Time reduction values
* Progression values
* Escape settings
* Clothing
* Notifications
* Ped models
* Sounds
* Commands

---

# 📝 Summary

This is a complete prison gameplay script, not just a simple jail timer. It adds prison work, progression, prison economy, contraband, searching, crafting, and escape mechanics while staying compatible with Qbox, QBCore, and ESX.
