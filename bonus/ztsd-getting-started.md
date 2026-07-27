---
description: >-
  Prevent and Resolve Incidents With Autonomous Workers and Chat AI
---

# Getting started

### Introduction and Objectives

IT support teams face mounting pressure as ticket volumes grow, employee expectations rise, and skilled agents become harder to retain. Too often, routine incidents — password resets, application crashes, device issues, access and equipment requests — consume the same time and attention as complex, high-impact problems. In this lab, you will experience firsthand how ServiceNow's Zero Touch Support capabilities transform the IT service desk with the L1 Service Desk AI Specialist resolving and triaging real incidents **entirely within ServiceNow** — no additional infrastructure required.

This lab is built around a single, proven capability: the L1 Service Desk AI Specialist resolving and triaging real incidents entirely within ServiceNow — including correctly recognizing when it should hand a ticket to a human instead of forcing a fit.

**By the end of this lab, you will be able to:**

1. Set up and activate the L1 Service Desk AI Specialist to autonomously classify, investigate, and resolve incidents.
2. Watch the AI Specialist autonomously resolve a real request, and separately, correctly escalate one it can't confidently match — both are success cases.
3. Run a complete end-to-end Zero Touch Support flow across native ServiceNow resolution and escalation.
4. Monitor AI Specialist performance, activity, and feedback through built-in dashboards.
5. Author and publish a knowledge article, then watch the AI Specialist use it to deflect a matching incident.

> **Your instance may vary.** Each student gets their own separately-provisioned lab instance, so specific values you see on screen — record numbers, names, sys_ids, seed timestamps and counts — are illustrative, not guaranteed to match this guide's screenshots exactly. Match on structure, labels, and description text rather than pixel-for-pixel record values, and you'll be fine.

***

### Lab Personas

This lab uses three personas. You will switch between them as instructed throughout the exercises.

| User                     | Role                         | Description                                                                                                                                                                                                                     |
| ------------------------ | ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **System Administrator** | ServiceNow Developer         | The person configuring the Zero Touch Service Desk. As admin you'll configure the L1 Service Desk AI Specialist.                                                                                        |
| **Abel Tuter**           | Employee, Product Management | A typical employee who experiences an IT issue and contacts the service desk for help. Abel is the **Caller** on incidents created in Exercise 3.                                                                         |
| **Bernard Laboy**        | Knowledge Manager / Approver | The designated approver for knowledge articles in the IT Knowledge Base. You will **impersonate** this user in Exercise 3 to approve your knowledge article, if it requires approval before it can be published.                                                                        |
| **Ravi Kapoor**          | IT Service Desk persona      | An IT Service Desk agent whose incident queue you'll work from in Exercise 2, assigning tickets to your AI Specialist as its partner.                                                                                                                                                              |

> **Impersonation** is used in this lab. To impersonate a user, select your user avatar in the top-right corner and choose **Impersonate another user**. When finished, return to the same menu and select **End impersonation**.

***

### Getting Started

No pre-work is required for this lab. Your lab instance comes pre-loaded with the necessary applications, plugins, and demo data. Simply log in and jump straight into the exercises.

1. Open your browser and navigate to your assigned lab instance URL (provided by your facilitator).
2. Log in as the **System Administrator** using the credentials provided.
3. Confirm you can see the **Shared admin dashboard** on the home page.
4. You're ready to go!

***

