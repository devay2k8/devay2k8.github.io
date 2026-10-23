# HabitMend privacy policy

Last updated: 23 October 2026

Envisioned by PD Nexus  
IDEAS • APPS • IMPACT  
Support: [pdnexus.apps@gmail.com](mailto:pdnexus.apps@gmail.com)

## Your core habits stay on your device

HabitMend stores habits, routines, pairs, daily check-ins and timestamped habit entries, voluntary notes, urge entries, reminder rules and history, and preferences in local SQLite storage. Home layout choices and personal SOS actions, including any optional timer and associated Break habit, are stored locally with preferences. Choosing a suggested or personal SOS action does not automatically record an urge or contact another person. There is no required account, advertising, analytics, or automatic cloud sync. Android backup is disabled for app data.

Local data uses Android's app sandbox. HabitMend does not add database encryption. Your device's security, encryption, and screen lock still matter. Uninstalling ordinarily removes app-private data; user-exported copies remain where you saved them.

## Optional reminders

Notifications require your choice and Android permission. They are scheduled locally from times and days you enter or suggestions based on your voluntary entries. Text is generic by default. Private habit names stay hidden. Detailed previews require your choice. Android may delay reminders. No internal urge detection or content monitoring is performed.

## Optional screen-use nudges

If you opt in, select apps, and grant Android Usage Access and notification permission, HabitMend periodically checks local app-use totals and recent foreground app events for the apps you selected. It may show a generic pause reminder after your chosen threshold. Android schedules checks about every 15 minutes or later under battery controls; an alert can be delayed or missed. The feature does not detect scrolling, read screens, messages, or browsing content, or connect directly to Digital Wellbeing. Selected apps, use totals, thresholds, and alert counts remain on the device and are not sent to AI or PD Nexus. Quiet hours and your configured daily reminder limit apply. Turning the option off cancels future checks. Revoking Usage Access stops checks and is reflected when HabitMend reopens. Delete all my data clears these native preferences.

## Optional Android app pause

Only if you enable it, select apps, grant usage access and display-over-apps permission, and start a focus session, HabitMend checks foreground package events locally and displays a pause over selected apps. It does not read screen contents, browsing history, messages, contacts, microphone input, or location. A visible foreground notification and the pause screen let you end the session. Permission revocation or Android controls can stop this feature. Launcher app names and choices stay on the phone and are not sent to AI.

## Optional AI connections

No AI service or provider subscription is bundled. You may connect this phone to a compatible operator-hosted HTTPS service. The connection screen shows the operator's policy before pairing. A one-use code obtains a phone token; Android SecureStore holds the token. Provider API keys remain on the operator's server.

Each AI request needs your review. The question you type is shared with the selected operator and its AI provider. Habit title and today's check-in count are independent optional fields, off by default. Private titles can be shared only if you deliberately include and review them. The habit database, notes, and history are not automatically uploaded.

The included gateway implementation stores token hashes, expiry, daily quota counters, and temporary pairing-code hashes for up to 30 days. It uses in-memory hashed network addresses for connection abuse controls within hourly windows. It does not store ordinary prompts or replies and requests provider responses with storage disabled. If you choose to report an AI response, a review screen shows the response, reason, and optional comment before sending. Only those fields are stored with a hashed phone token for operator safety review for up to 30 days. Reports are not sent to the AI provider. The service operator can review and delete them. This does not eliminate the provider's abuse-monitoring retention; applicable provider logs may remain up to 30 days unless the operator has an approved retention exception. Hosting and reverse-proxy behavior and the operator's final policy must also be reviewed.

Messages and answers remain only in the app screen's memory until you leave that screen. Disconnect removes the phone credential and attempts to revoke it at the service. If offline, the service token can remain until its expiry or operator revocation. Disconnect or local deletion cannot erase provider logs or already processed data. Use the connected operator's privacy contact for those requests.

## Exports, feedback, and deletion

Exports are readable JSON containing habit data, including private notes and voluntary entries. Credentials are excluded. A confirmation explains this before you choose a destination or sharing app. A copy remains in private app cache so the receiving app can read it. A new export overwrites this copy, and Delete all my data clears it. Third-party destinations handle saved files under their own policies.

Feedback is reviewed in HabitMend and then composed in your email app addressed to pdnexus.apps@gmail.com. Nothing is sent automatically. No diagnostic logs, screenshots, habit records, location, or attachments are added. Any personal details you choose to write are delivered through your email provider and can be received by support.

Delete all my data removes local SQLite records and preferences, secure phone credentials, native app-pause and screen-use preferences, the active focus guard, scheduled screen-use checks, and pending reminders. This requires typed confirmation and a second review. It does not remove exported copies, emails you sent, or service/provider retention.

## Your choices and contact

All advanced features are optional. You can change notification privacy, disable nudges or AI, revoke Android permissions, disconnect a service, export, or delete local data in Settings. Core habits remain available offline. HabitMend is an educational habit tool, not a medical device or substitute for professional care. Do not use it as an emergency service.

Privacy and app support: [pdnexus.apps@gmail.com](mailto:pdnexus.apps@gmail.com). Include only information you are comfortable sharing. We do not sell habit data or use sensitive habits for advertising.
