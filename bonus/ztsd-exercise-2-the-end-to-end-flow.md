# Exercise 2: The end-to-end flow

> **Objective:** Put everything together! Watch the L1 Service Desk AI Specialist work a real queue of incidents — some it resolves entirely on its own inside ServiceNow, and one it correctly declines to force a fit on and escalates instead.
>
> ⏱️ **Total time:** ~25 minutes

This exercise is split into three parts, all of them the primary, reliable proof of Zero Touch Support — the AI Specialist resolving and triaging real incidents entirely within ServiceNow, no additional infrastructure required.

***

### ❇️ Step 1 — Impersonate Ravi Kapoor

1. From the icon on top right, pull down and choose impersonate
2.  Choose **Ravi Kapoor**
3.  Select **Impersonate user** to confirm.

***

## Part A — Primary Autonomous Action: Monitor Request

This is the most reliable, fully-reproduced proof point in this lab: a low-priority request the AI Specialist matches to a real catalog item and resolves end-to-end, with no human involved.

### ❇️ Step 2 — Assign the Monitor request incident

1. As Ravi, on the Service Operations Workspace, select the **List** button on the far left, then under **Incidents** select **Assigned to you**. Find the incident by its short description — **"Request for additional monitor for remote work setup"** (the exact `INC00XXXXX` number varies per instance).
2. On the incident record, navigate to the **Details** tab, scroll to **Assignment**, and in **Assigned to** type `ai` and select your L1 Service Desk AI Specialist (e.g., **Athena Service Desk AI Specialist**).
3. An **Assign** dialog will appear with Now Assist-generated work notes summarizing the issue. Select the **Now Assist sparkle icon** if the summary hasn't populated yet.
4. Select **Save** to confirm the assignment.

### ❇️ Step 3 — Watch the AI Specialist resolve it

1. On the right sidebar, open **Agentic Processes** and select **Show steps**.
2. Watch the AI Specialist identify your device (e.g., an Apple iMac 27"), match it against the service catalog, and recommend a specific monitor model.

    > **Be patient:** this takes about 5-8 minutes.
3. In the **Activity** feed, review the resolution notes — you should see a specific catalog item recommendation (e.g., a "Standard 27\" Monitor") with clear next steps for the caller.
4. Confirm the incident **State** has moved to **Resolved** with a close code of **Solution provided**.

    > ✅ **This is the expected, proven outcome.** The AI Specialist identified the right catalog item and closed the loop with zero human involvement — the cleanest example of autonomous resolution in this lab.

***

## Part B — Escalation Contrast: Zoom License Request

Not every incident should be auto-resolved — an AI Specialist that forces a fit on every ticket is worse than one that knows when to hand off. This part shows the correct opposite behavior.

### ❇️ Step 4 — Assign the Zoom license incident

1. Find the incident **"Request for Zoom license upgrade to allow meeting recordings"** in Ravi's queue and assign it to your AI Specialist the same way as Step 2.

### ❇️ Step 5 — Watch it correctly escalate

1. Open **Agentic Processes** and **Show steps** as before.
2. This time, the AI Specialist's research will conclude that no existing catalog item explicitly supports "enabling Zoom meeting recordings" — the closest matches ("Request zoom webinar," a non-standard software request) don't actually cover the ask.
3. Review the **Activity** feed — the AI Specialist should reassign the incident to a human Support Engineer, with an explanation of what it checked and why it couldn't confidently resolve the request itself.

    > ✅ **This is also the expected, correct outcome.** The AI Specialist isn't failing here — it's demonstrating the escalation behavior you configured in Exercise 1 (**Escalate and reroute**). An honest "I don't have a good match" is a better outcome than a wrong resolution.

***

## Part C — Optional / Caveated: Password Reset

> ⚠️ **Known reliability caveat, read before running this one.** Semantically, this is the best-fit request in the whole lab — there's a real, matching knowledge article and a real, matching "Password Reset" catalog item, and the AI Specialist's research step reliably finds both with a very high confidence score. But the **next** step — fetching full catalog item details to build the resolution — has shown intermittent failures independent of this specific incident (the same failure has also been seen elsewhere in this lab's underlying tooling). Depending on the day, this incident may resolve cleanly via the catalog item, or it may fall back to generic guidance and escalate to a human even though the AI Specialist found the right resources. Either outcome is expected — this section exists to show you both, not to guarantee one.

### ❇️ Step 6 — Assign the Password Reset incident

1. Find the incident **"Need help resetting my Active Directory password"** in Ravi's queue and assign it to your AI Specialist.

### ❇️ Step 7 — Watch and interpret the result

1. Open **Agentic Processes** and **Show steps**.
2. Review the **Activity** feed. You should see the AI Specialist correctly cite a real knowledge article (e.g., "Resetting Your Active Directory (AD) Password") and the "Password Reset" catalog item.
3. From there, one of two things happens:
   * **Clean resolution:** the incident closes with a specific, catalog-grounded reset procedure. If you see this, great — it's the ideal outcome for this scenario.
   * **Escalation despite finding the right resources:** the AI Specialist falls back to generic guidance and reassigns to a human, even though it clearly identified the correct KB article and catalog item earlier in the same run.

    > This is a known, disclosed gap in this lab's current tooling reliability — not something you configured incorrectly, and not a reason to re-run the test repeatedly hoping for a different outcome (a resolved incident here won't reprocess if you reassign it again).

***

### Now go through the rest of Ravi's queue

You can continue through any remaining incidents assigned to Ravi and reassign them to your L1 Specialist the same way. Expect a similar mix of outcomes to what you just saw in Parts A–C: most resolve autonomously, some correctly escalate. That's Zero Touch Support working as designed — autonomous where it can be confident, and handing off cleanly where it can't.

#### ✅ Final Checkpoint

You have successfully:

* Watched the AI Specialist **autonomously resolve** a real incident end-to-end (Monitor request)
* Watched the AI Specialist **correctly escalate** an incident it couldn't confidently match (Zoom license)
* Seen a **known reliability caveat** in action, and understood why it's disclosed rather than hidden (Password Reset)

**You've just experienced Zero Touch Support — autonomous resolution where the platform can be confident, and a clean handoff where it can't.** 🎉
