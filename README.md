# FATE CLI

`Fate Condensed CLI` will cover the complete features of the Fate Condensed System.

This Command Line Interface (CLI) allows users to:

* Get help with condensed instructions.
* Create characters, aspects (that you can treat as characters), stunts, stress, consequences, and conditions.
* Roll fate dice with approach/skill bonuses while invoking/compelling any number of aspects (cannot invoke and compel in the same roll)
* Create zones, scenes, and scenarios (all of which can be treated as characters and rolled with).
* **COMING SOON** - Manage contests, challenges, and conflicts within zones, scenes, and scenarios.
* **COMING SOON** - Record narrative elements to read back and view them within the context of their scenes.
* **COMING SOON** - Return to a previous point in time to alter history on a new timeline

# HELP COMMANDS

`.d`

### FATE CLI:
* `.d` - display these instructions
* `.d` cheat {search} - display condensed game instructions

### User Setup:
* `.d (u)ser` - display user info
* `.d u help` - display user help

### Character Setup:
* `.d (c)haracter` - display active character
* `.d c help` - display character help

### Roll Fate Dice
* `.d r` - roll fate dice
* `.d r (i)nvoke {aspect}` [...(i)nvoke {aspect}] - roll fate dice and apply
* `.d r {approach|skill}` - roll fate dice with active character's stat bonus
* `.d r {approach|skill} (i)nvoke {aspect} (+2|reroll) [...(i)nvoke {aspect} (+2|reroll)]` - roll fate dice with active character's stat bonus
* `.d re (i)nvoke {aspect} (+2|reroll) [...(i)nvoke {aspect} (+2|reroll)]` - reroll the character's last roll
* `.d (av)ailable` - display invocable/compelable aspects
* `.d (i)nvoke {aspect} (+2|reroll) [...(i)invoke {aspect} (+2|reroll)]` - invokes an aspect and uses the active character's fate point(s)
* `.d compel {aspect} [...(c)compel {aspect}]` - compels aspect(s) and grants the active character a fate point

### Scenario Setup
* `.d scenario help` - display active scenario

### Scene Setup
* `.d (s)cene` - display active scene
* `.d s help` - display scene help

### Zone Setup
* `.d (z)oen` - display active zone
* `.d z help` - display scene help

### User Setup:
`.d u help` - display user help
* `.d (u)ser` - display user info
* `.d u tz {timezone}` - set user time zone
* `.d u tz (l)ist {search}` - search the list of time zones

### Character Help:
`.d c help` - display these instructions
* `.d (c)haracter` - display active character
* `.d c help` - display character help
* `.d c (st)ress help` - display help on stress tracks
* `.d c (con)sequence help` - display help on consequences and conditions
* `.d c {name}` - display/set active character
* `.d c (l)ist` - display list of characters
* `.d c (desc)ription {description}` - set the description for the active character
* `.d c (high/hc) concept {high concept}` - set the high concept for the active character
* `.d c (t)rouble {trouble}` - set the trouble for the active character
* `.d c (d)delete {name}` - removes a character
* `.d c (f)ate {refresh|+|-}` - display, refresh, add or subtract fate points
* `.d c (a)spect [(d)elete] {aspect}` - add/remove aspects
* `.d c (a)spect (c)character` - set the current aspect as the active character
* `.d c (s)tunt [(d)elete] {stunt}` - add/remove stunts
* `.d c (s)tunt (c)character` - set the current stunt as the active character
* `.d c (app)roach [(d)elete] {approach} {bonus}` - add/remove approach bonuses
* `.d c (app)roach help` - display a list of approach descriptions
* `.d c (sk)ill [(d)elete] {skill} {bonus}` - set/remove bonuses
* `.d c (sk)ill help` - display a list of skill descriptions

### Stress Help:
`.d c (st)ress help` - display these instructions
* `.d c (st)ress (m)ental|(p)hysical {1,2,3...}` - add stress
* `.d c (st)ress (d)elete (m)ental|(p)hysical {1,2,3...}` - remove stress
* `.d c (st)ress (t)itle {1,2,3...} {stress}` - create custom stress track
* `.d c (st)ress (t)itle (d)elete {(st)ress}` - delete custom stress track
* `.d c (st)ress {(st)ress} {1,2,3}`- add custom stress
* `.d c (st)ress (r)efresh` - clears all stress tracks
* `.d c (st)ress (r)efresh {(st)ress}` - clears the titled stress track
* `.d c (st)ress (d)elete {(st)ress}` - remove custom stress
* `.d c (st)ress (t)itle FATE` - reset stress boxes to standard FATE configuration

### Consequences and Conditions Help:
`.d c (con)sequence help` - display these instructions
* `.d c (con)sequence (mi)ld|(mo)derate|(se)vere {aspect}` - add consequence
* `.d c (con)sequence (d)elete (mi)ld|(mo)derate|(s)evere` - remove consequence
* `.d c (con)sequence (t)itle {1,2,3...} {condition}` - create condition
* `.d c (con)sequence (t)itle (d)elete {(co)ndition}` - delete condition
* `.d c (con)sequence {(co)ndition}` - add condition
* `.d c (con)sequence (d}elete {(co)ndition}` - remove condition
* `.d c (con)sequence (t)itle FATE` -reset consequences to standard FATE configuration

### Scenario Help:
`.d scenario help` - display these instructions
* `.d scenario` - display active scenario
* `.d scenario (n)ame {name}` - add/display/set active scenario
* `.d scenario (l)ist` - display list of scenarios
* `.d scenario (desc)ription {description}` - set the description for the active scenario
* `.d scenario (a)spect [(d)elete] {aspect}` - add/remove aspect for active scenario
* `.d scenario (a)spect (c)character` - set the current aspect as the active character
* `.d scenario (c)haracter [(d)elete] {character}` - add/remove character for active scenario
* `.d scenario (d)delete {name}` - removes a scenario

### Scene Help:
`.d s help` - display these instructions
* `.d (s)cene` - display active scene
* `.d s (n)ame {name}` - add/display/set active scene
* `.d s (l)ist` - display list of scenes
* `.d s (desc)ription {description}` - set the description for the active scene
* `.d s (a)spect [(d)elete] {aspect}` - add/remove aspect for active scene
* `.d s (a)spect (c)character` - set the current aspect as the active character
* `.d s (c)haracter [(d)elete] {character}` - add/remove character for active scene
* `.d s (d)delete {name}` - removes a scene

### Zone Help:
`.d z help` - display these instructions
* `.d (z)one` - display active zone
* `.d z (n)ame {name}` - add/display/set active zone
* `.d z (l)ist` - display list of zones
* `.d z (desc)ription {description}` - set the description for the active zone
* `.d z (a)spect [(d)elete] {aspect}` - add/remove aspect for active zone
* `.d z (a)spect (c)character` - set the current aspect as the active character
* `.d z (c)haracter [(d)elete] {character}` - add/remove character for active zone
* `.d z (d)delete {name}` - removes a zone

### APPROACHES:
* `.d character approach help`
* `.d c app help`
* Careful - pay close attention to detail and take your time.
* Flashy - draw attention to you; full of style and panache.
* Forceful - not subtle, but brute strength and power.
* Sneaky - emphasis on misdirection, stealth, or deceit.
* Clever - think fast, solve problems, or devise strategy.
* Quick - move fast and with dexterity

### SKILLS:
* `.d character skills help`
* `.d c sk help`
* Academics - knowledge, education, science expertise.
* Athletics - run, jump, dodge attacks.
* Burglary - bypass security, pick pockets, pull off crimes.
* Contacts - know the right people & helpful connections.
* Crafts - make, build, fix and break things.
* Deceive - lie, cheat, impersonate.
* Drive - maneuver, race, control vehicles.
* Empathy - counsel, spot lies, judge mood & intentions.
* Fight - fists or hand-to-hand weapons.
* Investigate - find clues, deductions, solve mysteries.
* Lore - supernatural knowledge.
* Notice - spot details, sense trouble, be perceptive.
* Physique - strength, durability, raw power.
* Provoke - scare, manipulate, anger, push people.
* Rapport - connect with others, build trust & goodwill.
* Resources - wealth, borrow or access material things.
* Shoot - ranged combat; guns, throwing knives, bows.
* Stealth - hide, evade, blend in, go unnoticed, vanish.
* Will - resist temptation, withstand trauma, hold steady.

# CHEAT CARDS
`.d cheat {search}`
### On Your Turn
1. Describe what you’re trying to do.
1. Choose the skill & action that fit.
1. Roll: 4dF + skill + stunt.
1. Optional: invoke aspect(s) - re-roll or add +2 (1 Fate point each)
1. Resolve action (see Outcomes/Actions). - Absorb shifts (if attacked).
            – **Stress**:
              • check off stress boxes
              • one box per shift
            – **Consequences**:
              • absorb 2/4/6 shifts
              • create a consequence aspect
              • attacker gets one free invoke
            – **Taken Out**:
              • if you can’t absorb the hit
              • attacker removes you from scene
            – **Concede**:
              • choose before a roll
              • you get a Fate point
              • you choose how to exit scene

### OUTCOMES/ACTIONS

        **Shifts** = 
          Your Effort - [Opposing Effort or Target Difficulty]
          
          •  *Fail*: effort < opposition
          •  *Tie*: effort = opposition
          •  *Success*: effort > opposition by 1 or 2
          •  *Success w/ Style*: effort > opp. by 3 or more
        
        **Create an Advantage (CaA)**
             Leverage and create aspects
        
             When creating a new situation aspect
                *Fail*: not created or free enemy invoke
                *Tie*: not created, but free boost
                *Success*: created with free invoke
                *SwS*: created with 2 free invokesn\
             When targeting existing/unknown aspects
                *Fail*: unknown or free enemy invoke
                *Tie*: free invoke on known, boost on unk.
                *Success*: free invoke on aspect
                *SwS*: 2 free invokes on aspect

### OUTCOMES/ACTIONS (cont.)

        **Attack**:
             to harm a target
                *Fail*:  you fail to connect
                *Tie*:  you get a boost
                *Success*:  deal a hit equal to shift(s)
                *SwS*:  may reduce 1 shift for a boostn\
        **Defend**:
             to oppose attack or stop foe
                *Fail*: foe succeeds or you take hit
                *Tie*: action’s tie results applies
                *Success*: enemy stopped/missed
                *SwS*: as Success with a boostn\
        **Overcome**:
             to clear obstacles or hindrances
                *Fail*: fail or success w/ major cost
                *Tie*: partial succ., at minor cost, or boost
                *Success*: you meet your goal
                *SwS*: as Success with a boost

### MAJOR/MINOR COSTS

        **Major**
             significantly worse or more complicated
             •  introduce new problem
             •  bring in new foes
             •  put PCs on a deadline
             •  mild/moderate consequence
             •  enemy gets situation aspect w/ free invoke
        **Minor**
             difficulty or complication, not hindrance
             •  a few points of stress
             •  a boost to the enemy
        **Recovery**
             •  stress clears at end of scene
             •  consequences vary:
                 roll to overcome using skill
                 –  Mild: +2(Fair)
                     •   clears in one full scene
                 –  Moderate: +4(Great)
                     •   clears in one full session
                 –  Severe: +6(Fantastic)
                     •   clears on major milestone

### ASPECTS

        Aspects are true. They can grant or withdraw
        permission for what can happen in the story.
        Invoke an aspect to get +2 on a roll, reroll,
        or increase foe’s difficulty by 2.
        Invoking costs a fate point or uses a free invoke.
        Compel an aspect to add complications to a
        character’s circumstances, Player receives fate point
        or spends fate point to deny circumstances.

### TYPES OF ASPECTS

        **Boost.** Temporary, sometimes unnamed aspect.
            Provides a free invoke. Vanishes once used.
            Can’t be compelled. Can’t be invoked with a fate point.
        **Character.** Aspect on a character sheet.
        **Situation.** Aspect of the scene.
            Lasts only long as the circumstances persist.
        **Organization, Scenario, Setting, Zone.**
            Situation aspects of a group, scene or storyline,
            campaign, or map area, respectively.',

### ADJECTIVE LADDER

        +8  Legendary
        +7  Epic
        +6  Fantastic
        +5  Superb
        +4  Great
        +3  Good
        +2  Fair
        +1  Average
        +0  Mediocre
        -1  Poor
        -2  Terrible
        -3  Catastrophic
        -4  Horrifying

### SETTING DIFFICULTY

        **Low** = below relevant PC skill
        **Medium** =  close to PC skill
        **High** = higher than PC skill
        **Not tough** = Mediocre (0) or don’t roll.
        +2 for tough, +2 for each extra factor against them.
        Consult aspects to adjust. Use adjective ladder as guide.

### TEAMWORK OPTIONS

        _Combine Skills._ Character with highest skill rolls. 
            PCs with same skill at Average (+1) or better use action to add +1.
            Max bonus is highest skill rating.
            Supporters face same costs & consequences as the PC who rolls.
        _On your turn._ Create an advantage & let allies
            use the free invokes on their turns.
        _Outside your turn._ Invoke an aspect to add a bonus to an ally’s roll.

### TURN ORDER

            At the start, everyone decides who goes first.
            After acting, player chooses who goes next.
            GM’s characters are in the turn order just like the PCs.
            Last player to go picks who starts next.

### EARN FATE POINTS WHEN YOU

          •  Accept a compel.
          •  Have your aspectsinvoked.
          •  Concede a conflict.',

### SPEND FATE POINTS TO

          •  Invoke an aspect.
          •  Power a stunt.
          •  Refuse a compel.
          •  Declare a story detail.
  
### CHALLENGES

        GM picks a number of skills representing the tasks needed to beat the challenge.
        Number of tasks roughly equals the number of players.
        Each player picks a task and rolls skill to overcome.
        GM considers mix of results to determine outcome.

### CONTESTS

        Take place over a series of exchanges.
        Each side takes an overcome action for their goals.
        Only one character from each side makes the roll.
        Each participant may try to Create an Advantage (CaA)
        in addition to rolling or combining skills.
        On failed CaA, forfeit roll or give over free invoke.
        At end of exchange, side with highest effort gains 1 victory
        Success with Style gains 2 victories.
        If harm is allowed, absorb shifts as stress.
        Tie results in unexpected twist - GM describes.
        First side to 3 victories (as GM determines) wins.

### CONFLICTS

        When violence/coercion is an option and each side could harm the other.
        Takes place over a series of exchanges. Each character acts in turn order (as On Your Turn).
        Defenders roll to oppose. Conflict ends when one side concedes or is taken out.
        Players who concede each take a fate point. GM also pays players hostile invoke fate points.
