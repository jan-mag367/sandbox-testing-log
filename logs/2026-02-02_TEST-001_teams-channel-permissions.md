# TEST-20260202-001 — Teams channel permissions

## Date
2026-02-02

## Goal
Validate a basic Teams structure with owners/editors and restricted channels.

## Tools
Microsoft Teams

## Steps
1. Create Team: "Branch Collaboration (Sandbox)"
2. Create channels: governance, comms, organising
3. Create a private channel for restricted governance content
4. Confirm owners can manage channel and members cannot

## Expected result
Private channel content is visible only to owners/members explicitly added.

## Actual result
As expected. Private channel visibility restricted correctly.

## Outcome
Pass

## Notes / Follow-up
Add a naming convention for channels and test guest access set to off.
