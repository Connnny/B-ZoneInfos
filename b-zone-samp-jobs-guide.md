# Ghid Complet Joburi - B-Zone SA:MP Rules

Acest document conține sinteza completă a informațiilor din toate sursele oficiale B-Zone SA:MP privind sistemele de joburi, regulile, comenzile utile și specificațiile fiecărei meserii.

---

## Cuprins
1. [Comenzi Utile Generale](#1-comenzi-utile-generale)
2. [Sisteme Speciale de Joburi](#2-sisteme-speciale-de-joburi)
   - [Jobul Zilei (Daily Job)](#jobul-zilei-daily-job)
   - [Job Clash](#job-clash)
3. [Ghid Detaliat al Joburilor](#3-ghid-detaliat-al-joburilor)
   - [Archeologist (Arheolog)](#archeologist-arheolog)
   - [Arms Dealer (Traficant de Arme)](#arms-dealer-traficant-de-arme)
   - [Bus Driver (Șofer de Autobuz)](#bus-driver-șofer-de-autobuz)
   - [Car Jacker (Hoț de Mașini)](#car-jacker-hoț-de-mașini)
   - [Car Mechanic (Mecanic Auto)](#car-mechanic-mecanic-auto)
   - [Chemist (Chimist)](#chemist-chimist)
   - [Craftsman (Meșter)](#craftsman-meșter)
   - [Detective (Detectiv)](#detective-detectiv)
   - [Drugs Dealer (Traficant de Droguri)](#drugs-dealer-traficant-de-droguri)
   - [Electrician](#electrician)
   - [Farmer (Fermier)](#farmer-fermier)
   - [Firefighter (Pompier)](#firefighter-pompier)
   - [Fisherman (Pescar)](#fisherman-pescar)
   - [Garbage Man (Gunoier)](#garbage-man-gunoier)
   - [Lawyer (Avocat)](#lawyer-avocat)
   - [Lumberjack (Tăietor de Lemne)](#lumberjack-tăietor-de-lemne)
   - [Miner](#miner)
   - [Pocket Thief (Hoț de Buzunare)](#pocket-thief-hoț-de-buzunare)
   - [Quarry Worker (Muncitor la Carieră)](#quarry-worker-muncitor-la-carieră)
   - [Transporter (Curier)](#transporter-curier)
   - [Trucker (Tirist)](#trucker-tirist)

---

## 1. Comenzi Utile Generale

* **/jobs** – Deschide o listă cu toate joburile disponibile, indicând orașul, tipul (legal/ilegal) și nivelul minim necesar.
* **/jobhelp** – Afișează comanda/comenzile specifice jobului curent detinut.
* **/getjob** – Permite angajarea la un job dacă jucătorul îndeplinește nivelul minim și se află la marcajul special (i).
* **/work** – Comandă principală pentru începerea muncii la majoritatea joburilor.
* **/skills** – Afișează nivelul de skill deținut la fiecare job.
* **/switchjob** – Schimbă între jobul principal și cel auxiliar (disponibil membrilor din facțiuni/mafii/departamente).
  - Departamente & Hitmen Agency: job auxiliar *Detective*.
  - Ganguri: job auxiliar *Arms Dealer*.
  - TTC, Paramedics, News Reporters, Taxi, School Instructors: job auxiliar *Car Mechanic*.
* **/jobskillup** – Crește skill-ul curent la job folosind gratuități de tip JobSkill.

---

## 2. Sisteme Speciale de Joburi

### Jobul Zilei (Daily Job)
* Sistem ce dublează câștigurile de bază la un job ales aleatoriu la ora 00:00.
* La câștigul dublu se adaugă bonusul de 50% pentru Cont Premium și alte bonusuri active.
* Joburi excluse din sistem: Pocket Thief, Detective, Lawyer, Farmer, Bus Driver, Craftsman.

### Job Clash
* Competiție zilnică în care jucătorii concurează completând curse de succes la un job Clash activ.
* Comandă clasament: **/jobclash**.
* Recompense la miezul nopții:
  - Locul 1: $200,000
  - Locul 2: $100,000
  - Locul 3: $50,000
* Joburi eligibile: Transporter, Drugs Dealer, Car Jacker, Car Mechanic, Arms Dealer, Archeologist, Electrician, Quarry Worker, Lumberjack, Miner, Garbage Man, Fisherman, Trucker, Chemist, Firefighter.

---

## 3. Ghid Detaliat al Joburilor

### Archeologist (Arheolog)
* **Tip:** Legal | **Nivel minim:** 3 | **Locație:** Las Venturas (Lil' Probe Inn, lângă HQ National Guard) / San Fierro
* **Descriere:** Constă în localizarea artefactelor, curățarea/conservarea lor prin procedură specifică și vânzarea lor la Negustorul Egiptean.
* **Detalii cheie:**
  - Puteți deține maxim 10 artefacte simultan.
  - Se poate lucra cu wanted (cazier).
  - Timp de localizare: 19 secunde (Skill 1) scăzând până la 10 secunde (Skill 10).
  - Limită încercări procedură: egală cu nivelul de skill (1-10).
  - Șansă Fragment Skin: 1% la Skill 8, 2% la Skill 9, 3% la Skill 10.
  - În San Fierro există 50% șansă ca artefactul să primească upgrade la nivelul următor.
* **Valoare artefacte (bază):**
  - Românesc ($350, 1 pct skill), Moldovenesc ($500, 1 pct), Egiptean ($650, 1 pct), Rusesc ($800, 1 pct), Ucrainean ($950, 2 pct), Tunisian ($1,100, 2 pct), Grecesc ($1,250, 2 pct), Italian ($1,400, 2 pct), Spaniol ($1,550, 3 pct), Chinezesc ($1,700, 3 pct).
  - Cont Premium adaugă +50% la valoarea de bază.
* **Avansare Skill:** Skill 1->2 (50 pct) ... Skill 9->10 (3000 pct, total 11000 pct).

---

### Arms Dealer (Traficant de Arme)
* **Tip:** Ilegal (la cantități mari) | **Sediul:** Estul orașului Los Santos
* **Descriere:** Cumpărarea de materiale de la depozitele din LS, LV, SF (10 mat = $1) și transportarea lor (/work).
* **Capacitate materiale stocate:**
  - Skill 1: 100.000 | Skill 2: 200.000 | Skill 3: 300.000 | Skill 4: 400.000 | Skill 5: 2.147.483.640.
* **Nivel Wanted la /work:**
  - Skill 1-2: Fără wanted | Skill 3-4: Wanted +1 | Skill 5: Wanted +3 (excepție dacă dețineți licență de materiale).
* **Vehicule:**
  - Skill 1-2: Benson (123 km/h) | Skill 3-4: Berkley's RC Van (136 km/h) | Skill 5: Orice vehicul personal.
* **Creare / Vânzare arme (/creategun, /sellgun):**
  - La Skill 5 puteți crea arme cu /creategun.
  - Consum materiale la Skill 5: SD Pistol (400), Deagle (700), Shotgun (1000), MP5 (2000), AK47/M4 (5000), Rifle (6000).
* **Comenzi:** `/work`, `/getmaterials`, `/sellmaterials`, `/creategun`, `/sellgun`.

---

### Bus Driver (Șofer de Autobuz)
* **Tip:** Legal | **Nivel minim:** 1 | **Locație:** Los Santos și San Fierro
* **Vehicul:** Autobuz (Bus, 130 km/h)
* **Mecanică & Câștiguri:**
  - Oprire în stații, fiecare stație oferă între $12 și $16.
  - Puteți seta tarif pasageri între $1 și $5 folosind `/fare`.
  - Misiunea se pierde dacă părăsiți autobuzul mai mult de 20 secunde.

---

### Car Jacker (Hoț de Mașini)
* **Tip:** Ilegal | **Nivel minim:** Necesită permis de conducere
* **Mecanică:** Furarea vehiculelor și livrarea lor la unul din cele 3 puncte din fiecare oraș. Cooldown de 5 minute între livrări.
* **Vehicule furate pe skill:**
  - Skill 1: Vehicule publice neîncuiate ($978)
  - Skill 2: Vehicule personale descuiate ($1,070)
  - Skill 3: Vehicule de gang ($1,200)
  - Skill 4: Vehicule personale încuiate cu `/picklock` ($1,380) -> oferă Wanted 1
  - Skill 5: Vehicule ale departamentelor de poliție ($1,659) -> oferă Wanted 3 fără drept de predare la `/work`.
* **Progresie curse:** Skill 1->2 (60 mașini) ... Skill 4->5 (240 mașini, total 480).

---

### Car Mechanic (Mecanic Auto)
* **Tip:** Legal | **Locație:** Nordul orașului Las Venturas
* **Mecanică & Minigame-uri:**
  - Completați minigame-uri la `/work`: Tow The Car, Adjust the Oil Level, Mount the Components.
  - Oferă `/repair` și `/refill` folosind kituri specifice (cumpărate de la membri TTC sau NPC).
* **Perk-uri Skill Înalt:**
  - **Skill 6:** `/carcolor` permanent direct la vehicul.
  - **Skill 7-10:** Puteți tuna vehiculul fără biz tuning, cu discount-uri (Skill 7: 5%, Skill 8: 10%, Skill 9: 15%, Skill 10: 20%).
* **Vehicule job:** Skill 1-2 (Utility Van), Skill 3-4 (Rumpo), Skill 5-6 (Bobcat), Skill 7-8 (Burrito), Skill 9-10 (TowTruck).

---

### Chemist (Chimist)
* **Tip:** Legal | **Nivel minim:** 1 | **Locație:** Montgomery (Los Santos) | **Condiție:** Cazier curat (fără wanted)
* **Etape producție laborator:**
  1. Pornire 5 generatoare (minigame de reflexe/sprint).
  2. Prelucrare chimică la mese (Filtrarea Substanțelor / Controlul Temperaturii).
  3. Controlul nivelului fluidelor la consolă (toleranță +-1.0%).
  4. Presa hidraulică (compactare minim 10 pastile).
  5. Masa de ambalare (pliere cutie + sigilare scoci).
  6. Depozitare logistică (stivuire 6 cutii pe rafturi).
* **Câștig & Kituri:**
  - Plată bază: $1,872 - $1,972 (Skill 1) până la $2,509 - $2,609 (Skill 10).
  - Șanse primire kituri: Medical (30%-50%) și Dependență (10%-30%).
  - Kiturile se folosesc cu `/usekit` (+100 HP sau -30 dependență) și pot fi vândute cu `/trade`.

---

### Craftsman (Meșter)
* **Tip:** Legal | **Nivel minim:** 5 | **Locație:** King's, San Fierro (lângă Bank SF)
* **Mecanică:**
  - Închiriere unelte pe 24h de la biz #160: Dulgher ($1000), Drujbă ($500), Mască ($500).
  - Colectare materiale (necesită min. Skill 5 la alte joburi): Lemn (Lumberjack), Bumbac (Farmer - cactuși), Aur (Miner), Argint (Quarry Worker).
  - Creare obiecte cu `/craft` (Scaune: Sk 1-3, Mese: Sk 4-6, Accesorii: Sk 7-8, Uși: Sk 9-10).
  - Livrare la bizul *House Upgrade* și încasare cec.
* **Nivel 10 Aerian:** La Skill 10 livrarea se poate face aruncând pachetul din elicopter/avion.
* **Vehicule:** Skill 1-4 (Pony), Skill 5-10 (Vehicul personal / aeronave).

---

### Detective (Detectiv)
* **Tip:** Legal | **Nivel minim:** 3 | **Locație:** Primăria Los Santos
* **Comandă:** `/find [ID/Nume]`
* **Efect:** Setează un checkpoint roșu pe hartă arătând distanța și zona în care se află jucătorul căutat.
* **Durată Checkpoint & Cooldown:**
  - Skill 1: 30 sec | Skill 2: 60 sec | Skill 3: 100 sec | Skill 4: 180 sec | Skill 5: Permanent.
  - La Skill 1-4 comanda se folosește o dată la 2 minute.

---

### Drugs Dealer (Traficant de Droguri)
* **Tip:** Ilegal | **Punct angajare:** San Fierro (Crack House)
* **Mecanică:** Transport de droguri (`/work`).
  - Nivel Wanted la `/work`: Skill 1-2 (fără wanted), Skill 3-4 (Wanted +1), Skill 5 (Wanted +3).
* **Achiziție droguri proprii (`/getdrugs`):**
  - Skill 1-2: Nu pot cumpăra | Skill 3-4: Max 25g/oră | Skill 5: Max 50g/oră.
* **Vânzare:** `/selldrugs [ID/Nume] [cantitate] [preț]`.
* **Vehicule:** Skill 1-2 (Benson), Skill 3-4 (Berkley's RC Van), Skill 5 (Vehicul personal).

---

### Electrician
* **Tip:** Legal | **Nivel minim:** 3 | **Locație:** Ocean Docks, Los Santos
* **Mecanică:**
  - Deplasare cu vehiculul jobului la instalația electrică avariată.
  - Minigame-uri aleatorii: Tăierea firelor (toate skillurile), Conectarea firelor (Skill 4-10), Reglarea voltajului (Skill 8-10).
  - Număr taskuri per tură: 10 taskuri (Skill 1) scăzând la 3 taskuri (Skill 10).
* **Vehicule:** Skill 1-2 (Sadler), Skill 3-6 (Picador), Skill 7-10 (Rancher).

---

### Farmer (Fermier)
* **Tip:** Legal | **Locație:** Ferma LS, LV, SF
* **Mecanică:**
  - Închiriere parcelă publică ($1,000/24h) sau privată (200 Gold/24h).
  - Arat terenul cu tractorul, cumpărare semințe de la biz agricol (#158), plantare, udare și recoltare.
* **Plante disponibile per Skill:**
  - **Skill 1:** Usturoi (maturitate 15 min, profit $244/plantă)
  - **Skill 2:** Ferigă (maturitate 45 min, profit $563/plantă)
  - **Skill 3:** Trestie (maturitate 2h, profit $1,050/plantă)
  - **Skill 4:** Mentă (maturitate 8h, profit $2,400/plantă)
  - **Skill 5:** Cactus (maturitate 16h, profit $4,200/plantă)

---

### Firefighter (Pompier)
* **Tip:** Legal | **Mecanică:** Intervenții dinamice de urgență cu autospecială și sistem de furtun.
* **Scenarii pe Skill:**
  - Skill 1: Cisterna de Petrol
  - Skill 2: Vehicule în Flăcări
  - Skill 4: Incendiu la Tomberoane
  - Skill 6: Clădire în Flăcări (salvare cal din interior)
  - Skill 8: Scurgere de Gaze (minigame memorie la valve)
  - Skill 10: Salvare de pe Acoperiș (plasare scară și salvare animal)
* **Control Furtun:** ALT/FIRE (PC) sau `/hose` (Mobil). Reîncărcare apă la stații (ALT / `/refillhose`).
* **Autospeciale pe Skill:** Moonbeam (Sk 1), Rumpo (Sk 2-3), BF Injection (Sk 4-5), DFT-30 (Sk 6-7), Fire Ladder (Sk 8), Securicar (Sk 9), Elite Fire Ladder (Sk 10).

---

### Fisherman (Pescar)
* **Tip:** Legal | **Nivel minim:** 1 | **Locație:** Docuri LS, LV, SF
* **Licență:** Obligatorie (fără ea primiți Wanted 1 per pește prins).
* **Tipuri de Pescuit:**
  1. **La sol:** Minigame cu marcaj radar și bară de progres.
  2. **Pe barcă (Skill 3+):** Expediții în zone maritime (Verzi: Sk 3+, Galbene: Sk 4+, Roșii: Sk 7+). Vânzare la docuri dedicate cu +15% bonus.
* **Echipamente (`/jobinventory`):** Pălărie, Costum, Bocanci, Undiță, Momeală (Tier 1-8). Cumpărate din 24/7. Au durabilitate și oferă șanse crescute de captură.

---

### Garbage Man (Gunoier)
* **Tip:** Legal | **Locație:** Los Santos & Las Venturas | **Skill:** Nu are sistem de skill
* **Mecanică:**
  - Conducere autospecială Trashmaster (`/work`).
  - Colectare gunoi de la 20 de pubele.
  - După minim 10 pubele colectate puteți folosi `/dumptrash` pentru a merge direct la descărcat.
* **Câștig:** Aproximativ $2,524 - $2,530 pe o cursă completă.

---

### Lawyer (Avocat)
* **Tip:** Legal | **Nivel minim:** 5 | **Locație:** Primăria Los Santos
* **Atribuții principale:**
  1. **Eliberare deținuți (`/free [ID/Nume] [Sumă]`):**
     - Necesită puncte *accept lawyer* (cumpărate de la polițiști R3+ cu $5k-$20k sau de la primărie cu $40k prin `/getlawyer`).
     - Suma percepută deținutului: $15,000 - $50,000.
     - Cooldown: 30 minute între eliberări. Nu funcționează la ajail.
  2. **Divorțuri (`/ldivorce [Nume] [Preț]`):** Asistență la divorț pentru $1,000 - $3,000.

---

### Lumberjack (Tăietor de Lemne)
* **Tip:** Legal | **Nivel minim:** 1 | **Mecanică:** Tăierea a 7 lemne în pădure și livrarea lor la bază.
* **Locații Păduri:**
  - Pădurea I: Shandy Creeks (6.7 km)
  - Pădurea II: Flint County (5.5 km)
  - Pădurea III: The Panopticon (5.3 km)
* **Bonus Cursă Consecutivă:** *job_bonus* crește cu +5 per cursă până la maxim +50.
* **Vehicule:** Walton (Skill 1-2), DFT-30 (Skill 3-4), Flatbed (Skill 5-10).

---

### Miner
* **Tip:** Legal | **Nivel minim:** 1 | **Mecanică:** Colectarea a 5 minereuri din mină și livrarea lor.
* **Câștiguri:** Calculat prin formulă cu *coeficient_premium* (1.5 pentru premium) și *job_bonus*.
* **Recompensă Skill Up:** +10 Gold per nivel de skill avansat.
* **Vehicule:** Bobcat (Skill 1-5), Yosemite (Skill 6-10).

---

### Pocket Thief (Hoț de Buzunare)
* **Tip:** Ilegal | **Nivel minim:** 5 | **Comandă:** `/pickpocket [ID/Nume]`
* **Reguli & Restricții:**
  - Victima trebuie să aibă minim nivel 15.
  - Nu se pot fura banii în Safezone, AFK, în interior sau din vehicule.
  - Aceeași victimă poate fi jefuită de maxim 2 ori per PayDay.
  - Victima poate da `/emergency` pentru Wanted 1 sau poate omorî hoțul pentru a-și recupera banii.
  - Polițiștii jefuiți pot da `/su` pentru Wanted 3 (Jefuire).
* **Rată de Succes:** <25% (Skill 1) crescând până la 100% (Skill 10).
* **Câștig:** $598 (Skill 1) până la $5,000 (Skill 10).

---

### Quarry Worker (Muncitor la Carieră)
* **Tip:** Legal | **Locație:** Vestul orașului Las Venturas
* **Mecanică:** Încărcarea materialelor din partea de sus a carierei și transportarea lor pe drumul abrupt în inima carierei.
* **Câștig:** $329 (Skill 1) până la $562 (Skill 10).
* **Vehicule:** Dozer (Skill 1-2), Cement Truck (Skill 3-4), Dumper (Skill 5-10).

---

### Transporter (Curier)
* **Tip:** Legal | **Nivel minim:** 3 | **Locație:** K.A.C.C Military Fuels, Las Venturas
* **Mecanică:** Livrarea coletelor din portbagaj la ușa caselor indicate.
* **Livrări pe tura de lucru:**
  - Skill 1-2: max 10 colete | Skill 3-4: max 20 colete | Skill 5-6: max 30 colete | Skill 7-8: max 40 colete | Skill 9-10: max 50 colete.
* **Sistem Bonus:** Începe cu $100 per 10 livrări, crescând cu +$20 per 10 livrări până la $10,000.
* **Vehicule:** Burrito (Skill 1-4), Solair (Skill 5-10).

---

### Trucker (Tirist)
* **Tip:** Legal | **Locație:** Baza lângă Aeroportul San Fierro
* **Mecanică:** Atasare remorcă și parcurgere trasee între orașe (limită 15 minute/cursă).
* **Tipuri de Transport:**
  1. **Comercial (Skill 1+):** 15% șansă pentru +1 extra punct de skill.
  2. **Materiale de Construcții (Skill 4+):** Garantează materiale pentru Craftsman (lemn/bumbac/aur/argint).
  3. **Fuel (Skill 7+):** 25% șansă pentru +30% bani pe cursă.
  4. **Marfă (Skill 9+):** 5% șansă de a primi o cutie aleatorie.
* **Parcare:**
  - Automată.
  - Manuală (spate în parcare portocalie + `/detach`): oferă Extra Skill Point (sau +20% Banii la Skill 10).
* **Tiruri:** Linerunner (Skill 1-2), Tanker (Skill 3-4), Roadtrain (Skill 5-10).

---
*Document generat pe baza regulamentului și wiki-ului oficial B-Zone SA:MP.*
