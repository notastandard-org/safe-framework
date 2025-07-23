---
id: SAFE-T0018
tactic: SAFE-TA0005
title: Induced Device Breakage or Downtime
status: draft
version: 0.1
author: Ben Menzies (benzies)
created: 2025-07-20
modified: 2025-07-20
tags:
---
# SAFE-T0018 - Induced Device Breakage or Downtime

## Summary

Abuser purposefully damages or misconfigures devices to delay access, isolate the victim, or instill helplessness.

## Purpose

To disrupt access to communication and support networks while increasing psychological dependence.

## Sub-techniques

* Overheating via forced workload
* Bricking devices through incorrect flashing

## Procedure Examples

* "Locked SIM card with repeated PIN entries."
* "Deleted key system files remotely."

## Mitigation / Intervention

* Remote diagnostics and emergency support access
* Regular backups and device insurance

## Detection

* Service logs showing intentional misconfiguration
* Patterns of repeated failures or resets

## References

* [MITRE ATT\&CK T1499: Endpoint Denial of Service](https://attack.mitre.org/techniques/T1499/)
* [DISARM Technical Disruption: Device Sabotage](https://github.com/centerforsecurityandemergingtechnology/DISARM-framework)
