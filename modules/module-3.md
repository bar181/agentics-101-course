# ***Module 3: Your Sandbox (GitHub) 🏗️***

***Time:** 45 minutes (Standard Path) | 60 minutes (Pro Path)*  
 ***Deliverable:** GitHub repo with `/specs` and `/src` folders*  
 ***Confidence Level:** ⭐⭐⭐⭐ (Infrastructure Setup)*

---

## ***Module Overview***

*Your agent needs a home. Not just a folder on your laptop that disappears when you spill coffee on your keyboard, but a professional workshop in the cloud where it can read instructions and write code safely.*

*In this module, you will create a **GitHub Repository**. If that sounds intimidating, don't worry. A "repository" is just a fancy word for a folder that lives on the internet. The same way Google Drive stores documents in the cloud, GitHub stores code in the cloud. That's it. No magic. No complexity. Just organized file storage with superpowers.*

***We will also choose your workspace.** For most of this course, we recommend using the **GitHub Website** directly. It works like Google Docs for code—simple, free, works on any device, and impossible to accidentally break your computer. You click "Edit," make changes, click "Save" (called "Commit" in GitHub-speak), and you're done.*

*However, if you want to feel like a professional engineer, we'll show you how to launch **GitHub Codespaces**. This gives you a full Visual Studio Code editor right in your browser—the same tool used by engineers at Google, Microsoft, and NASA. The best part? No downloads. No installation. No "it works on my machine" problems. Just click a button and start coding.*

***Sarah's Experience:***

*Sarah was terrified of "Git." She'd heard horror stories from developer friends about merge conflicts, detached heads, and accidentally force-pushing to production. She thought she would somehow delete the entire internet if she clicked the wrong button.*

*Fifteen minutes into this module, she laughed and said, "Wait, that's it? It's just organizing folders? I've been organizing folders my entire career. Why do programmers make this sound so scary?"*

***The truth:** Git is powerful, which means it can be complex if you want it to be. But for our purposes—creating folders, uploading files, and saving changes—it's just point-and-click. You've been doing harder things on your computer for years.*

***Let's build your agent's home together.***

### ***Your Learning Path***

*✅ Create your Agent's Home (Repository)*  
 *✅ Set up the "Input/Output" folders*  
 *✅ Upload your Module 2 files*  
 *✅ Verify your Agent's workspace is ready*  
 *✅ \[Optional\] Explore Pro Tools: Codespaces, Roo, Cursor, Claude Code*

---

## ***Lesson 3.1: Create Your Agent's Home***

***Time:** 10 minutes*  
 ***Outcome:** A professional repository structure*

### ***Lesson Overview***

*Agents act like chefs working in a kitchen. They need a designated place for recipes (`specs/` folder) and a separate place for the prepared food (`src/` folder). If you mix them up, the kitchen becomes chaotic. A chef who grabs a recipe thinking it's an ingredient is going to have a bad time.*

*We are going to build a clean, organized kitchen where everything has its place. This organizational system isn't arbitrary—it's based on decades of software engineering best practices. The structure we're building today is similar to how professional developers at companies like Apple, Amazon, and Netflix organize their code.*

### ***Why GitHub? (The Big Picture)***

*Before we start clicking buttons, let's understand why we're using GitHub instead of Dropbox or Google Drive.*

***GitHub is designed for code:***

* ***Version Control:** Every change is tracked. You can undo mistakes by reverting to any previous version.*  
* ***Collaboration:** Multiple people can work on the same files without overwriting each other.*  
* ***Deployment:** In Module 5, you'll deploy your site directly from GitHub with one click.*  
* ***Portfolio:** Employers check GitHub profiles. This repo becomes a portfolio piece.*

***The Kitchen Analogy:***

* *Dropbox \= A storage closet (good for files, bad for collaboration)*  
* *Google Drive \= A file cabinet (better for sharing, still not ideal for code)*  
* *GitHub \= A professional restaurant kitchen (designed specifically for building things)*

### ***Build Your Agent's Home: Step-by-Step***

***Step 1: Navigate to GitHub***

1. *Open your web browser*  
2. *Go to [github.com](https://github.com/)*  
3. *Sign in with the account you created in Module 0*  
4. *You should see your GitHub dashboard (a feed of activity)*

*Tip: If you forgot your password, click "Forgot password?" Don't create a new account—recovering your existing one maintains continuity.*

***Step 2: Create a New Repository***

*Look for the green **"New"** button. Depending on your screen, it's either:*

* *Top left, next to "Repositories"*  
* *Top right, in the navigation bar*

*Click it. You'll see a form titled "Create a new repository."*

***Step 3: Configure Your Repository***

*Fill in the form with these exact values:*

***Repository name:** `my-first-agent`*

* *Why this name? Consistency. When you need help in the community, everyone will know exactly what you're talking about.*  
* *Keep it lowercase with hyphens (the standard convention)*

***Description:** "Learning to build AI agents with structured specifications"*

* *This is optional but recommended*  
* *Helps you remember what this project is when you look at it in 6 months*

***Public or Private?***

* *Select **Public** (it's already selected by default)*  
* *Why public? You'll deploy this site in Module 5, and free deployment requires public repos*  
* *Don't worry about code theft—this is a learning project, not trade secrets*

***Initialize this repository with:***

* *✅ Check **"Add a README file"***  
* *Leave "Add .gitignore" empty*  
* *Leave "Choose a license" empty*

***Why add a README?** Every repository needs at least one file to exist. The README serves as your project's front page.*

***Step 4: Create the Repository***

*Click the green **"Create repository"** button at the bottom.*

***Boom. You just created your first GitHub repository.***

*GitHub will redirect you to your new repo's homepage. The URL will be:*

```
https://github.com/[your-username]/my-first-agent
```

***What you're seeing:***

* *A README.md file (created automatically)*  
* *Some buttons and tabs at the top*  
* *A green "\<\> Code" button (we'll use this later)*

***Sarah's reaction:** "That's it? I was expecting forms, verification steps, payment info. This is easier than creating a Facebook account."*

### ***Understanding Your Repository Dashboard***

*Let's orient ourselves. Your repository page has several sections:*

***The File List:***

* *Shows all files and folders in your project*  
* *Currently just has README.md*

***The Green "Code" Button:***

* *Lets you download, clone, or open in Codespaces*  
* *We'll use this later if you choose the Pro Path*

***The Tabs (Code, Issues, Pull Requests, etc.):***

* *Code: Your files (where you'll spend most time)*  
* *Issues: Bug tracking (ignore for now)*  
* *Pull Requests: Collaboration features (ignore for now)*

***The Commit History:***

* *Shows every change ever made*  
* *Currently shows 1 commit: "Initial commit"*

*You don't need to understand everything yet. Just know that this page is your repository's "home base."*

### ***Create the Folder Structure***

*Now we create the two-folder system that your agent will use. Here's where GitHub's web interface is a bit quirky—there's no obvious "New Folder" button. We use a simple trick.*

***Creating the `specs/` folder:***

1. *Click **"Add file"** (top right, near the green Code button)*  
2. *Select **"Create new file"** from the dropdown*  
3. *In the "Name your file" box, type: `specs/README.md`*  
   * ***Important:** The forward slash `/` creates the folder\!*  
   * *GitHub will show "specs" as a breadcrumb, then "README.md" as the file*  
4. *In the file content area, type: "This folder contains specifications (input for agents)"*  
5. *Scroll down to the "Commit new file" section*  
6. *In the commit message, it says "Create specs/README.md" \- that's perfect*  
7. *Click the green **"Commit new file"** button*

***What just happened?***

* *You created a folder called `specs`*  
* *You created a file inside it called `README.md`*  
* *GitHub committed (saved) this change to your repository*

***Creating the `src/` folder:***

*Repeat the exact same process:*

1. *Click **"Add file"** → **"Create new file"***  
2. *Type: `src/README.md`*  
3. *In the content, type: "This folder contains source code (output from agents)"*  
4. *Commit message: "Create src/README.md" (auto-filled)*  
5. *Click **"Commit new file"***

***Your repository should now have this structure:***

```
my-first-agent/
├── README.md
├── specs/
│   └── README.md
└── src/
    └── README.md
```

### ***Why This Structure Matters (The Philosophy)***

*This two-folder separation is the foundation of agentic engineering:*

***`specs/` \= Input (What the agent reads)***

* *Contains instructions, requirements, specifications*  
* *Think of this as the recipe cards*  
* *The agent reads from here but rarely writes here*  
* *You (the human) primarily write here*

***`src/` \= Output (What the agent writes)***

* *Contains generated code, assets, files*  
* *Think of this as the prepared dishes*  
* *The agent writes here based on specs*  
* *You (the human) primarily review here*

***The Separation Principle:***

*Keeping input and output separate prevents confusion. Imagine if a chef stored raw chicken next to cooked chicken—disaster waiting to happen. Same with code. Mixing instructions with output makes it impossible to know what's authoritative.*

***Professional developers use this pattern everywhere:***

* *`/docs` for documentation, `/code` for implementation*  
* *`/design` for mockups, `/build` for compiled apps*  
* *`/specs` for requirements, `/src` for source code*

*You're learning professional habits from day one.*

---

## ***Lesson 3.2: Choose Your Workspace***

***Time:** 10 minutes*  
 ***Outcome:** Decide how you want to work*

### ***Lesson Overview***

*You have a repository. Now, how do you edit files? You have two free options, each with different tradeoffs. This lesson helps you choose the right tool for your learning style.*

*The choice you make here doesn't lock you in forever. You can switch between workspaces at any time. Some students start with the Web Path to learn fundamentals, then graduate to Codespaces when they're ready for more power.*

### ***Option A: The Web Path (Recommended for Modules 3-5)***

***What is it?** Editing files directly on GitHub.com using your web browser. Click a file, click the pencil icon ✏️ to edit, type your changes, click "Commit changes" to save. That's the entire workflow.*

***Why use it?***

* ***Zero setup:** Works immediately on any device*  
* ***Forces review:** You manually copy code from Claude to GitHub, building the verification habit*  
* ***Can't break anything:** No terminal commands, no Git commands, no way to accidentally delete things*  
* ***Works everywhere:** School computer, library computer, tablet, anywhere with a browser*

***Why it's pedagogically valuable:** The manual copy-paste workflow seems tedious, but it's teaching you the most important skill in agentic engineering: **verification**. Every time you copy code from Claude to GitHub, you're forced to look at it. You notice patterns. You spot errors. You understand what the agent generated.*

*Students who start with automated tools (Codespaces \+ extensions) often don't develop this verification instinct. They approve changes without reading them. Then when something breaks, they don't know why.*

***The Web Path builds your "Supervisor Muscle."***

***How to use it:***

1. *Navigate to any file in your repo*  
2. *Click the pencil icon ✏️ (top right of the file content)*  
3. *Edit the file directly in your browser*  
4. *Scroll down, add a commit message*  
5. *Click "Commit changes"*  
6. *Done\!*

***Sarah's experience:** "I felt like I was editing a Google Doc. Zero learning curve. I could focus on understanding the concepts instead of fighting with tools."*

### ***Option B: The Pro Path (Codespaces)***

***What is it?** A full Visual Studio Code editor running in a cloud-based virtual machine, accessed through your browser. It's the actual VS Code application—the same one professional developers install on their computers—but running in the cloud.*

***Why use it?***

* ***Professional environment:** The same tools used at tech companies*  
* ***Terminal access:** Run commands, install tools, execute code*  
* ***Extensions:** Add powerful tools like Roo Code or Claude Code*  
* ***Real development experience:** Prepares you for professional work*

***Why it's advanced:** With great power comes great responsibility. Codespaces gives you:*

* *Terminal access (you can run commands that modify files)*  
* *Extension marketplace (you can install agent tools)*  
* *Git integration (you can use Git commands directly)*

*This means you can also:*

* *Accidentally delete files*  
* *Run commands you don't understand*  
* *Install extensions with bugs*  
* *Get confused by unfamiliar interfaces*

***When to choose Codespaces:***

* *You've completed Module 2 and feel confident*  
* *You're comfortable with some technical ambiguity*  
* *You plan to continue to Agentics 201*  
* *You want to experience professional tools*  
* *You have time for setup (adds 15-20 minutes to this module)*

***When NOT to choose Codespaces:***

* *This is your first programming-adjacent course*  
* *You're on a tight timeline to finish the course*  
* *You want to minimize cognitive load*  
* *You're using a shared/school computer*  
* *You just want to learn the concepts without tool complexity*

***How to use it:***

1. *Navigate to your repository homepage*  
2. *Click the green **"\<\> Code"** button*  
3. *Click the **"Codespaces"** tab*  
4. *Click **"Create codespace on main"***  
5. *Wait 30-60 seconds for the environment to launch*  
6. *A VS Code interface opens in your browser*  
7. *You now have a full development environment*

***The first time you launch Codespaces, you'll see:***

* *A file explorer on the left (your repo's files)*  
* *A large editor area in the center (where you'll edit code)*  
* *A terminal at the bottom (where you can run commands)*  
* *Extensions sidebar (where you can install tools)*

***Pro Path students should complete the optional setup section at the end of this module.***

### ***Making Your Choice***

***If you're unsure, choose the Web Path.** Here's why:*

*The goal of Agentics 101 is to teach you how to supervise agents. The workflow matters more than the tools. Whether you copy-paste manually or use automated tools, the underlying concepts are identical:*

1. *Write a spec*  
2. *Give it to an agent*  
3. *Verify the output*  
4. *Iterate as needed*

*The Web Path teaches these concepts without tool overhead. The Pro Path teaches the same concepts with professional tools added.*

***You can always upgrade later.** Many students complete Modules 3-5 on the Web Path, then switch to Codespaces for Module 6 when they want to build more complex projects.*

***For the rest of Module 3, we'll show both paths where they differ.***

---

## ***Lesson 3.3: Upload Your Module 2 Files***

***Time:** 10 minutes*  
 ***Outcome:** Module 2 files properly organized in GitHub*

### ***Lesson Overview***

*Time to move your furniture into the new house. You'll upload the Spec and Code you created in Module 2 into your GitHub repository. This transforms your local work into cloud-based, version-controlled project assets that your agent can access.*

*Remember that folder structure we set up? Now it pays off. Your spec goes in `specs/`, your code goes in `src/`. Clear separation. No confusion.*

### ***Upload the Specification (Web Path)***

***Step 1: Navigate to the specs folder***

1. *From your repository homepage, click the `specs` folder*  
2. *You'll see the README.md file you created earlier*

***Step 2: Create the spec file***

1. *Click **"Add file"** → **"Create new file"***  
2. *Name the file: `page-spec.md`*  
3. *Open your `agentics-101-project` folder on your computer*  
4. *Open `spec.md` in a text editor*  
5. *Copy ALL the content (your enhanced spec from Module 2\)*  
6. *Paste it into the GitHub file editor*

***Step 3: Commit the file***

1. *Scroll down to "Commit new file"*  
2. *Commit message: "Add enhanced page specification"*  
3. *Optional description: "Includes colors, measurements, and behaviors"*  
4. *Click **"Commit new file"***

***What you've done:** Your specification is now version-controlled in the cloud. If you lose your laptop, spill coffee on it, or accidentally delete the local file, this version is safe in GitHub forever.*

### ***Upload the Code (Web Path)***

***Step 1: Navigate to the src folder***

1. *Click the repository name at the top to go back to homepage*  
2. *Click the `src` folder*  
3. *You'll see the README.md file*

***Step 2: Create the HTML file***

1. *Click **"Add file"** → **"Create new file"***  
2. *Name the file: `index.html`*  
3. *Open your `agentics-101-project` folder on your computer*  
4. *Open `index.html` in a text editor*  
5. *Copy ALL the content (your generated HTML from Module 2\)*  
6. *Paste it into the GitHub file editor*

***Step 3: Commit the file***

1. *Scroll down to "Commit new file"*  
2. *Commit message: "Add initial HTML implementation"*  
3. *Optional description: "Generated from enhanced spec, includes responsive design"*  
4. *Click **"Commit new file"***

***Success\!** Your code is now in GitHub.*

### ***Verify the Upload (Both Paths)***

*Navigate back to your repository homepage. You should see:*

```
my-first-agent/
├── README.md
├── specs/
│   ├── README.md
│   └── page-spec.md    ← Your specification
└── src/
    ├── README.md
    └── index.html       ← Your code
```

***Quick verification checklist:***

* *\[ \] Does `specs/page-spec.md` contain your enhanced spec from Module 2?*  
* *\[ \] Does `src/index.html` contain your generated HTML from Module 2?*  
* *\[ \] Are both files in the correct folders?*

***If something is wrong:***

* *Click the file*  
* *Click the pencil icon ✏️ to edit*  
* *Fix the issue*  
* *Commit the changes*

### ***Sarah's Mistake (Learn From Her Pain)***

*Sarah was rushing. She accidentally created `page-spec.md` in the `src/` folder instead of the `specs/` folder. Later in Module 4, when she told Claude to "read the spec," Claude looked in `specs/` and found nothing. The agent was confused. Sarah was confused. Chaos ensued.*

***She fixed it by:***

1. *Creating the file in the correct folder*  
2. *Deleting the file from the wrong folder*  
3. *Committing both changes*

***Lesson:** Folder structure isn't arbitrary. The agent expects files in specific places. Put the spec in `specs/`, the code in `src/`, and everything works smoothly.*

---

## ***Lesson 3.4: Verify Agent-Ready Setup***

***Time:** 5 minutes*  
 ***Outcome:** Confirmed readiness for Module 4*

### ***Lesson Overview***

*Before we wake up the agent in Module 4, let's do a comprehensive "Pre-Flight Check." This verification ritual prevents 90% of the problems students encounter in Module 4\.*

*Think of this like a pilot's pre-flight checklist. Professional pilots check the same things every single time, even after 10,000 flights. Not because they don't trust themselves, but because checklists prevent errors. We're building the same professional habit.*

### ***The Agent-Ready Checklist***

*Work through this checklist carefully. Don't skip items.*

***Repository Structure:***

* *\[ \] Repository exists at `github.com/[your-username]/my-first-agent`*  
* *\[ \] Repository is public (visible to everyone)*  
* *\[ \] Repository has a README.md file*

***Folder Structure:***

* *\[ \] `specs/` folder exists*  
* *\[ \] `src/` folder exists*  
* *\[ \] Each folder has at least one file besides README.md*

***Specification File:***

* *\[ \] `specs/page-spec.md` exists*  
* *\[ \] File contains your enhanced spec (with hex codes, measurements, behaviors)*  
* *\[ \] Spec has all four sections: WHAT, PARTS, RULES, SUCCESS*  
* *\[ \] Spec is properly formatted (not corrupted)*

***Code File:***

* *\[ \] `src/index.html` exists*  
* *\[ \] File contains complete HTML (from `<!DOCTYPE html>` to `</html>`)*  
* *\[ \] HTML includes embedded CSS in `<style>` tags*  
* *\[ \] Code matches your specification*

***Editing Capability:***

* *\[ \] You can edit files (via pencil icon or Codespace)*  
* *\[ \] You can commit changes*  
* *\[ \] You can view your commit history*

***Backup Verification:***

* *\[ \] You still have local copies of both files*  
* *\[ \] You've tested that you can edit and save in GitHub*

***If any checkbox is unchecked, fix it now before continuing.***

### ***The Mental Model (Understanding the Flow)***

*Let's visualize how everything connects in Module 4:*

```
┌─────────────┐
│   Human     │ You write specifications
│    (You)    │ and verify agent output
└──────┬──────┘
       │
       ├─── Writes spec
       │
       ▼
┌─────────────┐
│   specs/    │ Contains instructions
│ page-spec.md│ (Input to agent)
└──────┬──────┘
       │
       ├─── Agent reads
       │
       ▼
┌─────────────┐
│   Claude    │ Processes specification
│   (Agent)   │ and generates code
└──────┬──────┘
       │
       ├─── Agent writes
       │
       ▼
┌─────────────┐
│    src/     │ Contains generated code
│ index.html  │ (Output from agent)
└──────┬──────┘
       │
       ├─── Human reviews
       │
       ▼
┌─────────────┐
│   GitHub    │ Stores everything with
│   (Storage) │ version control
└─────────────┘
```

***The cycle in Module 4:***

1. *You read the current spec and code*  
2. *You decide what changes to make*  
3. *You instruct Claude (the agent) what to do*  
4. *Claude generates updated code*  
5. *You review the changes*  
6. *You commit the changes to GitHub*  
7. *Repeat as needed*

***If your repository structure is correct, this cycle works smoothly.***

*If your structure is wrong (spec in the wrong folder, missing files, corrupted content), the cycle breaks at step 3 or 4, and you'll spend time debugging instead of learning.*

### ***The "5-Minute Build" Test***

*Want to verify everything is ready? Do this quick test:*

1. *Open a new Claude chat*  
2. *Type: "I have a specification at specs/page-spec.md in my GitHub repo. Can you suggest three improvements?"*  
3. *Claude should be able to discuss your spec conceptually (it can't actually access GitHub, but it can discuss the structure)*

*If you can explain your repository structure to Claude and it understands, you're ready for Module 4\.*

---

## ***Module 3 Complete\! 🎊***

### ***Quick Check***

```
Module 3 ■■■■■■■ COMPLETE!
Status: Infrastructure Ready ✓
Repository: Cloud-Based ✓
Workspace: Web or Codespaces ✓
Files: Uploaded and Organized ✓
```

### ***You Just Accomplished***

* *Created a professional GitHub repository*  
* *Set up the industry-standard folder structure (specs/ and src/)*  
* *Uploaded your specification and code to the cloud*  
* *Verified your agent's workspace is ready*  
* *Chose your development workspace (Web or Pro Path)*  
* *Understood version control and commit history*  
* *Built the foundation for Module 4's agent workflow*

### ***Your Badge***

```
🏗️ SANDBOX BUILDER
Module 3 Graduate
"My agent has a home in the cloud"
```

### ***What's Next?***

*In **Module 4: Build Your Agent**, the magic happens. We will connect the Brain (Claude) to the Body (GitHub). You will feed your spec to the agent and watch it build your vision in real-time.*

*This is the module everyone remembers. You'll experience the "Holy shit, I just built something real" moment that Sarah described. The moment where abstract concepts become tangible results.*

***Time to Module 4:** 90 minutes*  
 ***What to bring:** Patience, curiosity, and trust in the process*

*Take a break. Walk around. Grab a snack. Module 4 is intense and amazing. 🏗️*

---

## ***Quick Reference Card***

***Repository Structure***

```
my-first-agent/
├── README.md         (Project description)
├── specs/            (Input - Agent reads from here)
│   ├── README.md
│   └── page-spec.md  (Your enhanced specification)
└── src/              (Output - Agent writes to here)
    ├── README.md
    └── index.html    (Your generated code)
```

***Web Path Workflow***

```
1. Navigate to file in GitHub
2. Click pencil icon ✏️
3. Make changes
4. Scroll down, add commit message
5. Click "Commit changes"
```

***Codespaces Workflow***

```
1. Click green "Code" button
2. Click "Codespaces" tab
3. Click "Create codespace on main"
4. Edit files in VS Code interface
5. Use Source Control panel to commit
```

***Pre-Flight Checklist***

```
✓ Repository exists and is public
✓ specs/ folder has page-spec.md
✓ src/ folder has index.html
✓ Both files have complete content
✓ You can edit and commit
```

---

## ***Troubleshooting***

***"I can't find the 'New' button to create a repository"***

* *Look for a green button, usually top-right*  
* *If you see a "+" icon instead, click it and select "New repository"*  
* *Make sure you're logged in to GitHub*

***"GitHub won't let me create a file in a folder"***

* *Remember the slash trick: type `folder-name/file-name.md`*  
* *The slash creates the folder automatically*  
* *You can't create an empty folder—it must contain at least one file*

***"I uploaded my files but they're in the wrong folder"***

* *You can move files: Click the file → Click pencil icon → Edit the path in the filename box*  
* *Or delete and recreate: Click the file → Click trash icon → Recreate in the right place*

***"My index.html shows code instead of rendering the page"***

* *That's correct for now\! GitHub shows the raw HTML*  
* *In Module 5, you'll enable GitHub Pages to see it rendered*  
* *For now, you can test locally by saving and opening in a browser*

***"I accidentally deleted something"***

* *Click "Commits" in your repository*  
* *Find the commit before you deleted it*  
* *Click "Browse files" at that commit*  
* *Navigate to the deleted file*  
* *Click "Raw" and copy the content*  
* *Create the file again with that content*

***"Codespaces shows 'You've used X hours of your free 60 hours'"***

* *This is normal—Codespaces tracks usage*  
* *60 hours/month is plenty for this course*  
* *Remember to stop Codespaces when not using it (prevents waste)*  
* *Click "Codespaces" in the menu → Click "..." next to your codespace → "Stop"*

***"I'm confused about which workspace to use"***

* *When in doubt, use the Web Path (GitHub.com editor)*  
* *It's simpler and teaches verification habits*  
* *You can always switch to Codespaces later*  
* *Both paths work equally well for this course*

---

## ***💎 Optional: Pro Path Setup & Tools***

***Note:** This section is for advanced users who chose Codespaces in Lesson 3.2 and want to automate the workflow. You do not need this to complete the course.*

*Professional engineers use "Integrated Development Environments" (IDEs) and extensions to skip the copy-paste workflow. These tools let agents read your entire repository, modify multiple files, and commit changes automatically.*

***This is powerful. It's also dangerous.** These tools have write access to your code. Always review changes before accepting them.*

### ***Understanding the Pro Ecosystem***

*The Pro Path consists of three components working together:*

***1\. The Sandbox (Codespaces)***

* *Provides a safe cloud environment*  
* *Prevents agent errors from affecting your personal computer*  
* *Gives you a full development environment (VS Code \+ terminal)*

***2\. The Agent Tool (Roo Code, Cursor, or Claude Code)***

* *Connects AI agents to your codebase*  
* *Reads files automatically*  
* *Writes changes based on your instructions*

***3\. The API Key (Claude API)***

* *Allows tools to access Claude's intelligence*  
* *Pay-as-you-go pricing (\~$5-20/month for this course)*  
* *You Bring Your Own Key (BYOK model)*

***Think of it like this:***

* *Codespaces \= The car*  
* *Roo/Cursor/Claude Code \= The GPS navigation system*  
* *Claude API \= The fuel*

*You need all three for the complete Pro experience.*

### ***Tool Option 1: GitHub Codespaces \+ Roo Code***

***Best for:** Visual learners who prefer clicking buttons over typing commands.*

***Setup Steps:***

***Step 1: Launch Codespaces** (You already did this if you chose Option B in Lesson 3.2)*

***Step 2: Install Roo Code Extension***

1. *In Codespaces, click the Extensions icon (left sidebar, looks like four squares)*  
2. *Search for "Roo Cline"*  
3. *Click "Install"*  
4. *Wait 10-15 seconds for installation*

***Step 3: Get Claude API Key***

1. *Open a new browser tab*  
2. *Go to [console.anthropic.com](https://console.anthropic.com/)*  
3. *Sign up for an account (separate from Claude.ai)*  
4. *Click "API Keys" in the left sidebar*  
5. *Click "Create Key"*  
6. *Name it: "Agentics-101-Roo-Code"*  
7. *Copy the key (starts with "sk-ant-")*  
8. ***IMPORTANT:** Save this key somewhere safe—you can't view it again*

***Step 4: Configure Roo Code***

1. *Back in Codespaces, click the Roo Code icon (left sidebar)*  
2. *Click "Settings" (gear icon)*  
3. *Select "API Provider: Anthropic"*  
4. *Paste your API key*  
5. *Select "Model: Claude Sonnet 4.5"*  
6. *Click "Save"*

***Step 5: Test the Setup***

1. *In Roo Code interface, type: "Read specs/page-spec.md and summarize it"*  
2. *Roo should read your spec and provide a summary*  
3. *If it works, you're ready\!*

***Using Roo Code:***

* *Type instructions in the chat interface*  
* *Roo reads your entire repository automatically*  
* *It proposes changes (shows you a diff—red for deleted, green for added)*  
* *You review and accept/reject changes*  
* *Approved changes are written to files*  
* *You commit using the Source Control panel*

***Cost:** Free tool \+ \~$5-15/month for API usage*

### ***Tool Option 2: Cursor (Standalone Editor)***

***Best for:** Users who want the smoothest, most polished AI coding experience.*

***What is Cursor?** Cursor is a fork of VS Code (meaning it's built on the same foundation) but designed from scratch for AI-first development. It has "Composer Mode" where you describe what you want and the AI modifies multiple files across your project.*

***Setup Steps:***

***Step 1: Download Cursor***

1. *Go to [cursor.com](https://cursor.com/)*  
2. *Download for your OS (Windows/Mac/Linux)*  
3. *Install (same as any application)*  
4. *Launch Cursor*

***Step 2: Clone Your Repository***

1. *In Cursor, press `Cmd/Ctrl + Shift + P`*  
2. *Type "Git: Clone"*  
3. *Enter your repo URL: `https://github.com/[username]/my-first-agent`*  
4. *Choose a folder to clone to*  
5. *Open the cloned repository in Cursor*

***Step 3: Configure API Key***

1. *Click Settings (bottom right gear icon)*  
2. *Navigate to "Cursor" settings*  
3. *Select "Models"*  
4. *Click "Add API Key"*  
5. *Choose "Anthropic"*  
6. *Paste your Claude API key*  
7. *Select "Claude Sonnet 4.5" as default model*

***Step 4: Enable Composer Mode***

1. *Press `Cmd/Ctrl + I` to open Composer*  
2. *Type: "Read specs/page-spec.md and explain the project"*  
3. *Cursor should read and discuss your spec*

***Using Cursor:***

* *Press `Cmd/Ctrl + K` for inline AI editing*  
* *Press `Cmd/Ctrl + I` for Composer (multi-file) mode*  
* *Describe changes in natural language*  
* *AI proposes changes across multiple files*  
* *Review diff, accept/reject*  
* *Changes are applied automatically*  
* *Commit using built-in Git panel*

***Cost:** Cursor has a free tier with limited requests. Pro tier is $20/month. Or use BYOK (Bring Your Own Key) with Claude API.*

### ***Tool Option 3: Claude Code (CLI)***

***Best for:** Power users comfortable with terminal commands who want maximum control.*

***What is Claude Code?** A command-line tool that lets you interact with Claude directly from your terminal. You can pipe files to Claude, run scripts that generate code, and integrate agents into automated workflows.*

***Setup Steps:***

***Step 1: Install Node.js** (if not already installed)*

1. *In Codespaces terminal, type: `node --version`*  
2. *If it shows a version (v18+), you're good*  
3. *If not, install Node: `curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - && sudo apt-get install -y nodejs`*

***Step 2: Install Claude Code***

```shell
npm install -g @anthropic-ai/claude-code
```

***Step 3: Configure API Key***

```shell
claude-code config set ANTHROPIC_API_KEY your-api-key-here
```

***Step 4: Test Installation***

```shell
claude-code --version
```

*Should show version number.*

***Using Claude Code:***

***Read and summarize spec:***

```shell
claude-code read specs/page-spec.md --summarize
```

***Generate code from spec:***

```shell
claude-code implement specs/page-spec.md --output src/index.html
```

***Review changes before applying:***

```shell
claude-code implement specs/page-spec.md --dry-run
```

***Ask Claude questions:***

```shell
claude-code ask "How can I improve the accessibility of this HTML?"
```

***Cost:** Free tool \+ \~$5-15/month for API usage*

### ***Pro Path Workflow Comparison***

***Standard Web Path:***

```
Time per iteration: ~5 minutes
1. Write instruction in Claude chat
2. Copy generated code
3. Navigate to GitHub file
4. Click edit pencil
5. Paste code
6. Commit changes
7. Verify
```

***Codespaces \+ Roo Code:***

```
Time per iteration: ~1 minute
1. Type instruction in Roo
2. Review proposed diff
3. Click "Accept"
4. Commit via Source Control
```

***Cursor:***

```
Time per iteration: ~30 seconds
1. Press Cmd/K, describe change
2. Review diff
3. Press "Accept"
4. Auto-commits or manual commit
```

***Claude Code (CLI):***

```
Time per iteration: ~15 seconds
1. Run: claude-code implement spec.md
2. Review diff: git diff
3. Commit: git add . && git commit -m "message"
```

### ***Pro Path Safety Rules***

***Rule 1: Always Review the Diff** Never blindly accept agent changes. Always review:*

* *Red lines (deletions): What's being removed?*  
* *Green lines (additions): What's being added?*  
* *Does it match what you asked for?*

***Rule 2: Commit Often** Make small, frequent commits. If something breaks:*

```shell
git log              # See history
git checkout HEAD~1  # Go back one commit
```

***Rule 3: Test After Each Change** Don't stack changes. Test after each agent modification:*

* *Does the code still work?*  
* *Does it match your spec?*  
* *Any unexpected side effects?*

***Rule 4: Keep Local Backups** Even with version control, maintain local backups of critical specs.*

***Rule 5: Limit Agent Scope** Don't give the agent access to your entire computer. Use Codespaces (cloud sandbox) or dedicated project folders.*

### ***When to Use Pro Tools***

***Use Pro Tools when:***

* *You've completed Module 5 and want to build more*  
* *You're comfortable with the manual workflow*  
* *You understand what each step does*  
* *You can debug when things go wrong*  
* *You have budget for API usage*

***Don't use Pro Tools when:***

* *You're still learning the concepts*  
* *You can't explain what a commit is*  
* *You haven't finished the Web Path modules*  
* *You're on a tight budget*  
* *You want to minimize complexity*

***Bottom line:** Pro tools are an optimization, not a requirement. Master the fundamentals first, optimize later.*

---

***Course Creators:** Bradley Ross, Nicholas Ruest, The Agentics Foundation*  
 ***Version:** 2.0 | **Module:** 3 of 6*  
 ***Next Module:** Build Your Agent (90 minutes)*

***GitHub**: https://github.com/bar181/agentics-101-course*

