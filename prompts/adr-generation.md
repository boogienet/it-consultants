# ADR Generation Prompt

Use this prompt with Claude to research options, build a systematic comparison, and generate a complete ADR for your project.

## Main Prompt Template

```
I need help making a decision for my project and creating an ADR to document it.

**Decision Topic:** [What you need to decide on]

**Current Situation:** [Brief description of your current setup/problem]

**Initial Thoughts:** [Any options you're already considering, or "I'm not sure what options exist"]

**Key Requirements:** [What matters most - budget, performance, ease of use, reliability, etc.]

**Constraints:** [Any limitations - space, power, existing hardware, technical skills, budget range]

Please help me by:
1. Researching and presenting 3-5 viable options for this decision
2. Identifying the key evaluation criteria that matter for this choice
3. Building a systematic comparison grid evaluating each option against these criteria
4. Discussing the trade-offs and helping me think through the implications
5. Providing a clear recommendation with reasoning
6. Creating a complete ADR using the template from my repository

Let's start by exploring what options exist and what criteria we should use to evaluate them.
```

## Example Usage

**Full Research and Analysis Prompt:**
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
1. Researching and presenting 3-5 viable options for this decision
2. Identifying the key evaluation criteria that matter for this choice
3. Building a systematic comparison grid evaluating each option against these criteria
4. Discussing the trade-offs and helping me think through the implications
5. Providing a clear recommendation with reasoning
6. Creating a complete ADR using the template from my repository

Let's start by exploring what options exist and what criteria we should use to evaluate them.
```

## Quick Decision Starters

**When You Know Some Options:**
```
Help me systematically evaluate [OPTION A], [OPTION B], and [OPTION C] for [DECISION TOPIC]. Research any other viable options, build a comparison grid with relevant criteria, provide a recommendation, and create an ADR using my repository template.

Context: [Brief situation description]
Requirements: [Key needs]
```

**When You're Starting from Scratch:**
```
I need to [DESCRIBE GOAL] but I'm not sure what options exist. Please research the available approaches, identify evaluation criteria, build a systematic comparison, recommend the best option, and create an ADR using my repository template.

Current situation: [What you have now]
What you want to achieve: [End goal]
Constraints: [Limitations]
```

## What to Expect from the Conversation

**Phase 1: Options Research**
- Claude will research current options and technologies
- Present 3-5 viable approaches with brief explanations
- Clarify your specific needs and constraints

**Phase 2: Criteria Development**  
- Identify key evaluation criteria based on your requirements
- Customize criteria to your specific decision context
- Ensure all important factors are captured

**Phase 3: Systematic Comparison**
- Build a detailed comparison grid
- Evaluate each option against each criterion
- Provide ratings, explanations, or qualitative assessments
- Highlight key trade-offs and differentiators

**Phase 4: Discussion & Analysis**
- Deep dive into the most promising options
- Explore implementation considerations and risks
- Discuss how each option fits your broader goals
- Address questions and concerns about top choices

**Phase 5: Recommendation & ADR**
- Clear recommendation with supporting reasoning
- Complete, formatted ADR ready to copy to your documentation
- Professional documentation following your repository template
- Includes executive summary, decision grid, and recommendation

## Tips for Better Decision Analysis

**Be Specific About Your Priorities:**
- Rank importance: "Cost is more important than cutting-edge features"
- Mention deal-breakers: "Must have web UI" or "Cannot require extensive training"
- Time preferences: "Need quick implementation" vs "Can invest time for better long-term solution"

**Provide Complete Context:**
- Current pain points and what's working well
- Related decisions you've already made
- Future plans that might affect this decision
- Budget ranges and resource constraints

**Ask for Clarification During Analysis:**
- "Why is [OPTION] rated higher for [CRITERIA]?"
- "What would change if I had a bigger budget?"
- "How does this integrate with my existing setup?"
- "What are the long-term implications of each choice?"

## Sample Evaluation Criteria

**Technical Decisions:**
- Cost (upfront and ongoing)
- Performance/Capability
- Complexity (implementation and maintenance)
- Sustainability/Long-term viability
- Integration with existing systems
- Learning curve/Skills required
- Community support and documentation
- Scalability and growth potential

**Business/Consulting Decisions:**
- ROI and cost-effectiveness
- Risk level (technical, business, security)
- Time to implement and realize benefits
- Resource requirements (people, budget, time)
- Strategic alignment with goals
- Vendor/supplier stability
- Compliance and regulatory considerations

## Advanced Usage

**For Complex Multi-Criteria Decisions:**
```
This is a complex decision with multiple stakeholders. Please help me:
1. Research all viable options thoroughly
2. Develop weighted evaluation criteria (some factors are more important than others)
3. Create a scoring system for the decision grid
4. Consider both quantitative and qualitative factors
5. Address potential objections to the recommended choice
6. Create a comprehensive ADR suitable for executive review
```

**For Decisions with Unknown Options:**
```
I need to solve [PROBLEM] but I'm not even sure what types of solutions exist in this space. Please:
1. Research the solution landscape and categorize approaches
2. Identify 4-6 representative options across different categories
3. Help me understand the trade-offs between different approaches
4. Build a comparison framework appropriate for this decision
5. Recommend the best path forward with clear reasoning
```