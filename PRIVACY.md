# DoubleEntry privacy policy

*Effective 16 October 2026*

DoubleEntry is a personal bookkeeping app for Android published by Soloit Technologies, Lund,
Sweden ("we"). This policy explains what happens to your information when you use the app.

## In short

- **Without cloud backup, everything stays on your device.** We don't receive any of it.
- **Cloud backup and sync are optional and paid.** If you sign in, your ledger is stored on servers
  in the EU (Ireland), so it can be restored and kept in step on your devices and with people you
  share it with.
- We don't sell your data, show ads, or use analytics or tracking. The only diagnostics we collect
  are reports of cloud sync failures, which contain no bookkeeping data.
- You can delete your account and its cloud copy at any time, in the app or by email.

## Using the app without an account

The app stores the bookkeeping data you enter on your device: accounts, transactions, recurring
transactions, assets, invoices, reconciliations and your settings. Without an account, this data
never leaves your device unless you take one of the actions described under
[Other ways data leaves your device](#other-ways-data-leaves-your-device). You can delete your
ledger at any time with *Settings → Data management → Delete all*, and everything the app stores
by uninstalling it or clearing its storage in Android's app settings.

## Cloud backup and sync

Cloud backup is optional. It starts when you sign in under *Settings → Cloud backup & sync*, and
uploading needs a subscription. We store the following for as long as you have an account.

**Your account.** When you sign in with Google, we receive your email address, name and profile
picture from your Google account, and Google tells us your Google account ID. Accounts made
before Sign in with Google use an email address and password. The password is stored only as a
hash, and to reset it we email you a one-time code.

**Your ledger.** Everything in the ledger is stored: accounts, transactions, recurring transactions,
assets, invoices, reconciliations and settings. For each item we also store when it was last
changed and which account made the change. When you delete an item, a deleted copy is kept so
that your other devices learn about the deletion. Deleted copies are removed with your account,
or earlier when we clean up old deletions.

**Shared ledgers.** If you share a ledger, everyone you invite can see and change all of it, and
members can see each other's email addresses. When someone receives an invite, they see the
ledger's name and the owner's email address. Invite codes work once and expire after 7 days. We
store a code only in a form that can't be turned back into the code.

**Your subscription.** Payments are handled by Google Play, and we never see your payment details.
To know whether you may upload, we receive from Google and store: the purchase token, the plan,
the subscription's status, when it ends, and whether it renews. We link these to your account.

**Sync error reports.** When cloud sync fails unexpectedly, the app sends us a report so we can
find and fix the problem. A report contains:

- the kind of error and its technical message, with any of your bookkeeping data removed
- where in the app's code the error happened
- the app version
- how many changes were waiting to upload
- your account

The app doesn't report expected situations, such as being offline. Reports are deleted after
90 days.

**Technical data.** As with any online service, our hosting provider processes your IP address
and request details, such as times and the parts of the service used. This is needed to deliver
the service and keep it secure. Its logs are kept for a limited time.

**On your device.** The app keeps your sign-in session on the device, encrypted with a key held by
Android's keystore, and leaves it out of Android device backups. Copies of ledgers shared with you
are stored on the device like your own ledger.

## Who processes your data, and where

- **Supabase** hosts the cloud service (database, sign-in and the server functions) on our behalf,
  in the EU (Ireland, on Amazon Web Services). Supabase processes the data only under our
  instructions and its data processing agreement. That agreement uses the EU Standard Contractual
  Clauses for any access from outside the EU.
- **Google** provides Sign in with Google and Google Play billing. What Google itself does with
  your data is covered by [Google's privacy policy](https://policies.google.com/privacy).
- **GitHub** hosts the support pages, see below.

We don't share your data with anyone else, unless the law requires us to.

## Why we use your data (legal basis)

- **To provide cloud backup, sync and sharing**, which you sign up for: your account, ledger,
  shared ledgers and subscription status (performance of a contract).
- **To keep sync working and the service secure**: sync error reports and technical logs (our
  legitimate interest in a reliable and secure service, kept to what we need).

## How long we keep it

- **Account, ledger, shared-ledger memberships and subscription status:** until you delete your
  account.
- **Sync error reports:** 90 days.
- **Database backups:** our hosting provider keeps them for up to 30 days. After that, data you
  deleted is gone from the backups as well.

## Deleting your data

- **In the app:** *Settings → Cloud backup & sync → Delete account*. This deletes your account, the
  ledgers you own with everything in them, and your memberships of other people's ledgers. Changes
  you made in ledgers others own stay in those ledgers, without being linked to you. The ledger on
  your phone stays on your phone.
- **Without the app:** email [privacy@soloit.se](mailto:privacy@soloit.se) from the address of
  your account, and we'll delete it within 30 days.
- **Your subscription:** deleting your account doesn't cancel it. Cancel it in Google Play first:
  *Play Store → Profile → Payments & subscriptions → Subscriptions*.
- **Signing out** stops syncing and keeps your data on the phone and in the cloud.
  *Reset this device* removes it from the phone only.

## Your rights

You can ask us for a copy of your data, to correct it, to delete it, or to limit or object to how
we use it. You can also move it elsewhere: *Settings → Data management → Export to JSON* gives you
the whole ledger as a file, and we can send you the rest. To ask, email
[privacy@soloit.se](mailto:privacy@soloit.se). If you think we handle your data wrongly, you can
complain to the Swedish Authority for Privacy Protection (IMY), [imy.se](https://www.imy.se), or
to the data protection authority where you live.

## Other ways data leaves your device

Data also leaves your device in these cases, but only when you choose to:

- **Exports.** When you export a JSON backup or a CSV file, the app writes it to the location you
  pick (for example your device storage or a cloud drive app). What happens to the file after that
  is governed by wherever you saved or shared it.
- **Imports.** When you import a backup or a bank statement, the app reads only the file you pick.
- **Support links.** *Settings → Support* opens GitHub in your browser. A bug report is
  prefilled with the app version, Android version and device model, which you can review or
  remove before submitting. Anything you post on GitHub is public and covered by
  [GitHub's privacy statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).
- **Android device backup.** If Android backup is turned on for your device, Android may include
  the app's data in your device backup, for example in your Google account, including copies of
  ledgers shared with you. This is managed by Android and your backup settings, not by us. Your
  sign-in session is excluded.

## Permissions

- **Internet / network state.** Used only for cloud backup and sync, Sign in with Google and
  Google Play billing. Without an account the app doesn't use the network, and links open in your
  browser.
- **Notifications.** Used only for the optional daily invoice reminder, which you switch on
  yourself. Reminders are created on the device.
- **Biometrics / screen lock.** Used only for the optional app lock. Android checks your
  fingerprint, face or screen lock, and the app never receives biometric data.

## Children

DoubleEntry is meant for adults managing their own finances and isn't directed at children.

## Changes to this policy

If we change this policy, we'll publish the new version at this address and update the date at
the top. If a change affects what we collect or how we use it, we'll also say so in the app's
release notes.

## Contact

Soloit Technologies, Lund, Sweden.

- **Privacy questions and requests:** [privacy@soloit.se](mailto:privacy@soloit.se).
- **Questions about the app:** open an issue at
  <https://github.com/Soloit-Technologies/doubleentry-app/issues>. Issues are public, so don't
  include personal or financial details.
