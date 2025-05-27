# ADR Generation Prompt

Use this prompt with Claude to research options, explore considerations, and generate a complete ADR for your project.

## Main Prompt Template

```
I need help making a decision for my project and creating an ADR to document it.

**Decision Topic:** [What you need to decide on]

**Current Situation:** [Brief description of your current setup/problem]

**Initial Thoughts:** [Any options you're already considering, or "I'm not sure what options exist"]

**Key Requirements:** [What matters most - budget, performance, ease of use, reliability, etc.]

**Constraints:** [Any limitations - space, power, existing hardware, technical skills, budget range]

Please help me by:
1. Researching and presenting the main options available
2. Walking through the key considerations and trade-offs
3. Helping me think through the pros/cons of each option
4. Creating a complete ADR based on our discussion using the template from my repository

Let's start by exploring what options exist for this decision.
```

## Example Usage

**Full Research Prompt:**
```
I need help making a decision for my homelab consolidation project and creating an ADR to document it.

**Decision Topic:** Storage solution for my new Proxmox homelab

**Current Situation:** I have an old Synology DS218+ that's getting slow and only has 4TB total capacity. I'm building a new Proxmox server and want to consolidate storage to reduce my hardware footprint.

**Initial Thoughts:** I'm not sure what the best approach is - maybe TrueNAS? Or use Proxmox's built-in storage features?

**Key Requirements:** 
- Reliable storage for family photos, documents, and media files
- Easy backup/snapshot capabilities  
- Web-based management preferred
- Room to grow storage over time

**Constraints:**
- Budget around $500 for drives
- Single Proxmox server (Dell R730)
- Limited networking equipment
- Intermediate technical skills

Please help me by:
1. Researching and presenting the main options available
2. Walking through the key considerations and trade-offs  
3. Helping me think through the pros/cons of each option
4. Creating a complete ADR based on our discussion using the template from my repository

Let's start by exploring what options exist for this decision.
```

## Quick Decision Starters

**When You Know Some Options:**
```
Help me decide between [OPTION A], [OPTION B], and [OPTION C] for [DECISION TOPIC]. Research any other options I should consider, then help me work through the trade-offs and create an ADR documenting the final decision using my repository template.

Context: [Brief situation description]
Requirements: [Key needs]
```

**When You're Starting from Scratch:**
```
I need to [DESCRIBE GOAL] but I'm not sure what options exist. Please research the available approaches, help me understand the trade-offs, and create an ADR documenting the decision using my repository template.

Current situation: [What you have now]
What you want to achieve: [End goal]
Constraints: [Limitations]
```

## What to Expect from the Conversation

**Phase 1: Research & Options**
- Claude will research current options and technologies
- Present 3-5 viable approaches with brief explanations
- Ask clarifying questions about your specific needs

**Phase 2: Deep Dive Analysis**  
- Detailed pros/cons for each realistic option
- Cost comparisons and technical trade-offs
- Discussion of how each fits your requirements
- Questions to help you think through implications

**Phase 3: Decision Support**
- Help you narrow down to the best choice
- Discussion of implementation considerations
- Risk assessment and mitigation strategies

**Phase 4: ADR Generation**
- Complete, formatted ADR ready to copy
- Uses the template from your repository
- Includes all context from your conversation
- Professional documentation of your reasoning

## Tips for Better Research Conversations

**Be Honest About Your Knowledge Level:**
- "I'm new to [TECHNOLOGY]"  
- "I've heard of [OPTION] but don't understand the differences"
- "I'm comfortable with [SKILL LEVEL]"

**Share Your Priorities:**
- Rank importance: cost vs performance vs ease-of-use
- Mention deal-breakers: "Must have web UI" or "Can't require command line"
- Time constraints: "Need to implement in next month"

**Provide Context:**
- Mention related decisions you've already made
- Share what worked/didn't work in your current setup
- Describe your learning preferences

**Ask for Clarification:**
- "Can you explain why [OPTION] is better for [USE CASE]?"
- "What would I need to learn to implement [SOLUTION]?"
- "How does this integrate with my existing setup?"

## Sample Follow-up Questions

**During Research Phase:**
- "Are there any newer options I should consider?"
- "What do most people choose for this scenario?"
- "Which option has the best long-term support?"

**During Analysis Phase:**  
- "How difficult would it be to change my mind later?"
- "What are the common failure points with [OPTION]?"
- "Which choice best fits my implementation approach?"

**Before Final Decision:**
- "What would you choose if this was your project?"
- "What am I not thinking about that I should consider?"
- "How does this decision affect my other planned changes?"