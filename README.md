# Product Engineer Take-Home: Clinical Trial Matching System

## Challenge Overview
Build a clinical trial matcher for patients. We want to see:
1. A real patient-facing interface (basic is fine, but no CLI!)
2. Agent-powered matching (be clever here!)
3. A product we'd ship today because patients would love it

**Time:** ~3 hours. Ship fast, be scrappy, show your thinking.

## What You Need to Build, in no particular order

### 1. **Patient Interface**
- A interface a patient could actually use. Basic is fine.

### 2. **Agent Matcher** 
- Use agents to parse the eligibility text and match or rank trials. Any models, any architecture.

### 3. **The Patient Experience** ⭐ THIS IS KEY
We want to see how you think about the patient.
- They should get to the right trials, understand why they fit, and know what to do next.
- The hard moments matter: no good match, vague inputs, scary topics. Handle them deliberately.
- On the walkthrough call we will use your product together, as a patient would. Build for that.

**Just make it run:**

## Example codebase structure

```
name-your-solution/
├── trials.csv           # We provide this
├── patients.json         # We provide this
├── app/                  # Your product (structure however you want)
└── README.md
```

Structure however you'd like, free to add more files.

## Technical Details

### The Data
- We provide trials.csv: 65 real clinical trials with eligibility criteria as raw free text. The .csv is messy on purpose. I’d think about how you'd clean and parse it. The toughest bit is dealing with the inclusion/exclusion criteria.
- patients.json has a few personas for testing. No external APIs needed.
- Build with AI using Claude Code, Codex, worktrees, fanned out subagents or whatever you ship with. We expect it and hire for it!
- Got a specialty? Show it off! Whether it's UI/UX, product analytics, advanced prompting, post-training, or something else.
- A chat wrapper with stock prompting won't clear the bar. Show us what we can't make ourselves in 30 minutes.

## What Makes a Great Submission

**We care about:**
- It works
- Thoughtful build (show you understand the problem and users)
- Would a patient love this and engage with it
- How much real, working product you shipped in the window
- Rate of learning, Rate of execution

**We don't care about:**
- Perfect code architecture
- Test coverage and supporting every edge case
  
## Quick Start

```bash
# Install basics
npm or pip, whatever you need

# Start here:
1. Load trials.csv and get matching/ranking working
2. Put a patient persona in front of it, build the product, and iterate

# Tip:Start with one patient persona. Make their experience great first. If you'd like, focus on one cancer to start. Breast cancer works well.
```

## Submission Instructions

1. **Complete your solution** in a private GitHub repo
2. **Add bryan (@bryantanwz) as a collaborator**
3. **Include a brief README** explaining:
   - How to run your solution
   - Your approach and key decisions
   - Any TODOs or limitations
4. **Email the repo link** to bryan@radicalhealth.ai & simone@radicalhealth.ai
5. **Book a 45-minute walkthrough** to discuss your solution

## Final Thoughts

This is deliberately open-ended. We want to see:
- How you approach ambiguous problems
- Your instincts about what matters
- How you balance speed vs quality
- What you consider "good enough" for a 3-hour sprint

Remember: **We're a startup.** Show us you can ship fast, think clearly, and build things that patients love.

Good luck! 
