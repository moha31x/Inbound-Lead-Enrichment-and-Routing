# Inbound Lead Enrichment and Routing

## Business Problem
Sales teams lose revenue through slow lead follow-up and time wasted on manual qualification. High-value leads get treated the same as low-value ones.

## Solution
Every new inbound lead is automatically scored based on company size and routed accordingly. Enterprise leads trigger an immediate Slack alert and priority email to the sales rep. All leads are logged to a Notion CRM with enrichment data and priority tags.

## Business Outcome
Reduces lead response time from hours to under 2 minutes for high-value prospects. Eliminates manual data entry and ensures no lead is missed or misrouted.

## Stack
Google Sheets (form simulation) → Make.com → Gmail + Slack + Notion

## Modules Used
1. Google Sheets - Watch New Rows
2. Router - Priority scoring logic
3. Gmail - Send Email (High priority + Medium priority)
4. Slack - Create Message (High priority only)
5. Notion - Create Database Item
