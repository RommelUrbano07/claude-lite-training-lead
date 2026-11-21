# Quick-Start Guide: Your Personal AI Training & Enablement Swarm (Claude Lite Kit)

Welcome! This kit turns a **Claude Project** (on Claude.ai Web or the Claude Desktop App) into your personal **AI Training & Workflow Enablement Swarm**.

It comes pre-wired with **enterprise safety & quality guardrails** (automatic PII masking, secret/prompt-injection checks, step-by-step planning before big tasks, and an iteration log) while leaving your **roles, workflows, and daily deliverables 100% customizable** to how you actually work.

---

## 2-Minute Setup in Claude

### Step 1: Create a New Claude Project
1. Open **Claude** (Web or Desktop App) and click **Projects** -> **New Project**.
2. Name it something like: `Training & AI Enablement Hub`.

### Step 2: Paste the Master Router into "Project Instructions"
1. Open `01-PASTE-INTO-PROJECT-INSTRUCTIONS.md` from this folder.
2. Copy its entire contents and paste them into the **Set project instructions** box in your Claude Project.

### Step 3: Upload the 3 Modular Knowledge Files into "Project Knowledge"
Upload these three files from this folder into the **Project Knowledge** panel on the right side of your Claude Project:
1. `02-MY-SWARM-ROSTER-AND-COMMANDS.md` *(Your customizable roles, workflows & `/` commands)*
2. `03-CORE-GUARDRAILS-PII-AND-SECOPS.md` *(Locked-in PII masking, prompt safety & quality checks)*
3. `04-ITERATION-LOG-TEMPLATE.md` *(Your versioned log of deliverables and changes)*

---

## Two Ways to Customize Your Swarm to Your Exact Workflow

You don't need to know how to code or write complex prompts to tailor this to your job:

### Option A (Easiest): Let Claude Interview You via `/setup`
1. Start a new chat inside your Claude Project and type:
   ```text
   /setup
   ```
2. Claude will interview you **one question at a time** (with suggested answers) about:
   - What kinds of training materials you create most (slide outlines, hands-on labs, playbooks, cheat sheets, assessments).
   - How you help teams adopt AI in their workflows.
   - What other leadership, planning, or operational responsibilities you juggle.
3. At the end of the quick interview, Claude will generate a customized **`02-MY-SWARM-ROSTER-AND-COMMANDS.md` Artifact** for you.
4. Click **"Add to Project Knowledge"** on that Artifact (and remove the old blank one) — your custom swarm is now live!

### Option B: Fill in the Worksheet Directly
Open `02-MY-SWARM-ROSTER-AND-COMMANDS.md` in any text editor, fill in the `[FILL IN: ...]` sections at your own pace, and upload it to **Project Knowledge**.

---

## Your Built-In Slash Commands Cheat Sheet

Once inside your Claude Project, you can type normal messages or use any of these shortcuts:

| Command | When to Use It | What Happens |
| :--- | :--- | :--- |
| *(Normal casual chat)* | Quick questions, brainstorming, or quick rewrites | **Casual Fast-Path:** Claude answers directly with zero agent ceremony. |
| **`/setup`** | First time setup (or whenever your role evolves) | Interviews you 1-by-1 and generates your custom `02-MY-SWARM-ROSTER-AND-COMMANDS.md` file. |
| **`/grill-me <idea>`** | You have a rough training or AI-workflow idea | Interviews you 1 question at a time with `(Recommended)` options until every detail is crystal clear. |
| **`/plan <task>`** | Before drafting a major curriculum or rollout plan | Creates a structured **Implementation Plan Artifact** and waits for your approval before drafting. |
| **`/swarm <request>`** | Full end-to-end creation of a training module, lab, or AI workflow playbook | Runs the full pipeline: **1) `/grill-me` + `/plan` -> 2) Specialist Roles Draft -> 3) QA + PII/SecOps Safety Review -> 4) Version Log Entry**. |
| **`/qa-secops`** | Auditing a draft deck, prompt template, or team workflow | Runs the **Quality, PII-Masking & Prompt-Safety Reviewer** to catch unclear steps, unmasked personal data, or unsafe AI prompt loopholes. |
| **`/walkthrough [topic]`** | Anything feels confusing or like a "blackbox" | Activates your **Program Manager + AI Workflow Architect** to explain how the workflow or system works in clear, plain English with visual diagrams. |
| **`/log`** | Wrapping up a milestone or major edit | Generates the next numbered `ITER-XXXX` (`vX.Y.Z`) entry for `04-ITERATION-LOG-TEMPLATE.md`. |
