# DeCiv 2 Changelog

//
New Content
//

- Added Espionage content and spy names
    - Listening Post is now the Tier 1 anti-spy building
    - Field Office is the Tier 2 anti-spy building
    - Information Awareness Office is the National Intelligence Agency equivalent
    - Virtual Panopticon is the Great Firewall equivalent, but also reduces Unhappiness from population in all cities
- Added personalities
- Added new faction: The Hunnu (Mongolian themed raider gang)
- Added Community Garden (Neofeudal era Food building that boosts Great Person spawn rate, replaces Listening Post's old function)
- Added Domesday Project (Industrial era world wonder that boosts Great Person spawn rate and adds Science + Culture to luxuries worked by the city)
- Added Earthscraper (Information era building that adds more Food, more City HP, more protection from nukes, +1 population, and +1 of each specialist)
- Added Earthscraper Project (Information era national wonder that adds Production to active specialists and enables building Earthscrapers)
- Added Frumentarii Camp (Legion replacement for Listening Post, better spy defense)
- Added The Green Palace (Rebuilding era world wonder that creates a Factory farm, increases the yields of Factory farms, and increases Happiness in its city)

//
Balance Changes
//

- Arcology Dome now requires 20 population instead of 2 to build, but adds more City HP
- Arena/Colosseum now replace Stadium for Ignis/Legion
- Atlas, Blackwarden, Hexlock, Patriots all lose free Electronics Tech
- Barbarian Water units can no longer pillage tiles
- Computers and Radar now require Electronics
- Deadrock Clan now has better defense from spies and an extra spy instead of Barbarian recruitment
- Dinghy is no longer a Low Tech unit, addressing an issue caused for The Patriots
- Dinghy and Patrol Boat now obsolete at Manufacturing
- "Faction Identity" World Wonders are now automatically built when the capital is founded, due to changes in AI reverting behavior that previously encouraged them to build the wonders immediately
- Fixed problem of Unhappiness penalties applying at 0 Happiness
- Great Improvements cannot be placed on Mountains
- Helicopter units nerfed in several ways:
	- They no longer gain extra movement over water
	- They no longer evade melee attacks, aside from the Quadcopter Drone, which has its evasion chance reduced to 25%
	- They all lose 1 movement and cannot attack cities, aside from the Blimp and again, Quadcopter Drone
- Hydroponic Farming loses one Farmer slot
- Media Center is now a normal building instead of the worst National Wonder in the game
- Melee Naval units no longer have double movement in Coast, and aside from the Assault Ship they can no longer evade melee
	- Mariner Naval UUs have their evasion rate reduced from 66% to 20%
- Multiple Barbarian units (Biker, Outlaw, etc.) have been stripped of at least two free promotions each
- Power is no longer tradable
- Rationalism now makes the player more vulnerable to tech theft
- Rubble Gunman error of being a second Archer replacement for Deadrock is *finally* fixed (it now replaces Crossbowman)
- Scouts now upgrade to Forward Observers instead of Gunmen
- Shooter units no longer have Skirmish as an available promotion, but receive Forage to compensate
	- Forage is now a prerequisite for Suppression/Precision instead of Skirmish
- Springs can no longer have improvements other than Water pumps
- Standard and Salvaged Purge Robots now automatically start with Portable Power Cell, so Hexlock loses that ability from its UA
- Starting in a later era (Rebuilding onward) now actually gives the player extra units/buildings/population/etc. like it's supposed to

//
MISC Changes
//

- Added a list of links to all known DeCiv mods
- Added many missing style sprites along with a proper Afrikan sprite style drawn by ReallyBasicName
- Bartertown's "declaring war" line was changed from the generic line to a more appropriate quote from Beyond Thunderdome
- Hovercraft is now VTOL Gunship, with a new sprite from The Bucketeer
- "Identity" UBs (Faction World Wonders + City-State Monuments) now cost 0 Production (previously 1)
- Purge Robot fake unique has been removed from Purge Robot units
- Suppressed certain mod checker warnings

//
"Tech Expansion" Update
//

New Content:
- Added new faction: Prasiddh Shahar (Indian astronauts who waited out the Cataclysm in their space station)
- Added new City-State: Guiyu (the actual e-waste processing community of Guiyu in Guangdong Province, China)
- Added five UUs for the Dahomey CS based on the historical Dahomey Amazons
- Added several new technologies:
	- Decivilized era: Optics
	- Rediscovering era: Moisture Harvesting, Mountain Exploration, Record Keeping
	- Neofeudal era: Hoplology
	- Rebuilding era: Ecotheory
	- Industrial era: Re-Utilization
	- Postmodern era: Full-Spectrum Dominance
	- New Future era: Rewilding, Stealth
- Deleted one technology: Plastics Recycling (replaced by Re-Utilization)
- Added Condenser Cooler (Rediscovering era Water building that boosts Moisture trap yields but requires the city to be working a Moisture trap, consumes Coal to build, and obsoletes late-game)
- Added Eco-Sanctuary (New Future era Happiness building that requires a Nature preserve and boosts the yields of Nature preserves)
- Added Oasis Atoll (Decivilized era world wonder that increases the Water income and Naval unit construction speed of the coastal city that owns it)
- Added Observatory (Rediscovering era Science building that adds Science based on how many Mountains the city can work)
- Added State Archive (Rediscovering era national wonder that adds Culture and Science based on which luxuries the faction owns)
- Added Warnet (Postmodern era national wonder that adds +20% Strength to all units but requires building Aerospace Facilities, Armaments Production Lines, Armor Production Lines and Decryption Centers in at least 4 cities each)
- Added Mountaineer promotion (Special promotion that lets units enter Mountain tiles and makes them take 20 less damage if they end their turn on one)
- Added Filter pump improvement (Built on Lakes exclusively, improves tile's Water yield by 2)
- Added Offshore mine improvement
- Added Tunnel improvement (Built on Mountains exclusively)
- Added Mountain Tunnel terrain (Artificially created via Tunnel improvement, starts at +1 Production)
- Added Cactus luxury resource (Desert tiles only)
- Added Cobalt luxury resource (Ocean tiles only, revealed by Oceanography)
- Added Deep-sea Fish bonus resource (Ocean tiles only, revealed by Oceanography)
- Added Lithium bonus resource (Ocean tiles only, revealed by Oceanography)

Balance Changes:
- The AI now plays on a special difficulty, gets even more bonuses the player doesn't have, and is thus even harder to defeat
- Aerospace Facility no longer penalizes city Production, but now has a maintenance cost of 3
- Armaments Production Line no longer penalizes city Production, but also no longer gives a free Armory (it now *requires* an Armory) and has a maintenance cost of 3
- Armor Production Line no longer penalizes city Production and unlocks a new promotion, but also no longer gives a free Tank, its Production boost to Armor units is reduced to 33%, and it has a maintenance cost of 3
- Armory moved to Hoplology and no longer requires a worked Weapons tile
- Artificial glaciers and Moisture traps can now be placed on Mountains
- Biosphere Project moved to Atmosphere Remediation
- Bomb Shelter (and replacements) now give +3 Water per turn instead of +1
- Chemical Extractor no longer has a resource requirement or Culture penalty
- Crystal Carrier gains +10 to defense and ranged strength
- Data Center nerfed to +5 Science instead of +50% Science (Hexlock's version nerfed to +8 instead of +65%), but now adds +4 Science to worked Data and Encrypted Data tiles
- Fixed an error made during the Espionage update that allowed human players to start with two settlers on Immortal difficulty
- Fo Guang is no longer banned from constructing Science/Industrial/Power buildings or high-tech units
- Fusion Reactor now provides 20 Power
- Libraries now give +2 Science to worked Books tiles but no Culture
	- Faction specific replacements no longer have reduced Science, and several have additional distinguishing perks
- Listening Post has been moved to Radio (Crimson Legion's replacement still unlocks at Civil Service)
- Machine Guns are now Shooter units, considered Personnel, and start with Logistics
- Mechanized Workers can now enter impassable tiles and ignore terrain costs
- Missile Vehicle and Rocket Artillery receive additional buffs
    - Missile Vehicle now has 55 ranged strength and 200% bonus vs. Armor units, and can carry one Missile
    - Rocket Artillery now has 45 defense strength and 60 ranged strength
    - Hexlock's Gravity Turret now has 60 defense strength and 80 ranged strength
- Modern Armor has been moved to Full-Spectrum Dominance
- Moisture traps and Production-to-Water conversion now require Moisture Harvesting
- Most National Wonders have had their Production cost reduced
- Museums and Open the Vault moved to Record Keeping
- Museums no longer add Faith, but add 10% Culture and +1 Science/Culture to worked Artifacts tiles
- National College buffed to provide ~17% more Science, so it's no longer worse than a University
- Nature preserves moved to Rewilding
- Plankton is now a bonus resource
- Plastics Reprocessor moved to Re-Utilization
- Public Broadcast now costs 500 Production (previously 100, which was way too low)
- Public Schools (and replacements) no longer provide a scaling Culture yield, and the scaling Science yield is adjusted to 1 per 2 population and is delayed until Networking is discovered
- Purge Robots are now standalone units
- Rebels now spawn when below -10 Unhappiness instead of -20
- Reclamation Vats now consumes Power
- Recycling Plant renamed to Advanced Energy Recycling Plant, moved to Energy Weapons, and buffed to give 12 Power
- Salt tiles now provide +1 Food prior to improvement
- Siege units now have a 200% combat bonus when attacking cities (previously 100%)
- Stealth Fighter/Bomber have been moved to Stealth technology
- Several identity wonders have been nerfed
- Television Studio now gives +2 Culture but costs 2 Water per turn in maintenance
- The gold to science slider has been removed, and the Science costs of all technologies have been reduced accordingly
- Unit embarking now unlocks at Optics instead of Sailing
- Water providing buildings have been buffed slightly
- Wincon wonders, International Trade Center, and Manhattan Project can no longer have their production hurried
- Workers (but not Mounted or Mechanized Workers) can now build improvements on Lakes (currently only one improvement requires this)

//
- Credits from Icons to The Noun Project, Robert Bjurshagen, Manglyang Studio, Mangsaabguru, Kamin Ginkae and Royal Icons