# Privacy Policy

**DinoWallet 恐龍記帳** · last updated 22 September 2026

## The short version

DinoWallet does not collect your data, because it never receives it. Your
entries, receipts, balances and attachments are stored on your iPhone and, if
you turn on iCloud, in your own private iCloud account. We have no server
that your figures pass through and no way to read them.

There is one feature that reaches the internet, and it is off until you turn
it on: **share prices**. It is described in full below.

## What stays on the device

Everything you type, say, photograph or import:

- entries, bills, budgets, standing items and categories
- accounts, balances and the readings behind the net-worth line
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

## Share prices, the one thing that leaves the device

DinoWallet can show the price of shares you choose to follow. This is the only
part of the app that makes a network request.

**The app starts with one market index on the list** — the Hang Seng in Hong
Kong, and the equivalent local index elsewhere — so that the feature is
visible rather than hidden behind an empty screen. That means when you open
the app it asks the price service for that index.

If you would rather it did not, either remove the index from your list or turn
the feature off in Settings ▸ Markets ▸ *Show share prices*. With an empty list,
or the switch off, the app makes no request at all.

We chose an index rather than any company's shares deliberately: an index is a
measure, not a recommendation, and this app does not pick investments for you.

When it is on, the app asks a public price service — Yahoo Finance's chart
endpoint at `query1.finance.yahoo.com` — for the shares on your list.

**What is sent:** the ticker symbol, for example `0700.HK`. That is all. When
you search for a share to add, the words you type in the search box are sent
so that matches can be returned.

**What is never sent:** how many shares you own, what you paid, the value of
your holdings, or any other figure from your books. No name, no email, no
account, no advertising identifier, and no cookies — the request is made
without them.

The price service will see the request arriving from your internet connection,
as any website you visit would. We do not receive the request, cannot see it,
and keep no record of it. Your use of that service is subject to Yahoo's own
terms and privacy policy.

Turning the switch off stops it completely. Removing every share from your
list has the same effect.

## What we do receive

Nothing you enter. Two things happen outside the app and are handled by Apple,
not by us:

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
