# Three-Axis Vulnerability Diagnostic

## Product
<!-- Name the product you're diagnosing. Real product at your company — not a hypothetical. -->

**Product:** Sales CRM
**Your Role:** Product Lead

---

## Scores

### Contextual Moat — 3/5
*Workflow depth × switching cost. Would users leave in a weekend if a competitor showed up?*

**Score rationale:**
Our AI assistant reads directly from the Sales CRM objects (deals, client data, financial data). These objects are highly interconnected. 
The assistant retains the conversation for context continuity.
The prompts outcome depends on the security rules and users permissions on the objects and the fields, as defined in the system.
The assistant is accessible within the CRM UI as well as Teams.

For now, the assistant does not have access to live data stream (emails, calls..) for automatic enrichment. It does not write back in the system or performs actions. It is not accessible from Outlook. It does not learn preferred workflows and it is not contextually retrained based on proprietary conversations.

**Named attacker (from partner challenge):**
Spiich as its assistant knows permissible CRUD actions and schema meanings which is the most critical element in the AI assistant selection process for a Sales CRM system.

---

### Data Advantage — 4/5
*Proprietary signal that compounds with usage. What do you see that OpenAI doesn't?*

**Score rationale:**
Sales CRM has all clients and prospects data, all revenue outcome data (deals outcome, cycle length, financial and services proposal, etc.), commercial and interactions data as well as sales users activity (meetings, demos, comments, updates...).

**Named attacker (from partner challenge):**

---

### Platform Exposure — 4/5
*Encroachment risk × pivot speed. If Apple/Google/OpenAI ships your hero feature native — then what?*

**Score rationale:**
Sales CRM owns valuable commercial data (deals, history, activity, workflow, client...). The AI assistant changes the way Sales work, increases efficiency, helps analyzing trends, identifies risks and delays, proposes best next actions.

For now, it is a chatbot only and does not perform actions. Some of the objects have very complex data model which makes interactions with the data not always relevant. 

**Named attacker (from partner challenge):**

---

## Killer Memo

> You run AI at **[OpenAI / Google / Apple]**. Your OKR: make this product irrelevant.
>
> **3-sentence memo:**
>
> 1. Attack: 
> 2. Wedge:
> 3. Why users switch:

---

## Top Vulnerability
<!-- One line: what's the single biggest strategic risk? -->

## Confidence Level
<!-- H / M / L — how confident are you in this bet after the diagnostic? -->
M
