# Group Access to Integrations

Use this when Aubrey is paired with a Telegram or WhatsApp group and you want people in that group to use only the tools you approve.

This is useful for families, teams, school groups, events, carpools, clubs, and other shared workflows.

## What group access controls

Group access settings apply to people who are not the owner of the agent.

The owner can still use their own connected tools normally. Other group participants can use only the access options enabled for that connected group.

New groups normally allow participants to use agent-specific Aubrey information, such as:

* The agent's knowledge.
* The agent's knowledge sources.
* The agent's Aubrey inbox.
* The agent's Aubrey calendar.

The owner can also allow extra access for the group:

* **Selected Google Sheets**: read and update Sheets selected for this agent.
* **Selected Google Docs**: read and update Docs selected for this agent.
* **Connected app actions**: use approved actions such as Airtable actions connected to this agent.
* **Owner Gmail**: trusted group access to connected Gmail.
* **Owner Google Calendar**: trusted group access to connected Google Calendar.

Use owner Gmail or owner Google Calendar only for trusted groups, such as a family group where you want other people to check your calendar through Aubrey.

## Set it up

1. Open the agent workspace.
2. Choose **Channels**.
3. Find the connected Telegram or WhatsApp group.
4. Review the participant access checkboxes.
5. Enable only the access that group should use.

If the group needs a Google Doc or Sheet, select the file for the agent first. Then enable **Selected Google Docs** or **Selected Google Sheets** for the group.

If the group needs Airtable or another connected app, approve the action for the agent first. Then enable **Connected app actions** for the group.

## Examples

Use **Selected Google Sheets** when parents in a carpool group should be able to tell Aubrey who is driving, and Aubrey should update the approved sheet.

Use **Selected Google Docs** when an event group should be able to ask Aubrey to add notes to a planning document.

Use **Connected app actions** when a team coordinates in Airtable and Aubrey should create or update approved Airtable records from the group.

Use **Owner Google Calendar** when a family group should be able to ask Aubrey whether the owner is free or ask Aubrey to add a calendar event.

Use **Owner Gmail** only when the group is trusted enough to ask Aubrey about the owner's connected Gmail.

## What participants cannot do by default

Group participants cannot use owner Gmail, owner Google Calendar, selected Google files, or connected app actions unless the matching access option is enabled for that group.

Group participants also cannot make Aubrey search every file in Google Drive. Google Docs and Sheets are limited to files selected for the agent or files Aubrey created.

If a participant asks for something the group cannot access yet, Aubrey should explain what the owner needs to enable.

## Tips

Tell the group to address Aubrey directly. For example, say "Aubrey, I can drive Juniper" instead of relying on unaddressed group chatter.

For workflows that update shared data, tell Aubrey what counts as a clear instruction and when it should ask a follow-up question before changing anything.
