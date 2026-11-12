---
title: Camp Timanous App Privacy Policy
permalink: /privacy
---
# Camp Timanous Staff App: Privacy Policy

*Last updated November 12, 2026.*

The Camp Timanous app ("the app", listed as Camp Timanous Staff) is a tool for the staff of Camp Timanous in Raymond, Maine, on iPhone and Android. It lets staff answer and place calls on the camp's phone line, listen to the camp's voicemail, look up campers' families, and listen and talk on the camp's walkie-talkie radio. It is published on the App Store and Google Play by Engineering Pixels on behalf of Camp Timanous. This policy explains what information the app handles, why, and who can see it.

## Who can use the app

Only camp staff can sign in: you need a Google account that the camp office has added to the staff list. Anyone else can open a demo with made-up sample data. The demo never connects to the camp's systems and sends nothing off the phone.

## What the app handles, and why

**Your sign-in.** When you sign in with Google, the app receives your name and email address from Google. The camp's server checks them against the staff list and gives the app a session that expires. The app keeps that session in the phone's secure storage (the iPhone's Keychain, or Android's encrypted storage). The app does not see or store your Google password.

**Calls.** Calls you make or receive in the app go through Twilio, the camp's phone provider, and use the camp's phone number. To ring your phone for an incoming call, the app registers a push token with Twilio and with Apple (iPhone) or Google's Firebase Cloud Messaging (Android). The camp keeps a call history: the other party's number, the time, the length, and which staff member placed or took each call or transferred it. Staff signed in to the app can see this camp-wide history. The audio of a live call is carried to the other party and is not recorded by the app. Twilio's Voice SDK also sends call-quality data (for example network conditions during a call) to Twilio. For numbers that aren't in the directory or your contacts, the camp's phone system may look up the caller ID name and line type of the number through Twilio.

**Voicemail.** Callers to the camp can leave voicemail. Twilio records and transcribes those messages. Staff can play voicemails and read their transcripts in the app, and the app shows which staff members have listened. Voicemail audio is downloaded from the camp's server when you play it. Admins can record voicemail greetings in the app; those recordings are stored so callers can hear them.

**The camper directory.** The camp office loads a directory of campers and their parents (names, cabin, session and phone numbers) from the camp's registration system. The app downloads it so staff can find a family and call them, and keeps a copy on the phone so it works without a signal. Signing out removes it from the phone.

**Your phone's contacts.** If you allow it, the app reads your phone's contacts so you can call them from the camp's number and so Recents shows their names. Contacts are read on the phone only and are never sent to the camp or anyone else.

**The camp radio.** The Radio tab plays the camp's walkie-talkie channel, which a small computer at camp records. That computer keeps the audio of each transmission, a written transcript of it, and short summaries of busy stretches, so staff can scroll back and search. Transcripts are made by Cartesia, and summaries by an AI language model service, from the radio audio only. If you send a message over the radio from the app, your recorded voice (or the text you chose, spoken by Cartesia's text-to-speech) is sent to that computer and broadcast on the radio, and the log shows that it came from you. When certain phrases such as "emergency" are heard on the radio, the camp's server sends an alert to staff phones. Listening continues with the app closed only while you have it switched on.

**Notifications.** If you turn them on, the app sends you notifications of missed calls, new voicemail and radio alerts, through Apple's push notifications or Firebase Cloud Messaging.

**Text messages.** The app is built to send and receive text messages from the camp's number through Twilio. This is not switched on yet. When it is, messages and their sender and recipient numbers will be stored by Twilio for the camp.

**Microphone.** The app uses the microphone only during phone calls, to record voicemail greetings, and while you hold the radio's talk button.

## What the app does not do

- No advertising, no analytics, and no tracking across other apps or websites.
- No selling or sharing of information with data brokers or advertisers.
- No access to your photos or location.

## Where the information is kept

The camp's phone system runs on Twilio (calls, voicemail, call history, the staff list and the directory, kept in Twilio Sync). The radio's recordings, transcripts and summaries are kept on the camp's own radio computer, reached through Cloudflare. Sign-in uses Google. Apple and Google deliver push notifications. Cartesia and an AI language model service process radio audio and text as described above. These companies process the information for the camp under their own terms and privacy policies. Information stays only with the camp and these providers.

## How long it is kept

The camp keeps call history, voicemail, radio recordings, transcripts and the directory for as long as it needs them to run the camp's phones and radio and to contact families, and removes them when they are no longer needed. The directory is replaced each time the office loads a new one. A staff member's access ends when the office removes them from the staff list.

## Deleting your data

You can sign out at any time, which removes your session and the directory from your phone. Uninstalling the app removes everything it stored on the phone.

To have the camp delete information it holds about you, such as your staff account, your voicemail greetings, the radio messages you sent from the app, or call history entries about you or your family:

1. Email info@engineeringpixels.com (or contact the Camp Timanous office), saying you'd like your Camp Timanous app data deleted, and give the name and email address or phone number it is under.
2. We confirm the request and delete it within 30 days: your staff-list entry, your app sessions and push tokens, your greetings and radio messages, and the call history entries about you.

Some records may be kept where the camp needs them, for example call records it must keep for billing or safety, and copies in Twilio's or other providers' own logs and backups, which they delete on their own schedules.

## Children

The app is for camp staff, not for children. It holds campers' names and cabins only so staff can reach their families.

## Changes

If this policy changes, the new version will be posted at this address with a new date.

## Contact

Questions about this policy or the app: info@engineeringpixels.com.
