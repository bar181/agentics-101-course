# ***Module 2: From Chaos to Control 🎯***

***Time:** 60 minutes*  
 ***Deliverable:** Enhanced Spec \+ Working HTML file*  
 ***Confidence Level:** ⭐⭐⭐⭐ (Beginner Friendly)*

---

## ***Module Overview***

*Ready for some fun? You are about to do what everyone does wrong with AI—on purpose.*

*First, you are going to try **"Vibe Coding."** That's when you type vague requests like "Make it pop\!" and hope for the best. Spoiler: It's going to be a beautiful disaster. You will watch the AI change its mind every time you regenerate, creating a different mess with each attempt.*

*This isn't masochism—it's pedagogy. By experiencing the frustration firsthand, you'll understand at a visceral level why specifications matter. When Sarah tried vibe coding, she said it felt like "arguing with a very polite person who never quite understood what I wanted." That feeling will stay with you.*

*Then comes the transformation. You will take your 10-line spec from Module 1 and **enhance** it. You'll add specific colors (hex codes, not "blue"), precise sizes (pixels, not "medium"), and exact rules (behavior, not "nice"). Every vague word you replace removes one decision the AI has to guess.*

*Finally, the magic moment: Your spec becomes real, working code. Not a mockup. Not a template. Your actual project, built by AI, following your exact instructions. First try. No iteration. No frustration.*

***Sarah's Experience:***

*Sarah spent an hour in vibe coding hell. She got five different button designs, none of which matched what she imagined. She felt stupid, like everyone else "got" AI except her. Then she used the Enhanced Spec method. In 30 seconds, she had a working website that looked exactly like her mental picture. She said, "I felt like I went from begging the AI to commanding it. The shift from hope to control was instant."*

***That shift happens today.***

### ***Your Learning Path***

*✅ Experience the chaos of Vibe Coding (controlled failure)*  
 *✅ Enhance your Spec with precise details*  
 *✅ Generate your first working code*  
 *✅ Save everything for Module 3*

---

## ***Lesson 2.1: The Fun and Chaos of Vibe Coding***

***Time:** 15 minutes*  
 ***Outcome:** Experience why everyone struggles with AI (and why you won't anymore)*

### ***Lesson Overview***

*Time to break things on purpose\! You are going to try what 90% of people do with AI—type vague requests and watch the chaos unfold. This is the "before" picture. You'll reference this moment every time you're tempted to skip writing a proper spec.*

*Professional engineers call this "controlled failure"—intentionally experiencing a problem so you remember to avoid it. Like touching a hot stove once as a kid. You remember. Forever.*

*By experiencing the frustration firsthand, you will appreciate why specs matter so much. More importantly, when you encounter this behavior in the wild (colleagues, clients, teammates), you'll immediately recognize the problem and know how to fix it.*

### ***Let's Create Some Chaos***

*Open **Claude.ai** (or ChatGPT, or your preferred AI) right now. Start a fresh conversation. We are going to watch AI misunderstand you three times in a row.*

***Round 1: The Innocent Request***

*Type exactly this: "Make me a button."*

***What you get:***

* *A button appears. It exists.*  
* *But what color? Claude guessed. (Probably blue or gray)*  
* *What size? Claude guessed. (Probably medium)*  
* *What text? Claude guessed. (Probably "Button" or "Submit")*  
* *What happens when you click? Claude didn't even consider it.*

*The button isn't wrong. It's just not yours. It's Claude's interpretation of "generic button based on millions of examples."*

***Round 2: The Death Spiral Begins***

*Now type: "Make it better."*

***Watch what happens:***

* *Claude has no idea what "better" means*  
* *Does it add a gradient? Make it bigger? Change the color?*  
* *It picks something random from its training data*  
* *The button transforms into something completely different*  
* *You didn't ask for a redesign—you asked for improvement*  
* *But without knowing what "better" means to you, Claude guesses*

***Round 3: Peak Chaos***

*Now type: "You know what I mean, just make it nice."*

***Maximum confusion achieved:***

* *"Nice" is even more subjective than "better"*  
* *Claude redesigns the entire thing based on its statistical model of "nice"*  
* *Maybe it adds shadows, animations, icons*  
* *Maybe it strips everything down to minimalism*  
* *You have no idea what you'll get until you see it*  
* *And if you regenerate the response, you'll get something completely different*

### ***The Death Spiral (Keep Going If You Dare)***

*Continue the conversation:*

***You:** "Not like that."*  
 ***AI:** Changes everything again, different direction*

***You:** "No, go back to the blue one\!"*  
 ***AI:** Makes a different blue button than before*

***You:** "That's not the right blue\!"*  
 ***AI:** Tries a third shade of blue*

***You:** "FORGET IT."*  
 ***AI:** "I apologize for the confusion. Would you like to start over?"*

***Sound familiar?** This is the "AI is frustrating" experience everyone complains about. But here's the secret: **It's not the AI's fault. It's the instructions.***

### ***Why This Happens (The Technical Truth)***

*Every message is a fresh start for the AI's decision-making process. Yes, it has conversation history. But it can't read your mind about subjective terms. When you say "better," it has these options:*

* *Better contrast? Better size? Better animation?*  
* *Better for accessibility? Better for mobile? Better for print?*  
* *Better compared to what? Better for whom?*

*The AI picks from millions of examples of "better" in its training data. It's like telling a builder to "build a nice house" without giving them blueprints. The builder isn't incompetent—they just don't know if you want Victorian, modern, or rustic. What you get is what they consider "nice."*

***The problem isn't the AI. It's the ambiguity.***

### ***Your Chaos Trophy***

*Take a screenshot of your worst result from this exercise. Save it somewhere you can find it. In 30 minutes, you'll generate exactly what you wanted—first try. Put the screenshots side by side. The difference will shock you.*

*This isn't about shaming vibe coding. It's about building muscle memory for why precision matters. Every vague word in your spec is a lottery ticket for the AI to guess. And the AI's guess is rarely what you imagined.*

***Sarah's Chaos Trophy:** She got a button with a gradient, drop shadow, bouncing animation, and Comic Sans font. She said, "It looked like a 1997 website had a baby with a Vegas casino." She kept that screenshot on her desktop as a reminder to always write specs.*

---

## ***Lesson 2.2: Structure Wins \- Enhancing Your Spec***

***Time:** 20 minutes*  
 ***Outcome:** Transform your micro-spec into precise agent instructions*

### ***Lesson Overview***

*Your 10-line spec from Module 1 was the skeleton. Now we add the muscle, skin, and nervous system. You will expand each section with numbers, hex codes, and specific behaviors. Every detail you add removes one decision the AI has to guess.*

*This isn't about making the spec longer. It's about making it more precise. A 20-line spec with exact measurements is better than a 200-line spec full of "nice," "modern," and "professional." Quality over quantity.*

### ***From Sketch to Blueprint***

*Let's look at the transformation side by side.*

***The Old Spec (Vague) \- Module 1 Version:***

```
STYLE: Dark, professional theme
LAYOUT: Clean and simple
BUTTON: Make it stand out
```

***The New Spec (Specific) \- Module 2 Version:***

```
STYLING:
- Background: #1a1a1a (Charcoal)
- Text: #ffffff (White) for maximum contrast
- Accent color: #3b82f6 (Bright Blue)
- Font: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif
- Base font size: 16px
- Line height: 1.6 for readability

LAYOUT:
- Max width: 600px
- Centered horizontally with auto margins
- Padding: 40px on all sides (20px on mobile)
- Sections stacked vertically with 32px gaps

BUTTON:
- Background: #3b82f6 (Bright Blue)
- Text: #ffffff (White), 18px, bold
- Padding: 16px 32px
- Border radius: 8px (rounded corners)
- On hover: Background darkens to #2563eb
- On click: Scales down to 0.95 for feedback
- Cursor changes to pointer
```

***The Key Differences:***

| *Vague* | *Specific* | *Why It Matters* |
| ----- | ----- | ----- |
| *"Dark"* | *`#1a1a1a`* | *There are 50 shades of dark. This is THE dark.* |
| *"Professional"* | *`-apple-system` font stack* | *"Professional" could mean Times New Roman or Comic Sans. System fonts are universally professional.* |
| *"Make it stand out"* | *Specific hover and click animations* | *"Stand out" could mean bigger, brighter, or animated. We defined all three states.* |
| *"Clean and simple"* | *Max width 600px, 32px gaps* | *Numbers make "clean" measurable and reproducible.* |

### ***The Enhancement Formula***

*For every vague term in your Module 1 spec, apply this formula:*

***Colors → Hex Codes***

* *❌ "Blue" → ✅ "\#3b82f6"*  
* *❌ "Dark gray" → ✅ "\#1a1a1a"*  
* *Use [coolors.co](https://coolors.co/) or [color.adobe.com](https://color.adobe.com/) to find exact codes*

***Spacing → Pixels or Percentages***

* *❌ "Some space" → ✅ "32px margin"*  
* *❌ "Not too big" → ✅ "600px max width"*  
* *Use multiples of 8 (8, 16, 24, 32, 40\) for visual consistency*

***Layout → Alignment \+ Positioning***

* *❌ "Centered" → ✅ "Centered horizontally with auto margins, max-width 600px"*  
* *❌ "Side by side" → ✅ "Flexbox row, 24px gap, wrap on mobile"*

***Behavior → State Definitions***

* *❌ "Interactive" → ✅ "On hover: background darkens, cursor changes to pointer"*  
* *❌ "Responsive" → ✅ "Stack vertically below 768px, hide navigation at 640px"*

***Typography → Complete Specifications***

* *❌ "Nice font" → ✅ "System font stack, 16px base, 1.6 line height"*  
* *❌ "Big heading" → ✅ "32px, bold weight (700), 1.2 line height"*

### ***Your Turn: Enhancement Exercise***

*Open your spec from Module 1\. Let's enhance it together using the formula.*

***Step 1: Choose Your Color Palette (5 minutes)***

*Pick three colors:*

1. ***Background color** (usually dark or light)*  
2. ***Text color** (high contrast with background)*  
3. ***Accent color** (for buttons, links, highlights)*

***Quick picks if you're stuck:***

* ***Light theme:** Background \#ffffff, Text \#1a1a1a, Accent \#3b82f6*  
* ***Dark theme:** Background \#1a1a1a, Text \#ffffff, Accent \#10b981*

***Pro tip:** Use a 60-30-10 rule (60% background, 30% text, 10% accent).*

***Step 2: Add Measurements (5 minutes)***

*For each component in your spec, add:*

* *Width (if applicable): "400px" or "100% max-width 600px"*  
* *Height (if applicable): "auto" or "64px"*  
* *Padding/Margin: "16px" or "24px 40px" (vertical horizontal)*  
* *Font size: "16px" (body), "24px" (headings), "14px" (small text)*

***Step 3: Define Behaviors (5 minutes)***

*For interactive elements (buttons, links, forms):*

* ***Hover state:** What changes when mouse hovers?*  
* ***Active state:** What changes when clicked?*  
* ***Focus state:** What changes when keyboard-navigated?*

***Step 4: Add Responsive Rules (5 minutes)***

*Define what changes on mobile (screens under 768px):*

* *Do columns stack vertically?*  
* *Do font sizes scale down?*  
* *Does navigation collapse?*

***Example Enhancement:***

*Sarah's Module 1 spec said:*

```
MAIN PARTS:
- Headline
- Bio paragraph
- Contact button
```

*Sarah's enhanced Module 2 spec says:*

```
MAIN PARTS:

1. HEADLINE
   - Text: "Hi, I'm Sarah - Marketing Strategist"
   - Font size: 32px (24px on mobile)
   - Font weight: 700 (bold)
   - Color: #1a1a1a
   - Margin bottom: 16px

2. BIO PARAGRAPH
   - Max width: 500px
   - Font size: 16px
   - Line height: 1.6
   - Color: #4a5568 (Medium gray for softer reading)
   - Margin bottom: 32px

3. CONTACT BUTTON
   - Text: "Book a Free Consultation"
   - Background: #3b82f6 (Bright blue)
   - Text color: #ffffff
   - Font size: 18px, bold
   - Padding: 16px 32px
   - Border radius: 8px
   - Hover: Background #2563eb, slight scale up (1.05)
   - Click: Opens mailto:sarah@example.com
```

***See the difference?** Same three parts. But now any AI agent can build this exactly as Sarah imagined. No guessing. No randomness.*

### ***Common Enhancement Mistakes***

***Mistake 1: Too Much Detail** ❌ "Button should be exactly 147px wide with a 3.7px border radius" ✅ "Button should be \~150px wide with 4px border radius"*

*Round numbers are easier for AI to work with. Precision to the pixel usually doesn't matter.*

***Mistake 2: Still Using Subjective Terms** ❌ "Make the heading bold-ish and kinda big" ✅ "Heading font weight 600, size 28px"*

*If it ends in "-ish" or "kinda," it needs more precision.*

***Mistake 3: Forgetting Mobile** ❌ Only specifies desktop sizes ✅ Includes "On mobile (\<768px): font size 20px, padding 12px"*

*Mobile-first is standard practice. Always define mobile behavior.*

***Mistake 4: No Interactive States** ❌ "Blue button" ✅ "Blue button, darker on hover, slightly scale on click"*

*Interactive elements need at least three states: default, hover, active.*

---

## ***Lesson 2.3: Generate Your First Code Artifact***

***Time:** 15 minutes*  
 ***Outcome:** Watch your spec become real, working code*

### ***Lesson Overview***

*This is the moment everything changes. You will feed your enhanced spec to Claude and watch it generate complete, working code. Not pseudocode. Not fragments. Not "TODO: implement this part." A complete HTML file with embedded CSS that you can open in any browser and use immediately.*

*This is your first real agentic engineering moment. You wrote the plan. The agent writes the code. Just like we promised in Module 0\.*

### ***The Magic Prompt***

*Open **Claude.ai** in a fresh conversation. You're starting clean to avoid any residual confusion from the vibe coding exercise.*

*Copy this exact prompt, then paste your enhanced spec below it:*

```
You are a senior frontend developer. Create a complete, production-ready HTML file with embedded CSS based on the specification below.

[PASTE YOUR ENHANCED SPEC HERE]

Technical Requirements:
- Single HTML file (no external dependencies)
- CSS in <style> tags within <head>
- Semantic HTML5 (proper heading hierarchy, nav, main, footer)
- Mobile responsive (breakpoint at 768px)
- Accessibility features (ARIA labels, sufficient contrast)
- Clean, commented code
- Modern CSS (flexbox/grid for layout)

Output only the complete HTML code, ready to save and use.
```

***Why This Prompt Works:***

* ***"Senior frontend developer"** → Sets the expertise level*  
* ***"Complete, production-ready"** → No placeholders or TODOs*  
* ***"Based on specification below"** → Forces Claude to read your spec*  
* ***Technical Requirements list** → Removes ambiguity about standards*  
* ***"Output only the complete HTML"** → Prevents Claude from explaining, just generates*

### ***What Happens Next***

*Claude will:*

1. ***READ** your spec (you'll see it reference specific details)*  
2. ***PLAN** its approach (it may outline the structure first)*  
3. ***ACT** by generating the complete HTML and CSS*  
4. ***CHECK** against your requirements (it may note any assumptions)*

*The entire process takes 3-10 seconds. You'll get 100-300 lines of code depending on your project complexity.*

***Sarah's Result:***

*Sarah got 127 lines of perfect code in 3 seconds. Every color matched. Every spacing was exact. The hover states worked. The mobile layout stacked correctly. She said, "I stared at the screen for a full minute. A month ago, this would have taken me three days and looked worse."*

### ***Quality Check \- The Verification Ritual***

*Before you celebrate, verify the output. Copy all the code Claude generated. Open a text editor (Notepad on Windows, TextEdit on Mac). Paste the code. Save it as `index.html`.*

*Double-click the file to open it in your browser.*

***Now check these five things:***

1. ***Visual Verification:***

   * *\[ \] Do the colors match your hex codes?*  
   * *\[ \] Are the spacing measurements correct?*  
   * *\[ \] Does the font look right?*  
2. ***Component Verification:***

   * *\[ \] Are all parts from your spec present?*  
   * *\[ \] Is anything missing?*  
   * *\[ \] Is anything extra that you didn't ask for?*  
3. ***Interactive Verification:***

   * *\[ \] Do buttons hover correctly?*  
   * *\[ \] Do links work?*  
   * *\[ \] Do animations trigger?*  
4. ***Responsive Verification:***

   * *\[ \] Resize your browser window to mobile size*  
   * *\[ \] Does the layout adapt correctly?*  
   * *\[ \] Is text still readable?*  
5. ***Code Quality Verification:***

   * *\[ \] Open the HTML in your text editor*  
   * *\[ \] Is the code indented and readable?*  
   * *\[ \] Are there helpful comments?*

***If everything checks out: Congratulations\! You just did agentic engineering.***

***If something is wrong, here's how to fix it:***

### ***The Directive Feedback Method***

*If the output doesn't match your spec, don't say "fix it" or "that's wrong." Be directive. Specify exactly what needs to change.*

***Bad Feedback (Vague):***

* *❌ "The button looks wrong"*  
* *❌ "Fix the colors"*  
* *❌ "Make it better"*

***Good Feedback (Directive):***

* *✅ "Change button background from \#3b82f6 to \#2563eb"*  
* *✅ "Increase heading font size from 28px to 32px"*  
* *✅ "Add 16px margin below the bio paragraph"*

***How to give directive feedback:***

*In the same conversation with Claude, type:*

```
The output is close but needs these exact changes:

1. [Specific change with numbers]
2. [Specific change with numbers]
3. [Specific change with numbers]

Please update the code with only these changes.
```

*Claude will regenerate the code with your corrections. Copy the new version, save it, and verify again.*

***Sarah's Correction:***

*Sarah's button was too small. She didn't say "make the button bigger." She said: "Change button padding from 12px 24px to 16px 32px." Claude made the exact change. Done.*

---

## ***Lesson 2.4: Save Your Code & Document Success***

***Time:** 10 minutes*  
 ***Outcome:** Capture everything for your agent project*

### ***Lesson Overview***

*You have working code\! Now we save everything properly for Module 3\. This isn't just file management—you're creating the "seed files" for your agent's workspace. These files become the foundation that your agent reads from and writes to throughout Modules 3-5.*

*Think of this like setting up a new kitchen before a chef arrives. Everything has its place. The recipes (specs) are in one drawer. The ingredients (code) are in another. When the chef (agent) arrives in Module 4, they know exactly where everything is.*

### ***Lock In Your Success***

***Step 1: Create Your Project Folder***

*On your computer, create a new folder with this exact name:*

```
agentics-101-project
```

***Why this name?** Consistency. When you get to Module 3, everyone's project will have the same structure, making troubleshooting easier.*

***Where to put it?***

* ***Windows:** Desktop or Documents folder*  
* ***Mac:** Desktop or Documents folder*  
* ***Important:** Not in Downloads (things get lost there)*

***Step 2: Save Your Two Core Files***

*Inside `agentics-101-project`, save these two files:*

***File 1: Your Enhanced Spec***

* *Open your text editor*  
* *Copy your enhanced spec (all the detailed content from Lesson 2.2)*  
* *Paste it into a new file*  
* *Save as: `spec.md`*  
* ***Why .md?** Markdown format is the standard for specs and documentation*

***File 2: Your Generated Code***

* *Copy ALL the HTML code Claude generated (from `<!DOCTYPE html>` to `</html>`)*  
* *Paste it into a new file*  
* *Save as: `index.html`*  
* ***Why index.html?** This is the standard filename for website homepages*

***Your folder should now look like this:***

```
agentics-101-project/
├── spec.md
└── index.html
```

### ***Test Everything Before Moving On***

***Test 1: Does the HTML work?***

* *Navigate to your `agentics-101-project` folder*  
* *Double-click `index.html`*  
* *It should open in your default browser*  
* *Does it look correct?*  
* *Do interactive elements work?*

***Test 2: Can you edit the spec?***

* *Double-click `spec.md`*  
* *It should open in a text editor*  
* *Can you read it?*  
* *Can you make a small edit and save?*

***Test 3: Backup verification***

* *Email both files to yourself*  
* *Or save them to cloud storage (Google Drive, Dropbox)*  
* ***Critical:** Don't lose these files before Module 3*

### ***Why This Matters (The Big Picture)***

*In Module 3, we will upload these files to GitHub. In Module 4, your agent will:*

* ***READ** `spec.md` to understand what to build*  
* ***WRITE** updates to `index.html` based on your instructions*  
* ***MAINTAIN** version history so you can undo mistakes*

*You've just built the foundation. These two files are the seed from which your entire agent system grows.*

### ***Victory Moment (Reflect on the Journey)***

***Look at what you accomplished:***

* ***30 minutes ago:** You were in vibe coding hell, getting random results*  
* ***20 minutes ago:** You enhanced your spec with precise details*  
* ***10 minutes ago:** You generated perfect code on the first try*  
* ***Right now:** You have a working website saved on your computer*

*You learned the difference between hoping AI understands (Vibe Coding) and ensuring it understands (Specifications). This skill separates frustrated users from confident builders. This skill is worth tens of thousands of dollars in the job market.*

***Sarah's reflection:***

*"I finally understood what 'AI Engineering' meant. It's not about knowing how AI works internally. It's about knowing how to direct it precisely. I'm not a programmer. I'm a conductor, and the AI is my orchestra."*

---

## ***Module 2 Complete\! 🎊***

### ***Quick Check***

```
Module 2 ■■■■■■■ COMPLETE!
Status: Chaos Controlled ✓
Files: spec.md & index.html saved ✓
Skills: Specification Enhancement ✓
Confidence: High ✓
```

### ***You Just Accomplished***

* *Experienced why Vibe Coding fails (through controlled failure)*  
* *Enhanced a micro-spec with hex codes, pixels, and exact behaviors*  
* *Generated working code on the first try using the Magic Prompt*  
* *Saved your project files locally in proper structure*  
* *Understood the difference between hope and control*  
* *Developed the "Directive Feedback" skill for corrections*

### ***Your Badge***

```
🎯 CHAOS CONTROLLER
Module 2 Graduate
"I direct AI with precision, not hope"
```

### ***What's Next?***

*In **Module 3: Your Sandbox**, we move to the cloud. You will create a **GitHub Repository** (your agent's permanent home) and upload your files so the agent can access them safely. GitHub is where professional developers store all their code, and it's where your agent will live.*

*You'll learn why we separate specs (input) from code (output), how to commit changes like a pro, and how to verify your agent's workspace is ready for Module 4's build session.*

***Time to Module 3:** 45 minutes*  
 ***What to bring:** Your `agentics-101-project` folder with both files*

*Take a 10-minute break. You earned it. Your brain just learned a new way of thinking. 🎯*

---

## ***Quick Reference Card***

***The Enhancement Formula***

```
Vague → Specific
"Blue" → "#3b82f6"
"Big" → "32px"
"Nice" → Defined behaviors
```

***The Magic Prompt Structure***

```
[Role definition]
[Output format]
[Your spec]
[Technical requirements]
[Output instruction]
```

***File Structure***

```
agentics-101-project/
├── spec.md          (Input - What to build)
└── index.html       (Output - What was built)
```

***Quality Check Checklist***

```
✓ Colors match hex codes
✓ All components present
✓ Interactive states work
✓ Responsive on mobile
✓ Code is clean and commented
```

---

## ***Troubleshooting***

***"My generated code doesn't match the spec"***

* *Re-read your enhanced spec \- was it specific enough?*  
* *Use directive feedback to correct specific issues*  
* *Don't regenerate from scratch \- iterate on the existing code*

***"The HTML file won't open in my browser"***

* *Make sure you saved it as `.html` not `.txt`*  
* *Right-click the file → Open With → Chrome/Firefox/Safari*  
* *Check that you copied the entire code block from Claude*

***"I'm not sure if my spec is enhanced enough"***

* *Every color should be a hex code*  
* *Every size should be a number with units*  
* *Every behavior should describe what happens when*  
* *If you're still using "nice" or "modern," enhance more*

***"Claude generated too much code / too little code"***

* *Too much: Your spec was too complex, simplify for Module 2*  
* *Too little: Your spec was too minimal, add more components*  
* *Just right: 100-300 lines of HTML+CSS*

***"What if I want to change my project idea?"***

* *You can, but you'll lose momentum*  
* *Better to finish this simple project and build something complex in Module 6*  
* *Simple completion beats complex abandonment*

***"Can I use this for my real website?"***

* *Absolutely\! This is production-ready code*  
* *You'll deploy it for real in Module 5*  
* *Many students use their Module 2 project as their actual portfolio*

---

## ***Pro Tips***

***Color Palette Tools:***

* [*coolors.co*](https://coolors.co/) *\- Generate complete palettes*  
* [*color.adobe.com*](https://color.adobe.com/) *\- Adobe's color tool*  
* [*contrast-ratio.com*](https://contrast-ratio.com/) *\- Check accessibility*

***Hex Code Quick Reference:***

* *Black: \#000000*  
* *White: \#ffffff*  
* *Blue: \#3b82f6*  
* *Green: \#10b981*  
* *Red: \#ef4444*  
* *Gray: \#6b7280*

***Standard Spacing (Multiples of 8):***

* *Tiny: 8px*  
* *Small: 16px*  
* *Medium: 24px*  
* *Large: 32px*  
* *Extra Large: 48px*

---

***Course Creators:** Bradley Ross, Nicholas Ruest, The Agentics Foundation*  
 ***Version:** 2.0 | **Module:** 2 of 6*  
 ***Next Module:** Your Sandbox (45 minutes)*
