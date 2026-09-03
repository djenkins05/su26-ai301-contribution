# Contribution [#1]: Add Fear and Greed Crypto Sentiment Index Tool

**Contribution Number:** 1
**Student:** Dakarri Jenins  
**Issue:** https://github.com/tarunjandra/agent-tools-mcp-hub/issues/101
**Status:** Phase I 

---

## Why I Chose This Issue

I chose this issue because it aligns with my experience in Python and a goal of mine: 
strengthening my skills with APIs and data processing. I'm also really interested in 
cryptocurrency and financial data, so building a tool that retrieves the Crypto Fear and 
Greed Index felt like a natural fit. It’s a great opportunity to work with a real public 
API while contributing something useful to the project.

I'm interested in this because:
1. I have experience programming in Python and want to apply those 
   skills to more real-world contributions rather than personal projects
2. I want to build more experience working with public APIs and 
   handling JSON responses
3. The task is self-contained, which makes it a good 
   scope for a focused first/early contribution. While still
   allowing me to learn and grow.
5. I'm curious how historical data can be retrieved, processed, and 
   presented as a multi-day trend, which is something this task requires

From the issue description, the goal is to create a Python tool that 
retrieves the current Crypto Fear and Greed Index score along with 
historical sentiment ratings. My contribution will return the current 
score(from 1-100), its classification, and a trend history, while sticking to the 
project's required tool structure and validation process.

---

## Understanding the Issue

### Problem Description

The project currently doesn't have a tool for retrieving cryptocurrency market sentiment data. 
The goal of this issue is to create a Python tool that uses the public Alternative.me API to 
fetch the current Crypto Fear and Greed Index score and historical sentiment ratings. 
The tool should allow users to specify how many days of historical data they want, with a default of 7 and 
then up to a maximum of 30 days.

### Expected Behavior

The tool should accept a days parameter, defaulting to 7 and allowing a maximum of 30 days. 
It should retrieve data from the Alternative.me API and return the current Fear and Greed Index score, 
its corresponding classification(like extreme fear and fear), and the historical sentiment trend for the 
requested number of days. The tool should also include the required tool.py, metadata.json, requirements.txt, and 
README.md files, while passing python3 scripts/validate_tools.py.

### Current Behavior

Currently, there isn't a Crypto Fear and Greed Index tool in the project. As a result, users cannot retrieve 
the current cryptocurrency sentiment score or historical sentiment data through the project's existing tools.

### Affected Components

The main components affected would be the new tools/crypto_fear_greed_index/ directory and its associated files: 
tool.py for the API request and data processing, metadata.json for tool configuration and metadata,
requirements.txt for dependencies, and README.md for documentation. The project's tool validation process, 
scripts/validate_tools.py, will also be used to verify that the new tool follows the required structure and conventions 
that were previously established.

---

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]

### Steps to Reproduce

1. [Step 1]
2. [Step 2]
3. [Observed result]

### Reproduction Evidence

- **Commit showing reproduction:** [Link to commit in your fork]
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction]

---

## Solution Approach

### Analysis

[Your analysis of the root cause - what's causing the issue?]

### Proposed Solution

[High-level description of your fix approach]

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem]

**Match:** [What similar patterns/solutions exist in the codebase?]

**Plan:** [Step-by-step implementation plan]
1. [Modify file X to do Y]
2. [Add function Z]
3. [Update tests]

**Implement:** [Link to your branch/commits as you work]

**Review:** [Self-review checklist - does it follow the project's contribution guidelines?]

**Evaluate:** [How will you verify it works?]

---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]
