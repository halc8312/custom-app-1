# Dice Roller Reference

## 🎲 Command Syntax

Use these commands in your issue comments:

### Basic Rolls
- `!roll 1d6` - Roll one six-sided die
- `!roll 2d6` - Roll two six-sided dice
- `!roll 1d20` - Roll one twenty-sided die
- `!roll 3d4` - Roll three four-sided dice

### With Modifiers
- `!roll 2d6+3` - Roll 2d6 and add 3
- `!roll 1d20-2` - Roll 1d20 and subtract 2
- `!roll 3d6+STR` - Roll 3d6 plus your STR modifier

### Advanced Rolls
- `!roll 4d6k3` - Roll 4d6, keep highest 3
- `!roll 2d20kh1` - Roll 2d20, keep highest 1 (advantage)
- `!roll 2d20kl1` - Roll 2d20, keep lowest 1 (disadvantage)
- `!roll 3d6!` - Exploding dice (reroll max values)

## 📊 Manual Dice Methods

### Method 1: Timestamp Dice
Use the seconds of your comment timestamp:
```
00-09 sec = 1
10-19 sec = 2  
20-29 sec = 3
30-39 sec = 4
40-49 sec = 5
50-59 sec = 6
```

### Method 2: Hash Dice
1. Make a commit to update your character
2. Use first 2 digits of commit hash
3. Convert: 00-16=1, 17-33=2, 34-50=3, 51-67=4, 68-84=5, 85-99=6

### Method 3: Issue Number Dice
- Last digit of issue number = d10 (0=10)
- Last 2 digits = d100
- Issue number modulo 6 + 1 = d6

## 🎯 Quick Reference Tables

### Skill Check Results
| 2d6 + Mod | Result |
|-----------|---------|
| 2-5       | Failure |
| 6-8       | Partial Success |
| 9-11      | Success |
| 12+       | Critical Success |

### Damage Rolls
| Weapon Type | Damage |
|-------------|---------|
| Unarmed     | 1d4 |
| Light       | 1d6 |
| Medium      | 1d8 |
| Heavy       | 2d6 |
| Tech        | 1d6+TCH |

### Initiative Order
Roll 1d6 + AGI, act in descending order

## 🎰 Random Generators

### Quick NPC Names
Roll 2d6:

**First d6** (First Part):
1. Bit
2. Byte
3. Data
4. Code
5. Net
6. Sys

**Second d6** (Second Part):
1. runner
2. walker
3. breaker
4. keeper
5. hunter
6. master

### Random Loot (2d6)
| Roll | Item |
|------|------|
| 2    | Corrupted Data |
| 3-4  | Memory Chips (1d6 x 10GB) |
| 5-6  | Common Script |
| 7-8  | Healing.exe |
| 9-10 | Rare Function |
| 11   | Epic Algorithm |
| 12   | Legendary Artifact |

### Random Events (1d20)
| Roll | Event |
|------|-------|
| 1-5  | Nothing happens |
| 6-10 | Minor obstacle |
| 11-14| Useful discovery |
| 15-17| NPC encounter |
| 18-19| Dangerous situation |
| 20   | Extraordinary opportunity |

## 🛠️ Dice Probability

### 2d6 Probabilities
| Result | Chance | Probability |
|--------|---------|------------|
| 2      | 1/36   | 2.78% |
| 3      | 2/36   | 5.56% |
| 4      | 3/36   | 8.33% |
| 5      | 4/36   | 11.11% |
| 6      | 5/36   | 13.89% |
| 7      | 6/36   | 16.67% |
| 8      | 5/36   | 13.89% |
| 9      | 4/36   | 11.11% |
| 10     | 3/36   | 8.33% |
| 11     | 2/36   | 5.56% |
| 12     | 1/36   | 2.78% |

### Success Chances by Modifier
| Modifier | DC 6 | DC 8 | DC 10 | DC 12 |
|----------|------|------|-------|-------|
| +0       | 72%  | 42%  | 17%   | 3%    |
| +1       | 83%  | 58%  | 28%   | 8%    |
| +2       | 92%  | 72%  | 42%   | 17%   |
| +3       | 97%  | 83%  | 58%   | 28%   |
| +4       | 100% | 92%  | 72%   | 42%   |
| +5       | 100% | 97%  | 83%   | 58%   |

---

*Remember: The dice add excitement, but the story is what matters!*