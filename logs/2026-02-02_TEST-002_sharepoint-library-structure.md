# TEST-20260202-002 — SharePoint library structure

## Date
2026-02-02

## Goal
Create a basic document library structure and test versioning and access control.

## Tools
SharePoint

## Steps
1. Create site: "Branch Docs (Sandbox)"
2. Create folders: Governance, Campaigns, Comms, Training
3. Enable versioning (default) and confirm restore works
4. Restrict Governance folder access to Owners group only

## Expected result
Owners-only access to Governance; version history available for documents.

## Actual result
Access restriction worked. Version history visible and restore successful.

## Outcome
Pass

## Notes / Follow-up
Test sharing links and confirm external sharing disabled.
