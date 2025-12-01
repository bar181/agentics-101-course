# ***Module 5: Safety & Polish 🛡️***

***Time:** 60 minutes*  
 ***Deliverable:** Professional README, SAFETY.md, and Live Deployment*  
 ***Confidence Level:** ⭐⭐⭐⭐⭐ (Professional Grade)*

---

## ***Module Overview***

*Your agent works. Now make it safe and shareable.*

*You'll learn the **Three Laws of Agent Safety**—principles that separate amateurs from engineers. Then you'll transform your repository into a portfolio piece with professional documentation. Finally, you'll deploy to a live URL you can share on LinkedIn or in job applications.*

***Sarah's Reflection:** "Module 4 was exciting because the code worked. Module 5 made me hireable. Recruiters didn't care about the HTML—they cared that I had a SAFETY.md file. It showed maturity."*

### ***Your Learning Path***

*✅ Learn the Three Safety Laws*  
 *✅ Create SAFETY.md documentation*  
 *✅ Write a Portfolio-Grade README*  
 *✅ Deploy your work to the web*

---

## ***Lesson 5.1: The Three Laws of Safe Agents***

***Time:** 15 minutes*  
 ***Outcome:** Understand and apply core safety principles*

### ***Lesson Overview***

*Agents are powerful tools. These three laws keep them helpful instead of harmful. Even though you're copying code manually now, learning these principles prepares you for automated tools and demonstrates professional thinking to employers.*

### ***The Three Laws***

***Law 1: Human Approval Required (HITL)***

*Never let agents act without your review. This catches errors before they become problems.*

* ***Manual workflow:** Read code blocks completely before pasting to GitHub*  
* ***Automated tools:** Never enable "Auto-Approve," always review diffs*  
* ***Why:** AI is probabilistic—even good specs occasionally produce subtle bugs*

***Law 2: Bounded Scope***

*Tell agents exactly where they can work. Set clear boundaries.*

* ***The rule:** Agents READ from `specs/`, WRITE to `docs/`, cannot modify `.git` or root files*  
* ***Implementation:** Specify allowed folders in every prompt*  
* ***Why:** Without bounds, agents interpret "clean up the project" as permission to delete files*

***Law 3: Read Before Write***

*Show agents the current state before asking for changes.*

* ***The workflow:** Provide current file → Provide target spec → Agent proposes changes → Human reviews*  
* ***The analogy:** Doctors examine patients before prescribing medicine*  
* ***Why:** Context prevents overwrites, conflicts, and lost work*

### ***Real Examples***

***Case 1:** Developer said "Clean up the project." Agent deleted all images.*  
 ***Case 2:** Student pasted without reading. Browser crashed from infinite loop.*  
 ***Case 3:** Agent published passwords to public repo (no review step).*

***Sarah's close call:** "I almost said 'fix all styling issues.' Then I remembered Law 2\. I specified 'fix button colors in index.html only.' Perfect result. Vague instructions would have changed everything."*

***The mindset:** Treat agents like brilliant interns on day one. Genius? Yes. Common sense? No. Needs supervision? Always.*

---

## ***Lesson 5.2: Create Safety Documentation***

***Time:** 15 minutes*  
 ***Outcome:** Professional safety guidelines in SAFETY.md*

### ***Lesson Overview***

*Every professional agentic project needs safety documentation. Your `SAFETY.md` file serves two purposes: it protects you from mistakes, and it shows employers you think about risk and responsibility.*

### ***Create Your SAFETY.md***

***Step 1: Create the File***

*In your repository, click **"Add file"** → **"Create new file"**. Name it: `SAFETY.md`*

***Step 2: Paste the Template***

```
# Agent Safety Guidelines 🛡️

## Purpose
This AI agent converts specifications into code with human oversight.

## The Three Laws
1. **Human Approval Required**: Every change needs explicit review
2. **Bounded Scope**: Agent only modifies files in `docs/`
3. **Read Before Write**: Agent must see current code before changes

## Approved Actions
✅ Read any file in `specs/`  
✅ Generate HTML/CSS/JavaScript  
✅ Suggest improvements  
✅ Update files in `docs/`

## Forbidden Actions
❌ Delete files without explicit permission  
❌ Modify `specs/` folder (read-only)  
❌ Modify `.git` configurations  
❌ Make changes without showing code first

## Human Responsibilities
- Review every line of generated code
- Test in browser before committing
- Keep specifications clear and detailed
- Commit frequently to create rollback points

## Emergency Recovery
If agent generates bad code:
1. Do NOT commit the changes
2. If already committed, use Git history to restore previous version
3. Clarify the specification and regenerate
4. Document what went wrong to prevent recurrence
```

***Step 3: Commit***

*Scroll down, commit message: `Add agent safety guidelines`*

***Why this matters:** When hiring managers review your GitHub, this file signals professional maturity. Sarah said every interviewer specifically mentioned her SAFETY.md as evidence she thinks beyond "making it work."*

---

## ***Lesson 5.3: Write a Professional README***

***Time:** 15 minutes*  
 ***Outcome:** Portfolio-grade project documentation*

### ***Lesson Overview***

*Your `README.md` is your repository's front door. When recruiters visit your project, this is what they read first. Let's transform it from boilerplate into a professional showcase.*

### ***Build Your Professional README***

*Open your current `README.md`, click the **edit pencil ✏️**, and replace all content with this template:*

```
# My First AI Coding Agent 🤖

> AI-powered development workflow that converts specifications into production code through supervised agent execution.

Built during **Agentics 101** to master specification-driven development.

## What This Demonstrates

- **Specification writing**: Converting requirements into precise instructions
- **AI supervision**: Directing Claude.ai to generate code from specs
- **Human-in-the-loop review**: Maintaining quality through verification
- **Safety protocols**: Operating AI within bounded parameters
- **Professional documentation**: Creating maintainable projects

## The Workflow

```

*📝 Specification → 🤖 Agent Generation → 👤 Human Review → ✅ Production*

```

1. Write detailed requirements in `specs/`
2. AI agent generates code matching specifications
3. Human verifies output quality and accuracy
4. Approved code committed and deployed

## Results

- **Development Time**: 15 minutes spec-to-code (vs ~2 hours manual)
- **First-Pass Accuracy**: 95%+ with detailed specifications
- **Iterations**: 2-3 cycles to production quality
- **Efficiency Gain**: ~8x faster than traditional coding

**Key Learning**: Specification detail directly correlates with output quality.

## Technical Stack

**Development Tools**
- AI Agent: Claude.ai (Sonnet 4)
- Version Control: GitHub
- Deployment: GitHub Pages

**Approach**
- Methodology: Specification-driven development
- Human Role: Supervisor, reviewer, quality control
- Agent Role: Code generation, implementation
- Safety Model: Human-in-the-loop (HITL)

## Project Structure

```

*my-first-agent/ ├── specs/ \# 📋 Specifications (read-only for agent) ├── docs/ \# 📦 Generated code (deployed) ├── SAFETY.md \# 🛡️ Safety protocols └── README.md \# 📖 Documentation*

```

## How to Use

1. **Write Specification** in `specs/` with colors, measurements, behaviors
2. **Generate Code** using Claude.ai with system prompt
3. **Review Output** for accuracy and quality
4. **Deploy** to `docs/` and commit changes

## Key Learnings

- Precise specifications eliminate AI ambiguity
- Directive feedback beats vague requests
- Manual review builds error-detection intuition
- Safety protocols prevent disasters

## Safety Features

✅ Human approval required for all changes  
✅ Agent scope bounded to specific folders  
✅ Full Git history for rollback capability  
✅ Documented procedures in SAFETY.md

## Live Demo

🌐 **[View Live Site]** - [URL added after deployment]

---

**Course**: Agentics 101  
**Creators**: Bradley Ross, Nicholas Ruest, The Agentics Foundation  
**Completed**: [Today's date]

*Built with AI assistance, supervised by humans.*
```

***Customize before committing:***

* *Add today's date to completion date*  
* *You'll add the live URL in the next lesson*

*Commit message: `Update README with professional documentation`*

---

## ***Lesson 5.4: Deploy to Production***

***Time:** 15 minutes*  
 ***Outcome:** Live website with public URL*

### ***Lesson Overview***

*Time to deploy your website to GitHub Pages, giving you a real URL that works anywhere. GitHub Pages requires files in a `/docs` folder—a standard convention for documentation sites.*

### ***Deploy Step-by-Step***

***Step 1: Create docs Folder***

1. *Click **"Add file"** → **"Create new file"***  
2. *Type: `docs/index.html` (the `/` creates the folder)*  
3. *Open your `src/index.html` in another tab*  
4. *Copy all the HTML code*  
5. *Paste into `docs/index.html`*  
6. *Commit: `Create docs folder for deployment`*

***Step 2: Enable GitHub Pages***

1. *Repository → **Settings** tab (top navigation)*  
2. ***Pages** (left sidebar)*  
3. ***Branch**: Select `main`*  
4. ***Folder**: Select `/docs`*  
5. *Click **Save***  
6. *Wait 60-90 seconds, refresh page*  
7. *Your URL appears: `[username].github.io/my-first-agent`*

***Step 3: Update Repository***

1. *Code tab → **"About"** gear icon ⚙️ (right sidebar)*  
2. ***Website**: Paste your GitHub Pages URL*  
3. ***Topics**: Add `ai-agent`, `agentics-101`, `github-pages`*  
4. ***Save changes***

***Step 4: Add URL to README***

1. *Edit `README.md`*  
2. *Find "Live Demo" section*  
3. *Replace `[URL added after deployment]` with your actual URL*  
4. *Commit: `Add live site URL to README`*

### ***Test Your Site***

*Open your live URL. Verify colors, layout, mobile responsiveness, and interactive elements all work correctly.*

### ***Your 30-Second Demo Script***

*Practice explaining your project concisely:*

***Hook** (5 sec): "I built a coding agent that follows strict specifications"*  
 ***Process** (10 sec): "I write detailed requirements, AI generates code, I review everything"*  
 ***Result** (10 sec): \[Show live site\] "This was built in 15 minutes"*  
 ***Safety** (5 sec): "I built safety protocols to prevent unauthorized changes"*

*Sarah said being able to articulate her process in under a minute impressed interviewers more than technical details.*

---

## ***Module 5 Complete\! 🎊***

### ***Quick Check***

```
Module 5 ■■■■■■■ COMPLETE!
Safety: Documented ✓
README: Professional ✓
Live Site: Deployed ✓
```

### ***You Accomplished***

*Five modules ago, you had zero agentic engineering experience. Now you have:*

* *Professional GitHub repository with clear documentation*  
* *Safety protocols demonstrating responsible AI use*  
* *Live website anyone can visit*  
* *Portfolio piece for job applications*

### ***Your Badge***

```
🛡️ SAFETY SUPERVISOR
Module 5 Graduate
"I build AI systems responsibly"
```

### ***Homework***

1. ***Send your live URL to one friend**: "I supervised an AI to build this"*  
2. ***Post on LinkedIn** (optional): Share your project with \#Agentics101*  
3. ***Screenshot your repository** for your portfolio*

### ***What's Next***

***Module 6: Path Forward** (30 minutes) is your final module. You'll learn to scale this project, connect with the community, and plan your next steps.*

---

## ***Quick Reference***

***Essential Files***

```
SAFETY.md    - Safety protocols
README.md    - Professional docs
docs/        - Deployed code
specs/       - Specifications
```

***Three Laws***

```
1. Human Approval Required
2. Bounded Scope
3. Read Before Write
```

---

## ***Troubleshooting***

***"My GitHub Pages shows 404"***

* *Verify `index.html` is directly in `/docs` (not a subfolder)*  
* *Check Settings → Pages shows `main` branch and `/docs` folder*  
* *Wait 2-3 minutes for first deployment*  
* *Try Actions tab to see deployment status*

***"Live site looks different than expected"***

* *Clear browser cache (Ctrl/Cmd+Shift+R)*  
* *Verify CSS is embedded in `<style>` tags (no external files)*  
* *Check for absolute paths (use relative paths instead)*

***"Can't find the About gear icon"***

* *Code tab, right sidebar, very top*  
* *Small gear ⚙️ next to "About" text*  
* *Try zooming in if hard to see*

***"Changes not showing on live site"***

* *Wait 1-2 minutes for deployment*  
* *Hard refresh: Ctrl/Cmd+Shift+R*  
* *Check Git history that changes were committed*  
* *Try incognito mode (no cache)*

***"Should I delete /src folder?"***

* *Optional—both folders work fine*  
* *If deleting, verify `docs/` works first*  
* *Commit message: `Remove old src folder`*

---

## ***💎 Optional: Pro Path Safety***

***For:** Students using Cursor, Roo Code, or Claude Code*

*Automated tools require extra vigilance since they write files directly.*

***Additional Rules:***

***Always Review Diffs***

* *Red lines: Removed code*  
* *Green lines: Added code*  
* *Review before accepting every change*

***Never Auto-Approve***

* *Disable "auto-accept" in tool settings*  
* *Always manually review changes*  
* *One character error can break everything*

***Use Git Branches***

```shell
# Experiment safely
git checkout -b experiment
# Make changes, test
# If good: merge. If bad: delete branch
```

***Set Tool Permissions** In your system prompt:*

```
ALLOWED: Read specs/, Write docs/ only
FORBIDDEN: Delete files, modify specs/, change .git
```

***Commit After Each Change***

```shell
git add docs/index.html
git commit -m "Agent: Update button styles"
```

*Small commits \= easy rollback.*

***Recovery Commands***

```shell
# Undo uncommitted changes
git checkout -- docs/index.html

# Undo last commit
git reset HEAD~1

# Restore file from history
git checkout HEAD~3 -- docs/index.html
```

***When to Use Manual vs. Automated:***

* *Manual: Learning new concepts, critical changes*  
* *Automated: Routine changes, well-defined tasks*

*Sarah's approach: Manual for first implementation, automated for refinement.*


---

***Course Creators:** Bradley Ross, Nicholas Ruest, The Agentics Foundation*  
 ***Version:** 2.0 | **Module:** 5 of 6*  
 ***Next Module:** Path Forward (30 minutes)*

***GitHub**: [https://github.com/bar181/agentics-101-course](https://github.com/bar181/agentics-101-course)*

