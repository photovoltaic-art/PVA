# PVA growth model — from SUNDIAL to SUNSET

How PVA's first two works grow out of each other in one town: the same nine panels, first owned and run by PVA, then upgraded and handed to nine separate owners.

> Status: draft 1, 27 Oct 2026. Covers [SUNDIAL](https://github.com/photovoltaic-art/SUNDIAL) (no. 1) and [SUNSET](https://github.com/photovoltaic-art/SUNSET) (no. 2). Nothing built.

---

## TL;DR

- **Year 1, SUNDIAL:** nine panels across the town as sundials and sun monitors, with a summer event. **No tokens.** **PVA owns and manages everything.**
- **Year 2, SUNSET:** the **same nine panels** become SUNSET's nodes:
  - **4 wall nodes**, by a firmware update;
  - **5 interactive nodes**, by adding the battery tier and their own hardware (auction, arm, gettoneria, flip-dot wall, the set).
  - **Stamps and tokens** begin.
- **From year 2, each node is owned separately.** **Anyone** can own a node: a host, a sponsor, a local group. Each owner holds their node's key; nine owners together decide on rule changes and on the year's coin list.
- **PVA writes the firmware and the rules, and manages the website** (map, Sole, the explorer). It no longer owns the nodes.
- **The sundial stays:** every panel keeps its gnomon, so the town keeps its nine sundials whatever runs behind them.
- **Why:** the works end as they are powered, as a commons, like the sun.

---

## 1. Year 1: SUNDIAL

As specified in the SUNDIAL repository ([SUNDIAL.md](https://github.com/photovoltaic-art/SUNDIAL/blob/main/SUNDIAL.md)):

| | Year 1 |
| --- | --- |
| Panels | Nine, on walls (or a post on private ground), each a sundial |
| Layers | The sundial; Sole, the sun monitor, all year; the annual event |
| Money | None |
| Owner and manager | **PVA:** boards, firmware, permissions, insurance, rounds, website |
| Firmware | SUNDIAL 6.2 |

**One thing year 1 must already do for year 2: choose the nine sites with their year-2 roles in mind.** SUNSET's layout asks things a sundial doesn't (SUNSET.md 4):

| Year-2 role | What its year-1 site needs, beyond a south-facing wall |
| --- | --- |
| Walls 1–4 | Spread to the edges of the installation |
| Gettoneria and flip-dot wall | **Together,** within ESP-NOW range, near businesses with footfall; room for the hopper's housing and a 43 cm flip-dot square in shade or facing north beside the panel |
| Street auction | Where people pass; room for three lockers; ideally in ESP-NOW range of the gateway |
| Arm game | Shade for the arm's case |
| The SUNSET set | Near the town's sunset spot, with neighbours who can live with an hour of music |

So the year-1 site plan names a year-2 role for each panel, and the year-1 permissions request says the panels may grow into SUNSET.

---

## 2. Year 2: SUNSET

### 2.1 The conversion, at the spring visit

| Panels | Become | What changes |
| --- | --- | --- |
| **4** | **Wall nodes** | **Firmware only:** the SUNSET wall build. Same board, same wiring, no battery |
| **5** | **Interactive nodes** | **The battery tier** (Victron MPPT, LiFePO₄ battery, cabinet; JP1 off, the panel's own sun sensor compiled out), the node's own hardware, and the interactive build |

- **Same carrier board v1, unchanged,** as SUNSET always assumed. The firmware change is made with the box opened at the spring visit, as SUNDIAL's yearly updates are.
- **New keys at handover:** each node generates a fresh key in its new owner's presence; PVA's year-1 key is retired and published with its end date (stamp-format.md 2).

### 2.2 What carries on from SUNDIAL

| SUNDIAL layer | In year 2 |
| --- | --- |
| **The sundial** | **On all nine.** The gnomons and hour brackets stay; the town's nine sundials outlive any firmware |
| **Sole, the sun monitor** | **On all nine, if the interactive nodes carry a reference sun sensor.** On the battery tier the panel's own sun reading is compiled out, and a battery's harvest is not sunlight. A small reference solar cell on each interactive node (as the arm already needs: tokenomics.md 2.2) keeps the record honest. The walls carry on measuring as before, and are also the cross-check for the arm's sun claim |
| **The annual event** | **To decide:** whether SUNDIAL's event week continues on the four walls, on all nine, or ends with year 1 |

### 2.3 What is new

Everything in the SUNSET repository: stamps and tokens ([tokenomics.md](https://github.com/photovoltaic-art/SUNSET/blob/main/tokenomics.md)), the interactive nodes, the gateway, the explorer.

---

## 3. Ownership from year 2

### 3.1 Who

**Anyone can own a node:** a host, a sponsor, a local group, a school. **Owning a node and hosting it are different:**

| | Owner (keyholder) | Host |
| --- | --- | --- |
| Is | Whoever takes on the node | Whoever gives the wall or ground |
| Holds | The node's signing key; a say in rule changes and the year's coin list | Their wall, and their consent |
| Answers for | The node: care, insurance, its share of upkeep | Access to their wall |
| Often | The same person as the host, but need not be | |

### 3.2 What each part holds

| Role | Who | What |
| --- | --- | --- |
| **Writes the rules and firmware** | PVA | One rules file per season, frozen in firmware; reproducible builds with published fingerprints |
| **Manages the website** | PVA | The map, Sole, the explorer, the weekly coin table |
| **Holds a node** | Its owner | The node's key, generated on the node and never seen by PVA; a vote on rule changes (each owner re-flashes their own node) and on the year's coin list (for example 5 of 9 signatures) |
| **Carries, earns and verifies** | Anyone | Walk stamps, the sun's allowance at the arm, the explorer's script |

The full design, its checks and its risks are in [tokenomics.md 5](https://github.com/photovoltaic-art/SUNSET/blob/main/tokenomics.md).

### 3.3 Handing a node over

1. **Agreement:** the owner takes on the node, its care and its insurance; the host's consent stays in place.
2. **At the spring visit:** the conversion (2.1), then a new key generated on the node, its public half published.
3. **A public moment:** the handover can be part of the work, nine panels passing from PVA to the town.
4. **What if no one comes forward:** PVA keeps the node until someone does; the network runs with whatever owners it has.

### 3.4 Open in this model

| Question | Notes |
| --- | --- |
| **The terms of ownership** | Given, adopted, or paid for (an owner funding their node's conversion would fund year 2); and what happens when an owner leaves |
| Upkeep | Who does the rounds once nodes have nine owners: PVA as a service, the owners, or both |
| Insurance and permissions | Nine owners, one installation: one shared policy, or nine |
| The annual event | Continue, change, or end with year 1 (2.2) |
| The artwork | A PVA work becomes a commons: how the work, and PVA's authorship, is described from year 2 |

---

## 4. What it means for the plans

| Area | Change |
| --- | --- |
| **SUNDIAL's site plan** | Each site chosen for its year-2 role as well (1) |
| **SUNDIAL's permissions** | The request says the panels may grow into SUNSET in year 2 |
| **SUNSET's budget** | Panels, carrier boards, walls' boxes and fixings already exist from year 1: the year-2 cost is the five conversions, the coins and the reference sensors |
| **SUNSET's firmware** | The wall build includes Sole's logging, so the record continues |
| **Interactive nodes** | A reference sun sensor on each, for Sole (2.2) |
| **Governance** | tokenomics.md 5 moves from a proposal to the plan for year 2 |
