---
Owner: VVervir
Last edited time: 2024-12-06T02:26
Created time: 2024-12-06T01:07
---
- [[#Introduction]]
- [[#Stat Checks]]
- [[#Combat]]
    - [[#Turn Order]]
    - [[#Turn Participants]]
    - [[#Turn Sequence]]
    - [[#Damage]]
        - [[#Spell Damage]]
        - [[#Movement Damage]]
        - [[#Weapon Damage]]
        - [[#Ability Damage]]
        - [[#Interactions With Damage]]
    - [[#Targeting]]
        - [[#Contact]]
        - [[#Sweep]]
        - [[#Target Extension]]

# Introduction

# Stat Checks

Stat checks are the core of many interactions in the Hereafter within and outside of combat. The Hereafter’s stat checks utilize a d6 by default unless otherwise stated, and are most often in addition to the numerical value of the checked stat, plus any modifiers.

  

# Combat

Combat initiates upon the same instant as the first use of any offensively-capable action that leads to a player taking a turn, and ends either via a mechanic like Deescalation or after all participants choose not to take additional turns. In practice, this means that combat begins when a player takes a turn and ends when all participants of combat no longer take turns. While the different internal mechanics of each Color combined with the auxiliary level systems that the players possess may change the minutia of combat, the overall structure of a turn in combat remains the same.

## Turn Order

The order in which turns are taken is initially decided in the order of initial response. Before tempo enters into play, the initiator of combat takes their turn. Following this initial turn, tempo begins to keep track, and all those on tempo will be able to act. The priority of action first goes to those not currently being affected by an opponent combatant, in any order of player’s choice for allies, followed by those actively being affected by an opponent combatant, again in any order of player’s choice for allies.

  

## Turn Participants

Each turn includes both the whole of the combatants and the group of immediate combatants. The one whose turn it is becomes an immediate combatant, and anybody targeted by an immediate combatant becomes an immediate combatant. The targeting does not need to be successful, the inclusion of a combatant in targeting is enough to render them an immediate combatant at that instant. Only immediate combatants may gain or lose advantage without other mechanics within a turn.

  

## Turn Sequence

A turn’s various events resolve in a specific order of phases:

- Start: Effects that take place at the starting place activate simultaneously and are placed on the stack. These often include the expiry of effects.

- Spell: The combatants’ first spell this turn and the types in the spell sequence are defined here, before actions. Combatants may cast spells during this phase.

- Action: The combatants’ initial actions occur simultaneously with their targeting criteria set. Combatants may cast spells during this phase.

- Results: The effects of the combatant’s actions resolve, such as damage, status effects, and other triggered effects.

- End: Tempo for the next turn is set at this point, as well who the immediate combatants of the next turn will be. Any remaining effects on the stack must resolve before the end step.

For purposes of general combat, one does not need to go over all five steps step-by-step every turn. The start and end phase are generally implicit, only brought up when an interaction on the stack triggers on those phases, such as the addition or expiry of stackable effects. Instant effects, such as invocations, can enter the stack at any time, taking effect immediately rather than resolving upon the spell step for spells, or upon the result step for actions.

A turn cannot end until all effects on the stack are cleared.

  

## Damage

Damage can be inflicted via the environment, actions, spells, and instant effects. Damage inflicted by actions is calculated at the instant that action resolves, and the same holds for spell damage being calculated when a spell resolves. All other forms of damage exist on the stack. Damage calculations often use a stat or the stat’s tier, which is the stat divided by five rounded down. (e.g. 12 is tier 2, 16 is tier 3). Below is the list of these damage types, listed by the order they apply in when multiple types of damage exist in one instance.

### Spell Damage

Spells that inflict damage on their own inflict spell damage, immediately inflicting the damage upon resolving.

### Movement Damage

Actions that inflict damage without weapons or abilities inflict movement damage, inflicting the PHY tier of the attacker as physical damage by default, subtracted by the defense of the target. Whenever a combatant would inflict movement damage while at a multiple of the combatant’s base movement speed, their damage is multiplied by that multiple of their movement speed, rounded down.

### Weapon Damage

Any time an action inflicts damage through a weapon, whether it is by an ability or movement, it inflicts any trait-based damage on the weapon first as instant damage, followed by triggering all on-hit effects, followed by the base damage of the movement plus the weapon’s damage roll modifier, and finally followed by triggering all on-damage effects.

### Ability Damage

Actions that inflict damage without weapons or movements inflict ability damage, first triggering all on-hit effects, followed by inflicting the scaling damage of the ability, followed by triggering all on-damage effects. If the damage was triggered by a non-specific ability, it inflicts its highest Color affinity’s tier as damage.

  

Environmental damage applies always at the result step, while instant effects apply upon resolving on the stack.

### Interactions With Damage

Because many forms of damage exist on the stack, one can take advantage of the Last-In First-Out (LIFO) nature of the effects stack by utilizing instant effects to either amplify or mitigate damage before it is calculated. For example, utilizing a Purge effect on a status effect that would deal damage at the beginning of the Start step would take first resolve, preventing that damage because the status effect has been Purged, while activating a damage-boosting instant effect on the Result step would not work for action-based damage, as the calculation of damage occurs at the instant of that step (instead, a damage-boosting effect must be present _before_ the Result step).

  

## Targeting

Targeting defines the criteria by which all combat-capable things affect their targets. Untargeted combatants cannot be affected by anything with a targeting criteria, unless that criteria does not require the target to be targetable or targeted at the time.

### Contact

Contact is defined as the farthest straight-line the combatant can currently achieve with their phantasm’s reach. Contact is typically the physical reach of the combatant, but becomes more or less than the baseline when the phantasm is contracted or stretched. Upon the breaking of a phantasm barrier, contact range is reduced to zero until the end of turn.

### Sweep

Sweep is the angle of reach the combatant can currently achieve in this instant, forming a section of a circle in combination with contact. A target must be within the sweep of the combatant to be targeted. Sweep typically begins at 90 degrees and expands further, amplified by weapons with superior sweep or rendered up to 360 degrees by the shape of the phantasm. Unlike contact, the breaking of a phantasm barrier does not reduce sweep. In cases of asymmetrical or non-arc phantasm shapes, the target must check AGI against the PRC of their combatant to avoid the sweep.

### Target Extension

When an ability uses a non-physical targeting criteria, such as many Color abilities, they may overcome the contact and sweep requirements, substituting them for a check in the relevant Color’s affinity based on the abstraction level of the targeting criteria. Upon the breaking of a phantasm barrier, targeting extension cannot be performed.

  

Most abilities require contact within sweep of the combatant, though other effects can target those not in physical reach, such as effects targeting those with a specific effect or type on them.