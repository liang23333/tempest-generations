# Tempest Generations (Generazioni della Tempesta)

> *An Italian-American family saga forged in the deluge of Florence, November 1966.*

---

## 🎬 Project Overview

**Logline:**  
When an estranged Italian-American family reunites in Florence under the guise of settling an inheritance dispute over an ancestral Oltrarno artisan workshop, the apocalyptic Arno River flood of November 4, 1966 cuts off the city from the world—forcing two fractured branches of a dynasty to choose between saving their family legacy or saving each other.

- **Format:** Feature Film / Limited Drama Series (6 Episodes)
- **Genre:** Historical Drama / Family Saga / Disaster Survival
- **Setting:** Florence, Tuscany (Santa Croce, San Frediano, Ponte Vecchio) & New York City (Little Italy / Greenwich Village), Autumn 1966
- **Theme:** Generational rupture vs. ancestral roots; the fragility of art and craft; collective redemption amid catastrophic loss.

---

## 🌧️ Historical & Meteorological Data: November 4, 1966

The 1966 flood of the Arno (*Alluvione di Firenze del 4 novembre 1966*) remains the catastrophic benchmark of modern Italian environmental history. The screenplay grounds its dramatic stakes in documented atmospheric and hydrological records:

| Parameter | Historical Record | Narrative / Visual Significance |
|---|---|---|
| **Atmospheric Event** | Intense Mediterranean cyclone fed by moisture-laden air from North Africa; severe southern **Scirocco** gale winds reaching 35 m/s (~125 km/h / 70 kts) at mid-levels colliding with an Apennine cold trough. | Howling winds and unseasonable, suffocating warmth before dawn; rain hammering down diagonally like sheet metal. |
| **Antecedent Saturation** | October 1966 brought **150%–188% of average rainfall** (over 214 mm), fully saturating the Apennine soil and mountain watersheds. | The earth could absorb nothing; mountain runoffs became instant cataracts surging toward the valley. |
| **48-Hour Basin Rainfall** | **437.2 mm (~17.2 inches)** fell across the Arno basin between Nov 3–4 (approaching a third of Florence's entire annual precipitation in two days). | Relentless, blinding downpour that never let up from noon Nov 3 through the afternoon of Nov 4. |
| **Peak 24-Hour Rainfall** | Up to **200 mm (7.9 inches)** recorded in upper basin stations (e.g., Badia Agnano). | Catastrophic runoff velocity exceeding 1 m³/s/km² in steep sub-basins. |
| **Peak Arno Discharge** | Spiked from normal **~100 m³/s** to **4,100 – 4,500 m³/s** (over a 40-fold surge). | A terrifying roar echoing between narrow stone palazzo walls before sunrise. |
| **River Rise Rate & Height** | The Arno surged **6 meters in only 6 hours**, peaking at **4.93 – 4.95 meters (over 16 feet)** above reference gauge levels. | Basements submerged in seconds; ground-floor tenants awakened with water lapping at their mattresses. |
| **Current Velocity** | Floodwaters rushed through Florence's historic streets at **up to 60 km/h (37 mph)**. | Tearing street cobbles loose, overturning vehicles, sweeping away market stalls and heavy timber. |
| **Toxic Residue & Debris** | Over **600,000 tons of thick mud and silt**, mixed with thousands of gallons of subterranean domestic heating fuel (**gasolio**) from ruptured oil tanks. | Black, viscous, highly flammable slime coating Renaissance statues, fresco walls, furniture, and family archives. |
| **Human & Material Toll** | **35 fatalities** in Tuscany (17 inside Florence); **~50,000 left homeless**; **6,000 shops and workshops destroyed**; power, gas, and water severed for days. | Florence became a pitch-black, silent archipelago where neighbors communicated across rooftops. |

---

## 🏛️ Ground-Level Impact: Neighborhood Accounts

### 1. The Timing (November 4 — National Holiday)
November 4 was the *Festa dell'Unità Nazionale e delle Forze Armate* (Armed Forces Day, marking the armistice of WWI). Schools, public offices, and artisan bottegas were closed. Many Florentines were sleeping late or visiting relatives in the countryside. The lack of warning sirens or civil defense coordination meant residents woke up trapped in total darkness between 4:00 AM and 7:00 AM as black water burst through drains and windows.

### 2. Santa Croce & Via dei Neri (The Epicenter)
- Built on Florence's lowest ground, the Santa Croce district was drowned under **4.92 meters (16+ feet)** of black water.
- High water markers on **Via dei Neri** and Piazza Santa Croce commemorate where the flood crested above the first floors.
- Families on ground levels were hoisted through second-story windows by neighbors using tied bedsheets, wooden planks, and curtain rods.
- Inside the Basilica of Santa Croce, Cimabue’s 1288 *Crucifix* hung submerged in filthy diesel sludge, stripping 60% of its paint—a tragedy that became the worldwide emblem of the disaster.

### 3. San Frediano & the Oltrarno (The Artisan Heart)
- The working-class neighborhood of leatherworkers, woodcarvers, silversmiths, and bookbinders across the river.
- Cellars and subterranean vaults backed up first as sewer lines reversed. Families fled up narrow medieval stairs as waters rose past doors.
- Generations of irreplaceable hand tools, aged walnut and mahogany, custom binding presses, and family ledgers dating back to the 19th century were obliterated under petroleum-soaked silt.

### 4. Ponte Vecchio & Central Florence
- Goldsmiths and watchmakers raced in the pre-dawn darkness to empty display cases into burlap sacks before waves tore through the rear windows of the bridge.
- The **Biblioteca Nazionale Centrale** (National Library) and State Archives were flooded, drowning over **3 million rare books and manuscripts**.

### 5. The "Mud Angels" (*Gli Angeli del Fango*)
- In the days immediately following, before government aid arrived, thousands of domestic and foreign youth, students, and artists descended on Florence by hitchhiking and train.
- Shoulder-to-shoulder with local families, they formed human bucket chains in the freezing mud, scraping slime from cellars and drying priceless manuscripts page by page with talcum powder.

---

## 🗂️ Screenplay Repository Architecture

To maintain industry-standard version control and modular development, this repository follows the open **Fountain** markup standard (`.fountain`):

```text
tempest-generations/
├── README.md                      # Project master bible & research summary
├── Screenplay.fountain            # Master screenplay compile target
├── acts/
│   ├── act_01_the_tide_rises.fountain
│   ├── act_02a_inundation.fountain
│   ├── act_02b_the_black_current.fountain
│   └── act_03_mud_angels.fountain
├── bible/
│   ├── characters/                # Character profiles & voice notes
│   │   ├── renzo_fontana.md       # Traditional Oltrarno leather artisan (Patriarch)
│   │   ├── anthony_fontana.md     # Estranged son returned from Queens, NY
│   │   └── chiara_fontana.md      # Young Florence art conservator & student
│   ├── history_and_weather.md     # Meteorological data & hydrological timeline
│   └── locations.md               # Visual breakdowns (San Frediano, Via dei Neri, Ponte Vecchio)
├── treatments/
│   ├── series_outline.md          # 6-episode beat sheet
│   └── feature_treatment.md       # 3-act feature screenplay treatment
└── tools/
    └── export_to_pdf.sh           # CLI compilation via 'afterwriting' or 'fountain-js'
```

---

## 🛠️ Recommended Screenplay Tooling

- **Fountain Standard:** Plain-text screenplay markup ([fountain.io](https://fountain.io/)) compatible with Git diffs, VS Code, and terminal workflows.
- **VS Code:** Install the **BetterFountain** extension for real-time screenplay preview, scene navigation, and character autocomplete.
- **Command-line compilation:** Use [`afterwriting-labs`](https://github.com/ifrost/afterwriting-labs) or [`screenplain`](https://github.com/vilcans/screenplain) to convert `.fountain` files to production-ready industry PDFs and Final Draft (`.fdx`) format.
