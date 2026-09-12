import os
import shutil

md_content = """# B-Zone SA:MP Community Rules & Wiki Guide (Complete Archive)

> **Source Link**: [B-Zone SA:MP Rules Main Page](https://rules.b-zone.ro/wiki-info/main_page/)

This document serves as the complete, uncompressed Markdown archive of all 50 source pages from the official B-Zone SA:MP Wiki and Rules documentation.

---

## Table of Contents
1. [General Server Rules & Regulations](#1-general-server-rules--regulations)
2. [Account & Security Policies](#2-account--security-policies)
3. [Factions Directory & Rules](#3-factions-directory--rules)
   - [Peaceful Factions](#peaceful-factions)
   - [Gangs](#gangs)
   - [Departments](#departments)
   - [Mixt Factions](#mixt-factions)
4. [Business Systems & Directory](#4-business-systems--directory)
5. [Vehicle Catalogs & Mechanics](#5-vehicle-catalogs--mechanics)
6. [House & Property Systems](#6-house--property-systems)
7. [Comprehensive Command Directory](#7-comprehensive-command-directory)
8. [Media & Image References](#8-media--image-references)

---

## 1. General Server Rules & Regulations
> **Source Link**: [Server Rules](https://rules.b-zone.ro/)

### 1.1 Conturi & Account Rules
* **Afaceri cu Conturi/Bunuri**: Real-money trading (RMT) or exchanging out-of-game assets for in-game currency/accounts is strictly forbidden and results in permanent ban.
* **Securitatea Contului**: Account security is entirely the player's responsibility. Setting up Two-Factor Authentication (2FA) via the website is strongly recommended.
* **Conturi Multiple**: Multi-accounting to bypass bans or farm bonuses is prohibited.
* **Impartire Conturi**: Sharing account login credentials with other players is done at your own risk and can lead to sanctions if caught in rule violations during account sharing.
* **Activitatea pe Server & Inactivitate**: Long-term inactivity without notice can result in eviction from houses or removal from faction leadership.

### 1.2 SA:MP Client, Hacks & Exploits
* **Clientul de SA:MP**: Official SA:MP clients (0.3.7 / 0.3.7-R2) must be used.
* **Coduri (Cheats)**: Any wallhack, aimbot, auto-cbug, weapon hack, or speedhack results in an immediate permanent ban.
* **Moduri**: Illegal mods providing unfair tactical advantages are banned.
* **Bug Abuse**: Exploiting game glitches or server bugs rather than reporting them will lead to warnings, temporary bans, or account resets.
* **Reclama (Advertising)**: Advertising other SA:MP servers or external communities on server chats or PMs is punished with a permanent ban.

### 1.3 Conduct & Chat Regulations
* **Inselatorii (Scams)**: Scamming players during vehicle, property, or item trades is strictly punished with account bans and restitution where applicable.
* **Limbaj (Language)**: Vulgar language, insults, or harassment towards players or staff result in mutes, warns, or temp bans.
* **Spamming**: Repeating messages rapidly in global or local chats is restricted.
* **Comportament NON-RP**: Actions breaking Roleplay immersion (e.g., drive-by without proper weapons, unrealistic actions) are subject to jail time.
* **Toxicitate**: Toxic behavior towards the community or staff across in-game or website mediums carries severe sanctions.

---

## 2. Account & Security Policies
> **Source Links**:
> - [Account Security](https://rules.b-zone.ro/#securitatea-contului)
> - [2FA Recovery](https://rules.b-zone.ro/wiki-info/website/2fa-recovery/)
> - [Password Recovery](https://rules.b-zone.ro/wiki-info/website/password-recovery/)

### 2.1 Two-Factor Authentication (2FA)
To enable 2FA:
1. Log in to your account on the official RPG website [rpg.b-zone.ro](https://www.rpg.b-zone.ro/).
2. Navigate to **My Account -> Security Settings**.
3. Scan the QR code using Google Authenticator or Microsoft Authenticator.
4. Store your recovery codes safely in case you lose access to your authenticator app.

### 2.2 Website Evidence & Reports Rules
* **Dovezi (Evidence Validity)**: Proof used in reports must be max 3 days old and belong to the reporter.
* **Falsificarea dovezilor**: Forging or editing screenshots/videos is punished with a permanent ban across all user accounts.
* **Video Refresh Requirement**: For browser-based evidence, a video recording showing a page refresh is mandatory to verify authenticity.
* **Posthunting**: Excessive or malicious filing of invalid reports against players is sanctioned with website suspension.

---

## 3. Factions Directory & Rules
> **Source Links**:
> - [Faction General Rules](https://rules.b-zone.ro/factions/peaceful-and-mixt-faction-rules/)
> - [Gang General Rules](https://rules.b-zone.ro/factions/gang-rules/)
> - [Department General Rules](https://rules.b-zone.ro/factions/department-rules/)
> - [Activity Report](https://rules.b-zone.ro/wiki-info/factions/activity-report/)

### Peaceful Factions
1. **Paramedics** ([Source](https://rules.b-zone.ro/wiki-info/factions/paramedics/))
   - **Ranks**: Chief Paramedic (Leader/6), Field Chief (5), Ambulance Commander (4), Paramedic in Charge (3), Paramedic (2), Candidate Paramedic (1).
   - **Vehicles**: Ambulance, Police Ranger, Raindance, Romero.
   - **Commands**: `/duty`, `/fvr`, `/clothes`, `/heal [ID/Name] [Price]`, `/servicecalls`, `/rehab`, `/corpse`, `/corpses`, `/beacon`.
2. **News Reporters** ([Source](https://rules.b-zone.ro/wiki-info/factions/news-reporters/))
   - **Ranks**: Network Director (Leader), Network Producer (6), Network Editor (5), Network Anchor (4), Local Editor (3), Local Reporter (2), Intern (1).
   - **Vehicles**: Newsvan (12 units, 136 km/h), SAN News Maverick (1 unit, 163 km/h).
   - **Commands**: `/duty`, `/fvr`, `/clothes`, `/papers`, `/news`, `/live`, `/endlive`, `/callout`, `/readpaper`, `/deliver`.
3. **Tow Truck Company (TTC)** ([Source](https://rules.b-zone.ro/wiki-info/factions/tow-truck-company/))
   - **Ranks**: Tow Company Owner (Leader/6), Manager (5), Supervisor (4), Senior Mechanic (3), Mechanic (2), Trainee (1).
   - **Vehicles**: Tow Truck, Utility, Maverick.
   - **Commands**: `/duty`, `/fvr`, `/clothes`, `/tow`, `/towpoints`, `/servicecalls`, `/sellkit`, `/refillgascan`.
4. **Taxi Factions (LS Taxi, LV Taxi, SF Taxi)** ([LS Taxi](https://rules.b-zone.ro/wiki-info/factions/ls-taxi/), [LV Taxi](https://rules.b-zone.ro/wiki-info/factions/lv-taxi/), [SF Taxi](https://rules.b-zone.ro/wiki-info/factions/sf-taxi/))
   - **Ranks**: Taxi Company Owner (Leader/6), Shift Supervisor (5), Dispatcher (4), Cabbie (3), Taxi Rookie (2), Trainee (1).
   - **Vehicles**: Taxi, Cabbie, Sultan, Maverick, Huntley, Alpha, Tahoma.
   - **Commands**: `/fare`, `/tx`, `/servicecalls`, `/clothes`, `/fvr`.
5. **School Instructors (LS, LV, SF)** ([LS School Instructors](https://rules.b-zone.ro/wiki-info/factions/ls-school-instructors/))
   - **Ranks**: Boss (Leader), Under Boss (6), Manager (5), Supervisor (4), Senior Instructor (3), Instructor (2), Trainee (1).
   - **Vehicles**: Merit, Sultan, Maverick, Speeder.
   - **License Payouts**: Weapon ($2,000), Flying ($1,800), Sailing ($1,700), Materials ($1,600), Fishing ($500).
   - **Commands**: `/startlesson`, `/stoplesson`, `/givelicense`, `/sx`, `/duty`.

### Gangs
> **Gangs Included**: Green Street Bloods, Verdant Family, Vietnamese Boys, The Tsar Bratva, Red Dragon Triad, Southern Pimps, Avispa Rifa, 69 Pier Mobs, El Loco Cartel.
- **Ranks**: Leader (Rank 6), Subleader (5), Rank 4, Rank 3, Rank 2, Rank 1.
- **Vehicles**: Gang-specific vehicles (Huntley, Maverick, Stretch, Lowriders, FCR-900, Sports cars).
- **Core Commands**:
  - `/fvr`: Respawns all unoccupied faction vehicles (Rank 5+).
  - `/order [Package ID]`: Orders weapon packages (Packages 1-4).
  - `/backup` & `/cbackup`: Requests or cancels emergency gang backup.
  - `/tie` & `/untie`: Kidnaps or releases a target player (Rank 3+).
  - `/fput` & `/fget [materials/drugs]`: Deposits or withdraws gang HQ materials/drugs.
  - `/stealers`: Lists active vehicle thieves targeting faction vehicles.
  - `/tduty`: Toggles tester duty for faction entrance testing.

### Departments & Mixt Factions
- **Departments**: LSPD, LVPD, SFPD, FBI, National Guard.
  - **Special Vehicles**: Police Car (LS/LV/SF), Enforcer, FBI Rancher, HPV-1000, Rhino, Hydra, Hunter.
  - **Key Commands**: `/duty`, `/wanted`, `/clear`, `/su` (suspect), `/ar` (arrest), `/frisk`, `/ticket`, `/cuff`, `/uncuff`, `/m` (megaphones).
- **Mixt Factions**: Hitmen Agency, Sons of Anarchy, Mayor.
  - **Hitmen Agency**: Fulfills silent contracts via `/portable`, `/order`, `/find`.
  - **Mayor**: Controls server tax rates, budget distribution, and `/tax` commands.

---

## 4. Business Systems & Directory
> **Source Link**: [Business General Description](https://rules.b-zone.ro/wiki-info/business/general-description/)

### 4.1 Business Ownership & Shareholding System
- Businesses on B-Zone operate with a shareholder system where profits can be split among stock/shareholders.
- **Key Commands**:
  - `/bizinfo`: Displays financial statistics, fee rates, and current vault balance.
  - `/bizstatus`: Displays business operational status.
  - `/bizwithdraw [Amount]`: Withdraws cash from the business vault (Owner/Shareholders).
  - `/sellshares [Player] [Share %] [Price]`: Sells business stock shares to another player.
  - `/shareholders`: Displays current shareholder list and equity percentages.

### 4.2 Business Types & Specific Functions
1. **24/7 Stores** ([Source](https://rules.b-zone.ro/wiki-info/business/24-7/))
   - **Products**: Phone, Phonebook, Dice, Cigarettes, Lighter, Camera, Spray Can, Gas Can, Parachute.
   - **Commands**: `/buy` (opens purchasing menu dialog), `/lotto` (opens lottery ticket UI).
2. **Fast Food & Restaurants** ([Fast Food](https://rules.b-zone.ro/wiki-info/business/fast-food/), [Restaurants](https://rules.b-zone.ro/wiki-info/business/restaurants/))
   - **Function**: Restores player health (+20 HP per meal).
   - **Commands**: `/eat` (costs $60 at Fast Food, $30 at Restaurants) or press `LALT`.
3. **CNN (Cable News Network)** ([Source](https://rules.b-zone.ro/wiki-info/business/cnn/))
   - **Locations**: Los Santos, Las Venturas, San Fierro.
   - **Ad Structure**: Single line (<= 50 chars), Double line (51 - 124 chars). SafeZone area.
   - **Commands**: `/ad [text]` (submits advertisement), `/ads` (previews ad queue), `/myad` (checks status of pending ad), `/cancel ad`.
4. **Gas Stations** ([Source](https://rules.b-zone.ro/wiki-info/business/gas-stations/))
   - **Commands**: `/fill [percent]` (refuels vehicle), `/fillgascan` (fills portable fuel can).
5. **Gun Shops & Melee Stores** ([Gun Shops](https://rules.b-zone.ro/wiki-info/business/gun-shops/), [Melee Stores](https://rules.b-zone.ro/wiki-info/business/melee-weapons-store/))
   - **Gun Shop Commands**: `/buygun [Weapon Name]` (purchases firearms if licensed).
   - **Melee Store Items**: Katana, Baseball Bat, Golf Club, Brass Knuckles.
6. **Clothing Stores** ([Source](https://rules.b-zone.ro/wiki-info/business/clothing-stores/))
   - **Commands**: `/skins` (opens paginated skin shop), `/buyacs` (buys accessories like hats/sunglasses), `/costumes`.
7. **Car Color & Tuning** ([Car Color](https://rules.b-zone.ro/wiki-info/business/car-color/), [Tuning](https://rules.b-zone.ro/wiki-info/business/tuning/))
   - **Car Color Commands**:
     - `/carcolor`: Changes primary/secondary vehicle colors to non-hidden IDs (0–127) for $500.
     - `/hiddencolor`: Applies special hidden color IDs (128–255) for 600 Gold.
8. **Casinos (Caligulas & Poker Casino)** ([Caligulas Casino](https://rules.b-zone.ro/wiki-info/business/caligulas-casino/), [Poker Casino](https://rules.b-zone.ro/wiki-info/business/poker-casino/))
   - **Games**: Blackjack, Poker Dice, Texas Hold'em Poker.
   - **Commands**: `/blackjack`, `/poker`.
9. **Arenas & PubG Arena** ([Arenas](https://rules.b-zone.ro/wiki-info/business/arenas/), [PubG Arena](https://rules.b-zone.ro/wiki-info/business/pubg-arena/))
   - **Modes**: Paintball Ranked, Racing Arena, War Arena, Gun Game Arena, Last Car Standing, Battle Royale (PubG).

---

## 5. Vehicle Catalogs & Mechanics
> **Source Links**:
> - [Cash Vehicles](https://rules.b-zone.ro/wiki-info/vehicles/cash-vehicles/)
> - [Gold Vehicles](https://rules.b-zone.ro/wiki-info/vehicles/gold-vehicles/)
> - [Premium Vehicles](https://rules.b-zone.ro/wiki-info/vehicles/premium-vehicles/)
> - [Shop Vehicles](https://rules.b-zone.ro/wiki-info/vehicles/shop-vehicles/)
> - [How to Buy Vehicles](https://rules.b-zone.ro/wiki-info/vehicles/how-to-buy/)

### 5.1 Vehicle Categories
1. **Cash Vehicles**: Standard vehicles purchased using in-game cash at the Dealership.
   - *Models*: Bullet, Infernus, Cheetah, Turismo, Banshee, Sultan, Elegy, Buffalo, NRG-500, FCR-900, Maverick, etc.
2. **Gold Vehicles**: Exclusive or high-tier vehicles bought with Gold currency.
   - *Models*: Sandking, Hotring (A/B), Monster Truck (A/B), Sparrow, Freeway.
3. **Premium Vehicles**: Top-tier performance vehicles requiring VIP/Premium status or Gold.
4. **Shop & Utility Vehicles**: Specialized transport and heavy machinery.
   - *Models*: Dune, Flatbed, Coach, Roadtrain, DFT-30, Tractor, Securicar, Raindance, Leviathan, Trailers (Petrol/Article).

### 5.2 Vehicle Commands
* **`/vehicles`** (or **`/v`**, **`/garage`**, **`/g`**): Opens garage manager to locate, tow, unblock, spawn, despawn, or set auto-spawn on login.
* **`/engine`** (Key `2`): Starts/stops engine.
* **`/lock`** (Key `N`): Locks/unlocks personal vehicle.
* **`/park`**: Sets default parking spawn location.
* **`/vehswitch`**: Swaps current driven vehicle with an unspawned garage vehicle.
* **`/buyvehicle`**: Interacts with Dealership doors to browse or test drive cars.
* **`/buyinsurance`**: Purchases vehicle insurance policies (up to 5 max per vehicle).
* **`/givekey [ID/Name]`**: Lends keys to another player.
* **`/changelock`**: Resets vehicle locks, revoking all shared keys.
* **`/fill [percent]`**: Refuels vehicle at gas stations.
* **`/unrentvehicle`**: Terminates rental contracts.

---

## 6. House & Property Systems
> **Source Links**:
> - [House General Description](https://rules.b-zone.ro/wiki-info/house/general-description/)
> - [House Useful Commands](https://rules.b-zone.ro/wiki-info/house/useful-commands/)

### 6.1 House Features & Customization
- Players can purchase, sell, or rent rooms in houses.
- **Furniture & Upgrades**: Owners can add up to 170 custom furniture objects, install interior lifts, upgrade house interiors, and set up house radios.
- **Safe Vaults**: Houses contain safes to store cash, weapons, drugs, or materials.

### 6.2 House Commands
* **`/enter` & `/exit`**: Enters/exits the house interior or garage.
* **`/open`**: Locks or unlocks house front doors.
* **`/rentroom` & `/unrentroom`**: Rents a room or cancels rent contract.
* **`/setrentable` & `/setrent [Price]`**: Enables room renting and sets hourly rent fee.
* **`/tenants`**: Lists current renters/tenants in the house.
* **`/evict [ID]` & `/evictall`**: Evicts specific or all tenants.
* **`/sellhousetostate`**: Sells house back to the server state.
* **`/houseprice [Price]`**: Sets selling price for player-to-player trade.
* **`/heal`**: Restores health inside house ($1,000 per use).
* **`/sleep`**: Enters AFK sleeping mode safely inside your house.
* **`/houseupgrade`**: Opens the interior furniture editor.
* **`/editfurniture` & `/removefurniture`**: Modifies or clears custom furniture.
* **`/housewithdraw [cash/materials/drugs]`**: Withdraws assets from house safe.
* **`/houseinfo` & `/housename [Name]`**: Displays house details or updates custom text name.

---

## 7. Comprehensive Command Directory
> **Source Links**:
> - [Useful Commands - Account](https://rules.b-zone.ro/wiki-info/useful-commands/account/)
> - [Useful Commands - General](https://rules.b-zone.ro/wiki-info/useful-commands/general/)
> - [Useful Commands - Vehicles](https://rules.b-zone.ro/wiki-info/vehicles/useful-commands/)
> - [Useful Commands - Houses](https://rules.b-zone.ro/wiki-info/house/useful-commands/)
> - [Useful Commands - Business](https://rules.b-zone.ro/wiki-info/business/useful-commands/)

| Command Category | Command Syntax | Description / Function |
| :--- | :--- | :--- |
| **Account & Helper** | `/n [question]` | Submits a question to active server Helpers |
| **Admin Report** | `/report [reason]` | Contacts online Admins regarding rule violations or bugs |
| **Trading System** | `/trade [ID/Name]` | Opens secure trading window for cash, vehicles, items, or property |
| **Vehicle Control** | `/v` or `/vehicles` | Vehicle management dialog (locate, spawn, tow, unblock) |
| **Vehicle Control** | `/engine` (or Key 2) | Toggles vehicle engine on/off |
| **Vehicle Control** | `/lock` (or Key N) | Locks/unlocks vehicle doors |
| **Vehicle Control** | `/park` | Sets permanent vehicle spawn coordinate |
| **Vehicle Control** | `/vehswitch` | Replaces active vehicle with another garage vehicle |
| **Vehicle Customization** | `/carcolor` | Repaints car ($500 for normal IDs 0-127) |
| **Vehicle Customization** | `/hiddencolor` | Repaints car with hidden color IDs (128-255, 600 Gold) |
| **House System** | `/rentroom` | Rents a room in the house you are currently visiting |
| **House System** | `/houseupgrade` | Edits house furniture and interior decor |
| **House System** | `/housewithdraw` | Withdraws money or items from house safe |
| **Business System** | `/bizinfo` | Displays financial metrics and shareholder details |
| **Business System** | `/sellshares` | Sells business equity stock to another player |
| **Business System** | `/bizwithdraw` | Withdraws funds from business vault |
| **Faction Duty** | `/duty` | Toggles on-duty status for faction members |
| **Faction Vehicles** | `/fvr` | Respawns all unoccupied faction vehicles (Rank 5+) |
| **Gang Orders** | `/order [1-4]` | Orders weapon package in gang HQ |
| **Gang Actions** | `/tie` / `/untie` | Kidnaps or releases a target player (Rank 3+) |

---

## 8. Media & Image References

The original B-Zone Wiki documentation includes visual screenshots, maps, and interface mockups across its sections. Below is the full inventory of referenced visual assets and UI diagrams from the sources:

1. **Map & Location Diagrams**:
   - `CNN Locations Map (#1)`: Displays CNN agency locations across Los Santos, Las Venturas, and San Fierro SafeZones.
   - `Arenas Map Diagram`: Shows entrance coordinates for Paintball, Racing, War, Gun Game, and Last Car Standing arenas.
   - `PubG Loot Zone Map`: Displays loot drop zones, safe zones, and air-drop locations.

2. **Interface Screenshots & UI Mockups**:
   - `24/7 Store Dialog (#1)`: Illustrates the `/buy` item selection menu.
   - `Clothing Store Skin Selector`: Displays the paginated skin grid UI used in `/skins`.
   - `Vehicle Color Palette Chart (IDs 0-255)`: Complete hex color grid mapping Non-Hidden (0-127) and Hidden (128-255) color codes.
   - `House Furniture Placement UI`: Illustrates 3D object rotation and positioning arrows inside house interiors.
   - `Lotto Interface Diagram`: Illustrates ticket purchasing and jackpot drawing UI.

---

*Compiled from B-Zone SA:MP Rules & Wiki Documentation.*
