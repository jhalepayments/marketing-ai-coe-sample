# How to adapt a skill for your team

You don't need to know anyone here to do this. Follow these steps.

1. **Find a starting point.** Open `INVENTORY.md` and pick the live skill closest to what you need.
2. **Copy the folder.** Copy `.claude/skills/<skill-name>/` and give the copy a new name that says what it does, for example `.claude/skills/partner-launch-coach/`.
3. **Rename it inside.** In the new `SKILL.md`, change the `name:` line to match the folder name, and rewrite the `description:` line in one plain sentence.
4. **Change the content to fit your team.** Usually that means:
   - the guide or rules (brand, compliance, whatever your team checks)
   - the checklist
   - the "who to ask" table, using roles on your team, not people's names
5. **Keep the stop-and-ask rule.** Don't remove or soften it. It's what keeps the skill from guessing, and it's how the skill gets better over time.
6. **Test it with bad answers.** Run it and give vague or missing answers on purpose. It should stop, name the right role, and add a row to `gaps/gap-log.md`. If it guesses instead, tighten the wording and test again.
7. **Add it to the inventory.** Add a row to `INVENTORY.md` with you as owner. Mark it "proposed" until it passes testing, then "live."
8. **Review your gaps monthly.** Once it's live, your open gaps go into the monthly gap review like everyone else's.
