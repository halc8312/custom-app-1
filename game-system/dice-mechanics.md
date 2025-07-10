# Dice Mechanics & Tools

## 🎲 How to Roll Dice

In GitHub Chronicles, we use various methods to generate random numbers:

### Method 1: Comment Commands
When playing in an issue thread, use these commands:
- `!roll 2d6` - Roll two six-sided dice
- `!roll 1d20` - Roll one twenty-sided die
- `!roll 3d6+2` - Roll three six-sided dice and add 2

The Game Master will interpret these rolls.

### Method 2: Commit Hash Dice
Use the first digits of commit hashes as random numbers:
1. Make any small commit (even updating your character sheet)
2. Use the first X digits of the hash as your dice result
3. For 2d6: Use first two digits, modulo 6, plus 1 each

### Method 3: Issue/PR Numbers
- New issue/PR numbers can serve as d100 rolls
- Last digit can be used as d10
- Last two digits as percentile dice

### Method 4: Timestamp Dice
Use the seconds from action timestamps:
- 00-09 seconds = 1
- 10-19 seconds = 2
- 20-29 seconds = 3
- 30-39 seconds = 4
- 40-49 seconds = 5
- 50-59 seconds = 6

## 🎯 Quick Resolution Tables

### Success Levels
| Roll Total | Result |
|------------|---------|
| Natural 2  | Critical Failure |
| 3-5        | Failure |
| 6-8        | Partial Success |
| 9-11       | Success |
| 12+        | Great Success |
| Natural 12 | Critical Success |

### Combat Quick Reference
| Action | Roll | Effect |
|--------|------|--------|
| Attack | 2d6 + STR/AGI | Damage on hit |
| Defend | 2d6 + AGI | Reduce incoming damage |
| Hack | 2d6 + TCH | Digital effects |
| Inspire | 2d6 + CHA | Buff allies |
| Analyze | 2d6 + INT | Gain information |
| Perceive | 2d6 + WIS | Notice hidden things |

## 🛠️ Player Tools

### Character Actions Template
```markdown
## [Character Name]'s Action

**Intent**: What I'm trying to do
**Approach**: How I'm doing it
**Skill/Attribute**: What I'm using (e.g., STR, Hack skill)
**Roll**: !roll 2d6+X
**Flavor**: Description of the action

*Waiting for GM response...*
```

### Combat Round Template
```markdown
### Round X - [Character Name]

**Movement**: Moving to [location]
**Action**: [What you're doing]
**Roll**: !roll [dice]
**Target**: [Who/what you're targeting]

*[Dramatic description of your action]*
```

### Skill Check Format
```markdown
**Attempting**: [Task description]
**Using**: [Attribute] + [Skill if applicable]
**Difficulty**: [If known]
**Roll**: !roll 2d6+X

*[Describe your approach]*
```

## 🎪 Special Mechanics

### Advantage/Disadvantage
- **Advantage**: Roll 3d6, drop lowest
- **Disadvantage**: Roll 3d6, drop highest
- **Double Advantage**: Roll 4d6, drop 2 lowest

### Team Checks
When multiple characters work together:
1. Designate a lead character
2. Each helper rolls 2d6
3. Each roll of 8+ adds +1 to lead's roll
4. Maximum bonus: +3

### Extended Challenges
For complex tasks requiring multiple successes:
- **Simple**: 3 successes before 3 failures
- **Moderate**: 5 successes before 3 failures
- **Complex**: 7 successes before 4 failures

### Clash Rolls
When two characters oppose each other:
1. Both roll 2d6 + attribute
2. Highest total wins
3. Ties go to defender/status quo
4. Natural 12 beats everything except another natural 12

## 🎰 Random Tables

### Quick NPC Generator
Roll 2d6 for each:

**First Die - Personality**:
1. Nervous
2. Friendly
3. Suspicious
4. Helpful
5. Grumpy
6. Mysterious

**Second Die - Occupation**:
1. Debugger
2. Data Miner
3. Security Guard
4. System Admin
5. Beta Tester
6. Code Reviewer

### Random Encounters (2d6)
| Roll | Encounter |
|------|-----------|
| 2    | Corrupted Data Beast |
| 3-4  | Lost Process |
| 5-6  | Helpful AI |
| 7-8  | Nothing unusual |
| 9-10 | Useful Terminal |
| 11   | Hidden Cache |
| 12   | Rare Artifact |

### Loot Table (2d6)
| Roll | Loot |
|------|------|
| 2    | Cursed Variable |
| 3-4  | Memory Chips (1d6) |
| 5-6  | Basic Script |
| 7-8  | Healing Potion.exe |
| 9-10 | Useful Function |
| 11   | Rare Algorithm |
| 12   | Legendary Code |

## 📊 Quick Stats

### Minion Stats
- **HP**: 3-5
- **Attack**: 2d6+1
- **Defense**: 10
- **Damage**: 1d6

### Boss Stats
- **HP**: 20-30
- **Attack**: 2d6+4
- **Defense**: 12
- **Damage**: 2d6
- **Special**: Unique ability

### Environmental DCs
- **Easy Lock**: DC 6
- **Standard Firewall**: DC 8
- **Complex Puzzle**: DC 10
- **Master Encryption**: DC 12
- **Quantum Lock**: DC 15

---

*Remember: Dice add randomness, but storytelling drives the adventure!*