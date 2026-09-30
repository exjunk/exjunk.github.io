+++
date = '2026-09-30T09:00:00+05:30'
draft = false
title = 'Hisaab — Privacy Policy'
+++

**Last updated:** 30 September 2026

Hisaab is an offline household payments tracker for Android. This policy explains what the app
does with your information. The short version: it stays on your phone.

This policy covers the **Hisaab Android app** only. The privacy policy for this blog is
[here](/privacy/).

## What we collect

**Nothing.** Hisaab has no account system, no server, no analytics and no advertising. The
developer receives no data about you or your use of the app, and has no way to.

## What the app stores, and where

Everything you enter — people, salaries, attendance, advances, bills, payments and settings — is
stored in a database inside the app's private storage on your device. Android prevents other apps
from reading it. Nothing is transmitted anywhere.

The Android build of Hisaab does not request the `INTERNET` permission. Without it the operating
system blocks the app from making any network connection at all, so your records cannot be
uploaded in the background even by mistake. This is enforced automatically on every build.

Card details are never stored in full. When you add a credit card, Hisaab keeps only a nickname
and the **last four digits**, together with the statement and due dates you enter.

## When data leaves your device

Only when you explicitly ask for it, and only to where you choose:

- **Backup** writes a single `.hisaab` file through Android's own file picker. You pick the
  destination — your device, an SD card, or a cloud drive you already use. If you choose a cloud
  location, that provider's privacy policy governs the copy you put there.
- **CSV export** and **payment slips** are shared through Android's standard share sheet to an app
  you pick.

Hisaab has no visibility into any of these once they leave the app.

## Permissions

| Permission | Why |
|---|---|
| Notifications | Reminders for bills falling due, pay days and backup nudges. Optional; the app works without it. |
| Biometrics / device credential | Optional app lock, checked by Android. Hisaab never sees your fingerprint, face or PIN. |
| Run at startup, wake lock, foreground service, network state | Used by Android's WorkManager to deliver scheduled reminders reliably after a reboot. They do not grant internet access. |

Hisaab requests no access to contacts, location, camera, microphone, SMS, call logs, or files
outside what you explicitly pick in the system file picker.

## Children

Hisaab is a household bookkeeping tool intended for adults. It collects no data from anyone,
including children.

## Deleting your data

Uninstalling the app deletes its database and all its contents from your device. There is no copy
anywhere else for us to delete. Backup files you created yourself are yours to delete from
wherever you saved them.

## Changes

If this policy changes, the revised version will be published at this address with a new date at
the top.

## Contact

Questions about this policy or the app: **[hello@androiddevapps.com](mailto:hello@androiddevapps.com)**
