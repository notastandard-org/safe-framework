---
id: SAFE-T0015
tactic: SAFE-TA0004
title: Unauthorized Account Access for Control
status: draft
version: 0.1
author: Ben Menzies (benzies)
created: 2025-07-20
modified: 2025-07-20
tags:
---
# SAFE-T0015 - Unauthorized Account Access for Control

## Summary

Abuser gains access to victim’s personal accounts (e.g., email, cloud storage, social media) to exert psychological control.

## Purpose

To manipulate, surveil, or impersonate the victim, often without their knowledge.

## Sub-techniques

* Password reset via security questions
* Session hijacking

## Procedure Examples

* "Changed recovery details on target’s email without consent."
* "Monitored conversations by logging into shared email."

## Mitigation / Intervention

* 2FA on all personal accounts
* Security hygiene education and privacy checkups

## Detection

* Account activity from unrecognized IPs
* Sudden lockouts or recovery emails

## References

* [MITRE ATT\&CK T1078: Valid Accounts](https://attack.mitre.org/techniques/T1078/)
* [MITRE DEFEND D3-MA: Monitor Account Activity](https://d3fend.mitre.org/technique/d3ma/)
