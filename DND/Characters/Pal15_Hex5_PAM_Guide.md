# Paladin 15 / Hexblade 5 (PAM Flex) – High-Resilience Nova & Control Guide

**Concept Focus:** A level 20 multiclass (Paladin 15 / Hexblade Warlock 5) engineered for repeatable *short‑rest nova* bursts, sustained frontline durability, and *reach-based control* via Polearm Master (PAM) – while retaining the tactical option to swap to sword + shield when survival or tight quarters demand it.

Designed for a Half‑Elf (Drow variant) leveraging Elven Accuracy, darkness options, and Charisma centralization. This guide emphasizes original synthesis (not a copy of other sources) and provides dual-mode combat planning: **Reach Great Weapon Mode** & **Shield Mode**.

---
## Table of Contents
1. Core Identity & Play Loop  
2. Why This Split (15 / 5)  
3. Race: Half‑Drow Half‑Elf Breakdown  
4. Starting & Final Ability Scores  
5. Level Progression Roadmaps (Primary & Variants)  
	5.1 Level-by-Level Cheat Sheet (What To Do & Track)  
6. Class Feature Milestones  
7. Feats & ASI Sequencing  
	7.1 GWM Value Assessment & Alternatives  
8. Weapon Modes: Reach vs Sword & Board  
9. Action / Bonus / Reaction Economy  
10. Spell Selection (Paladin & Warlock)  
11. Invocations (3 picks)  
12. Resource & Rest Cycle Management  
13. Nova Math Snapshots  
14. Defensive Layering & Sustain  
15. Optional Oath Choices (Primary vs Alternatives)  
	15.1 Oath Feature Timeline & Comparison  
16. Darkness / Vision Package – Pros & Cons  
17. Magic Item Priorities  
18. Tactical Cheat Sheet  
19. Common Pitfalls & Mitigations  
20. Roleplaying Hooks  
21. Quick Reference Summary  
22. Reallocating Levels (Dropping Paladin 14–15)  
23. At-a-Glance Reference (Thresholds & Tables)  

---
## 1. Core Identity & Play Loop
**Identity Pillars:**
- Reliable baseline melee DPR with *reach control* (threat sphere, OA funnel) using Polearm Master.
- Short‑rest refueled *3rd‑level pact slots* for Eldritch Smite + reactive casting (Shield / Darkness if taken) without draining long‑rest Paladin pool.
- High save resilience (Aura of Protection + optimized CHA) for uninterrupted concentration on key buffs (Haste, Bless, or Spirit Shroud / Darkness variant).
- Flexible loadout: Halberd / Glaive for zone denial; instant switch to Longsword + Shield for defensive phases (boss phases, radiant breath anticipation, low healer availability).

**Round Template (Reach Nova Example):**
1. Pre-fight (if time): Cast *Bless* or *Aid*; apply *Armor of Agathys* (AoA) using a pact slot if expecting early swarm hits.  
2. Round 1: Bonus: *Hexblade's Curse* (or *Vow of Enmity* if AC high – saving curse for later). Action: Attack twice (declare GWM if advantage established). Reaction: PAM OA if enemy enters reach; smite on crit or needed kill.  
3. Round 2+: Maintain advantage (Vow active / Faerie Fire / Darkness synergy), fish for crit → apply *Divine Smite* + (optionally) *Eldritch Smite* only if target will not survive until next round or prone rider is pivotal.  

---
## 2. Why This Split (15 / 5)
| Target | Benefit | Notes |
|--------|---------|-------|
| **Paladin 6** | Aura of Protection | Early durability inflection point |
| **Paladin 7–10** | Oath features + Aura of Courage + improved slot volume | Foundation for mid-tier sustain |
| **Paladin 11** | Improved Divine Smite? (No – that’s level 11; *but we stop at 15 still benefiting*) | Adds 1d8 radiant per hit – strong sustained DPR boost |
| **Paladin 14** | Cleansing Touch | Counter debuffs / saves slots |
| **Paladin 15** | Oath-specific feature (depends) | Examples: Soul of Vengeance (Vengeance), Undying Sentinel (Ancients), Scornful Rebuke (Conquest) – evaluate vs dip potential (§22) |
| **Warlock 3** | Pact of the Blade (CHA weapon) | Weapon flexibility / infusion |
| **Warlock 5** | 3rd‑level pact slots & Eldritch Smite availability | Nova engine w/out deeper Warlock investment |

**Why not Warlock 6+?** Armor of Hexes (Warlock 10) is powerful, but pushing there delays Paladin 15 aura/utility and 4th‑level Paladin slots. This build values *higher long-rest slot scaling + Improved Divine Smite + Cleansing Touch* over the attack-null chance.

---
## 3. Race: Half‑Drow Half‑Elf
| Feature | Impact |
|---------|--------|
| +2 CHA, +1 STR, +1 CON (allocation) | Core SAD backbone + durability + early plate strength requirement |
| Darkvision (60 ft), potential upgrade (90) via DM | Enables dark tactical play; synergy with Darkness if Devil’s Sight chosen |
| Fey Ancestry | Advantage vs charm + sleep immunity (situational but saves critical failures) |
| Drow Magic Variant (if allowed) | *Dancing Lights*, *Faerie Fire* (advantage scaffold), *Darkness* (rare slotless cast) – EC synergy |
| Skill Versatility (2 skills) | Patch perception / athletics / persuasion gaps |

**Faerie Fire vs Darkness:** Faerie Fire (no self-blind) is party-friendly; Darkness + Devil’s Sight is selfish – decide early.

---
## 4. Starting & Final Ability Scores
(27 Point Buy + Racial)

| Stat | Start | Racial | Level 20 Goal |
|------|-------|--------|---------------|
| STR | 15 | +1 = 16 | 16 (baseline for plate; not prioritized after) |
| DEX | 8 | – | 8 (dump; initiative/DEX save patched by Aura) |
| CON | 14 | +1 = 15 | 16 (one half-feat / ASI optional) |
| INT | 8 | – | 8 |
| WIS | 10 | – | 10 (passable baseline; Aura backfills) |
| CHA | 15 | +2 = 17 | 20 (primary ASIs + Elven Accuracy bump) |

**SAD Justification:** After Hex Warrior, STR becomes purely armor qualifier + occasional Athletics; CHA drives all offense / defense synergy.

---
## 5. Level Progression Roadmaps
### Primary (Balanced Early Aura then Nova)
| Char Lvl | Class | Notes / Power Gained |
|----------|-------|----------------------|
| 1 | Pal 1 | Heavy armor, Fighting Style (Dueling for early sword+shield) |
| 2 | War 1 | Hexblade’s Curse, Hex Warrior (swap to CHA attacks immediately) |
| 3 | Pal 2 | Divine Smite online |
| 4 | Pal 3 | Oath (Vengeance/Ancients/Conquest per style) |
| 5 | Pal 4 | ASI #1 (Polearm Master) – prep for reach weapon soon |
| 6 | Pal 5 | Extra Attack (drop GFB reliance) |
| 7 | Pal 6 | Aura of Protection (survivability spike) |
| 8 | War 2 | Invocations #1–2 (Agonizing Blast + Devil’s Sight OR Eldritch Mind) – cannot take Improved Pact Weapon yet |
| 9 | War 3 | Pact of the Blade (now CHA can apply to your pact weapon even if two‑handed); optionally swap into Improved Pact Weapon now |
|10 | War 4 | ASI #2 (Elven Accuracy +1 CHA to 17→18 or full +2 CHA) |
|11 | War 5 | 3rd‑level pact slots, Invocation #3 (Eldritch Smite) |
|12 | Pal 7 | Aura of Courage (fear immunity passive for allies) |
|13 | Pal 8 | ASI #3 (+2 CHA to 20 or GWM depending ordering) |
|14 | Pal 9 | 3rd‑level Paladin slots (Revivify baseline earlier; now more fuel) |
|15 | Pal 10 | Oath feature (varies) |
|16 | Pal 11 | Improved Divine Smite (flat scaling) |
|17 | Pal 12 | ASI #4 (Great Weapon Master or Resilient CON / War Caster) |
|18 | Pal 13 | 4th‑level Pal slots (Staggering Smite / Death Ward) |
|19 | Pal 14 | Cleansing Touch (dispel on demand) |
|20 | Pal 15 | Oath 15 feature (Soul of Vengeance / Undying Sentinel / Scornful Rebuke) |

### Variant: Faster Pact Nova
Take Warlock 1 earlier (already done) and rush Warlock 5 by character 10 (Pal 1 / War 1 / Pal 2–6 / War 2–5) then finish Paladin. Gains earlier Eldritch Smite at cost of slightly delayed ASIs.

### 5.1 Level-by-Level Cheat Sheet (What To Do & Track)
| Level | Class | Pick / Action | Power Spike Use This Level | Notes / Reminders |
|-------|-------|---------------|-----------------------------|-------------------|
| 1 | Pal | Fighting Style (Dueling) | Higher 1H baseline DPR | STR attacks (no CHA yet) |
| 2 | War | Hexblade Patron, Hexblade's Curse | Single-target burst & +Prof damage | Bind longsword for CHA (still 1H) |
| 3 | Pal | Divine Smite online | Hold for crits / priority kills | Conserve slots early |
| 4 | Pal | Choose Oath | Channel Divinity unlocked | If Vengeance: plan future reaction load |
| 5 | Pal | Feat: Polearm Master | Bonus butt + entry OA (once using polearm) | CHA not on 2H polearm until War 3; you may stay 1H until 9 |
| 6 | Pal | Extra Attack | Reliable output | Prep to transition to reach soon |
| 7 | Pal | Aura of Protection | Major defense jump | Track allies' positioning |
| 8 | War | Invocations: Agonizing Blast + Devil's Sight/Eldritch Mind | Ranged scale / advantage engine setup | Skip Improved Pact Weapon now |
| 9 | War | Pact of the Blade; swap for Improved Pact Weapon | CHA now works on 2H pact polearm | Rebind weapon each day |
|10 | War | ASI: Elven Accuracy (+1 CHA) | Crit fishing foundation | Take +2 CHA if low advantage uptime |
|11 | War | Invocation: Eldritch Smite (War 5) | Prone force nova | Reserve 1 pact slot per rest |
|12 | Pal | Aura of Courage | Fear immunity | Cluster around aura vs dragons |
|13 | Pal | ASI: +2 CHA (to 20) or GWM | Max accuracy / aura | Decide Path A (GWM) or B (Resilience) |
|14 | Pal | 3rd-level Pal slots | Haste / Spirit Shroud online | Choose ONE concentration staple |
|15 | Pal | Oath feature (depends) | Vengeance gap / Ancients safety / Conquest chip | Evaluate if pushing to 20 worth reaction feature |
|16 | Pal | Improved Divine Smite | Each hit +1d8 | Increases butt/OA value |
|17 | Pal | ASI: GWM or Resilient (CON)/War Caster | Spike or stability | Take Resilient if conc failing >1/day |
|18 | Pal | 4th-level Pal slots | Death Ward / Staggering Smite | Pre-buff before dangerous boss |
|19 | Pal | Cleansing Touch (3/day) | On-demand debuff purge | Track uses (tokens) |
|20 | Pal | Oath 15 feature live | Soul of Vengeance reaction / etc. | Reaction priority shifts |

Cheat Sheet Core Reminders:
1. Pre-combat choose ONE concentration (Bless vs Haste vs Spirit Shroud vs Faerie Fire). Avoid mid-fight churn.
2. Reaction ladder (Vengeance 15): Soul of Vengeance > PAM entry OA > Shield (if lethal) > other.
3. Nova rule: Only stack Eldritch + Divine Smite when target’s remaining HP justifies the slot expenditure or a crit lands.
4. Maintain 1 pact slot in reserve until encounter outcome is clear.

---
## 6. Class Feature Milestones (Why They Matter)
| Milestone | Impact | Synergy |
|-----------|--------|---------|
| Hexblade’s Curse | +Prof damage, crit 19–20, heal on kill | Elven Accuracy crit engine |
| Vow of Enmity | Sustained advantage vs boss | GWM reliability / EA triple-roll |
| Aura of Protection | +CHA to all saves (party) | Concentration reliability (Haste / Bless) |
| Eldritch Smite | Force + prone on hit (dice doubled on crit) | Sets prone before allies act; OA follow-ups |
| Improved Divine Smite | +1d8 radiant per weapon hit | Scales multi-hit (PAM butt / OA) |
| Cleansing Touch (Pal 14) | Action debuff purge (self/ally) | Conserves spell slots vs repeat dispels |
| Soul of Vengeance (Vengeance 15) | Reaction attack vs Vow target | Extra crit vector; reaction economy tension |

---
## 7. Feats & ASI Sequencing
You have access to **FOUR** ASI / feat picks in a Paladin 15 / Warlock 5 build (Paladin 4, 8, 12 and Warlock 4). The earlier version listed five sequential choices; below they are reorganized into two main 4‑pick paths plus swap logic.

### Path A – Crit / Nova Emphasis (GWM Route)
1. **Polearm Master (PAM)** – Core engine: entry OA + bonus butt (extra smite trigger & Improved Divine Smite rider).
2. **Elven Accuracy (+1 CHA to 18)** – Triples advantage roll depth; fuels crit fishing with Vow / Faerie Fire / Darkness.
3. **+2 CHA (18→20)** – Maximize attack, damage, save aura, concentration.
4. **Great Weapon Master** – -5/+10 toggle for advantaged reach swings; bonus action attack on crit/kill (choose vs PAM butt). 
	- Clarification: -5/+10 applies ONLY with a *heavy* weapon (glaive/halberd). In shield mode (longsword/spear) you can’t use the penalty/bonus, but still gain the crit/kill bonus action option.

*When to alter:* If concentration failures are frequent before ASI #3, swap order: take **Resilient (CON)** at slot 3, push +2 CHA to slot 4, and delay / drop GWM (especially if reach advantage uptime < ~60%).

### Path B – Control / Resilience (Skip GWM)
1. **Polearm Master (PAM)**
2. **Elven Accuracy (+1 CHA to 18)** (or +2 CHA first if advantage sources are delayed)
3. **+2 CHA (to 20)**
4. **Resilient (CON)** *or* **War Caster** (pick based on whether you want universal CON save scaling vs OA cantrips + somatic ease). 

*Result:* You trade GWM spike turns for higher concentration retention (Bless/Haste uptime) and defensive consistency—often superior in spell‑heavy or fear/control‑immune campaigns.

### Other Flex / Replacement Options (Compete for Slot 4 or replace Elven Accuracy if you abandon crit plan)
| Feat | Use Case |
|------|----------|
| **Sentinel** | Harder movement lock paired with reach; choose if party benefits more from pinning than raw DPR. |
| **Tough** | Attrition or low-healing campaigns; raises buffer for Armor of Agathys value. |
| **Inspiring Leader** | Party durability across many short rests (temp HP scaling with CHA). |
| **Piercer** (if frequent spear shield stance) | Slight sustained DPR + crit bump for piercing mode while advancing STR/DEX by +1 if needed. |
| **Fey Touched** | Adds Misty Step (if not already) + a 1st-level enchantment/divination (e.g., Hex) and +1 CHA (can help reach 20 earlier). |
| **Skill Expert** | Patch Athletics (grapple/shove) *and* a social or perception gap while nudging a stat +1. |

**Choosing Between Resilient (CON) vs War Caster:**
| Factor | Resilient (CON) | War Caster |
|--------|-----------------|-----------|
| Concentration Math | Boosts *and* gains proficiency | Advantage only (if you already have proficiency it narrows gap) |
| Somatics w/ Shield | Needs free hand / focus juggling | Automatically solved |
| Reaction OA Spell | No | Yes (Booming Blade / EB if DM allows) |
| Synergy if low DEX | Better (more CON save total) | Slightly weaker for raw saves |

Rule of Thumb: If you lack CON save proficiency (you do) and value numerical reliability → Resilient (CON). Choose War Caster if you aggressively plan on Booming Blade OAs in tight lanes or constantly cast in shield stance.

### TL;DR Selection Flow
1. Always take PAM first.
2. If you will reliably have advantage scaffolding → take Elven Accuracy second.
3. If concentration wobble is hurting you more than missed crit chains → prioritize Resilient (CON) before +2 CHA or GWM.
4. Only add GWM if reach stance with advantage is a majority of encounters; otherwise finalize with resilience/control feat.

---
**Alternative / Niche Feats:** *Tough*, *Inspiring Leader*, *Sentinel*, *Piercer*, *Fey Touched*, *Skill Expert* (see table above) can replace the 4th slot or displace Elven Accuracy if you abandon heavy crit focus.

### 7.1 GWM Value Assessment & Alternatives
This subsection helps you decide whether to TAKE, DELAY, or SKIP Great Weapon Master entirely based on your table conditions.

**Where It Works:** Only while swinging the *heavy* reach weapon (glaive/halberd). In shield mode (longsword or spear) the -5/+10 option is disabled; you still keep the crit/kill bonus action trigger (which competes with the PAM butt).

**Core Break‑Even Math (Baseline Swing, No Smite):**
Let p = original hit chance (including crits), p' = hit chance after -5. DPR improves if 10 * p' > 5 * p (difference in static) → (Weapon+mods ignored for ratio) → more directly using expected weapon+static example yields empirical threshold ≈ p'/p > 0.697 for a d10 + mods build. Practical translation: AFTER applying the -5 penalty you must retain about 70% of your prior hit probability for -5/+10 to be a net gain on that attack.

**Advantage Impact (Representative AC 18–20, mid/high levels attack bonus +11 to +13):**
| State | Single-Roll Hit% (ex) | After -5 | Ratio | GWM Toggle? |
|-------|-----------------------|----------|-------|-------------|
| No Advantage vs AC 20 | ~70% | ~45% | 0.64 | OFF |
| Advantage (2d20) | ~91% | ~70% | 0.77 | ON |
| Elven Accuracy (3d20) | ~97% | ~70% | 0.72 | ON |
| Adv + Bless (avg +2.5) | ~94% | ~75% | 0.80 | ON |
If you cannot *regularly* secure at least normal advantage, GWM’s toggle spends most of combat OFF, sharply lowering its feat ROI.

**Bonus Action Conflict:** PAM butt (always available) vs GWM bonus swing (conditional). Often the reliable d4 + radiant + static from PAM is sufficient; GWM adds *spikes* when crit/kill chains happen. If your bonus action is already taxed (Vow of Enmity opener, Hexblade's Curse mid-fight, Misty Step reposition, casting, or spear shield-mode PAM butt), incremental value declines.

**Mode Uptime Consideration:**
| Reach Weapon Usage | GWM Value | Guidance |
|--------------------|-----------|----------|
| >70% of rounds AND frequent advantage | High | TAKE (earlier) |
| ~50–70%, advantage common | Moderate | DELAY (after core CHA 20) |
| <50% or sparse advantage | Low | SKIP (choose alt feat) |

**Opportunity Cost (Alternatives & What They Do):**
| Alternative | What You Gain Instead of GWM | When Superior |
|-------------|------------------------------|---------------|
| Resilient (CON) | +1 CON & proficient CON saves; better concentration on Bless/Haste/Spirit Shroud | If concentration frequently breaks or you lack Warcaster |
| War Caster | Advantage on concentration; somatic w/ shield; BB/EB opportunity cast | Shield mode heavy or casting OAs plan |
| Sentinel | Locks movement, procs OAs even on Disengage; stacks w/ reach threat | Party needs harder control, not raw DPR |
| +2 CON | HP, concentration baseline, better survivability scaling | High-lethality / attrition campaigns |
| Tough | Large front-loaded HP buffer | Low-magic healing / many small combats |
| Inspiring Leader | Party-wide temp HP per long/short rest (DM dependent) | Team durability focus; multiple martials benefit |
| Piercer (if spear build) | +1 STR/DEX, reroll 1 pierce dmg, +1 die on crit | Spear shield stance common & crit fishing continues |
| Skill / Utility Feat (e.g., Skill Expert, Telekinetic, Fey Touched) | Versatility / extra control or mobility | Campaign emphasizes exploration / social / control layering |

**Decision Quick Flow:**
1. Do you engineer advantage (Vow, Faerie Fire, prone) most rounds with the *glaive* out? If NO → skip.
2. Is reach mode your dominant stance (≥60% rounds)? If NO → skip or delay.
3. Are concentration failures costing major tempo? If YES → take Resilient (CON) first, revisit GWM later.
4. Need tighter lockdown for party synergy? Sentinel may outperform GWM’s personal DPR gains.

**Take GWM If:** You live in reach stance, have routine advantage scaffolding, and want peak burst/nova scaling on non-smite rounds.

**Delay GWM If:** You still lack 20 CHA or your concentration is fragile.

**Skip GWM If:** Dungeon crawl/tight maps force shield mode often, or party already saturates boss HP thresholds and needs reliability/control.

**Bottom Line:** GWM is *situationally great* here—not mandatory. Optimize around *advantage infrastructure first*; if that foundation is inconsistent, invest in resilience or control instead.

---
## 8. Weapon Modes
### Reach Great Weapon Mode
| Weapon | Halberd / Glaive (d10) |
| Style Transition | Dueling → Defense (on ASI respec if allowed) OR keep Dueling for 1H mode, accept lost synergy 2H |
| Core Loop | Threaten approach; OA + smite choice; proning via Eldritch Smite denies movement |
| Pros | Zone control, earlier crit trial (reaction), pairs with PAM butt scaling |
| Cons | Lower AC (no shield), reliant on positioning, narrow corridors reduce reach benefit |

### Sword & Shield Mode
| Weapon | Longsword (versatile) or Battleaxe / Warhammer |
| Shield | +2 AC; combined with Defense style + aura = durable platform |
| Use Cases | Boss phases with high hit bonuses; ranged magic attrition; when party lacks front blockers |
| Pros | AC spike (plate 18 + shield 2 + Defense 1 + magic 2 = 23 baseline potential before Shield spell) |
| Cons | Lose PAM entry OA & -5/+10 damage option entirely (no heavy weapon); fewer bonus action damage riders |

**Practical Swap:** Hex Warrior allows CHA use on chosen pact-bound weapon; bind both a reach option and 1H fallback after long rest (one via pact, one selected Hex Warrior slot). Keep a magical polearm prioritized for attunement; 1H can be generic +X.

#### Optional Spear & Shield Variant (Retain PAM Butt Attack)
If you want to keep a meaningful damage bonus action while shielded, a *spear* (now explicitly supported by Polearm Master per errata) lets you continue making the PAM d4 butt attack in defensive stance. Trade‑offs:
* Pros: Maintains PAM bonus action and entry OA trigger (since you’re still wielding a qualifying polearm); higher sustained DPR than a longsword shield stance because of extra hit instances (each carrying Improved Divine Smite + Curse static); smoother transition—no mental switch-off of PAM tactics.
* Cons: Base one‑hand damage die drops to d6 (vs longsword’s d8), losing ~1 average weapon damage per main attack; far fewer published magic spears than magic swords (loot reliability); still cannot use GWM’s -5/+10 while shielded (spear isn’t heavy).
* Recommendation: Choose spear if your table often lets you sit in shield mode for multiple rounds and your bonus action is typically free. Choose longsword if you expect more magical upgrades or your shield stance is primarily about survival and reaction bandwidth (Counterspell/Shield) rather than DPR.

---
## 9. Action / Bonus / Reaction Economy
| Economy Slot | Competing Uses | Prioritization Logic |
|--------------|----------------|----------------------|
| Bonus Action | PAM butt, GWM bonus swing, Vow of Enmity, Hexblade’s Curse, Misty Step, Spiritual Weapon (Conquest list), Shield of Faith (cast) | Early fight: Vow / Curse. Mid: choose *either* butt *or* GWM bonus (not both). Avoid crowding. |
| Reaction | Soul of Vengeance attack (Vengeance 15), PAM OA (entry), Opportunity Attack (leaving), Shield spell, Counterspell (if selected) | Prioritize free Soul swing > PAM OA > Shield vs lethal hit. Eldritch Smite costs no reaction. |
| Concentration | Bless, Haste, Spirit Shroud (alt), Darkness, Faerie Fire | Use ONE. Ladder: Bless (team >1 striker), Haste (safe, extended fight), Spirit Shroud (if persistent melee cluster), Faerie Fire (if no friendly hazard), Darkness (selfish) |

---
## 10. Spell Selection
### Paladin (Effective Caster Level 7 ⇒ Slots: 4/3/3/1)
**1st:** Bless (core), Shield of Faith (situational), Wrathful Smite (lockdown alt), Divine Favor (niche radiant vs regen).  
**2nd:** Find Steed (utility & scouting), Aid (HP pad), Lesser Restoration, Magic Weapon (only if weapon drought), Hold Person (crit enabler vs humanoids).  
**3rd:** Aura of Vitality (out-of-combat heals), Haste, Spirit Shroud (damage scaling alternative to Hex), Revivify, Dispel Magic.  
**4th:** Death Ward, Staggering Smite (swing debuff), Banishment (slot from earlier but still core removal), Freedom of Movement (if grapple heavy).

### Warlock (Pact Slots: 2 × 3rd per short rest)
| Level | Pick | Role |
|-------|------|------|
| 1 | Armor of Agathys | Pre-fight buffer → punishes hits (scales per slot) |
| 1 | Shield | Emergency AC spike (slot discipline) |
| 2 | Darkness *or* Misty Step | Advantage engine (with Devil’s Sight) *OR* reposition |
| 3 | Counterspell | Reactive denial |
| 5 | Hypnotic Pattern (optional) | Wide AoE control (if party lacks) |
| — | Shadow of Moil (War 7 dip) | Self-advantage + damage; requires reallocation path |

**Cantrips:** Eldritch Blast, Green‑Flame Blade (early fill), Toll the Dead / Booming Blade (if Warcaster OA plan), Prestidigitation (utility).

**Concentration Discipline:** Avoid swapping concentration mid-fight unless first effect is nullified or ended; wasted rounds = steep DPR loss.

---
## 11. Invocations (3 Total)
| Invocation | Rating (Build Context) | Reasoning |
|------------|------------------------|-----------|
| Agonizing Blast | Mandatory | Ranged fallback; scales with CHA investment |
| Improved Pact Weapon | High | +1 (if needed), focus, swap ease between loadouts |
| Eldritch Smite | High | Nova + control (prone) at Warlock 5 | 

**Flex Alternatives:** Devil’s Sight (if Darkness route), Eldritch Mind (advantage on concentration – can displace Resilient/Warcaster), Thirsting Blade (NOT needed; Paladin Extra Attack already there).

---
## 12. Resource & Rest Cycle Management
| Resource | Pool | Use Guidance |
|----------|------|--------------|
| Pact Slots | 2 (3rd) / short rest | Armor of Agathys (15 temp HP) pre-fight; Eldritch Smite (reserve 1); emergency Shield |
| Paladin Slots | 1st–4th long rest | Divine Smites (crit), Bless/Haste uptime, utility (Revivify) |
| Channel Divinity | 1 / short rest | Open with Vow on boss OR hold if AC unknown; alternate with Curse across fights |
| Hexblade’s Curse | 1 / short rest | Prioritize on predicted long-lived target; delay if scouting phase needed |
| Lay on Hands | 75 HP pool | Spot revive at 1 HP (5 points) beats cure spells mid-battle |
| Cleansing Touch | 3 / long rest | Strip enemy debuffs (Hold / Slow / Bane) or free an ally without spending slot |

---
## 13. Nova Math Snapshots (Representative)
Assumptions: Glaive (d10), CHA 20, Improved Divine Smite, Lifedrinker *not taken (Warlock <12)*, Hexblade’s Curse active, GWM toggled, crit event.

**Rules Clarification:** 4th-level Divine Smite = 5d8 (crit → 10d8). Eldritch Smite (3rd-level slot) = 4d8 (crit → 8d8). Static bonuses (GWM +10, Curse +Prof, CHA) are not doubled.

**Single Crit Attack (No Eldritch Smite):**
- Weapon: 2d10 ≈ 11
- Improved Divine Smite: 2d8 ≈ 9
- Divine Smite (4th-slot crit): 10d8 ≈ 45
- GWM static: +10
- Hexblade’s Curse: +6
- CHA mod: +5
= ~86 average

**Add Eldritch Smite (3rd-slot crit):** +8d8 ≈ 36 → ~122 average. Prone rider multiplies party follow-up.

**Round DPR Context:** With two attacks + PAM bonus (non-crit baseline ~ (d10 5.5 + 1d8 4.5 + 5 CHA + 6 curse + 10 GWM) ≈ 31 per hit before hit chance) plus butt (d4 2.5 + 1d8 4.5 + 5 + 6 + 10) ≈ 28; sustained (no smites, 50% hit @ GWM advantage scenario ~ expected ~40–45 DPR). Nova eclipses 150+ when multi-crit / OA triggers added.

---
## 14. Defensive Layering & Sustain
| Layer | Mechanic | Timing |
|-------|----------|--------|
| AC Stack | Plate 18 + Shield 2 + Defense 1 + Magic +1–2 | Shield mode phases |
| Active Buff | Shield Spell (+5) | Only vs significant multi-attack burst |
| Temp HP Reflect | Armor of Agathys (15 @ 3rd, 20 @ 4th if War 7 dip) | Pre-engage vs expected chip swarms |
| Saves | Aura of Protection (+5) + Resilient CON | Maintains Haste / Bless |
| Condition Cleanse | Cleansing Touch | Preserve action economy; ignore enemy control attempts |
| Fear Immunity | Aura of Courage | Dragon / terror aura insurance |

---
## 15. Oath Choices
High-level: Pick the oath whose *level 3 + 7 package* most directly advances your plan (advantage engine, mitigation, or hard control). Paladin 15 adds a distinct feature for every oath (e.g., Soul of Vengeance / Undying Sentinel / Scornful Rebuke); weigh its value against multiclass dip options (§22).

| Focus Type | Best Oath | Why |
|------------|----------|-----|
| Reliable single-target advantage / crit fishing | Vengeance | Vow of Enmity (Channel Divinity) + Soul of Vengeance reaction + spell list (Misty Step, Haste, Banishment) |
| Party-wide magical durability / attrition | Ancients | Aura of Warding halves spell damage; excellent against casters / AoE |
| Battlefield lockdown via fear & speed zero | Conquest | Aura of Conquest (speed 0 for feared) + synergizes with prone / reach / Sentinel (if taken) |

If choosing Ancients, Darkness package is *less necessary*; your defensive edge comes from resistance, allowing more open vision tactics (Faerie Fire). Vengeance maximizes Elven Accuracy value. Conquest requires reliable fear applications and enemies that aren’t immune (undead, constructs, some fiends/dragons reduce value).

### 15.1 Oath Feature Timeline & Comparison
Below, each oath’s key features (levels 3, 7, 15, 20) and spell list additions (spell level shown) with a quick evaluation in the context of a Pal 15 / Hex 5 (or Pal 13 / dip) PAM build.

#### Oath of Vengeance (PRIMARY Recommendation)
| Paladin Level | Feature / Spells | Evaluation (Build Context) |
|---------------|------------------|----------------------------|
| 3 | Spells: (1) Bane, Hunter's Mark. Channel Divinity: Abjure Enemy (fear/slow), Vow of Enmity (1 min advantage vs one target) | Vow = cornerstone crit/accuracy engine enabling GWM toggles & Elven Accuracy; Abjure niche (speed control / fiends & undead disadvantage on checks) |
| 5 | Spells: (2) Hold Person, Misty Step | Misty Step mobility fits BA budget early; Hold Person = crit enabler vs humanoids (nova alignment) |
| 9 | Spells: (3) Haste, Protection from Energy | Haste is premium sustained DPR + AC + speed; synergizes with control reach; Prot Energy situational |
| 13 | Spells: (4) Banishment, Dimension Door | Banishment core control; Dim Door reposition / extraction; both high utility |
| 15 | Soul of Vengeance (reaction attack vs Vow target) | Extra crit vector; reaction competition with PAM OA / Shield |
| 17 | Spells: (5) Hold Monster, Scrying | (Beyond base plan) Hold Monster replicates Hold Person value more broadly, fuels crit nova |
| 20 | Avenging Angel (transform, fly, frighten aura) | Powerful capstone, but unreachable if you reallocate after 13/15 |

Summary: Vow of Enmity’s sustained advantage + Soul of Vengeance reaction swing compound crit odds; spell list curates mobility (Misty Step), buff (Haste), and removal (Banishment) — aligning with reach control + crit smite strategy.

#### Oath of the Ancients (DEFENSIVE Alternative)
| Paladin Level | Feature / Spells | Evaluation (Build Context) |
|---------------|------------------|----------------------------|
| 3 | Spells: (1) Ensnaring Strike, Speak with Animals. Channel Divinity: Nature's Wrath (restrain), Turn the Faithless (fey/fiend turn) | Nature’s Wrath gives single‑target restrain (save STR/DEX) – can replicate prone control; Turn niche |
| 5 | Spells: (2) Misty Step, Moonbeam | Misty Step still great; Moonbeam concentration competes with Bless/Haste (lower priority) |
| 9 | Spells: (3) Plant Growth, Protection from Energy | Plant Growth strong area slow (out of combat setup); Prot Energy situational |
| 13 | Spells: (4) Ice Storm, Stoneskin | Both concentration or mid damage; Stoneskin expensive (costly vs non-physical magic bypass) |
| 7 | Aura of Warding (spell damage resistance for you + allies within 10 ft) | Huge mitigation vs casters; preserves HP & concentration; high party value |
| 15 | Undying Sentinel (drop to 1 HP once / long rest, immobile by age) | Strong safety net; sustains concentration through lethal spike |
| 17 | Spells: (5) Commune with Nature, Tree Stride | Exploration tilt |
| 20 | Elder Champion (regen & improved spells) | Excellent sustain late, rarely reached |

Summary: Aura of Warding dramatically cuts magical attrition; excels in spell-heavy campaigns. Sacrifices Vow’s guaranteed advantage, so crit fishing less reliable (EA value lower); may shift priority away from GWM to resilience feats.

#### Oath of Conquest (CONTROL Alternative)
| Paladin Level | Feature / Spells | Evaluation (Build Context) |
|---------------|------------------|----------------------------|
| 3 | Spells: (1) Armor of Agathys, Command. Channel Divinity: Conquering Presence (fear burst), Guided Strike (+10 attack) | Guided Strike = accuracy spike for critical smite attempt; Conquering Presence sets up Aura lockdown if it lands |
| 5 | Spells: (2) Hold Person, Spiritual Weapon | Spiritual Weapon adds BA competition; Hold Person synergy as usual |
| 9 | Spells: (3) Bestow Curse, Fear | Fear pairs with Aura of Conquest (speed 0 + psychic dmg) — huge lockdown if enemies fail |
| 13 | Spells: (4) Dominate Beast, Stoneskin | Situational/ costly; limited improvement |
| 7 | Aura of Conquest (reduce speed to 0 of frightened enemies + psychic damage = CHA mod) | Core engine: combine with Fear / Conquering Presence for immobilization inside your reach threat zone |
| 15 | Scornful Rebuke (CHA psychic damage to creatures that hit you in melee) | Reactive damage (small); synergizes modestly with high AC / retaliation theme |
| 17 | Spells: (5) Dominate Person, Cloudkill | Dominate strong if it lands, Cloudkill rarely synergistic with frontline positioning |
| 20 | Invincible Conqueror (resist all damage, extra attack) | Potent capstone; unreachable if dipping early |

Summary: Highest ceiling for *area denial* when fear lands: immobilize cluster inside 10‑ft reach + PAM OAs. Weak vs fear-immune foes; resource / save variance risk. Works well if party can pile on frightened targets (e.g., Wizard Hypnotic Pattern alternative when ineffective). Requires social contract to manage fear effects (does not stack with some party strategies).

### Quick Comparative Highlights
| Aspect | Vengeance | Ancients | Conquest |
|--------|-----------|---------|----------|
| Advantage Reliability | Excellent (Vow) | Low (must source elsewhere) | Medium (Guided Strike 1/short rest burst) |
| Defensive Mitigation | Moderate (Haste AC; mobility) | High (Aura of Warding) | Moderate (fear reduces attacks if enemies can’t approach) |
| Control Radius | Low (single-target) | Low-Moderate (restrain CD) | High (Aura + fear combos) |
| Synergy with GWM / EA | Peak | Reduced | Good (Guided Strike enables safe -5 turn) |
| Campaign Type Fit | Boss-centric / nova | Spell/AoE heavy attrition | Crowd / morale manipulation |

**Recommendation Recap:** 
Primary pick remains **Vengeance** for consistent crit engine. Choose **Ancients** if magical damage survival & concentration integrity outpace the need for crit reliability. Opt **Conquest** if your DM field composition rarely invalidates fear and your party wants static zones where enemies cannot leave.

---
## 16. Darkness / Vision Package
| Path | Components | Upside | Downside |
|------|-----------|--------|----------|
| Darkness Control | Darkness spell (racial 1/day or slot) + Devil’s Sight | Solo advantage, enemy disadvantage | Party blindfire; table enjoyment risk |
| Faerie Fire Support | Racial Faerie Fire + Elven Accuracy | Party-wide advantage, no LoS penalty | Concentration competition; saves apply |
| Shadow of Moil | Self-advantage + damage | Non-racial; immune to counter-light tactics | 4th-level slot overtime cost |

**Guidance:** Favor Faerie Fire path unless party explicitly supports Darkness (Blind Fighting style, similar vision aids).

---
## 17. Magic Item Priorities
| Slot | Priority Items | Rationale |
|------|---------------|----------|
| Weapon (Reach) | +2/+3 Glaive or Halberd, Sunblade (if allowed versatile), Flame Tongue (early nova augment) | Core DPR scaling |
| Weapon (1H) | Defensive +X Longsword, Radiant / utility on-hit | Shield mode reliability |
| Armor | Plate +1/+2; Adamantine (crit mitigation) | Prevent spike variance |
| Shield | +1/+2 Shield; Sentinel Shield (initiative + adv perception) | Engage early & stable defense |
| Ring | Spell Storing (Bless / Shield / Cure), Protection | Slot economy / passive defenses |
| Amulet | Holy Symbol of (X) +1; Amulet of Health (if CON lacked) | Save boost / stat smoothing |
| Cloak | Displacement (early), Protection; Cape of Mountebank | Opening reposition / panic button |
| Wondrous | Belt of Giant Strength (if STR route chosen instead) – otherwise deprioritize | If pivot to STR-based variant |
| Rod/Wand | Pact Keeper (+1–3) | Boost EB / spell DC; slot recovery |

---
## 18. Tactical Cheat Sheet
| Situation | Plan |
|-----------|------|
| Boss (unknown AC) | Open with Vow (adv reliability) → test AC → apply Curse next short rest cycle if overkill risk low |
| Swarm / Minions | Bless + Aid; avoid early Eldritch Smite; use PAM OA funnel |
| High Mobility Enemy | Ready OA zone; Misty Step chase; consider Eldritch Smite for prone denial |
| Spellcaster Elite | Close with Vow (force disadvantage via Darkness only if party ok); Counterspell key casts; Smite on crit |
| Attrition Dungeon | Reserve pact slots for Shield / AoA; reduce over-smite habit; prioritize Improved Divine Smite baseline DPR |

---
## 19. Common Pitfalls & Mitigations
| Pitfall | Mitigation |
|---------|-----------|
| Blowing both pact slots on first crit | Hold 1 for threat; only double-smite on pivotal elimination |
| Stacked bonus action backlog | Pre-plan opener (Vow or Curse, not both same round if also wanting PAM butt) |
| Darkness griefing allies | Default to Faerie Fire or Shadow of Moil; communicate intent |
| Overusing Shield spell | Evaluate incoming DPR vs future slot demand for AoA / Counterspell |
| GWM always on | Toggle only with advantage + Bless / Faerie Fire / Vow present |

---
## 20. Roleplaying Hooks
- **Redeemer of Shadow:** Weapon pact forged to harness drow ancestral magic responsibly under a sacred oath – tension between heritage and sworn radiance.
- **Tactician of Reach:** Polearm is an arcane focus – runic inlays pulse with pact energy on smite, visualizing the blend of oaths and eldritch promise.
- **Shadow Cavalier (late game):** Summoned steed emerges from overlapping radiance and umbral wisps – symbolizing internal balance.

Conflict Themes: Use of manipulative darkness vs party trust; moral calculus in expending overwhelming nova vs measured justice.

---
## 21. Quick Reference Summary
| Aspect | Value |
|--------|-------|
| Split | Paladin 15 / Hexblade 5 |
| Core Feats | PAM → Elven Accuracy → +2 CHA → (GWM OR Resilient CON / War Caster) |
| Modes | Reach Glaive (control + PAM) / Sword+Shield (defense) |
| GWM Note | -5/+10 damage option only while using the heavy reach weapon (glaive/halberd), not in shield mode |
| Nova | Crit + Divine Smite (4th) + Eldritch Smite (3rd) ≈ 100+ avg burst single swing |
| Sustain | Improved Divine Smite + PAM butt + Curse static |
| Defense | Plate, Shield (situational), Aura, AoA buffer, Shield spell |
| Control | Reach OA, prone (Eldritch Smite), optional Faerie Fire, Banishment |
| Utility | Lay on Hands, Cleansing Touch, Revivify, Find Steed (scouting) |
| Advantage Suites | Vow of Enmity, Faerie Fire (racial), Elven Accuracy, (optional Darkness package) |

---
**Final Thought:** Pushing Warlock only to 5 secures elite nova cadence while preserving Paladin’s deep kit (auras, cleansing, 4th‑level slots, improved radiant throughput). Polearm Master transforms that chassis into battlefield architecture – you *decide* enemy entry vectors. The shield stance lets you pivot when survival outranks reach. Play patiently: advantage scaffolding before GWM toggle; smite only when meaningful. The result is a flexible, resilient, tactically rich striker who commands melee space.

Happy hunting.

---
## 22. Reallocating Levels (Dropping Paladin 14–15)
If you decide Paladin 14 (Cleansing Touch) and Paladin 15 (your oath’s 15 feature) are underwhelming for your table, you can stop at Paladin 13 / Warlock 5 (retaining 4th‑level spells & Improved Divine Smite) and repurpose the final TWO character levels elsewhere. Here’s what you lose and what you can gain.

**What You Forfeit by Capping at Pal 13:**
| Lost | Impact |
|------|--------|
| Cleansing Touch (3/day dispel) | Reliable self/ally debuff purge; saves slots vs repeated Hold / Slow |
| Oath 15 Feature (Soul of Vengeance / Undying Sentinel / Scornful Rebuke) | Reaction attack (Vengeance), death denial (Ancients), chip damage (Conquest) |
| 2nd 4th‑Level Paladin Slot (Pal 15 table) | Slight reduction in high-tier smite / spell endurance |

**Baseline Chassis Retained:** Aura of Protection, Improved Divine Smite, 4/3/3/1 slot progression, all core auras, Channel Divinity cadence, heavy armor, GWM/PAM engine (if chosen).

### Top Replacement Paths (Two-Level Packages)
| Package | Resulting Split (Examples) | Gains | Synergy Rating |
|---------|----------------------------|-------|----------------|
| Fighter 2 | Pal 13 / War 5 / Ftr 2 | Action Surge (extra Attack action = 2 more swings + smite windows), Fighting Style #2 (Defense / Dueling / Blind Fighting) | S (Highest immediate nova & flexibility) |
| Sorcerer 2 (1–2 dip) | Pal 13 / War 5 / Sor 2 | CON save proficiency (Sor 1), Metamagic (Quickened = bonus-action Hold Person / Darkness / EB; Twinned low-level buffs), extra CHA-based spell list (Absorb Elements) | A |
| Warlock +2 (to 7) | Pal 13 / War 7 | Pact slots to 4th level (bigger Eldritch Smite +1d8, Armor of Agathys 20 THP), one more invocation *if* you later go War 8 (needs +3 lvls total) | B+ (requires Darkness/AoA plan) |
| Fighter 1 + Sorcerer 1 | Pal 13 / War 5 / Ftr 1 / Sor 1 | Fighting Style (stack), Second Wind, CON save proficiency, low-level sorcerer spells | B |
| Bard 2 | Pal 13 / War 5 / Brd 2 | Jack of All Trades (initiative boost), Bardic Inspiration (d6), extra support spells | B- (utility > DPR) |
| Rogue 2 | Pal 13 / War 5 / Rog 2 | Expertise, Cunning Action, Sneak 1d6 (occasionally adds), skills | C+ (mobility/skills, low combat gain) |
| Cleric 1 + Fighter 1 | Pal 13 / War 5 / Clr 1 / Ftr 1 | Domain feature (e.g., Peace for Emboldening Bond; Twilight for temp HP), extra Fighting Style via Fighting Initiate alt (if allowed) | C+ (table / domain dependent) |
| Warlock +1 (to 6) + 1 floating | Pal 13 / War 6 / X 1 | Accursed Specter (weak scaling), small control minion; one spare dip (Fighter 1 or Sorc 1) | C |

### Detailed Notes
**Fighter 2 (Action Surge):** Doubles your nova window on demand: two extra weapon attacks = two additional crit/smite chances, or post-Hold Person burst. Style pick: Defense (if you kept Dueling), Blind Fighting (negates darkness self-tax, freeing invocation), or Interception for party mitigation.

**Sorcerer 1–2:** Sorcerer 1 grants CON save proficiency instantly (if you didn’t already take Resilient CON), potentially freeing that feat slot. Sorcerer 2 provides Metamagic: Quickened Spell lets you cast a concentration spell (Hold Person / Darkness / Spirit Shroud if swapped) and still attack; Twinned Spell works on low-level single-target buffs (Bless cannot be twinned) or Hold Person early. Subclass: Divine Soul expands list (Guiding Bolt, Bless redundancy), Shadow grants Strength of the Grave + synergy with darkness thematics.

**Warlock 7:** Incremental power: Eldritch Smite scales (4d8 → 5d8), Armor of Agathys 15→20 temp HP, access to 4th-level known spells (Shadow of Moil). Opportunity cost: delays dips; still far from Armor of Hexes (War 10).

**Hybrid Fighter 1 + Sorcerer 1:** If Action Surge is less critical but you want a blend of style + CON saves + a couple of utility spells (Shield already known? choose Absorb Elements, Feather Fall), this distributes benefits, though lacks the spike of Fighter 2 or the metamagic depth of Sorc 2.

**Bard 2:** Jack of All Trades improves initiative (important for setting up Vow / Faerie Fire before allies act). College of Swords (if 3rd, needs extra level) would allow Blade Flourishes; with only two levels you mainly gain Inspiration dice—still helpful but not transformative.

**Rogue 2:** Expertise (Athletics + Intimidation) empowers grapples/shoves (prone setup without smite expenditure) and social dominance. Cunning Action for Dash/Disengage liberates Misty Step slot usage. DPR impact minor; Sneak Attack seldom applies without tactical set-up (needs finesse or ranged; your glaive isn’t eligible unless DM allows versatile interactions with spear + Dex build—outside intended STR/CHA focus).

**Cleric 1 + Fighter 1:** Peace Domain’s Emboldening Bond can mimic a mini-Bless without concentration (scales with proficiency uses) but DM gating may apply. Twilight’s 1d6+lvl temp HP aura is strong but may overshadow party balance concerns. Action Surge absence keeps nova ceiling lower than Fighter 2 path.

**Warlock 6 (Accursed Specter) + 1 Flex:** Specter offers marginal battlefield presence; its offense and durability lag at higher tiers. Use only if narrative strongly favors deepening pact flavor; pair with Fighter 1 or Sorc 1 for a mixed package.

### Ranking Summary
| Rank | Package | Rationale |
|------|---------|-----------|
| S | Fighter 2 | Largest immediate burst + versatile style pick; simple execution |
| A | Sorcerer 2 | Metamagic utility + CON save proficiency; flexible action economy |
| B+ | Warlock 7 | Incremental pact scaling; supports Darkness/AoA strategies |
| B | Fighter 1 + Sorcerer 1 | Broad but shallow; still nets CON saves + style |
| B- | Bard 2 | Initiative & support improvements; low direct DPR |
| C+ | Rogue 2 | Mobility + skill focus; minor offensive gain |
| C+ | Cleric 1 + Fighter 1 | Situational domain power + minor combat tool |
| C | Warlock 6 + 1 | Weak feature; mostly flavor |

### Decision Guidance
Choose Fighter 2 if your table highlights set-piece boss fights and you crave higher ceiling novas.
Choose Sorcerer 2 if concentration retention & tactical casting flexibility outvalue once-per-short-rest burst.
Choose Warlock 7 if you lean heavily on Armor of Agathys, Eldritch Smite scaling, or Shadow of Moil pacing.
Otherwise, remain Paladin 14 for Cleansing Touch if your campaign is debuff-heavy (charm/hold/paralysis spam) and dispel reliability is saving real resources.

**Bottom Line:** The *opportunity* of two optimizable levels often outweighs Cleansing Touch + a single extra 4th-level slot + a moderate oath feature (unless Soul of Vengeance reaction swing is central). If Cleansing Touch or the 15 feature regularly saved encounters, stay; otherwise Action Surge / Metamagic usually deliver more encounter equity.

---
### Rules Accuracy Appendix (2014 PHB / XGtE)
Integrated Corrections:
1. GWM requires a heavy melee weapon (glaive/halberd) for -5/+10; bonus-action attack clause still works in shield mode on crit/kill with other weapons.
2. Hex Warrior + Pact of the Blade allows CHA on a two-handed pact weapon only after Warlock 3.
3. Invocation prerequisites: Improved Pact Weapon requires Pact of the Blade; Eldritch Smite requires Warlock 5 & Pact of the Blade.
4. Eldritch Smite damage = (slot level +1)d8 force (3rd-level slot = 4d8; doubled on crit).
5. Divine Smite: 1st-level = 2d8; +1d8 per slot level above 1st (4th-level slot = 5d8; crit doubles dice). Fiend/undead extra 1d8 (added then doubled) if applicable.
6. Armor of Agathys scaling: 3rd slot 15 temp HP (cannot reach 25 without a 5th-level slot); 4th slot 20 (if Warlock 7 dip).
7. Paladin 15 Vengeance feature (Soul of Vengeance) exists; reaction economy updated. Ancients (Undying Sentinel), Conquest (Scornful Rebuke) likewise clarified.
8. Hypnotic Pattern (3rd-level) available to a Warlock only once 3rd-level pact slots are gained (Warlock 5). Shadow of Moil requires 4th-level pact slots (Warlock 7).
9. Improved Divine Smite applies to every melee weapon attack (including PAM butt & reaction attacks).
10. Slot table confirmation: Paladin 15 half-caster effective level 7 → slots 4/3/3/1; Warlock 5 pact slots 2×3rd separate.

---
## 23. At-a-Glance Reference (Thresholds & Tables)
Designed for fast table consultation.

### GWM Toggle Quick Rule
Use -5/+10 only if (post-penalty hit chance) / (normal hit chance) ≥ ~0.70. With advantage vs typical AC (attack bonus +11 to +13), this is usually satisfied; without advantage, keep it OFF.

### Concentration DC Table
| Damage Taken (single hit) | Con Save DC |
|---------------------------|-------------|
| 1–20 | 10 |
| 21–40 | 11–20 (half damage) |
| 41–50 | 21–25 |
| 51–60 | 26–30 |
Add Aura of Protection (+CHA) + Resilient CON (if taken) to your d20; War Caster adds advantage (not proficiency).

### Divine Smite Damage (Average Added, Non-Crit)
| Slot Level | Dice | Avg Added | Marginal Gain vs Prior |
|------------|------|-----------|------------------------|
| 1st | 2d8 | 9 | — |
| 2nd | 3d8 | 13.5 | +4.5 |
| 3rd | 4d8 | 18 | +4.5 |
| 4th | 5d8 | 22.5 | +4.5 |
Crit doubles dice; add +1d8 (avg 4.5) vs fiends/undead (also doubled on crit).

### Eldritch Smite Damage (Average Added, Non-Crit)
| Pact Slot (Lvl) | Dice | Avg | Prone Rider |
|-----------------|------|-----|------------|
| 3rd | 4d8 | 18 | Str save to rise (costs half movement) |
| 4th (War 7 dip) | 5d8 | 22.5 | As above |
Crit: double dice (36 / 45 avg).

### Smite Efficiency Guidance
| Situation | Preferred Expenditure |
|-----------|----------------------|
| Early in long adventuring day | Save 4th-level slots for utility / Death Ward; use 1st–2nd on crits |
| Boss opener with advantage & full resources | 4th-level Divine Smite on first crit; add Eldritch Smite if target ≥50% HP |
| Target likely to die this round anyway | Use lower slot or none; rely on Improved Divine Smite |

### Reaction Priority (Vengeance 15)
1. Soul of Vengeance free attack (if triggers).  
2. PAM OA (entry / movement).  
3. Shield spell (if it prevents ~20+ expected damage or concentration loss).  
4. Opportunity Attack on exit (if no earlier trigger).  

### Bonus Action Priority (Typical)
1. Vow of Enmity (if not already active) OR Hexblade’s Curse (choose one first round).  
2. PAM butt (default filler if no competing high-impact BA).  
3. GWM bonus swing (only if butt already used prior round’s BA or high kill/crit chain).  
4. Misty Step / reposition.  
5. Spiritual Weapon (Conquest) if taken and sustained over multiple rounds.

### Slot Allocation Planner (Per 3–4 Encounter Adventuring Day)
| Resource | Encounter 1 | Encounter 2 | Encounter 3 | Encounter 4 (Boss) |
|----------|------------|------------|------------|--------------------|
| Pact Slot A | Armor of Agathys | Eldritch Smite | Eldritch Smite | Eldritch Smite |
| Pact Slot B | (Hold) | Shield (if needed) / Smite | Recovered → AoA | Eldritch Smite |
| 4th Pal Slot | (Save) | Death Ward (pre-boss) | — | Divine Smite (crit) |
| 3rd Pal Slots | Haste / Bless | Maintain | Recast if dropped | Spirit Shroud (if swap) |

### Ability Score / Feat Snapshot
| Path A (Nova) | PAM → Elven Accuracy → +2 CHA → GWM |
| Path B (Resilience) | PAM → Elven Accuracy → +2 CHA → Resilient (CON) / War Caster |

### Typical Endgame Numbers (Shield Mode / Reach Mode)
| Metric | Shield Mode | Reach (GWM Off) | Reach (GWM On w/ Adv) |
|--------|------------|-----------------|-----------------------|
| AC (Plate + Shield + Defense +1 magic) | 22–23 | 20–21 | 20–21 |
| Main Attack Hit Bonus (CHA 20, +1 weapon, Prof +6) | +12 | +12 | +7 (after -5) |
| PAM Butt Avg (no smite, no crit) | ~ (2.5 + 4.5 +5 +6)=18 | same | same |

### Quick Advantage Sources Checklist
Vow of Enmity • Faerie Fire • Darkness+Devil’s Sight • Prone (ally setup) • Guided Strike (Conquest accuracy assist, not advantage) • Restrain (Hold Person / Nature’s Wrath).

### Pre-Combat One-Liner
"Bless up, Vow target called, AoA loaded, polearm zone set."  

Keep this appendix printed or in a separate note for instant reference.
