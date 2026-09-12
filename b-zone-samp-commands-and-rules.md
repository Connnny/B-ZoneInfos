# B-Zone SA:MP Essential Gameplay Commands and Server Rules

This document provides a comprehensive, source-grounded compilation of gameplay commands, formulas, mechanics, and server rules across all 11 categories available on the B-Zone SA:MP RPG server.

---

## 1. Account Commands

The Account category commands focus strictly on controlling and managing your own account.

* **`/stats`**: Displays all current account information. The details provided in-game match the information available directly on your website account profile. [4]
* **`/buylevel`**: Allows players to advance to a new level, provided they possess the required Respect Points (RP). [4]
  * **Respect Points & Cost Formulas**:
    * **Level Price Formula**: $\text{Price} = \text{Level} \times 250$ [5]
    * **Required RP Formula**: $\text{Required RP} = (\text{Level} \times 4) - 2$ [5]
  * **RP Loss Rule**: Any excess Respect Points beyond the required amount will be **lost** upon buying the level, **except** for players with an active **Premium Account**, who retain extra RP. [4, 5]
  * **Level Up Reward**: Each level advancement awards **20 Gold** as a reward. [4]
* **`/changepass`**: Initiates account password change. Opens a dialog requiring your current password before prompting for the new password. If forgotten, use the website's password recovery function. [5, 6]
* **`/changeemail`**: Displays information via dialog box regarding account email changes. If unvalidated, emails can be changed directly in-game. [6, 7]
* **`/arenas`**: Checks whether specific server arenas are currently occupied or available. [7]

---

## 2. Bank Commands

The server features 3 banks, located in **Los Santos**, **Las Venturas**, and **San Fierro**. Most banking commands must be used inside one of these 3 banks (except ATM commands). [10]

* **`/balance`**: Displays the exact amount of money in your bank account. Must be inside a bank. [10]
* **`/withdraw [amount]`**: Withdraws money from your bank account to your cash on hand (e.g., `/withdraw 5000` receives $5,000 in hand). Must be inside a bank. [11]
* **`/deposit [amount]`**: Deposits money from your cash on hand into your bank account (e.g., `/deposit 5000`). Must be inside a bank. [11, 12]
* **`/transfer [PlayerID/PlayerName] [amount]`**: Transfers money from your bank account directly into another player's bank account (e.g., `/transfer 13 5000` or `/transfer Adi007 5000`). [12]
  * **Requirements & Taxes**: Requires a minimum of **Level 3**. A **1% transfer tax** is applied ($	ext{Tax} = rac{1}{100} 	imes 	ext{transferred amount}$). Event organizers are exempt from location restrictions. [12, 13]
* **`/atmwithdraw` | `/atm`**: Used directly in front of an ATM to open an interactive ATM UI to withdraw cash to hand. If closed accidentally, these commands reopen the interface. [13]

---

## 3. Business Commands

Business commands control business management, income, shares, and customer interaction. The in-game command `/businesshelp` lists all business control commands. [16]

* **`/bizradio`**: Allows business owners to stream a radio station or YouTube URL inside their business. Non-owners can use this command inside a business to toggle audio stream playback on or off. [16, 17]
* **`/enter`** (or press key **F**): Used near the door entrance to enter a business. [17]
* **`/exit`** (or press key **F**): Used near the exit door to exit a business. [17]
* **`/sellshares`**: Sells a business share back to the state. Collects whatever funds are currently in the business safe. [18]
* **`/shareholders`**: Displays the shareholders of a specific business. [18]
* **`/bizwithdraw [amount]`**: Withdraws money generated from entry fees out of the business safe. Using `/bizwithdraw` without specifying an amount displays the current safe balance. Must be inside near the door or outside near the entrance. [18, 19]
* **`/bizinfo`**: Available anywhere to business owners. Displays:
  * Business level
  * Entry fee value
  * Total earnings
  * Minimum sale value
  * Share percentage owned
  * Business production based on shares [20]
* **`/bizstatus`**: Displays information about a business's safe balance and minimum sale price. [20]
* **`/mybiz`**: For owners of rental businesses (cars, bikes, airplanes). Manages owned vehicles and allows buying new ones up to the 10-vehicle server limit. [20]
* **`/arenas`**: Shows whether server RPG arenas are free or occupied. [20]
* **`/help` -> Bizuri**: Provides in-game documentation of business features. [20]

---

## 4. Chat Commands

Chat commands enable socialization and communication across various server channels and ranges. [23]

* **`/ignore`**: Displays your ignored players list. Selecting *"Add player..."* blocks a player by ID/Name from sending whispers (`/w`), SMS (`/sms`), or calling (`/call`). Selecting a player removes them from ignore. [23]
* **`/say [message]`**: Default local chat. Visible only to players whose names/nametags are visible to you. Can be typed directly into the console. [24]
* **`/s [message]`**: Shouts a message over a wider range than standard chat. [24]
* **`/w [PlayerID/PlayerName] [message]`**: Sends a private whisper to a specific player. Requires **Level 3+**. [24, 25]
* **`/b [message]`**: Out-of-Character (OOC) local chat. Displays message inside round double parentheses `(( message ))` at normal chat range. [25]
* **`/f [message]`**: Faction chat for all non-department factions (Gangs, Peaceful, Mixt). [25]
* **`/r [message]`**: Radio chat exclusively for police departments (LSPD, SFPD, LVPD, National Guard, FBI). [26]
* **`/c [message]`**: Clan chat. [26]
* **`/ac [message]`**: Alliance chat. [26, 27]
* **`/cw [message]`**: Car Whisper chat. Sends messages only to occupants inside the same vehicle. [27]
* **`/wt [message]`**: Walkie-Talkie frequency chat. Requires a Walkie-Talkie (bought at 24/7), a set frequency (`/setfreq`), and **Level 5+**. [27]
* **`/sms [PlayerID/PlayerName] [message]`**: Sends a text message to a mobile phone. [28]
* **`/call [PlayerID/PlayerName]`**: Initiates a phone call to a player. [28]
* **`/lc [message]`**: Faction Leader and Admin 4+ private chat channel. [28, 29]
* **`/al [message]`**: Admin-to-Player chat channel opened when an admin accepts your `/report`. [29]
* **`/hl [message]`**: Helper-to-Player chat channel opened when a helper accepts your `/helpme`. [29]
* **`/e [message]`**: Event Broadcast chat. Used by event organizers to broadcast messages to all players on the server. [29, 30]
* **`/ec [message]`**: Event Staff chat. Communicates between event organizers and event assistants. [30]
* **`/d [message]`**: Department chat. Transmits messages across all police departments (LSPD, SFPD, LVPD, NG, FBI). [30]
* **`/tx [message]`**: Taxi company cross-chat between LS, SF, and LV Taxi companies. [30, 31]
* **`/sx [message]`**: School Instructors cross-chat between LS, SF, and LV School Instructors. [31]
* **`/gc [message]`**: Gang Alliance chat used by mafia members during alliance wars. [31]
* **`/rc [message]`**: Rob Team chat for players executing a group robbery. [31]

---

## 5. General Commands

* **`/id [PlayerID/PlayerName]`**: Displays player details: ID, Name, Ping, real-time FPS, Level, Status (**AFK** | **SLEEP** | **AFK & SLEEP**), Faction Name, Special Skin type (Diamond/Onyx), and Skin ID. [34, 35]
* **`/pay [PlayerID/PlayerName] [amount]`**: Pays cash in hand to a nearby player.
  * Players under Level 3 can send a maximum of **$10** per transaction.
  * Level 3+ players can send up to **$10,000** per transaction with a few seconds cooldown. [35]
* **`/buy`**: Purchases items inside a 24/7 store. [36]
* **`/givekey [PlayerID/PlayerName]`**: Hands over spare keys of your current vehicle to another player (retained until disconnect or `/throw`). [36]
* **`/drink [DrinkName]`**: Buys drinks inside bars and clubs. [36]
* **`/turfs`**: Toggles mafia turf territory overlays on the minimap and main map. [36, 37]
* **`/licenses`**: Displays your current licenses and remaining validity periods. [37]
* **`/requestlicenses [PlayerID/PlayerName]`**: Requests to view another player's licenses. [37]
* **`/skills`**: Shows job skill levels and points needed to upgrade. [38]
* **`/sleep`**: Enters/exits AFK mode (must be inside a house or safe area). [38]
* **`/lotto`**: Places lotto tickets. [38]
* **`/cigarettes`**: Displays held cigarettes and lighter status. [38]
* **`/spawnchange`**: Changes spawn location choices (House owned/rented, Default spawn, Faction HQ, or City spawn locations for civilians). Disabled if wanted by police. [38, 39]
* **`/eject [PlayerID/PlayerName]`**: Driver command to forcibly eject a passenger from your vehicle. [39]
* **`/rob`**: Initiates a bank robbery (group of 4-8 players) or selecting "Rob Solo" to rob a business/house alone. [39]
* **`/robhelp`**: Provides robbery system guidance. [39]
* **`/service [Taxi/Medic/Mechanic/Lawyer/Towtruck]`**: Sends a location-tagged service request to active job providers/faction members. [39, 40]
* **`/report`**: Sends a report ticket to online admins. Allowed maximum 1 un-opened report. Auto-closes after 5 minutes if unhandled. Strictly for severe issues/cheaters. [40, 41]
* **`/helpme` | `/n [text]`**: Sends a question to on-duty helpers. Broadcasts to players levels 1-40 or opens a private chat (`/hl`). Restricted to server help/questions. [41, 42]
* **`/speedlimit [0 or 90-230]`**: Sets maximum vehicle speed limit between 90–230 km/h (0 disables restriction). [42]
* **`/accept [Service]`**: Accepts incoming services/offers (Drugs, Repair, Job, Live, Refill, Ticket, Paper, Licenses, Escape, Trade, Taxi, Medic, Lawyer, Mechanic, Free, Gun, Materials, Needlicense, Lawyercall, Lesson, Rob, Dice, Alliance, Eventhelper, Pubg, Friend, Bunker). [42, 43]
* **`/cancel [Service]`**: Cancels/refuses an offered service. [44]
* **`/usedrugs [Marijuana/Cocaine/Ecstasy/Meth]`**: Consumes owned drugs. [44]
* **`/fill [percentage]`**: Fills vehicle fuel tank by specified percentage at a gas station. [44]
* **`/fillgascan`**: Fills a portable fuel gas can. [44]
* **`/needlicense`**: Sends a license request to all active School Instructors. [44]
* **`/buyweaplic`**: Buys a Weapon License directly from an NPC at School Instructors HQ (Level 5+ required). Auto-unlocked if no instructors respond within 5 minutes.
  * **Price Structure**:
    * **Levels 5–9**: **$5,000**
    * **Levels 10–49**: **$10,000**
    * **Level 50+**: **$20,000** [45]
* **`/lawyers`**: Displays active lawyers and accept points; clicking calls them. [46]
* **`/animlist`**: Displays all available server animations. [46]
* **`/carradio`** (or key **R**): Driver command to pick and play car radio streams. [46]
* **`/mp3`**: Plays radio anywhere on foot (requires MP3 Player item from 24/7 & Premium Account). [47]
* **`/throw [Keys/Guns/Drugs/Materials]`**: Drops held items on the ground with a roleplay chat message (cooldown of ~2 mins if warned by police). [47]
* **`/trade`**: Sends a secure trade invitation to another player. [48]
* **`/givecigarette [PlayerID/PlayerName]`**: Gives a cigarette to another player. [48]
* **`/tog`**: Toggles settings/chats/logs: News, Newbie Chat, Advertisements, Whisper Chat, Faction Chat, Clan Chat, Damage 'ding', HUD, Nametags, Event Chat, Spray Messages, Admin Punishments, Confidential Messages, Neons, Surfing. [48]
* **`/clanleaders`**: Displays online clan leaders. [49]
* **`/fps`**: Toggles real-time FPS display on screen (disabled during `/drink`). [49]
* **`/cheater [ID/Player] [Hack]`**: Sends a cheat report directly to admins. [49]
* **`/referrals`**: Displays online players registered under your Referral ID. [50]
* **`/clanHQs`**: Displays clan HQs and IDs for GPS navigation (`/gps`). [50]
* **`/safeboxes`**: Displays owned safeboxes, map locations, and storage capacities. [50]
* **`/opensafe`**: Opens a nearby safebox to store/extract/throw weapons, drugs, or materials. [51]
* **`/clearfp`**: Uses a ClearFP perk to reset Faction Punish points to 0. [51]
* **`/goldaward`**: Displays top 15 players with most real played hours (excluding sleep). [52]
* **`/premiu`**: Displays Chest System daily tier progress and real hours played. [52]
* **`/surrender`**: Surrenders in Jail if surrender rights exist (wait 3 minutes for police arrival; auto-arrests if no police are online). [52]

---

## 6. Houses Commands

Houses mimic real RPG living. Permissions regulate owners, tenants, and visitors. [55, 56]

* **Permissions Overview**:
  * `/tenants` & `/sleep`: Only owners and tenants. [56]
  * `/open`, `/setrentable`, `/setrent`, `/evict`, `/evictall`, `/sellhousetostate`, `/houseprice`, `/housewithdraw`, `/houseupgrade`: Owners only. [56]
  * `/heal`, `/enter`, `/exit`: Open to all if house is unlocked; restricted to owner & tenants if locked. [56]
  * Furniture becomes invisible and editing is disabled if owner has Wanted level. [56]
* **`/enter`** (or press **F**): Enters the house when close to the door. [57]
* **`/exit`** (or press **F**): Exits the house. [57]
* **`/open`**: Locks/unlocks the house door. [58]
* **`/setrentable [Yes/No]`**: Enables or disables tenant renting. [58]
* **`/setrent [price]`**: Sets tenant rent price per PayDay (**$0 – $1,000**). [59]
* **`/tenants`**: Displays online tenants list. [59]
* **`/evict [PlayerID/Name]`**: Evicts a specific tenant. [60]
* **`/evictall`**: Evicts all current tenants. [60]
* **`/sellhousetostate`**: Sells house to state and collects safe balance. [61]
* **`/houseprice [price]`**: Sets offline/online sale price.
  * **Minimum Price Formula**: $\text{Min Price} = \text{House Level} \times 1,000$ [61]
  * **Maximum Price Formula**: $\text{Max Price} = \text{House Level} \times 200,000$ [62]
* **`/heal`**: Restores HP to 100 inside an owned or rented house (10 mins rental required). Grants 100 Armour if player is a department member and house has Armour upgrade. [62]
* **`/sleep`**: Roleplay sleep mode. Grants level RP at PayDay (played hours do not increase). Protected from damage. Disabled near door, if wanted, or within 60s of a crime. [63, 64]
* **`/houseupgrade`**: Renovation menu for Heal, Armour, radio, and furniture ($1,000 per object, max 170 custom objects). Lost upon house sale. [64, 65]
* **`/removefurniture`**: Clears custom added furniture (no refund). [65]
* **`/editfurniture`**: Edits or removes custom furniture positions. [65]
* **`/defaultfurniture`**: Shows or hides default initial house objects. [66]
* **`/housewithdraw [amount]`**: Withdraws money accumulated from rent in the house safe. [66, 67]
* **`/houseinfo`**: Displays level, online tenants, rent status/price, lock status, min sale value, state tax value ($	ext{State Tax} = 	ext{House Level} 	imes 100$), and house name. [68]
* **`/houseradio`**: Streams radio or YouTube audio inside the house. [69]
* **`/housename [name]`**: Sets custom visible text name for the house exterior. [70]
* **`/lift`**: Teleports players between house zones (roof, parking). Requires owner/tenant status. Bought via ticket support starting at 2000 Gold (ordered within last 7 days) for 1 floor. [70]

---

## 7. Jobs Commands

Jobs provide legal and illegal income streams across server cities. [73]

* **`/jobs`**: Opens interactive job catalog listing Job Name, City, Type (Legal/Illegal), and Minimum Required Level. [73]
* **`/jobhelp`**: Shows specific job commands for your current employment. [74]
* **`/getjob`**: Joins a job while standing near the job marker `(i)`. [74]
* **`/work`**: Begins job tasks (applies to all jobs except Detective, Car Mechanic, and Lawyer). [74]
* **`/skills`**: Shows job skill progression and points needed for next skill rank. [75]
* **`/switchjob`**: Switches between primary job and faction auxiliary job:
  * **Departments & Hitmen Agency**: Auxiliary job = **Detective**
  * **Gangs**: Auxiliary job = **Arms Dealer**
  * **Peaceful Factions (TTC, Paramedics, News Reporters, Taxi, Instructors)**: Auxiliary job = **Car Mechanic** [75, 76]
* **`/jobskillup`**: Uses JobSkill perks to boost job skill rank (requires valid perk and job skill system). [76]

---

## 8. Locations Commands

* **`/locations` | `/gps`**: Main navigation command opening a menu with 10 primary categories: [79]
  1. **Locatii importante** (Banks, CNN, Gun Shops, DMV, City Hall, etc.) [80]
  2. **HQ-uri Factiuni** (69pm, Hitmen, TTC, National Guard, etc.) [80]
  3. **Case** (Enter House ID) [80]
  4. **Biz-uri** (Enter Business ID) [81]
  5. **HQ-uri Clanuri** (Select Clan HQ) [81]
  6. **ATM-uri** (List of all ATMs) [81]
  7. **24/7-uri** (List of convenience stores) [82]
  8. **Benzinarii** (List of gas stations) [82]
  9. **Magazine de haine** (List of clothing stores) [82]
  10. **Magazine de mancare** (List of fast-food & restaurant locations) [82]

---

## 9. Other Commands & Sub-Menus

This section lists sub-command suites unlocked by core parent commands. [86]

### Cellphone Commands (`/cellphonehelp`)
* **`/p(ickup)`**: Answers incoming phone calls. [86]
* **`/h(angup)`**: Ends active phone calls. [86]
* **`/call [ID/Name]`**: Calls a player. [86, 87]
* **`/turn [on/off]`**: Powers mobile phone on or off. [87]
* **`/speaker`**: Toggles speakerphone to allow nearby players to see conversation messages. [87]
* **`/sms [ID/Name] [message]`**: Sends text messages. [87, 88]

### House Renting Commands (`/renthelp`)
* **`/enter`** & **`/exit`**: Enter/exit rented house. [88]
* **`/tenants`**: Views online co-tenants. [89]
* **`/unrentroom`**: Cancels house room lease. [89]

### Vehicle Renting Commands (`/rentcarhelp`)
* **`/unrentvehicle`**: Relinquishes rented vehicle and keys. [89]
* **`/locaterentedcar`**: Places a map marker on your rented vehicle location. [90]
* **`/vehicles`**: Opens vehicle list. [90]
* **`/givekey`**: Lends keys. [90]
* **`/changelock`**: Changes locks. [91]
* **`/park`**: Parks rented vehicle (must be undamaged). [91]

### Event Commands (`/eventhelp`)
* **`/event`**: Shows current event title, prize, type, location, organizer, minimum level, and max participants. [92]
* **`/requestevent`**: Submits event creation request to Level 2+ Helpers and Admins. [92]
* **`/join`**: Joins an active event. [93]
* **`/leaveevent`**: Exits an active event. [93]

### Faction Leader Commands (`/leaderhelp`)
* **`/members`**: Opens interactive faction members list, Faction Applications, and Faction Tests edit menus. [93]
* **`/factiontest`**: Rank 4+ testers initiate a test for an applicant. [94]
* **`/tog`**: Disables `/f` chat for standard members (only Leader & Admin 4+ can chat). [94]
* **`/fvr`**: Respawns all unoccupied faction vehicles (Rank 5+ required). [94]
* **`/lc`**: Opens leader-only chat. [94]
* **`/fwithdraw [amount]`**: Checks or withdraws money from faction safe. [95]
* **`/fmotd [message]`**: Reads or sets the Message of the Day. [95, 96]
* **`/fget` & `/fput`**: Puts/withdraws drugs or materials in faction HQ (`/fgetdrugs`, `/fgetmaterials`). [96]
* **`/setgc`**: Sets minimum rank required to send `/gc` alliance war messages. [96]
* **`/vehrank`**: Sets minimum rank requirement for faction vehicles (Rank 6+ required). [96]

### Clan Commands (`/clanhelp`)
* **`/claninvite`**: Invites a player (Rank 6+ requires an accepted application). [97]
* **`/c`**: Clan chat. [97]
* **`/clanmembers`**: Lists online clan members. [97]
* **`/clanresign`**: Leaves the clan. [98]
* **`/setclanowner`**: Transfers clan ownership. [98]
* **`/spray`**: Sprays a clan turf in clan colors. [98]
* **`/clanxp`**: Displays total clan XP progress. [98]
* **`/clanzones` | `/clanturfs`**: Lists/shows clan turfs. [98]
* **`/clancolor`**: Sets clan color (leader only). [99]
* **`/clangoldwithdraw`**: Withdraws gold from clan safe (leader only). [99]
* **`/cmotd`**: Sets clan motto. [99]
* **`/clanrename`**: Renames clan rank titles. [99]
* **`/clanduty`**: Toggles clan duty. [99]
* **`/clanleaders`**: Displays online clan leaders. [99]
* **`/ctalkpower`**: Restricts `/c` chat usage for specific ranks (Rank 5+ required). [100]
* **`/topclan`**: Displays clan leaderboard by turf control. [100]
* **`/clanwithdraw` & `/clandeposit`**: Withdraws/deposits money into clan safe (Rank 6+ for withdraw). [100]
* **`/clanput` & `/clanget`**: Deposits/withdraws clan materials/drugs. [100]
* **`/cwithdrawpower`**: Sets rank permissions for clan withdrawals (leader only). [100]
* **`/claimhq`**, **`/leavehq`**, **`/interiorhq`**: Claims, abandons, or sets interior for Clan HQ. [101]
* **`/claninfo`**: Shows clan administrative info (leader only). [101]
* **`/cvs` & `/cvr`**: Spawns clan vehicles (`/cvs`) or respawns all clan vehicles (`/cvr`, Rank 5+ required). [101]
* **`/buyclanvehicle`**: Purchases clan vehicles. [102]
* **`/clanwar`**, **`/guns`**, **`/leavewar`**: Manages clan war roster, weapon loadout selection, and exiting clan wars. [102]

---

## 10. Premium Commands

Premium features use Gold (real currency currency) in the virtual shop. [105]

* **`/shop`**: Opens the virtual server store showing products and Gold costs. Items color green if affordable, red if insufficient Gold. [105, 106]
* **`/hiddencolor`**: Used near the CarColor business to teleport vehicle into special hidden color selection menu using Gold. [106]

---

## 11. Vehicles Commands

Controls personal vehicle operations, spawning, tuning, insurance, and management. [109]

* **`/vehicles` | `/v` | `/garage` | `/g`**: Vehicle control center displaying slot ID, vehicle name, status (available/occupied/hidden), and despawn timer. [109, 110]
  * **Spawn Limits**: Premium Account = up to **8 vehicles** simultaneously; Non-Premium = up to **2 vehicles**. Standard garage slots = 4 (expandable via Shop). [110, 117]
  * **Control Options**:
    * **Informatii**: Details model, price, status, colors, KM, age, insurance count/cost, ID, VIP status. [111]
    * **Localizeaza**: Sets a map checkpoint. [111]
    * **Remorcheaza**: Respawns vehicle to parked spot ($200 fee). [111]
    * **Spawnează/Despawnează**: Toggles vehicle presence on server. [111]
    * **Deblochează**: Unstucks vehicle parked in wall/water to safe spot. [111, 112]
    * **VIP Options**: Convert to VIP Vehicle, Edit VIP Text, Edit VIP Color, Edit VIP Position. [112, 113]
    * **Vehicle Age**: Add 30 Days (400 Gold), 180 Days (2000 Gold), or 365 Days (4000 Gold). [113]
    * **3D Label**: Adds 3D text label (400 Gold / 30 days). [114]
    * **Favorites**: Add/Remove from favorite vehicles list. [114]
    * **Plate & Color**: Change Vehicle Plate (vulgar text penalized), Change Vehicle Color (requires **Car Mechanic Skill 6+**; redirects money to biz). [115]
    * **Tuning (Mechanic Skill 7+)**: Tune vehicle without going to a tuning shop. [116]
      * **Skill 7**: Front/Rear Bumper, Sideskirts, Hydraulics (**5% discount**). [116]
      * **Skill 8**: Roof, Front Bullbar, Hood, Lamps, Vents (**10% discount**). [116]
      * **Skill 9**: Spoiler, Wheels, Exhaust (**15% discount**). [116]
      * **Skill 10**: NOS, Paintjob, Neons (**20% discount**). [116]
    * **Vinde**: Sells vehicle to Dealership (near Dealership; tutorial car requires Level 5+). [116, 122]
    * **Spawnare la conectare**: Sets auto-spawn preferences on login. [116]
    * **Cumpara asigurare**: Purchases insurance (max 5 insurances per vehicle). [116, 119]
    * **Adauga in Bazar**: Lists vehicle in Auto Market. [117]
* **`/engine`** (or press key **2**): Starts or stops vehicle engine. [117]
* **`/lock`** (or press key **N**): Locks or unlocks vehicle doors from nearby. [117]
* **`/park`**: Sets vehicle spawn location when driving. [118]
* **`/vehswitch`**: Switches current vehicle with an un-spawned garage vehicle. [118]
* **`/carcolor`**: Teleports vehicle into CarColor garage near business. [118]
* **`/buyinsurance`**: Purchases vehicle insurance policy (max 5). Uninsured broken vehicles cannot be driven until repaired. [119]
* **`/buyvehicle`**: Teleports to Dealership garage for buying, previewing, or test-driving vehicles. [119]
* **`/givekey [PlayerID/Name]`**: Lends keys allowing `/lock` access. [120]
* **`/changelock`**: Changes locks to revoke key access. [120]
* **`/throw`**: Drops held items or rented vehicle keys. [121]
* **`/swapcolors`**: Swaps primary and secondary vehicle colors. [121]
* **`/lights`**: Toggles headlights without triggering NOS. [122]
