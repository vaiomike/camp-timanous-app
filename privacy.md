---
title: Camp Timanous App Privacy Policy
permalink: /privacy
---
# Camp Timanous Staff App: Privacy Policy

*Last updated November 1, 2026.*


The Camp Timanous app ("the app") is a tool for the staff of Camp Timanous in Raymond, Maine. It lets staff answer and place calls on the camp's phone line, listen to the camp's voicemail, and look up campers' families. It is published on the App Store by Engineering Pixels on behalf of Camp Timanous. This policy explains what information the app handles, why, and who can see it.

## Who can use the app

Only camp staff can sign in: you need a Google Workspace account on one of the camp's domains, and the camp office must have added your address to the staff list. Anyone else can open a demo with made-up sample data. The demo never connects to the camp's systems and sends nothing off the phone.

## What the app handles, and why

**Your sign-in.** When you sign in with Google, the app receives your name, email address and Google Workspace domain from Google. The camp's server checks them against the staff list and gives the app a session that expires. The app keeps that session in the iPhone's Keychain. The app does not see or store your Google password.

**Calls.** Calls you make or receive in the app go through Twilio, the camp's phone provider, and use the camp's phone number. To ring your phone for an incoming call, the app registers a push token with Twilio and Apple. The camp keeps a call history: the other party's number, the time, the length, and which staff member placed or took each call or transferred it. Staff signed in to the app can see this camp-wide history. The audio of a live call is carried to the other party and is not recorded by the app. Twilio's Voice SDK also sends call-quality data (for example network conditions during a call) to Twilio.

**Voicemail.** Callers to the camp can leave voicemail. Twilio records and transcribes those messages, and the camp's phone system may look up the caller ID name and line type of the calling number. Staff can play voicemails and read their transcripts in the app. Voicemail audio is downloaded from the camp's server when you play it.

**The camper directory.** The camp office loads a directory of campers and their parents (names, cabin, session and phone numbers) from the camp's registration system. The app downloads it so staff can find a family and call them, and keeps a copy on the phone so it works without a signal. Signing out removes it from the phone.

**Text messages.** The app is built to send and receive text messages from the camp's number through Twilio. This is not switched on yet. When it is, messages and their sender and recipient numbers will be stored by Twilio for the camp, and the app will register a push token to tell you about new messages.

**Microphone.** The app uses the microphone only during phone calls.

## What the app does not do

- No advertising, no analytics, and no tracking across other apps or websites.
- No selling or sharing of information with data brokers or advertisers.
- No access to your contacts, photos or location.

## Where the information is kept

The camp's phone system runs on Twilio (calls, voicemail, call history, the staff list and the directory, kept in Twilio Sync). Sign-in uses Google. Apple delivers push notifications. These companies process the information for the camp under their own terms and privacy policies. Information stays only with the camp and these providers.

## How long it is kept

The camp keeps call history, voicemail and the directory for as long as it needs them to run the camp's phones and contact families, and removes them when they are no longer needed. The directory is replaced each time the office loads a new one. A staff member's access ends when the office removes them from the staff list.

## Children

The app is for camp staff, not for children. It holds campers' names and cabins only so staff can reach their families.

## Your choices

You can sign out at any time, which removes the session and the directory from your phone. To ask what information the camp holds about you or your family, or to correct or delete it, contact the camp office.

## Changes

If this policy changes, the new version will be posted at this address with a new date.

## Contact

Questions about this policy or the app: Michael Bell, bell@engineeringpixels.com.
