# ***Module 0: Welcome & Pre-Flight Check 🚀***

***Time:** 15 minutes (Standard Path) | 30 minutes (Pro Path)*  
 ***Deliverable:** Completed readiness checklist \+ Workspace setup*  
 ***Confidence Level:** ⭐⭐⭐⭐⭐ (Easy Start)*

***Course Creators:** Bradley Ross, Nicholas Ruest, The Agentics Foundation*

---

## ***Module Overview***

*Welcome to **Agentics 101**.*

*If you've ever tried to write code with ChatGPT and ended up with a broken mess, you aren't alone. Meet Sarah. Sarah is a marketing manager who wanted to build a simple portfolio site. She spent three hours arguing with ChatGPT. It gave her code, she pasted it, the site broke, and she didn't know why. She felt like she wasn't "technical enough."*

***The problem wasn't Sarah. It was her workflow.***

*This course isn't about learning to type syntax. It's about learning to **think**. You are going to stop being a "User" and start being a "Product Manager." By the end of this course, you won't just be chatting with a bot; you will be directing an autonomous agent to build, style, and deploy a real website.*

*The manual workflow we use isn't a limitation—it's a feature. By acting as the "hands" between the Brain (Claude) and the Hard Drive (GitHub), you'll develop the most critical skill in agentic engineering: **verification**. Every time you copy code, you review it. Every time you review it, you learn to spot problems before they become disasters.*

### ***Course North Star***

***"You write the plan, the agent writes the file."***

### ***Your Learning Path***

*✅ **Module 0: Setup (You are here\!)***  
 *✅ Module 1: The Theory*  
 *✅ Module 2: The Spec*  
 *✅ Module 3: The Infrastructure*  
 *✅ Module 4: The Build*  
 *✅ Module 5: Safety*  
 *✅ Module 6: The Future*

---

## ***Lesson 0.1: The Mindset Shift***

***Time:** 5 minutes*  
 ***Outcome:** Understanding your new role*

### ***Lesson Overview***

*Before we touch a single button, we need to agree on one thing: **You are the Supervisor.** Think of the AI as a brilliant but literal intern. If you give them vague instructions, they will make a mess. If you give them a clear plan, they will perform magic.*

*This shift from "user" to "supervisor" is what separates casual AI users from professional agentic engineers. Users hope for the best. Supervisors verify every step. Users get frustrated when things break. Supervisors catch errors before they happen.*

### ***The New Rules of Engagement***

*We follow **The Bradley Method™**. Don't worry about memorizing this yet—we will practice it together throughout the course.*

1. ***Simplify the Spec:** If the instructions are long, the agent gets confused. Cut the words in half. Precision beats verbosity.*  
2. ***Test First:** Verify the plan in a chat window before touching the codebase. Never let an agent write directly to production.*  
3. ***Check the Diff:** Never blindly trust the AI. Look at the changes before you accept them. This habit will save you hours of debugging.*  
4. ***Smallest Change:** Always ask, "What is the smallest change that works?" Incremental progress beats massive rewrites.*

*These four rules will become second nature by Module 6\. For now, just know they exist.*

---

## ***Lesson 0.2: Pre-Flight Checklist***

***Time:** 5 minutes*  
 ***Outcome:** Confirmation that you are ready*

### ***Lesson Overview***

*We have stripped this course down to the absolute essentials. To succeed, you only need to confirm five things. Think of this as checking your luggage before the flight. If something is missing now, it's easy to fix. If we discover it missing in Module 4, we'll lose momentum.*

### ***The Checklist***

* *\[ \] **I can read basic HTML.** (You don't need to write it, just recognize that `<button>` is a button and `<div>` is a container)*  
* *\[ \] **I have access to an LLM.** (Claude.ai Free Tier is our recommendation, but ChatGPT or other LLMs work too)*  
* *\[ \] **I have a GitHub Account.** (This is where we save our work and deploy our final project)*  
* *\[ \] **I can commit 6 hours.** (Roughly 1 hour per module, self-paced. You can spread this over days or weeks)*  
* *\[ \] **I am ready to build.** (Attitude is everything. If you're curious and patient, you'll succeed)*

***If you checked all five boxes, you're ready. Let's set up your tools.***

---

## ***Lesson 0.3: Quick Setup (Standard Path)***

***Time:** 5 minutes*  
 ***Outcome:** Your tools are ready*

### ***Lesson Overview***

*Let's get your tools ready. We are using a **Free, Web-Based Stack** so anyone, anywhere can take this course. We call this the "Standard Path" or "Web Path."*

***Why the Standard Path?***

*We intentionally avoid complex software installation for the core curriculum. You will act as the "Hands" of the agent, manually moving code from the Brain (Claude) to the Hard Drive (GitHub). This forces you to **review** every line of code, which is the most important skill in 2025\.*

*Professional developers using $10,000/month AI tools still review every change. The manual workflow teaches you this habit from day one. Think of it like learning to drive with a manual transmission—it teaches you how the car actually works.*

### ***Step 1: Create Your Accounts***

1. ***GitHub:** Go to [github.com/signup](https://github.com/signup)*

   * *Use a professional username (you'll be sharing projects from this account)*  
   * *Verify your email address before proceeding*  
   * *Analogy: This is your **Hard Drive** in the cloud—where all your work lives permanently*  
2. ***Claude.ai:** Go to [claude.ai](https://claude.ai/)*

   * *Sign up with the same email you used for GitHub (keeps things organized)*  
   * *Free tier gives you access to Claude 3.5 Sonnet—perfect for this course*  
   * *Analogy: This is your **Brain** (The Agent)—where all the thinking happens*

*Tip: If GitHub is loading slowly, try refreshing. If Claude requires a waitlist, ChatGPT 4.0 works as an alternative.*

### ***Step 2: Verify Your Setup***

*Let's make sure everything works before we start building.*

1. ***GitHub Test:** Log into GitHub, click your profile icon (top right), and verify you see "Your profile" in the dropdown*  
2. ***Claude Test:** Open a new chat in Claude and type: "Respond with exactly: Setup verified ✓"*  
   * *If Claude responds correctly, your Brain is working*  
   * *If you get an error, check your internet connection and try again*

### ***Step 3: Bookmark These Links***

*You'll reference these throughout the course:*

* ***Course Style Guide:** \[Your repo\]/style-guide.md*  
* ***Course Handbook:** \[Your repo\]/instructor-handbook.md*  
* ***Community Chat:** \[Discord/Slack link\]*  
* ***Student Showcase:** \[Showcase link\]*

### ***Step 4: Choose Your Path***

*You have two options for completing Agentics 101:*

***🌐 The Standard Path (Recommended for First-Timers)***

* *Uses only web browsers (GitHub.com \+ Claude.ai)*  
* *Zero installation required*  
* *Works on any device (laptop, tablet, school computer)*  
* *Cost: $0*  
* *Time investment: 6 hours*  
* ***This is what 90% of students should choose***

***💎 The Pro Path (For Students Ready to Invest)***

* *Uses professional tools (Codespaces \+ Roo Code or Claude Code)*  
* *Requires setup and API key configuration*  
* *Automates the copy-paste workflow*  
* *Cost: \~$25-35/month (Codespaces \+ Claude API)*  
* *Time investment: 6 hours course \+ 1 hour setup*  
* ***Only choose this if you plan to continue with Agentics 201+***

***Decision Guide:** Start with Standard Path. You can always upgrade to Pro Path after Module 6 when you understand why the automation matters. Jumping straight to Pro Path without understanding the manual workflow is like learning to drive in a Tesla with full self-driving—you never learn how the car actually works.*

---

## ***\[Optional\] Pro Path Setup 💎***

***Note:** This section is entirely optional. The Standard Path teaches you everything you need for this course. Pro tools are for students who want to experience professional-grade automation.*

### ***What You're Getting***

*The Pro Path replaces manual copy-paste with automated workflows. Instead of copying code from Claude to GitHub by hand, your tools do it for you. This is how professional agentic engineers work once they've mastered the fundamentals.*

***Standard Path Workflow (Manual):***

1. *Write spec in GitHub*  
2. *Copy spec to Claude*  
3. *Claude generates code*  
4. *Copy code from Claude*  
5. *Paste code into GitHub*  
6. *Commit changes*  
7. *Verify output*

***Time per iteration:** \~5 minutes*

***Pro Path Workflow (Automated):***

1. *Write spec in Codespaces*  
2. *Run command: `roo implement page-spec.md`*  
3. *Tool reads spec, generates code, writes to files automatically*  
4. *Review diff in VS Code*  
5. *Commit changes*  
6. *Verify output*

***Time per iteration:** \~30 seconds*

### ***Pro Path Requirements***

* ***GitHub Account** (you already have this)*  
* ***GitHub Codespaces** (\~$10/month for 100 hours, or 60 hours free)*  
* ***Claude API Key** (\~$15-20/month for moderate usage, pay-as-you-go)*  
* ***Roo Code** (VS Code extension, free) OR **Claude Code** (CLI tool, free)*  
* ***Comfort with terminal commands** (we'll teach you, but this adds complexity)*

### ***Pro Path Setup Instructions***

*If you choose the Pro Path, follow these steps after creating your GitHub account:*

#### ***Step 1: Enable Codespaces***

1. *Go to your GitHub account settings*  
2. *Navigate to "Codespaces" in the left sidebar*  
3. *Verify you have access (all free GitHub accounts get 60 hours/month)*  
4. *Note: You'll create your first Codespace in Module 3*

#### ***Step 2: Get Claude API Access***

1. *Go to [console.anthropic.com](https://console.anthropic.com/)*  
2. *Sign up for an account (separate from Claude.ai)*  
3. *Navigate to "API Keys"*  
4. *Click "Create Key" and name it "Agentics-101"*  
5. *Copy the key and store it securely (you'll need this in Module 3\)*  
6. *Add $20 in credits to your account (this will last months for this course)*

*Important: The API key is different from your Claude.ai login. API access is pay-as-you-go, while Claude.ai free tier is for chat only.*

#### ***Step 3: Choose Your Tool***

***Option A: Roo Code (Recommended for Beginners)***

* *Visual interface inside VS Code*  
* *Click buttons to run agents*  
* *Easier to understand what's happening*  
* *Best for: Visual learners, first-time terminal users*

***Option B: Claude Code (Recommended for Advanced Users)***

* *Command-line interface*  
* *Faster once you learn the commands*  
* *More flexible and scriptable*  
* *Best for: Students comfortable with terminal, planning to automate workflows*

*You'll install your chosen tool in Module 3 when we set up the repository.*

### ***Pro Path Cost Analysis***

*Let's be transparent about costs:*

***One-Time Setup:***

* *GitHub account: Free*  
* *Claude API account: Free*  
* *Initial API credits: $20 (lasts 2-3 months for this course)*

***Monthly Recurring:***

* *Codespaces: $0-10/month (60 free hours, then $0.18/hour)*  
* *Claude API usage: $5-15/month (moderate usage, pay-as-you-go)*  
* *Roo Code: Free*  
* *Claude Code: Free*

***Total first month:** \~$25-35*  
 ***Total months 2+:** \~$5-25/month depending on usage*

***Is it worth it?***

*If you plan to take Agentics 201 and 301, or if you're building agents professionally, yes. The time savings compound quickly. If you're just exploring or on a tight budget, stick with the Standard Path—you'll learn the same concepts.*

### ***When to Upgrade***

*You should upgrade to Pro Path when:*

* *You complete Module 6 and want to build more complex projects*  
* *You find yourself frustrated by manual copy-paste in Module 4*  
* *You're planning a career in agentic engineering*  
* *You have budget for professional development tools*

*You should NOT upgrade to Pro Path if:*

* *This is your first programming course*  
* *You're still learning what agents are (finish Module 1-2 first)*  
* *Budget is tight (Standard Path is equally valid)*  
* *You haven't finished the course yet (don't optimize prematurely)*

***Bottom line:** 95% of students should start with Standard Path and upgrade later if they want to.*

---

## ***⚡ Quick Win: Make It Official***

*You are set up. Now, commit to the journey by joining the community.*

1. *Go to the **Community Chat** (Discord/Slack)*  
2. *Find the `#agentics-101-cohort` channel*  
3. *Post this exact message:*

***"Ready to build\! 🚀 \#Agentics101"***

***Why this matters:** Public commitment increases completion rates by 40%. When you tell others you're doing something, you're more likely to follow through. Plus, your cohort-mates will be your support system when you hit challenges in Module 4\.*

---

## ***Module 0 Complete\! 🎊***

### ***Quick Check***

```
Module 0 ■■■■■■■ COMPLETE!
Status: Pre-Flight Check Passed ✓
Tools: Ready ✓
Mindset: Supervisor ✓
Path: Standard [or Pro]
```

### ***You Just Accomplished***

* *Created professional accounts on GitHub and Claude*  
* *Verified your development environment works*  
* *Chose your learning path (Standard or Pro)*  
* *Joined a community of agentic engineers*  
* *Established the "Supervisor" mindset*

### ***Your Badge***

```
🚀 PRE-FLIGHT READY
Module 0 Graduate
"Cleared for takeoff"
```

### ***What's Next?***

*In **Module 1: Meet Your First Agent**, we stop talking about tools and start talking about **Food**.*

*You'll learn why "chatting" with AI is like cooking without a recipe (chaotic, unpredictable, often disappointing). Then you'll learn why agents with specifications are like chefs following your grandmother's precise lasagna recipe (consistent, reliable, exactly what you wanted).*

*By the end of Module 1, you'll write your first Micro-Spec—a simple, 10-line instruction set that any AI agent can follow to build something real.*

***Time to Module 1:** 45 minutes*  
 ***What to bring:** Your curiosity and a project idea (even if it's just "I want a personal website")*

*Let's go. 🚀*

---

## ***Troubleshooting***

***"GitHub won't let me sign up"***

* *Try a different email address*  
* *Use an incognito/private browser window*  
* *Clear your cookies and try again*

***"Claude says I'm on a waitlist"***

* *Use ChatGPT 4.0 as an alternative*  
* *Check back in 24-48 hours (waitlists move quickly)*  
* *Join the community chat—someone may have an invite code*

***"I'm still not sure if I should choose Standard or Pro Path"***

* *If you're asking this question, choose Standard Path*  
* *You can always upgrade later*  
* *The course is designed for Standard Path first*

***"I don't understand the 'Brain/Hard Drive' analogy"***

* *Brain (Claude) \= Where thinking happens, not permanent*  
* *Hard Drive (GitHub) \= Where files are stored permanently*  
* *Your job \= Move good ideas from Brain to Hard Drive*

***"Can I use a different AI instead of Claude?"***

* *Yes\! ChatGPT 4.0, Gemini, or any advanced LLM works*  
* *Some commands may need adjustment but concepts are the same*  
* *Claude is recommended because it follows specs very precisely*

---

***Course Creators:** Bradley Ross, Nicholas Ruest, The Agentics Foundation*  
 ***Version:** 2.0 | **Last Updated:** 2024*  
 ***License:** Educational Use | MIT* 

***GitHub:** https://github.com/bar181/agentics-101-course*

