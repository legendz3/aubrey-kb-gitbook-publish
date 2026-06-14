# Jury Duty Check

Use this when you want Aubrey to remind you to check a public jury duty reporting page for your exact group number.

Source: [San Francisco Jury Duty](https://www.helloaubrey.com/use-cases/san-francisco-jury-duty)

{% hint style="warning" %}
Court obligations are high stakes. Treat Aubrey as a reminder and extraction helper. Always verify the official court page yourself before acting.
{% endhint %}

## Good fit

This example is written for San Francisco jury duty, where jurors check reporting instructions after 4:30 p.m. during the summons week.

It works well when:

* You have a jury group number.
* You know the summons week.
* The reporting instructions are posted on a public page.
* You want Aubrey to alert you only when the page needs attention.

## Set it up

1. Tell Aubrey your exact jury group number.
2. Tell Aubrey your summons week.
3. Give Aubrey the official reporting-instructions page.
4. Ask Aubrey to check only after the court's update time.
5. Ask Aubrey to alert you if the page is stale, unavailable, ambiguous, or says your group must report.

## Starter prompt

```
Create a recurring jury duty check for my San Francisco jury summons.

My jury group number is [GROUP NUMBER].
My summons week is [START DATE] through [END DATE].
Check this public reporting-instructions page every weekday after 4:30pm America/Los_Angeles:
https://sf.courts.ca.gov/divisions/jury-reporting-instructions

Each time you check:
- Confirm the page is for my summons week before acting.
- Look for my exact group number, not partial matches.
- Tell me immediately if my group is instructed to report in person.
- Include the report date, time, courthouse, room, and any instructions shown on the page.
- Tell me if my group is listed as dismissed, excused, completed, or no longer required, if the page says that.
- If my group is only on standby, do not message me unless the page says I need to check again at a specific time.
- If the page is stale, unavailable, for the wrong week, or ambiguous, message me and tell me to manually verify with the court.

Stop checking after the summons week ends or once the page clearly says my group has reported, been dismissed, excused, or completed service.
```

## Example output

```
Jury duty alert

Your group number 110 is listed under "Please report in person."

Report:
- Date: Tuesday, May 12, 2026
- Time: 8:30 a.m.
- Location: Civic Center Courthouse
- Address: 400 McAllister St.
- Room: 007

Source checked:
San Francisco Jury Reporting Instructions

Please verify the page yourself before leaving, since this is an official court obligation.
```

## Tips

Use exact group-number matching. Do not rely on partial matches. Ask Aubrey to stop checking after the summons week ends or after the official page resolves your group.
