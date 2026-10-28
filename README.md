# Agent Atlas plugins for Claude

**Map Your Month** from Agent Atlas: Claude reads your last 30 days of email and calendar, read-only,
in your own Claude account, and shows you where your time went, what's slipping, and five things
worth taking off your plate.

## Add it to Claude

1. In Claude (claude.ai or the desktop app), go to **Customize > Plugins**.
2. Choose **Add > Add marketplace** and paste:

   ```
   GeraldZingraf/agent-atlas-plugins
   ```

3. Add the **Agent Atlas** plugin from the list.
4. Connect Gmail and Google Calendar (or Microsoft 365) under **Customize > Connectors**.
5. Start a new chat and say **"map my month"**.

In Claude Code: `/plugin install agent-atlas --marketplace GeraldZingraf/agent-atlas-plugins`

The full step-by-step guide is at https://agent-atlas.co/map/start/

## What it sends

Nothing leaves your Claude account unless you say yes. See
[`plugins/agent-atlas/README.md`](plugins/agent-atlas/README.md) for exactly what the optional
Agent Atlas connector receives, and https://agent-atlas.co/privacy.html.

<!-- Built from the QSR AI Partners folder by phase-1/build-packages.py. Don't edit the skill here;
     edit phase-1/map-your-month/ and rebuild. -->
