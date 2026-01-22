# Contraband Tagging Overhaul

| Designers | Implemented | GitHub Links |
|-----------|---|--------------|
| 2DSiggy   | :x: No | TBD       |

## Overview

This overhaul to contraband tagging is intended to make a more sensible. This is going to primarily be done by making contraband tagging deeper than a simple "Minor", "Major", "Highly illegal" system that provides little nuance. This is also designed to make it so certain highly illegal items can receive approval in round from players of authority (Nanotrasen Representatives, Magistrates, or Internal Affairs Agents.) This also makes the Highly Illegal category less important.

Space law would also be updated to accomodate these changes.

## Background

Contraband in game is seen as a very on or off system. It is frankly a joke that items such as the Antimov law board are treated with the same legal severity as a syndicate scarf even if it's only on paper. Such things lead to security players deciding that since they have nothing better to do, to pursue people using joke items that were either purchased for a gag or found in maintenance or other methods.

Also notable is that this would make owning an unauthorized firearm of any kind would be the same crime as owning a Syndicate Firearm. The only difference being security is not allowed to use Syndicate weapons.

Important context would be that firearm contraband, wearable contraband, and weapon contraband would be unmodified by context from being a Syndicate source.

## Features to be added

### New contraband subcategories

The main feature that would be added or changed is the removal of the "Highly illegal" contraband tags in exchange for more specific purpose related tags. Said items would still be illegal and should be confiscated but punishments should be lighter for various pieces of contraband. This would involve adding seven new contraband categories.

#### Souvenir Contraband

Souvenir Contraband as a tag would be added to indicate useless or gag items. Items that would fit into this category would mainly be items from the pointless category. Cat ears being the only exclusion. Notably, Souvenirs would not be confiscatable until the owner has committed a different crime.

#### Utility Contraband

Utility Contraband is for primarily items that are used for their unique features. Items such as Magboots, Voice Masks, Chameleon Clothing, Cybersun pens, and Binary encryption keys.

#### Chemical Contraband

Chemical Contraband is for items and purchases that are primarily reagents. Interdyne Cigarettes, Hyperzine Injectors, and the Chemical Synthesis Kit would be tagged with Chemical Contraband

#### Weapon Contraband

Weapon Contraband would be the category for all non-firearm weapons. Energy Swords, Combat knives, Throwing knioves, and similar items that would be tagged as Weapon Contraband.

#### Armor Contraband

Armor Contraband would consist of items designed for protection. Energy shields, Web vests, and hardsuits would be tagged as this category.

#### Firearm Contraband

Firearm Contraband is self-explanatory. Weapons that are firearms would fit into this category. Ammunition could be added to the category. Notably is that all forms of unauthorized firearms would be added to this category. Having an unauthorized Nanotrasen firearm would be the same crime as having a C-20r.

#### Terroristic Contraband

Terroristic Contraband is for items purely for causing mass death and destruction. The singularity beacon, syndicate bomb, and the various combat mechs would be added to this category, alongside cat ears to maintain the joke of cat ears being illegal items.

## Game Design Rationale

The fact syndicate branded clothing can be treated with the same legal severity as a high powered grenade launcher by a power-tripping Magistrate or Warden has always been a bother to me. The same for a Heretic's blade and their Codex Cicatrix. These items though being similar in origin are not anywhere nearly as close with their actual threat presented to the station by existing. Having an energy dagger shouldn't be a greater crime than owning an unauthorized WT550.

## Roundflow & Player interaction

This would primarily affect security and antagonists. Security would have less incentive to waste their time pursuing people with gag items while keeping them as confiscatable equipment. Items that are specifically for combat would still be sentence-worthy but items such as Syndicate Jaws of Life and the Cybersun pen would be a simple "confiscate on sight" issue.

## Administrative & Server Rule Impact (if applicable)

Outside of adjustments to space law and security needing to properly enforce space law, this would have little if any impact on server administration.

# Technical Considerations

This overhaul should not pose any difficulties for performance as it would be mostly yml and ftl. Difficulty would be in ensuring all items use the new contraband tagging though it can be done when new items are added to the game
