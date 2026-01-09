# Severity Classification Guidelines

This document explains how to interpret and classify dependency issues
reported by the dependency review action.

## Severity levels

- LOW: informational issues with no immediate security impact
- MEDIUM: potential risks that should be addressed in a reasonable timeframe
- HIGH: known vulnerabilities or risky patterns requiring prompt action
- CRITICAL: actively exploitable vulnerabilities or supply-chain compromises

## Review recommendations

- LOW: document and monitor
- MEDIUM: plan remediation and track
- HIGH: fix before merging
- CRITICAL: block merge until resolved

## False positives

If an issue is a false positive:
- Add a clear justification
- Reference upstream documentation or advisories
- Prefer narrow exceptions over global ignores

Consistent severity handling helps keep reviews objective and actionable.
