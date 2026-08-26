# Exercise 2: The end-to-end flow

> **Objective:** Put everything together! Watch the L1 Service Desk AI Specialist work a real queue of incidents — some it resolves entirely on its own inside ServiceNow, and one it correctly declines to force a fit on and escalates instead.
>
> ⏱️ **Total time:** \~25 minutes

This exercise is split into three parts, all of which are the primary, reliable proof of Zero Touch Support — the AI Specialist resolving and triaging real incidents entirely within ServiceNow, no additional infrastructure required.

> **If nothing happens after you assign an incident below** — no work notes, no activity, total silence — don't re-configure anything. This is almost always the known trigger-activation gap called out at the end of Exercise 1: ask your instructor to complete the privileged-account activation step, then reassign the incident.

***

### Step 1 — Impersonate Ravi Kapoor

1. From the icon on top right, pull down and choose impersonate
2. Choose **Ravi Kapoor**
3. Select **Impersonate user** to confirm.

***

## Part A — Primary Autonomous Action: Monitor Request

This is the most reliable, fully-reproduced proof point in this lab: a low-priority request the AI Specialist matches to a real catalog item and resolves end-to-end, with no human involved.

### Step 2 — Assign the Monitor request incident

1. As Ravi, on the Service Operations Workspace, \*you may have to REFRESH the browser after impersonating to get the widgets to show
2. Select Incidents assigned to you widget shows all the incidents assigned to Ravi
3. Select INC0010002 from the list and open it. It will open in another tab
4. On the right side of the incident, select the 'Reassign card' ![](<../../.gitbook/assets/2026-08-26 11.16.11.png>)
5. Geneartive AI Skill summarize incident automatically summarizes all the history of the incidents, this is a default setting on these labs.
6. In the Reassign field, type in whatever you have named your L1 Service Desk Specialist -hit **Save**![](<../../.gitbook/assets/2026-08-26 11.17.31.png>)

### Step 3 — Watch the AI Specialist resolve it

1. On the right sidebar, open **Agentic Processes** and select **Show steps**.![](<../../.gitbook/assets/2026-08-26 11.19.08.png>)
2.  Watch the AI Specialist identify your device (e.g., an Apple iMac 27"), match it against the service catalog, and recommend a specific monitor model.

    > **Be patient:** this takes about 5-8 minutes.
3. In the **Activity** feed, review the resolution notes — you should see a specific catalog item recommendation (e.g., a "Standard 27" Monitor") with clear next steps for the caller.
4. Now go through the rest of Ravi's queue

You can continue through any remaining incidents assigned to Ravi and reassign them to your L1 Specialist the same way. Expect a  mix of outcomes to what you just saw in Parts A–C: most resolve autonomously, some correctly escalate. That's Zero Touch Support working as designed — autonomous where it can be confident, and handing off cleanly where it can't. Some will be REASSIGNED back to the IT Support group.

#### Final Checkpoint

You have successfully:

* Watched the AI Specialist **autonomously resolve** a real incident
* Watched the AI Specialist **correctly escalate** an incident it couldn't confidently match&#x20;



**You've just experienced Zero Touch Support — autonomous resolution where the platform can be confident, and a clean handoff where it can't.** 🎉
