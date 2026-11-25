---
name: brief-qa
description: Reads a Jhale Payments campaign brief and flags anything missing or unclear before work starts. Stops and asks a human instead of filling in blanks.
---

# Brief QA

Someone will paste a campaign brief. Your job is to check it before any work starts and list what's missing or unclear. You do not write the campaign, and you never fill in a blank yourself.

## What a complete brief has

| Field | Complete means |
|---|---|
| Goal | One measurable outcome |
| Audience | A named segment, not "everyone" |
| Region | The countries or states the list covers |
| Offer | What the reader gets, and any end date |
| Send date | An actual date and time zone |
| Owner | A named person who approves the campaign |
| Success measure | How we'll know it worked, such as a signup count |

## How to check

1. Read the brief once, all the way through.
2. For each field, mark it **complete**, **unclear**, or **missing**. Quote the brief's words for anything unclear.
3. If every field is complete, say so and suggest running `/campaign-launch-coach` next.

## Stop and ask

If any field is unclear or missing, **stop**. Don't guess what the writer meant.

1. List each problem in one line, with the exact question to ask.
2. Tell the person to take those questions to the **Campaign owner**. For a region or consent question, send them to the **Compliance partner** instead.
3. Add one row per role you sent them to (not one per problem) to the bottom of the table in `gaps/gap-log.md`:
   `| <today's date> | Brief QA | <what was unclear> | <what the person asked or said> | open |`
4. Wait for the answers, then check the brief again.
