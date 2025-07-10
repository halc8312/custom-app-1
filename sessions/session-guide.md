# Session Management Guide

## 🎮 How Sessions Work

GitHub Chronicles uses GitHub Issues as the primary platform for game sessions. Each adventure is a living document that grows with player actions.

## 🚀 Starting a Session

### For Game Masters
1. Create a new Issue with title: `[Adventure] Title of Adventure`
2. Use the adventure template below
3. Tag it with `adventure`, `open-session`
4. Set difficulty: `beginner`, `intermediate`, or `advanced`
5. Specify max players (recommended: 3-5)

### For Players
1. Find an open adventure in Issues
2. Read the setup and requirements
3. Comment with your character introduction
4. Wait for GM to confirm your participation

## 📝 Adventure Issue Template

```markdown
# [Adventure Title]

**Session Type**: [One-shot / Campaign / Tutorial]
**Difficulty**: [Beginner / Intermediate / Advanced]
**Players**: 0/[max] slots filled
**Status**: Recruiting

## 🎯 Adventure Hook
[The compelling reason why characters would get involved]

## 📍 Starting Location
[Where the adventure begins]

## 🎭 Background
[Any important context players should know]

## ⚔️ Expected Challenges
- Combat: [Low/Medium/High]
- Puzzles: [Low/Medium/High]
- Social: [Low/Medium/High]
- Exploration: [Low/Medium/High]

## 📋 Requirements
- Character Level: [1-3, any, etc.]
- Time Commitment: [Estimated sessions/hours]
- Special: [Any specific requirements]

## 👥 Party Roster
1. [Empty slot]
2. [Empty slot]
3. [Empty slot]
4. [Empty slot]

---

### 🎲 Session Log

*GM will update this section as the adventure progresses*

**Session Start**: [Date/Time]

---

### 📢 How to Join
Comment below with:
1. Link to your character sheet
2. Brief character introduction
3. What attracted your character to this adventure
```

## 🎲 During the Session

### Turn Order
1. GM posts scene description
2. Players have 24 hours to post actions (or as agreed)
3. GM rolls dice and narrates outcomes
4. Repeat until scene complete

### Player Actions Format
```markdown
## [Character Name] - [Class]
*[Current HP/Max HP] | [Status Effects]*

**Action**: [What you're doing]
**Roll**: !roll 2d6+[modifier]
**Intent**: [What you hope to achieve]

*[In-character description of action]*

---
```

### GM Response Format
```markdown
### GM Response

**[Character Name]'s Roll**: [Result] vs DC [X] - [Success/Failure]

*[Narrative of what happens]*

**Consequences**:
- [What changes in the scene]
- [Any damage or effects]
- [New information revealed]

**Scene Update**:
[Updated description of the situation]

**What do you do?**
```

## 📊 Tracking Progress

### Session Summary Template
```markdown
## Session Summary - [Date]

### 🎭 Key Events
- [Major event 1]
- [Major event 2]
- [Major event 3]

### 💎 Loot & Rewards
- [Character 1]: [What they gained]
- [Character 2]: [What they gained]

### 📈 Experience
- Each character gains [X] XP
- Bonus XP for: [Special achievements]

### 🔮 Cliffhanger
[What happens next?]

### 📅 Next Session
[Date/Time if continuing]
```

## 🏁 Ending Adventures

### Success Conditions
- Primary objective completed
- Creative alternative solution achieved
- Party agrees to conclude

### Archiving
1. GM posts final summary
2. Update character sheets with rewards
3. Add session to campaign history
4. Close issue with `session-complete` label

## 🎯 Best Practices

### For Game Masters
- Post at least once per day
- Be clear about expectations
- Encourage creative solutions
- Say "Yes, and..." or "No, but..."
- Keep things moving

### For Players
- Check in regularly
- Respect other players' time
- Stay in character
- Communicate if you'll be absent
- Help drive the story forward

## 🚨 Handling Issues

### Player Absence
- After 48 hours, GM can autopilot character
- Character takes defensive actions only
- Player can catch up when they return

### Conflicts
- Rules discussions in separate thread
- GM has final say during session
- Major issues: Create meta discussion issue

### Technical Problems
- Lost posts: Check GitHub history
- Dice issues: GM can roll for you
- Markdown problems: Ask for help

## 🎪 Special Session Types

### Tutorial Sessions
- Designed for new players
- Simplified rules
- Extra guidance from GM
- No character death

### Speedrun Sessions
- Complete adventure in single real-time session
- 2-3 hour time limit
- Quick decisions required
- Higher rewards

### Sandbox Sessions
- No predetermined plot
- Players drive entirely
- GM responds to actions
- World-building focused

### PvP Sessions
- Player characters can conflict
- Special rules for fairness
- GM as neutral arbiter
- Consent required from all

## 📚 Campaign Management

### Connecting Adventures
- Reference previous issues
- Recurring NPCs and locations
- Continuing story threads
- Character relationship development

### Campaign Log
Create a `campaign-[name].md` file tracking:
- Session summaries
- Major plot points
- NPC relationships
- World changes
- Party achievements

---

*Remember: The goal is collaborative fun! Rules serve the story, not the other way around.*