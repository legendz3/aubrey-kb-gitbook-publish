# Email, Calendar, and Messaging

Aubrey can work through the web app, built-in email, calendar feeds, and paired messaging channels. Google Workspace can also be connected on paid plans.

## Jump to

* [Use Aubrey email](email-calendar-and-messaging.md#use-aubrey-email)
* [Connect Google Workspace](email-calendar-and-messaging.md#connect-google-workspace)
* [Select Google files](email-calendar-and-messaging.md#select-google-files)
* [Pair Telegram or WhatsApp](email-calendar-and-messaging.md#pair-telegram-or-whatsapp)
* [Subscribe to the Aubrey calendar](email-calendar-and-messaging.md#subscribe-to-the-aubrey-calendar)

## Use Aubrey email

Open an agent and choose **Email**.

If an email address is ready, use **Copy** to copy it.

You can use Aubrey email in three ways:

* Forward mail to Aubrey to store it.
* Email Aubrey directly when you want a reply.
* Cc Aubrey with an explicit request when you want it to collaborate in a thread.

If Gmail sends a forwarding confirmation request, the Email tab can show a setup card. Use the card to confirm with Google, copy the confirmation link, mark it confirmed, or dismiss it.

## Connect Google Workspace

Google Workspace is available on paid plans.

To connect it:

1. Open the agent workspace.
2. Go to **Tools** or follow the Google Workspace prompt in **Email**.
3. Choose **Connect**.
4. Complete the Google authorization flow.

After connecting, the Tools tab shows the connection status. Depending on the state of the account, you may also see **Reconnect**, **Revoke**, or **Upgrade**.

## Select Google files

When Google Workspace is connected, the Tools tab can show a Google Workspace files section.

Use **Select Google files** to choose files Aubrey can read or update through Google Workspace tools. The selection flow opens a Google file picker. Choose the files, confirm the selection, and Aubrey returns to the agent when the selection is saved.

If Aubrey needs a Google Doc, Sheet, or Drive file that is not available yet, the chat may pause and ask you to select the file. Follow the file-selection card, choose the file in the Google picker, and return to Aubrey so it can continue.

Use **Remove** to remove a selected file from the agent.

Aubrey can use selected files and files it created for the agent. It should not claim it searched your entire Google Drive.

When Aubrey creates or changes Google Workspace content, it should only report success after Google confirms the change, such as a saved file, updated document, calendar event, sent message, or changed sheet range.

## Pair Telegram or WhatsApp

Open an agent and choose **Channels**.

To pair a direct chat:

1. Choose **Pair Telegram** or **Pair WhatsApp**.
2. Open the pairing link.
3. Finish the pairing flow in the messaging app.

After pairing, the channel shows as connected. Use **Unpair** if you want to remove the direct connection.

If a paired channel supports a group setup, the Channels tab can show a group connection option and setup command. Copy the command and follow the displayed instructions before the link expires.

Group messages usually need to address Aubrey directly. For example, say "Aubrey, I can drive Juniper" instead of relying on unaddressed group chatter.

Groups can also control which approved integrations group participants may use. See [Group Access to Integrations](group-access-to-integrations.md).

For example, if a group needs to update a shared Sheet, select that Sheet for the agent first, then enable **Selected Google Sheets** for the group.

## Subscribe to the Aubrey calendar

Open an agent and choose **Calendar**.

The Calendar tab can show upcoming Aubrey calendar events and one or more calendar feed URLs.

Use:

* **Copy** to copy the calendar feed URL.
* **Regenerate link** to create a new feed URL.
* **Disable link** to turn the current feed URL off.
* **Create new link** if the link is disabled.

To add the feed to a calendar app:

* Google Calendar: Other calendars -> From URL -> paste link
* Outlook: Add calendar -> Subscribe from web -> paste link
* Apple Calendar: File -> New Calendar Subscription -> paste link

## FAQ

### Is Aubrey email the same as Gmail?

No. Aubrey built-in email is included on every plan. Google Workspace is separate and is available on paid plans.

### Can Aubrey use Google Calendar?

Yes, after Google Workspace is connected and authorized. Aubrey's own calendar feed is also available from the Calendar tab.

### Can I disconnect a messaging channel?

Yes. Open **Channels** and choose **Unpair** for the connected channel.

### Can group participants update a Google Sheet?

Yes, if the owner selected the Sheet for the agent and enabled **Selected Google Sheets** for that group. Aubrey should ask for clarification before changing a Sheet when a group reply is vague.
