---
solution: Campaign Classic
product: campaign
title: Get started with Campaign architecture
description: Get started with Campaign architecture
feature: Overview
role: Data Engineer
level: Beginner
---

# Get Started with Campaign architecture{#gs-ac-archi}

## Mid-sourcing deployment{#mid-sourcing-deployment}

General communication between servers and processes is carried out according to the following schema:

![](assets/architecture.png) 

* The execution and bounce management modules are disabled on the instance.

* The application is configured to perform message execution on a remote "mid-sourced" server that is driven using SOAP calls (over HTTP or HTTPS).

>[!NOTE]
>
> If you are transitioning from Campaign Classic v7, note that all deliveries go through the mid-sourcing server (MID. Campaign v8 relies on a hybrid architecture.
> As a consequence, internal routing is not possible in Campaign v8, and the external account has been disabled accordingly.
>


