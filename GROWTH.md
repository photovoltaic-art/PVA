# PVA growth model — from SUNDIAL to SUNSET

How PVA's works grow in one town: one panel as the artist's proof, then nine panels as SUNDIAL, then the same nine as SUNSET, handed to nine separate owners. Beyond one town, by forking.

> Status: draft 4, 27 Oct 2026: the final shape. The path: artist's proof, SUNDIAL, SUNSET; two stages in one town (1–3); growth by forking (5); when the works are complete, and the node catalogue (6). Covers [SUNDIAL](https://github.com/photovoltaic-art/SUNDIAL) (no. 1) and [SUNSET](https://github.com/photovoltaic-art/SUNSET) (no. 2). Nothing built.

---

## TL;DR

- **The path: proof, SUNDIAL, SUNSET.** One panel as SUNDIAL's **artist's proof**; then **nine panels as SUNDIAL**; then **the same nine as SUNSET** (the path, below).
- **Year 1, SUNDIAL:** nine panels across the town as sundials and sun monitors, with a summer event. **No tokens.** **PVA owns and manages everything.**
- **Year 2, SUNSET:** the **same nine panels** become SUNSET's nodes:
  - **4 wall nodes**, by a firmware update;
  - **5 interactive nodes**, by adding the battery tier and their own hardware (auction, arm, gettoneria, flip-dot wall, the set).
  - **Stamps and tokens** begin.
- **From year 2, each node is owned separately.** **Anyone** can own a node: a host, a sponsor, a local group. Each owner holds their node's key; nine owners together decide on rule changes and on the year's coin list.
- **PVA writes the firmware and the rules, and manages the website** (map, Sole, the explorer). It no longer owns the nodes.
- **The sundial stays:** every panel keeps its gnomon, so the town keeps its nine sundials whatever runs behind them.
- **Beyond one town: growth by forking, never by linking.** Nine panels is the sweet spot: the network, the economy and the governance all work at nine and get worse with more. A new town forks the works and runs its own nine, with its own keys, coins, rules and website. Towns are never networked (5).
- **Complete when tested and forkable:** each repository is complete when its hardware and software have been trialled and it has a reproducible build a fork can repeat; only then is it licensed. **Before SUNSET is licensed, PVA builds and tests further interactive nodes,** so each fork chooses its own nine from a catalogue of tested nodes (6).
- **Why:** the works end as they are powered, as a commons, like the sun.

---

## The path

| Stage | Panels | What | Owned by |
| --- | --- | --- | --- |
| **Artist's proof** | **1** | A single SUNDIAL panel, outside the edition | PVA, always |
| **SUNDIAL** (year 1) | **9** | The edition: nine sundials and Sole (1) | PVA |
| **SUNSET** (year 2) | **the same 9** | The same nine panels as an offline network with its own money (2) | Nine separate owners (3) |

**Every PVA public installation is an edition of nine panels: never more, never less** (the manifesto's first line). The artist's proof is not a public installation. Nine is the threshold, tested and proven in Bosa before any other town copies the work (5).

### The artist's proof

As in printmaking, the **artist's proof** (*prova d'artista*) stands outside the numbered edition: a single panel with its carrier board, **a complete SUNDIAL on one panel** (the sundial and Sole both work alone).

- **Owned by PVA, always.** Never installed as a town's work, never counted in an edition, never sold or forked as a work.
- **Made first,** before the nine: it is SUNDIAL's pilot panel.
- **What it is for:**
  - proving the panel, the carrier board, the gnomon and the hour lines before nine are built;
  - bench-testing every firmware build, before it goes into the nine;
  - showing the comune, the hosts and (from year 2) the owners what they are agreeing to;
  - exhibitions and talks.
- **SUNDIAL only.** SUNSET has no artist's proof: one node can't show it, because walking needs somewhere to walk to. SUNSET is tested on the bench (two boards upwards) and in its pilot (TASKS.md in the SUNSET repository), and its catalogue nodes are built and tested by PVA ([NODES.md](https://github.com/photovoltaic-art/SUNSET/blob/main/NODES.md)).

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
| **Forking** | Each repository carries a FORK-TASKS.md; SUNSET's follows SUNDIAL's (5.4) |

---

## 5. Growth by forking

**Nine panels per town. A new town forks; towns are never linked.**

### 5.1 Why nine, and not more

A PVA work is nine panels: the one rule of SUNDIAL and SUNSET. For SUNSET, nine is also where the design works, and every part gets worse as one network grows to N nodes:

| | 9 nodes | 20 nodes | 30 nodes | Why |
| --- | --- | --- | --- | --- |
| Walk stamps a day | 72 | 380 | 870 | Every node pays for the first delivery of every other node's block: N × (N − 1). Issuance grows with the square of N |
| Blocks each node keeps (7 days, about 5 KB each) | about 315 KB | about 700 KB | about 1.05 MB | Every node holds every node's blocks, within a 1.2 MB budget |
| The courier's bag on a phone (3 days) | about 135 KB | about 300 KB | about 450 KB | Within 500 KB |
| A spend's news reaching every node | about a day | longer | longer still | Carried on foot: the double-spend window and the grace period widen |
| Governance | 5 of 9 | ? of 20 | ? of 30 | Every key built into every node; more owners to agree |
| The gateway | one | still one | still one | One gettoneria is the authority for coins, tied to the flip-dot wall by ESP-NOW range |

What does not care about N: each node's own Wi-Fi, the sun's allowance at an arm, the 1,000-coin stock, and checking a spend.

### 5.2 Why not link towns

Linking two networks of nine, by radio or by couriers between towns, brings back every problem of a bigger network, and adds new ones: whose keys to trust, whose rules apply when they differ, and a coin stock that is no longer closed. **So towns are never linked:** no shared stamps, coins, keys, chain or explorer. A town may borrow firmware and ideas from any other; it never shares money.

The radio node once sketched in GO TO BED (a LoRa link to the next village) is set aside for this reason.

### 5.3 What a fork is

| | The fork (the new town) | PVA |
| --- | --- | --- |
| Owns | Its nine panels, its keys, its coin list, its rules file, its website and explorer, its permissions | Nothing in the new town |
| Writes | Its town's texts, logos, coin artwork, site plan | The repositories, the firmware, the rules template, the verifier |
| Asks | A link back (a request, not a licence condition) | |

**The path in a new town is the same as in Bosa:** fork SUNDIAL for year 1; fork SUNSET for year 2, converting the same nine panels; hand the nodes to nine owners.

**Towns are kept apart by design, not by trust:**
- **Keys:** a node accepts only its own town's nine keys, so another town's stamps and blocks fail the first signature check. *No change to the block format or the seal is needed.*
- **The web address:** each town picks its own access-point address, so its pages and the phone's storage are a different site from every other town's: a visitor's Bosa passport is not readable by another town's pages.
- **Coins:** each town's coins carry a link to its own website, never another town's; its coin list is its own.

### 5.4 What this asks of the repositories

- **The licences are the growth plan.** Both repositories are "not yet licensed for reuse", so no one can legally fork them yet. Each is released, with its licences, once field-tested (SUNDIAL at SUNDIAL 2027; SUNSET after its first full season in Bosa, 2028).
- **Everything that belongs to Bosa in one folder,** so a fork replaces that folder and nothing else: SUNDIAL's [FORK-TASKS.md](https://github.com/photovoltaic-art/SUNDIAL/blob/main/FORK-TASKS.md), and SUNSET's [FORK-TASKS.md](https://github.com/photovoltaic-art/SUNSET/blob/main/FORK-TASKS.md), which builds on it.
- **A list of towns** on photovoltaic.art, for forks that send their link: so the instances can find each other without being networked.

---

## 6. When the works are complete

**The shape is fixed:** two stages in one town (SUNDIAL, then SUNSET on the same nine panels), and forking as the only route to more towns. What remains is proof.

### 6.1 Complete, then licensed

Each repository is **complete** when both are true:

1. **Trialled:** its hardware and software have run in the field. SUNDIAL at SUNDIAL 2027; SUNSET through its first full season in Bosa, 2028.
2. **Reproducible:** a fork can build exactly what was trialled: everything town-specific in one site folder, pinned versions, a tagged release, a fork rehearsed for another town.

**Only then is it licensed,** and the licences are what make it forkable. The task lists are each repository's FORK-TASKS.md.

### 6.2 As simple as possible

Designing for forking is the main goal, so every choice leans to the simplest thing a town can repeat:

- **One board everywhere.** The PVA carrier board v1, unchanged, on every panel of both works and every catalogue node; SUNSET's interactive nodes add the battery tier, not a different board.
- **One image per work.** All nine SUNDIAL panels run the same firmware file, and all nine SUNSET nodes another; a panel's name, keys (and in SUNSET its role) are written to its flash at installation.
- **Security in proportion.** SUNDIAL has no money in it, so it keeps its light security. SUNSET carries stamps and coins, so its security work (SECURITY.md in the SUNSET repository) stays in SUNSET.

### 6.3 SUNSET's node catalogue

SUNSET is licensed later than SUNDIAL for one more reason: **PVA builds and tests further interactive nodes first.** Every node in the catalogue meets the same rules (its own sun, the same seal, stamps only from walk or sun, offline, closed at sunset, secure, keeps no one), and is field-tested by PVA before a fork may choose it.

- **Bosa's nine are the reference set:** four walls, the gettoneria, the flip-dot wall, the street auction, the arm game, the SUNSET set.
- **A fork chooses its own nine** from the catalogue, respecting each node's needs (the flip-dot wall needs the gettoneria beside it).
- **The catalogue and its candidates:** [SUNSET NODES.md](https://github.com/photovoltaic-art/SUNSET/blob/main/NODES.md).

So the organisation's lasting output is not one installation but **two tested works and a catalogue of tested nodes,** from which any town can make its own nine.

