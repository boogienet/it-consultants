# Requirements Analysis Prompt

Use this prompt with Claude to conduct a thorough requirements analysis session after receiving the client survey data.

## Main Prompt Template

```
I need you to act as a senior IT business analyst to help me conduct a requirements analysis session. I have survey data from a client, and I need to have a systematic conversation to fill in the gaps and develop a complete requirements document.

**Survey Data:**
[Paste the completed client survey here]

**My Role:** [IT consultant/internal IT/project manager - specify your context]

**Analysis Approach:**
Please act as an experienced business analyst and guide me through a structured conversation to:

1. **Validate and clarify** the survey responses
2. **Identify gaps** in the information provided
3. **Explore the sensitive topics** not covered in the survey (budget, timeline, performance, pain points, stakeholder dynamics)
4. **Prioritize requirements** based on business impact and constraints
5. **Generate insights** about risks, dependencies, and implementation considerations
6. **Create the final requirements document** using my template

**Important:** Skip any questions that aren't relevant to this specific project. Focus on what matters most for this situation. After we complete our discussion, please summarize the key findings in your own words before generating the requirements document.

Start by reviewing the survey data and asking me probing questions to understand what we still need to discover. Focus on the areas that require deeper conversation rather than just confirming what's already clear.
```

## What to Expect from the Analysis Session

**Phase 1: Survey Review & Validation**
- Analyst reviews survey responses for inconsistencies or gaps
- Clarifies any ambiguous responses
- Identifies areas that need deeper exploration

**Phase 2: Deep Dive Conversations**
The analyst will systematically explore relevant topics, summarizing understanding, insights, and assumptions after each section before moving to the next:

**Current State & Pain Points:**
- "Tell me about what's not working with the current system"
- "Walk me through a typical day when things go wrong"
- "What's the impact when [current system] has problems?"
- "What workarounds are people using now?"
- *[Analyst summarizes understanding, shares insights about root causes or patterns, and states assumptions before proceeding]*

**Stakeholder Dynamics:**
- "Who are the real decision makers vs influencers?"
- "Where might we encounter resistance to change?"
- "Who will be most affected by this project?"
- "What's the approval process for a project like this?"
- *[Analyst summarizes understanding, shares insights about organizational dynamics, and states assumptions before proceeding]*

**Budget & Financial Constraints:**
- "What's driving the budget for this project?"
- "How do you typically make technology investment decisions?"
- "Are there budget cycles or constraints I should know about?"
- "What happens if the project costs more than expected?"
- *[Analyst summarizes understanding, shares insights about financial priorities, and states assumptions before proceeding]*

**Timeline & Dependencies:**
- "What's driving the timeline pressure, if any?"
- "Are there seasonal considerations or business cycles?"
- "What other projects or initiatives might compete for resources?"
- "What happens if we need more time to do this right?"
- *[Analyst summarizes understanding, shares insights about scheduling constraints, and states assumptions before proceeding]*

**Technical Performance Requirements:**
- "How many people need to use this simultaneously?"
- "What are the peak usage times and patterns?"
- "How much downtime is acceptable for maintenance?"
- "What response time do users expect?"
- *[Analyst summarizes understanding, shares insights about technical implications, and states assumptions before proceeding]*

**Risk Assessment:**
- "What keeps you up at night about this project?"
- "What would happen if this project failed?"
- "How comfortable are you with new vs proven technology?"
- "What's your experience with similar projects?"
- *[Analyst summarizes understanding, shares insights about risk factors, and states assumptions before proceeding]*

**Technology Landscape:**
- "What technology relationships do you have that I should know about?"
- "Are there any vendors or approaches you definitely want to avoid?"
- "Do you have existing licenses or contracts that affect this?"
- "What's worked well (or poorly) for you in the past?"
- *[Analyst summarizes understanding, shares insights about technical constraints, and states assumptions before proceeding]*

**Phase 3: Requirements Prioritization**
- Help categorize requirements as Must-Have, Should-Have, Nice-to-Have
- Identify potential trade-offs between competing requirements
- Understand what's negotiable vs non-negotiable

**Phase 4: Summary & Validation**
- Analyst summarizes key findings in their own words
- Confirms understanding of priorities and constraints
- Validates that nothing important was missed
- Identifies any assumptions that need client confirmation

**Phase 5: Documentation Generation**
- Create the formal requirements document using your template
- Ensure all discoveries are captured appropriately
- Identify any follow-up actions or validations needed

## Sample Analyst Questions by Topic

**Probing Current Pain Points:**
- "You mentioned [problem from survey] - can you give me a specific example of when this happened recently?"
- "When this issue occurs, how does it affect your business operations?"
- "What's the cost of these problems - in time, money, or missed opportunities?"

**Understanding Stakeholder Dynamics:**
- "I see [person] is listed as the decision maker - do they need to approve every aspect, or just the final recommendation?"
- "Who else will be affected by this change that we haven't talked about yet?"
- "Are there any groups that might resist this change? Why?"

**Exploring Budget Reality:**
- "Help me understand your investment thinking - are you looking for the most cost-effective solution, or willing to pay more for specific benefits?"
- "If the perfect solution cost 50% more than expected, what would happen?"
- "How do you typically handle projects that come in over budget?"

**Timeline Discovery:**
- "What happens if this project takes longer than hoped?"
- "Are there any events or deadlines that would make timing critical?"
- "Would you rather have a partial solution quickly or wait for the complete solution?"

**Technical Deep Dive:**
- "Walk me through your busiest day - what kind of system load should we plan for?"
- "If the system was down for maintenance, when would that be least disruptive?"
- "What does 'reliable' mean to you in specific terms?"

## Tips for Effective Analysis Sessions

**Create Psychological Safety:**
- "There are no wrong answers - I'm trying to understand your real situation"
- "This information helps me design the right solution for you"
- "Everything we discuss is confidential and focused on project success"

**Dig Deeper on Vague Responses:**
- When they say "reliable," ask "What does reliable mean specifically?"
- When they say "fast," ask "How fast? What's acceptable vs ideal?"
- When they say "easy to use," ask "Easy for whom? What's their technical background?"

**Watch for Red Flags:**
- Unrealistic budget/timeline combinations
- Unclear decision-making authority
- Competing stakeholder priorities
- Technical requirements that conflict with stated goals

**Confirm Understanding:**
- "Let me make sure I understand..."
- "So what I'm hearing is..."
- "How does this sound as a summary?"

## Follow-up Actions

After the analysis session, the analyst should help you:
- **Identify information gaps** that need client follow-up
- **Flag potential risks** that need mitigation planning
- **Prioritize requirements** for phased implementation if needed
- **Prepare questions** for technical stakeholders if required
- **Create action items** for both you and the client

The goal is a complete, realistic requirements document that sets proper expectations and enables successful project execution.