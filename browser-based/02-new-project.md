# Step 2: Fresh Project Introduction

Following the principles we've established, I'm ready to begin a new project.

## Project Description
[User provides their project description here]

## Your Required First Response
1. Acknowledge what I'm trying to build
2. Ask 3-5 specific clarifying questions about:
   - Technical requirements I haven't specified
   - User interactions or workflows
   - Data persistence needs
   - Integration points
   - Specific constraints or preferences
3. DO NOT create any code or implementation details yet
4. End with: "Based on your answers, I'll create a comprehensive game plan for us to review before any implementation."

## After I Answer Your Questions

Create a game plan artifact titled "GamePlan-[ProjectName]" with these exact sections:

### 1. Project Overview
- **Goal**: One paragraph explaining WHY we're building this and what problem it solves
- **Core Features**: Bullet list of main functionality
- **Success Criteria**: How we'll know it's working correctly

### 2. Technical Architecture
- **Tech Stack**: Specific technologies and why
- **Data Flow**: How data moves through the system
- **Key Design Decisions**: Important architectural choices
- **External Dependencies**: APIs, libraries, services

### 3. Project Structure
```
project-root/
├── src/
│   ├── components/
│   │   ├── Header.js
│   │   └── Footer.js
│   ├── utils/
│   │   └── helpers.js
│   └── index.js
├── public/
│   └── index.html
├── tests/
│   └── App.test.js
├── package.json
└── README.md
```

### 4. Development Phases

#### Phase 1: Foundation Setup
**1.1 Project Initialization**
- [ ] Create directory structure
- [ ] Initialize package.json
- [ ] Install core dependencies
- **Test:** `npm install` completes successfully

**1.2 Basic Component Structure**
- [ ] Create main App component
- [ ] Create basic routing (if applicable)
- **Test:** App renders "Hello World"

#### Phase 2: Core Features
**2.1 [Feature Name]**
- [ ] Implement [specific functionality]
- [ ] Add error handling
- **Test:** [Specific test criteria]

[Continue with all phases...]

### 5. Git Commit Strategy (Optional)
- After section 1.1: "Initial project setup"
- After section 1.2: "Add basic component structure"
- After section 2.1: "Implement [feature]"
- [etc.]

### 6. Verification Checkpoints
Summary of all test points and how to verify each phase

## Remember
- Each section marked with **Test:** is a stopping point
- We implement one section at a time
- I verify each section works before we continue
- You create bash scripts for structure, artifacts for code
- We update this game plan as we progress (checking off completed items)

## When Tests Reveal Unexpected Behavior

**CRITICAL: We investigate, we don't "fix"**

When a test produces unexpected results:

1. **Document the Observation**
   - "Expected: [what should have happened]"
   - "Actual: [what you observed]"
   - "Difference: [specific divergence]"

2. **Investigate Systematically**
   - Ask: "What assumptions did my code make?"
   - Ask: "What could cause this specific difference?"
   - Suggest: "Let's add a console.log at [location] to see [specific value]"
   - Create minimal test cases to isolate the behavior

3. **Propose ONE Investigative Step**
   - "To understand this better, let's [single specific action]"
   - Never suggest multiple changes at once
   - Focus on gaining information, not changing behavior

4. **After Each Investigation**
   - "What did we learn from that?"
   - "Does this change our understanding?"
   - Only then: "Based on this understanding, the code should [specific change]"

**Forbidden Patterns:**
- "Let me fix this by..."
- "I'll solve this with..."
- "Here are three possible fixes..."
- Making multiple changes hoping one works

**Required Pattern:**
- "This behavior suggests [hypothesis]. To test this, let's examine [specific thing]. Please add console.log to line X and tell me what value you see."

## After Game Plan Approval
Once I approve the game plan, we'll begin with Phase 1.1. You'll:
1. Create a bash script for the file structure
2. Create artifacts for any code files
3. Tell me exactly how to test the implementation
4. Wait for my verification before proceeding