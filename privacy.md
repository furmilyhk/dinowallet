# Privacy Policy

**DinoWallet 恐龍記帳** · last updated 23 November 2026

## The short version

DinoWallet does not collect your data. Your entries, receipts, balances and
attachments are stored on your iPhone or Android phone and, on iPhone, if you
turn on iCloud, in your own private iCloud account. We have no way to read them.

There is one optional exception: **sharing a book with friends**. Nothing is
sent to us unless you share a book or join a friend's. When you do, the book
is encrypted on your phone before it leaves it, and our server keeps only the
encrypted copy, which it cannot read. See "Sharing a book with friends" below.

Apart from that, DinoWallet makes no network requests of its own. The only
other network use is Apple's — iCloud sync if you leave it on, and App Store
purchases.

## What stays on the device

Everything you type, say, photograph or import:

- entries, bills, budgets, standing items and categories
- accounts, balances and the readings behind the net-worth line
- the dinosaur meadow, your daily check-in streak, your coins and what you spent them on
- photographs and PDFs attached to an entry
- the text read off a receipt

Receipts are read on the phone. Text recognition uses Apple's Vision
framework; where the device supports it, Apple's on-device model works out the
shop, the total and a category. Neither sends the picture or the text off the
device. On devices without that model the same job is done by rules built into
the app — also on the device.

Speech recognition for voice entry is set to on-device recognition.

## iCloud

If you leave iCloud on, your books sync between your own devices through
Apple's CloudKit, inside your personal iCloud account. Apple's terms cover
that storage. We cannot see it. Turning on **Local only** in Settings keeps
everything on one device.

If you share a book with family, the people you invite can read and add to
that book. That sharing also runs through your iCloud account.

## Sharing a book with friends

This is optional and works between iPhone and Android. It is used only when you
turn on **Share with friends** for a book, or join one with an invite.

- **What leaves your phone.** The entries, accounts, categories, bills,
  budgets and names in that book (and the names of the people in it), each
  encrypted on your phone with a key that exists only on the phones of the
  people in the book. The key is passed to a friend inside the invite and is
  never sent to us. Photos and PDFs attached to an entry are not shared.
- **What our server keeps.** The encrypted records, which it cannot read; a
  random book identifier and a hash of the book's access token; random record
  and device identifiers; times of change; and, for 7 days, an invite (a hash
  of the code and the encrypted key). The invite code itself is never sent to
  us. The database is hosted by Supabase, our service provider. Like any web
  service, the provider's logs can include the IP address a request came from;
  we do not use them to identify you.
- **Who can read it.** Everyone who has joined the book sees every entry in it,
  with the names people typed. Share an invite only with people you trust, and
  note that they keep the copy on their own phone.
- **Automatic filing stays private.** Payments your phone files by itself from
  notifications, texts or email go into your own book, not a shared one, unless
  you turn on "Also file my automatic payments here" for that book.
- **Stopping.** The person who started sharing can stop it: the book and all
  its records are then deleted from our server. Everyone keeps the copy already
  on their phone. Anyone can leave a book and keep their copy.

We do not sell, analyse or advertise with this data.

## What we do receive

Nothing you enter, apart from a shared book as described above. Two things
happen outside the app and are handled by Apple, not by us:

- **Purchases.** Membership is sold through the App Store. Apple tells the app
  whether a purchase is active. We never see your name, your payment details
  or your Apple Account.
- **Crash and usage reports**, only if you have agreed to share them with
  developers in iOS Settings. Those come from Apple, are aggregated, and
  contain no ledger data.

## Face ID

The app lock is optional and off unless you turn it on. It uses Apple's
LocalAuthentication, which means the app asks the system whether it is you and
receives a single yes or no.

DinoWallet never receives, sees or stores any biometric data. Your face data
stays in the Secure Enclave on your device; there is no interface that would
let an app read it, and we hold none of it. Nothing biometric is collected,
which is why none is declared.

## Analytics and advertising

There are none. No third-party analytics, no advertising identifiers, no
trackers.

## DinoWallet for Android

Everything above about your books applies to the Android app, with these
differences.

- **What stays on your phone.** Your books, the receipts you scan, what you say
  to voice entry, the dino meadow and your coins are stored only on your phone.
  There is no account and no sign-in. Backups are files you choose to save
  (JSON or CSV); where you keep them is up to you.
- **Receipts and voice.** The page scanner and text reader are Google ML Kit
  components that run on the phone; the picture and text are not sent anywhere.
  Voice entry uses Android's on-device speech recognition only.
- **Diagnostics sent to Google.** Google's ML Kit libraries send anonymous
  diagnostics to Google while you use them: phone model, Android version, app
  version, an installation identifier not meant to identify you, performance
  figures and error codes. No images, text, voice or financial data are
  included. Details: <https://developers.google.com/ml-kit/android-data-disclosure>.
- **Notifications, texts and email.** Automatic filing reads a payment
  notification, a text from a bank, or an email notice on the phone only, to
  write the entry. Nothing it reads is sent anywhere, and payment apps only
  are read unless you add others.
- **Network.** The app uses the internet only for shared books, when you
  choose them, and for Google Play purchases.
- **Permissions.** Camera (scanning), microphone (voice entry, only while you
  tap it), notification access (only if you turn on Automatic filing), and
  internet access for shared books. No location, contacts or photo library
  access.
- **Advertising and tracking.** None.

## Children

DinoWallet is a household ledger and is not directed at children.

## Deleting your data

Delete the app and the copy on that device goes. To remove what is in iCloud,
delete the books inside the app first, or remove the app's data in
Settings ▸ Apple Account ▸ iCloud ▸ Manage Storage.

## Changes

If this policy changes, the date at the top changes with it.

## Contact

Questions: open an issue at
<https://github.com/furmilyhk/dinowallet/issues>.
