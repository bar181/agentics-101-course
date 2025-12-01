# ***Module 4: Build Your Agent 🚀***

***Time:** 90 minutes (break at 45 min)*  
 ***Deliverable:** Working code generated from your specification*  
 ***Confidence Level:** ⭐⭐⭐ (The Main Event)*

---

## ***Module Overview***

*This is it. You are about to direct an AI to read your specs and write your code.*

*You will use **Claude.ai (Free Tier)** as your agent. You'll give Claude a system prompt that transforms it from chatbot into coding agent. Then you'll feed it your specification from Module 2, and it will generate complete HTML and CSS. You manually copy the code to GitHub, building your verification instincts.*

***The Workflow:***

1. ***Brain (Claude):** Reads specs, generates code*  
2. ***Hands (You):** Copy code to GitHub*  
3. ***Boss (You):** Review and approve work*

***Sarah's Experience:** "I gave it my spec. It gave me perfect code. I pasted it. My site worked. That simple."*

*Note: Pro tools (Cursor, Roo Code) are covered in the optional section at the end.*

### ***Your Learning Path***

*✅ Wake your agent with system prompt*  
 *✅ Feed your specification*  
 *✅ Generate and review code*  
 *✅ Iterate to polish*  
 *✅ Document your work*

---

## ***Lesson 4.1: Wake Your Agent***

***Time:** 15 minutes*  
 ***Outcome:** Claude understands its role as your coding agent*

### ***Setup Your Workspace***

*Open three tabs: **GitHub repo** (left), **Claude.ai** (right), and optionally **src/index.html** preview. Split your screen 50/50 if on one monitor. You'll constantly switch between reading specs in GitHub and instructing Claude.*

### ***The System Prompt***

*In GitHub, open `specs/page-spec.md` and copy all content. In Claude.ai (fresh conversation), paste this prompt with your spec below it:*

```
You are my coding agent. Your job:
1. Read specifications carefully
2. Generate complete HTML with embedded CSS
3. Follow every requirement exactly
4. Output full files ready to copy-paste
5. No external dependencies or frameworks

CONSTRAINTS:
- Single file output (index.html)
- All CSS in <style> tags
- Semantic HTML5
- Mobile responsive
- No explanations unless asked

Here is my specification:
[PASTE YOUR SPECS/PAGE-SPEC.MD HERE]

Confirm you understand and are ready to generate code.
```

***Claude responds** with a summary of what it will build. Read it carefully. Does it mention your colors, components, and layout? If yes, proceed. If it missed something, clarify before generating code.*

***Why this works:** You defined Claude's role (coding agent, not tutor), constraints (no improvisation), and output format (complete files). Clear instructions produce reliable results.*

---

## ***Lesson 4.2: Feed Context to Your Agent***

***Time:** 15 minutes*  
 ***Outcome:** Agent has current state and desired state*

### ***The Two-Part Context Pattern***

*Your agent needs to know where you are (current state) and where you're going (desired state). Copy your current `src/index.html` from GitHub. In Claude, type:*

```
Here is my current code:
```

*\[PASTE CURRENT INDEX.HTML \- EVEN IF EMPTY\]*

```

My desired state is in the specification you already have.

Before generating code:
1. Summarize what currently exists
2. Identify what needs to be built
3. Confirm your implementation plan
```

***Claude responds** with an analysis like:*

*"Current: Empty file. Needs to be built: Dark theme layout, profile card, CTA button, mobile responsive. Plan: Semantic HTML5 structure, flexbox centering, media query at 768px. Ready to generate."*

### ***Review Claude's Plan***

*Read carefully. Check for:*

* *\[ \] All components mentioned*  
* *\[ \] Colors correct*  
* *\[ \] Layout approach appropriate*

***If good:** Type "Generate the complete index.html file now"*  
 ***If issues:** Type "You missed \[specific detail\]. Revise plan before coding"*  
 ***If too complex:** Type "Start simpler. Just layout and background first"*

*This planning step catches misunderstandings before Claude writes 200 lines of wrong code.*

---

## ***Lesson 4.3: Generate Working Code***

***Time:** 30 minutes*  
 ***Outcome:** Complete working code from your specification*

### ***Give the Build Command***

*Type in Claude: `Generate the complete index.html file now.`*

*Claude streams code in real-time (5-30 seconds depending on complexity). As it appears, scan for your color codes and component names.*

### ***The 5-Point Review***

*When the code block appears with "Copy code" button, **don't click yet**. Review first:*

***1\. Visual Scan (30 sec):** Starts with `<!DOCTYPE html>`, ends with `</html>`, properly indented?*  
 ***2\. Color Check (60 sec):** Search (Ctrl/Cmd+F) for your hex codes. Exact matches?*  
 ***3\. Component Check (60 sec):** All parts from your spec present in correct order?*  
 ***4\. Responsive Check (30 sec):** Find `@media` query. Matches your mobile specs?*  
 ***5\. Structure Check (30 sec):** Semantic HTML (`<header>`, `<main>`) not just `<div>`?*

***Total review: 4 minutes. If issues found, use directive feedback in next lesson.***

### ***Copy to GitHub***

***Click "Copy code"** in Claude. Switch to GitHub, open `src/index.html`, click **edit pencil ✏️**. **Select All (Ctrl/Cmd+A)**, **Delete** completely, then **Paste** (Ctrl/Cmd+V).*

*Scroll down, commit message: `Agent initial build from specification`*

*Click **Commit changes**.*

### ***Test Your Creation***

***Local test:** Download the file from GitHub and open in browser. **Or wait for Module 5** when we deploy to GitHub Pages for live testing.*

*Check: Does layout look right? Do colors match? Do hover states work? Resize window to mobile \- does it adapt?*

### ***🎊 Celebration Checkpoint***

*Screenshot this moment. You just directed an AI to build production software from your specification. Your text description became working code. **This is agentic engineering.***

---

## ***Lesson 4.4: Iterate to Polish***

***Time:** 20 minutes*  
 ***Outcome:** Refined code through directive feedback*

### ***Test and Document Issues***

*Test your code thoroughly. Make a list of specific problems:*

```
1. Button padding too small (is 12px 24px, should be 16px 32px)
2. No hover effect on button (should darken to #2563eb)
3. Mobile text too small (is 14px, should be 16px)
```

*Prioritize: Fix critical and major issues first. Save polish for later.*

### ***The Full File Trick***

***Always ask for the complete updated file**, not snippets. In Claude:*

```
Please make these exact changes:

1. Button padding: 16px 32px (not 12px 24px)
2. Add button hover state: background #2563eb
3. Mobile font size: 16px (not 14px)

Output the FULL updated index.html with these changes.
```

***What makes feedback directive:***

* *Specific measurements: "16px 32px" not "bigger"*  
* *Exact values: "\#2563eb" not "darker blue"*  
* *Action verbs: "Change... Add... Increase..."*

***What makes feedback bad:***

* *❌ "The button looks weird"*  
* *❌ "Make it more modern"*  
* *❌ "Fix the mobile version"*

### ***Apply and Test***

*Claude outputs complete updated file. Review changes, then:*

1. *Copy from Claude*  
2. *GitHub → `src/index.html` → Edit*  
3. *Select All → Delete → Paste*  
4. *Commit: "Iteration 1: Fixed button, mobile responsive"*  
5. *Test again*

*Iterate as needed until your SUCCESS CRITERIA from the spec are all checked.*

---

## ***Lesson 4.5: Document Your Work***

***Time:** 10 minutes*  
 ***Outcome:** Professional documentation*

### ***Update Your README***

*Navigate to your main `README.md` (not in folders). Click edit pencil, replace with:*

```
# My First Agent Project

A personal [project type] built using agentic engineering during Agentics 101.

## Overview
[2-3 sentences describing what this is]

## Built With
- AI Agent: Claude.ai
- Method: Specification-driven development
- Human Role: Supervisor and reviewer

## Process
- Module 1: Wrote 10-line micro-spec
- Module 2: Enhanced with hex codes and measurements
- Module 3: Set up GitHub repository
- Module 4: Generated code via agent
- Iterations: [X] rounds of feedback
- Time to completion: [Y] minutes

## What I Learned
- Clear specs eliminate AI ambiguity
- Manual review builds supervision skills
- Directive feedback produces accurate results

## Live Demo
[Module 5 will add deployment link]

---
**Course:** Agentics 101 | Bradley Ross, Nicholas Ruest, The Agentics Foundation
```

### ***Review Commit History***

*Click "Commits" to see your development story from empty → basic → polished. This demonstrates process, not just results.*

---

## ***Module 4 Complete\! 🎊***

### ***Quick Check***

```
Module 4 ■■■■■■■ COMPLETE!
Agent: Claude.ai ✓
Workflow: Specification → Code ✓
Result: WORKING SOFTWARE ✓
Skill: AGENTIC ENGINEER ✓
```

### ***You Just Mastered the Core Skill***

***Directing AI with specifications to build production software.***

*Everything else—copy-pasting, Git commits, file management—is just logistics. The real skill is:*

1. *Writing clear specifications*  
2. *Giving directive feedback*  
3. *Reviewing output critically*  
4. *Iterating to perfection*

*This skill is worth tens of thousands of dollars in the job market. Sarah leveraged it into a $95,000/year role. Not because she could code (she couldn't), but because she could supervise agents that code.*

### ***You Accomplished***

* *Transformed Claude from chatbot to coding agent*  
* *Fed specifications and context systematically*  
* *Generated 100+ lines of production code*  
* *Iterated using directive feedback*  
* *Documented your process professionally*  
* *Built version control habits*  
* *Developed the "Supervisor Muscle"*

### ***Your Badge***

```
🚀 AGENTIC ENGINEER
Module 4 Graduate
"I supervise AI that builds software"
```

### ***The Reflection Moment***

*Think back to Module 0\. You were probably intimidated by "AI Engineering" and "GitHub" and "agents." Now you've:*

* *Created professional repository structure*  
* *Written production-grade specifications*  
* *Supervised an AI agent to generate code*  
* *Iterated on output like a senior engineer*  
* *Documented your work for portfolio use*

***That's the transformation. User → Supervisor → Engineer.***

### ***⚠️ Free Tier Limits***

*Claude's free tier has conversation length limits. If Claude says "I can't reply" or "This conversation is too long," you've hit the limit.*

***Solution:***

1. *Start a **new chat** in Claude.ai*  
2. *Paste your system prompt again*  
3. *Paste your current code from GitHub*  
4. *Paste your specification*  
5. *Continue from where you left off*

*The context reset is annoying but prevents you from losing progress. Always keep your spec and code saved in GitHub—that's your source of truth.*

### ***What's Next?***

*In **Module 5: Safety & Polish**, we professionalize your work. You'll:*

* *Create safety documentation (how you supervise agents)*  
* *Polish your README for portfolio use*  
* *Deploy your site to a live, public URL*  
* *Add the project to your LinkedIn*  
* *Prepare for job interviews*

*Module 5 is short (60 minutes) but critical. It's the difference between "I made a thing" and "I made a thing professionally, here's the live link."*

***Time to Module 5:** 60 minutes*  
 ***What to bring:** Your working project and a sense of accomplishment*

*Take a break. You've earned it. What you just did is genuinely impressive. 🚀*

---

## ***Quick Reference Card***

***System Prompt Template***

```
You are my coding agent. Generate complete, production-ready code based on specifications. Follow requirements exactly. Output full files, not snippets.

[Paste your spec here]
```

***Context Pattern***

```
CURRENT STATE: [paste existing code]
DESIRED STATE: [already in spec]
TASK: Transform current to desired.
```

***Directive Feedback Template***

```
Please make these exact changes:
1. [Specific change with numbers]
2. [Specific change with numbers]

Output the FULL updated file.
```

***Iteration Workflow***

```
1. Test current version
2. List specific issues
3. Give directive feedback
4. Review generated changes
5. Copy → Paste → Commit
6. Test again
7. Repeat as needed
```

---

## ***Troubleshooting***

***"Claude won't generate code"***

* *Check if you provided the system prompt*  
* *Make sure you pasted your specification*  
* *Try: "Please generate the code now"*  
* *If still stuck, start a new chat with full context*

***"Claude generated incomplete code"***

* *Say: "The code seems incomplete. Please output the full index.html from \<\!DOCTYPE\> to \</html\>"*  
* *Free tier may have hit rate limit—start new chat*

***"Code has syntax errors when I paste to GitHub"***

* *Common culprit: Smart quotes or Unicode characters*  
* *Paste into plain text editor first (Notepad, TextEdit)*  
* *Then copy from there to GitHub*

***"Changes aren't showing when I refresh"***

* *Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)*  
* *Clear browser cache*  
* *Try a different browser or incognito mode*

***"I made a mistake and want to undo"***

* *GitHub keeps all history*  
* *Click "History" on your file*  
* *Click the commit before your mistake*  
* *Click "Browse files"*  
* *Copy the old version*  
* *Paste it back as a new commit*

***"My commits aren't showing in history"***

* *Make sure you clicked "Commit changes" not just "Save"*  
* *Check if you're on the right branch (should be "main")*  
* *Refresh the GitHub page*

***"Claude forgot my specification"***

* *Free tier conversations have memory limits*  
* *Start new chat, paste system prompt \+ spec again*  
* *Consider keeping a "working prompt" document with your full context*

---

## ***💎 Optional: Pro Challenge (Automated Workflow)***

***For:** Students who completed Modules 0-4 and want professional automation*  
 ***Prerequisites:** Comfortable with technical tools, completed Web Path first*

### ***Why Go Pro***

*The Web Path teaches verification through manual copy-paste (\~5 min/iteration). Pro tools automate this to \~30 seconds/iteration while maintaining the review step. Setup and pricing details are in Module 3's Pro Path section.*

### ***Tool Options***

***Cursor (Best for Beginners)***

* *Smooth AI-first editor built on VS Code*  
* *Composer Mode: Describe changes, AI modifies multiple files*  
* *Setup in Module 3 applies here*

***Roo Code (Best for Flexibility)***

* *VS Code extension supporting multiple AI providers*  
* *Reads files with `@filename` syntax*  
* *Setup in Module 3 applies here*

***Claude Code (Best for Terminal Users)***

* *CLI tool for command-line workflows*  
* *Example: `claude-code generate --spec specs/page-spec.md --output src/index.html`*  
* *Setup in Module 3 applies here*

### ***The Workflow Difference***

***Web Path (Current):***

```
Spec → Claude → Copy → GitHub → Test
```

***Pro Path (Automated):***

```
Spec → Tool Command → Review Diff → Approve → Test
```

*The supervision skill is identical. The mechanical work is automated.*

### ***Safety First***

***Always review diffs** (red \= deleted, green \= added) before accepting changes. **Commit frequently** for easy rollback. **Use branches** for experiments. Pro tools have write access—review everything.*

### ***When to Upgrade***

*Use Pro tools when you've finished Module 6, understand the manual workflow completely, and want to scale to larger projects. Don't optimize prematurely—master fundamentals first.*

---

***Course Creators:** Bradley Ross, Nicholas Ruest, The Agentics Foundation*  
 ***Version:** 2.0 | **Module:** 4 of 6*  
 ***Next Module:** Safety & Polish (60 minutes)*

***GitHub**: https://github.com/bar181/agentics-101-course*

