# Setup help

Walk the owner through only the steps they need, one at a time. Wait for them to finish each step.

## Turn off training (recommended, once)

In Claude, open **Settings > Privacy** and turn off **Help improve Claude**, so their chats aren't
used to train models. Anthropic says it doesn't train on Gmail, Calendar, or Drive connector data,
but turning this off covers the conversation too.

## Connect Google (Gmail and Google Calendar)

1. On a computer or in the phone's web browser, go to **claude.ai/customize/connectors**. Adding
   connectors inside the phone app may not work yet.
2. Find **Gmail** and select **Connect**. Sign in to Google and allow access.
3. Do the same for **Google Calendar**.
4. Start a new chat. Select **+**, then **Connectors**, and make sure Gmail and Google Calendar are
   on.

These connectors need a paid Claude plan (Pro or higher).

## Connect Microsoft 365 (Outlook)

1. Go to **claude.ai/customize/connectors**, find **Microsoft 365**, and select **Connect**.
2. Sign in with the work Microsoft account.
3. If Microsoft says an administrator must approve it, the person who manages the company's
   Microsoft 365 needs to approve it once. In a small business that's often the owner or their IT
   provider. If that can't happen, the scan can run on the calendar alone, or on a Google account
   the business controls.

## How to undo all of it

- Disconnect any connector at **claude.ai/customize/connectors**.
- For Google, also remove Claude at **myaccount.google.com/connections**.
- Deleting a chat deletes the email data pulled into it.
