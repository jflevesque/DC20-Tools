
```statblock
layout: DC20 Adversary
name: Adversary
image: [[DC20Logo.png]]
size: Medium
type: Beast
level: 3
archetype: Humanoid
hp: 13
pd: 8
ad: 10
mig: 3
agi: 3
cha: 0
int: 0
resistances:
- Bludgeoning (Half)
- Piercing (Half)
- Slashing (Half)
reductions:
- MDR
vulnerabilities:
- Radiant (Double)
immunities:
- Poison
- Umbral
immunities_conditions:
- Exhausted
- Grappled
skills:
- Awareness +3
- Stealth +2
- Trickery +5
languages:
- Common
- Elvish
senses:
- Darkvision 20
characteristics:
- name: Other
  desc: Stuff
features:
- name: Umbral Susceptability
  desc: When you take umbral damage you have disADV on next attack
- name: Devout
  desc: You have ADV on saves against being charmed or possessed
actions: 4
legendary_actions: 2
attack: +4
save_dc: 16
speed: 5
attacks_spells:
- name: (1) Radiant Flame
  desc: Ranged Spell attack vs PD 10 spaces, 1 Radiant
  traits:
  - name: (1) Super Flame
    desc: +1 Radiant
  - name: (1) Bite
    desc: Melee Martial Attack vs PD, 1 Piercing
reactions:
- name: Reaction
  desc: Reacts in a way
- name: Another Reaction
  desc: Reacts in a different way
apex_actions:
- name: Round 1
  desc: Name of the action
  traits:
  - desc: Long description of what happens
```
