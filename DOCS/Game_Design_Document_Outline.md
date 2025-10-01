# The Reclamation Cycle: GDD Outline (V0.1)

**Purpose:** Define the core gameplay loop, systems, and win conditions.

![Blueprints](./../IMAGES/gdd.png "Blueprints")

---

## 1. Core Gameplay Loop

The player's primary interaction follows a continuous cycle driven by the need to support a growing population and evolving infrastructure.

1.  **Survey & Salvage:** Identify derelict structures, ruins, and wrecks using scouting teams. Dispatch vehicles or teams to secure the salvage site and extract raw materials.
2.  **Disassemble & Refine:** Process the raw salvage (e.g., car chassis, rubble, junk) in dedicated facilities to yield usable resources (Scrap Metal, Concrete Aggregate, Motors, Polymers).
3.  **Produce & Build:** Use refined resources to construct new residential buildings, core utilities (water, power), and essential transport infrastructure (rail, roads). This is the key decision point for the **Restoration** vs. **Adaptation** path.
4.  **Maintain & Upgrade:** Manage the health, efficiency, and resource consumption of existing structures. Repairs are constant, forcing a choice between the high-efficiency, high-cost maintenance of Restoration and the low-cost, low-efficiency upkeep of Adaptation.
5.  **Expand & Research:** Increase the settlement's population, unlock advanced technologies via research (dependent on chosen path), and secure new regions to restart the cycle and grow the regional network.

---

## 2. Key System Breakdown

### 2.1 The Reclamation and Resource System

The game is built around material flow, scarcity, and transformation. **Salvage is a finite resource.**

| Resource Type | Description | Source Examples | Strategic Importance |
| :--- | :--- | :--- | :--- |
| **Old World Salvage** | Raw, unprocessed materials recovered from ruins. | Wrecked Vehicles, Ruined Buildings, Landfills. | Essential for Restoration Path. Finite, high-risk retrieval. |
| **Refined Components** | Processed, necessary for high-tier construction and repair. | Steel Rebar, Polymers, Working Motors, Electronic Kits. | Automation and advanced utility function. |
| **New World Resources** | Sustainable, renewable materials. | Lumber (Forestry); Stone (Quarrying); Compost/Fertilizer (Waste Management); Crops. | Essential for Adaptation Path. Requires land and time investment. |
| **Utilities** | Essential flows for population health and building function. | Water (Potable/Grey), Power (kW/h), Sanitation (Sewage/Compost), Fuel (Diesel/Biofuel). | Managing efficient distribution is a major logistics challenge. |

### 2.2 Dual Tech Paths (The Restoration Choice)

The player commits resources to one of two diverging construction philosophies. This choice dictates the research tree, resource bottlenecks, and the settlement's final shape.

* **The Restoration Path:** Focus on restoring high-density housing and automated, efficient utilities using **Refined Components** and **Old World Salvage**. *High reward, high complexity, high maintenance.*
* **The Adaptation Path:** Focus on resilient, low-maintenance housing and decentralized utilities using **New World Resources**. *Low reward, high sustainability, low complexity.*

### 2.3 Logistics & Transport System

The game's scale dictates that efficient movement of goods across the regional map is critical.

* **Tiers:** Progression from slow manual transport (foot/carts) to motorized vehicles (trucks/railbuses).
* **Infrastructure:** Requires investment in specific transport lines (narrow-gauge rail, paved roads) and supporting depots/stations to manage transfer and storage.

---

## 3. Game Scope and Objectives

### 3.1 Three Phases of Growth

The player must guide the settlement through three distinct phases, each defined by logistical complexity and scale:

* **Phase I (The Outpost):** Focus on basic survival and securing the immediate salvage area. Small, single-tile settlement.
* **Phase II (The Town):** Focus on establishing resource specialization and connecting outposts via transport links. Multiple interconnected settlements on a regional map.
* **Phase III (The Network):** Focus on the final Grand Project—either massive restoration or complete regional sustainability.

### 3.2 Win Conditions (The Vision)

1.  **Restoration Victory:** Successfully restoring a **Major Old World Monument** (e.g., a hydro dam or central data center) to full operational status.
2.  **Adaptation Victory:** Establishing a **Network of X self-sustaining, resilient settlements** that operate indefinitely without relying on Old World salvage, achieving complete regional peace and stability.

### 3.3 Loss Conditions

* **Population Collapse:** Inability to provide critical utilities (Water, Food) resulting in mass exodus or death.
* **Critical Infrastructure Failure:** Loss of a non-replaceable, salvaged Core Component (e.g., the last functional engine) leading to catastrophic cascading system failures.

---

## 4. Next Steps (Related Documents)

* **DOCS/Tech\_Tree\_V0.1.md:** Detailed recipes, component requirements, and technology divergence for the Dual Paths.
* **DOCS/Scenarios/Scenario\_Contamination.md:** Specific mechanics, threats, and resource impacts of the first proposed scenario.
