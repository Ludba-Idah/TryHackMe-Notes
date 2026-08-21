# Room: SOC L1 Alert Triage
**Category:** Fundamentals

## Overview
This room makes us learn more about SOC alerts and build a systematic approach to efficiently triaging them.

## Key Takeaways

**Events vs Alerts**
* **Events:** Everything that happens. Every time someone walks through the door or badges in. Most of this is normal daily activity.
* **Alerts:** When someone tries to pick a lock or climb a window. It is a specific event that forces the security guard to go check it out.

**Alert Properties**
* **Time:** Exactly when did it happen?
* **Name:** What triggered it?
* **Severity:** How dangerous is it?
* **Status:** Is it New, being worked on (In Progress), or Done (Closed)?
* **Assignee:** Which analyst is currently fixing it?
* **Verdict:** Was it a real threat (**True Positive**) or a mistake/false alarm (**False Positive**)?

**Triage Plan**
When an alert pops up, follow this specific order of operations:
1. **Pick:** Grab the most dangerous or oldest alert first.
2. **Claim:** Change the status to "In Progress" and put your name on it so teammates don't do double work.
3. **Investigate:** Dig into the details. Look up usernames, IP addresses, and file names. Check the company's rulebook (Playbook) on what to do.
4. **Decide:** Figure out if this is a real hack (True Positive) or just a normal employee doing normal work (False Positive).
5. **Close/Escalate:** Write notes on what you found. Close the ticket if it's safe, or pass it to senior teams (Tier 2) if it is a massive emergency.
