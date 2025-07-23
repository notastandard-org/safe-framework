---
id: SAFE-T0007
tactic: SAFE-TA0002
title: Digital Pattern Mapping
type: Technique
status: draft
version: 0.1
author: Ben Menzies (benzies)
created: 2025-07-20
modified: 2025-07-20
tags:
---

# SAFE-T0007 - Digital Pattern Mapping

## Summary

Abuser uses tools or manual observation to track the victim's digital routines and infer offline patterns.

## Purpose

To create a behavioral map that supports timing for manipulation, contact, or coercion.

## Sub-techniques

* Mobile app usage tracking
* Screen-time analysis

## Procedure Examples

* "Monitored sleep schedule through Snapchat activity time stamps."
* "Used family-sharing screen time logs to check when the target was online."

## Mitigation / Intervention

* Disable app activity sharing
* Limit permissions on shared apps or parental control settings

## Detection

* Unexpected location or device access logs

## References

* [MITRE ATT\&CK T1056: Input Capture](https://attack.mitre.org/techniques/T1056/)
* [MITRE DEFEND D3-DA: Audit Usage Patterns](https://d3fend.mitre.org/technique/d3da/)
