# Soccer Carpool

Use this when a shared carpool sheet is supposed to stay up to date, but ride assignments change in chat.

Source: [Soccer Carpool](https://www.helloaubrey.com/use-cases/soccer-carpool)

## Good fit

This works well when:

* A team uses a shared Google Sheet for ride assignments.
* Parents coordinate in a WhatsApp group.
* The sheet is not always updated when plans change.
* You want Aubrey to check for missing rides before practice.

## Set it up

1. Connect Google Workspace and select the Google Sheet Aubrey should use.
2. Pair Aubrey with the soccer WhatsApp group.
3. In **Channels**, open the connected group and enable **Selected Google Sheets** for group participants.
4. Confirm the sheet has columns such as practice date, player name, driver, notes, and status.
5. Ask Aubrey to run a recurring check before practice.
6. Tell Aubrey to update the sheet only after a clear direct commitment.

If the team uses Airtable instead of Google Sheets, connect the Airtable action for the agent and enable **Connected app actions** for the group.

## Starter prompt

```
Set up a recurring soccer carpool check.

Every [DAY] at [TIME], before my daughter's soccer practice, check this Google Sheet:
[SPREADSHEET LINK OR ID]

Use the tab/range: [TAB NAME AND RANGE].
The sheet tracks:
- Practice date
- Player name
- Driver
- Pickup location or notes
- Status

For the next upcoming practice:
1. Read the carpool sheet.
2. Identify any players who do not have a confirmed ride or driver.
3. If everyone is covered, post a short confirmation in the soccer WhatsApp group.
4. If anyone is missing a ride, message the WhatsApp group and ask for a volunteer.
5. When someone replies directly to you with a clear commitment, update the Google Sheet with the driver and status.
6. If a reply is ambiguous, ask a follow-up before changing the sheet.
7. Do not update the sheet based on vague or unaddressed group chatter.

Keep the WhatsApp message short and practical.
```

## Example output

```
Soccer carpool check for Thursday practice

Still needs a ride:
- Emma
- Lucas

Confirmed:
- Ava riding with Priya
- Mia riding with Jordan
- Sophie riding with Ben

Can someone take Emma and Lucas to practice this Thursday? Please reply to Aubrey with something like:
"Aubrey, I can drive Emma and Lucas."
```

After a clear reply:

```
Updated the carpool sheet.

Thursday practice:
- Emma riding with Priya
- Lucas riding with Priya

Everyone now has a confirmed ride.
```

## Tips

Tell Aubrey exactly what counts as a clear commitment. This prevents the sheet from changing based on vague group chatter.
