---
title: Privacy Policy
---

# Dispatch Privacy Policy

**Last updated:** October 26, 2026

## Summary

Dispatch is a local-first news reader for iPhone. It has no accounts, no analytics of its own, no tracking and no advertising of its own. What you read stays on your device and in your own iCloud.

Some features connect to other companies, and this policy names each one: YouTube's player when you play a YouTube video, Google's video service for some publishers' streams, and OpenAI if you add your own OpenAI key for Listen. With your own key, only the article itself (its title, source and text) and your voice settings are sent; never anything else about you.

## Data Collection

Dispatch itself collects no personal data. Specifically:

- **No user accounts.** The app requires no sign-up, login or registration to use.
- **No analytics of our own.** Dispatch itself sends no analytics, crash reports or telemetry. YouTube's player and publishers' own web pages, which Dispatch loads when you play or read them, may measure use as they do in a browser.
- **No tracking.** No advertising identifiers, no device fingerprinting, no cross-app tracking. The app shows no App Tracking Transparency prompt because it doesn't track you.
- **No advertising of our own.** Dispatch shows no ads and contains no ad SDKs. Videos and live streams from publishers, and YouTube's player, can include ads that those companies serve.
- **No third-party SDKs.** The app is built only on Apple's frameworks. To play YouTube videos it loads YouTube's embedded player (see [YouTube videos](#youtube-videos)).
- **No Dispatch servers.** Dispatch has no backend of its own. Dispatches (the editor's picks) is read from Apple's CloudKit, and if you turn on notifications for new picks, Apple keeps a subscription for your iCloud account so it can deliver them. The developer receives only emails you choose to send from Send Feedback or "Found a bug? Tell me."

The App Store privacy label for Dispatch, and why, is at the end of this policy.

## Data Stored On-Device

The following data is stored on your device and, where noted, synced across your devices through your own iCloud account (Apple's iCloud key-value storage):

- **Saved articles.** The articles you save: their address, title and source. Synced via iCloud. Saved articles are also downloaded, with their photos, so they open without a connection; those copies stay on this device.
- **Reading history.** The articles you've opened recently (address, title, source, reading progress), kept for 14 days for Recently Read and to pick up where you left off. Synced via iCloud, without thumbnails. **Settings › Privacy & Data › Reading History** turns the Recently Read log off, and **Clear Recently Read** wipes it, on your other devices too once they sync. Dispatch still marks articles you've opened as read, so it can dim them, and syncs those marks.
- **Reading preferences.** Your sources (including the ones you prefer or mute), appearance, hidden categories and display settings. Synced via iCloud.
- **Followed topics and writers.** The topics and writers you follow. Synced via iCloud.
- **Highlights, collections and queues.** Your highlights, collections, reading positions, listening queue, search history and mutes. Synced via iCloud.
- **Custom feeds.** RSS feed addresses you add yourself. Synced via iCloud.
- **Headline cache.** Recently fetched headlines, cached in a file on your device for offline access and a fast launch. On-device only.
- **AI Suite results.** Summary, 5 Facts and 5 W's, generated on your device and kept so they show again quickly. On-device only.
- **Everything else the app keeps.** Article caches and offline copies, images, papers and magazines, past newsletter editions (up to 100 per newsletter, or six months), video and podcast lists, BBC News's schedule, a tally of how many stories each source has published lately, and writers' photos and bios from stories you've opened stay on your device.
- **Tip jar receipts.** Apple's records of any tips you make, managed by Apple's StoreKit.

All iCloud syncing goes through your own iCloud account and is governed by Apple's privacy policy and your iCloud settings. Dispatch has no access to your iCloud account information. Dispatches reads from a public CloudKit database that holds only what Dispatch's editor publishes there, such as the picks; nothing you read or save is written there.

If you save a photo from an article, Dispatch writes it to your photo library with your permission. It asks only to add photos, so it can't see your library.

## Delete All Data

You can delete everything Dispatch has stored at any time from **Settings › Privacy & Data › Delete All Data**. This is provided under Apple App Store Review Guideline 5.1.1(v).

Delete All Data wipes all Dispatch data on this device: reading history and read marks, saved articles and their offline copies, highlights, collections, reading positions, your listening queue, AI Suite results, source preferences (which sources are on, which you prefer or mute, and their order), followed topics and writers, custom feeds, past newsletter editions, video lists, YouTube's video pictures and your video playlist, your OpenAI key, and your sign-in to The Information's subscriber feed. Cookies set by publishers when you signed in are cleared too, so you'll need to sign in to those publishers again. It also removes your notification subscription for new picks and clears Dispatch on your Apple Watch. Dispatch empties what it holds in memory first, so it doesn't save your earlier data back afterwards.

**What Delete All Data doesn't remove:**

- **App Store receipts.** Tips stay on your Apple ID, under Apple's platform rules, and Dispatch can't delete them.
- **Your other devices.** If you're signed in to iCloud, Dispatch syncs your data through your iCloud account. Another device signed in to the same iCloud account keeps its own copy until you tap Delete All Data there too. Until then, your reading from before the wipe (Recently Read, read marks, highlights, collections and your listening queue) doesn't come back from that device through iCloud, but its saved articles, follows and settings can sync back when it next saves them. To stop syncing, turn off iCloud for Dispatch in the Settings app (your name › iCloud).
- **Notifications already delivered,** which stay in Notification Center until you clear them.
- **The Safari extension's list** of up to 100 pages where you closed its bar, which it keeps on this device.

## Network Requests

Dispatch makes network requests in two situations:

1. **When you use the app:** opening it, pulling to refresh, opening an article, playing audio or video, using Listen, and so on. While it's open, Dispatch also downloads some top stories ahead of time so they open quickly.
2. **When iOS runs Background App Refresh.** Dispatch asks iOS for background refresh time. When iOS grants it, Dispatch fetches the latest headlines, today's papers and magazines from the sources you follow, and some top stories, so they're ready when you open the app. The stories it downloads in the background skip the built-in publishers you can sign in to, and newsletters.

The requests are:

- **Feed fetches.** Dispatch fetches publishers' public RSS and Atom feeds to show headlines. They carry no identifier from Dispatch. Feeds you've signed in to (Substack, The Information's subscriber feed, custom feeds with a login) send that sign-in to that publisher only.
- **Weekend section pages.** For the Weekend, Dispatch reads a few publishers' section pages (Bloomberg, The Information and The Washington Post) at most once a day, with no cookies. If you're signed in to The Wall Street Journal and The Saturday Essay is on, it reads that page once each Saturday while the app is open, in a hidden web view that starts with no cookies and keeps none afterwards, so that read is signed out. The page's own scripts run there, as they would in a browser.
- **Article pages.** When you open a headline, the app fetches the article's web page to show it in Dispatch's reader. This is the same as visiting the page in a web browser: if you've signed in to that publisher, your sign-in goes with the request, as it would in Safari.
- **Images.** Article photos and podcast artwork load from publishers' servers over HTTPS.
- **Video lists.** Media › Videos and the Weekend's Watch & listen read each channel's public video feed from YouTube, with no cookies, and show each video's picture from YouTube's image server.
- **Live TV and video.** Bloomberg TV and CBS News live streams, and Bloomberg's videos, load when you choose to watch them. Bloomberg's videos and the CBS News stream are delivered by Google's ad-insertion service, which adds those publishers' ads to the stream. Dispatch's request for a Bloomberg video sends no cookies and no advertising identifier, and tells Google you've opted out of the sale of your personal information. Google receives your IP address and the video requested, and [Google's Privacy Policy](https://policies.google.com/privacy) applies. BBC News live plays BBC News's own stream on YouTube, in YouTube's embedded player (see [YouTube videos](#youtube-videos)); to pick the stream offered in your iPhone's region, Dispatch reads BBC News's public list of live streams from YouTube, at most once a day while BBC News is chosen, with no cookies; your region setting isn't sent. While BBC News's US stream plays, Dispatch also reads that day's schedule from bbc.co.uk, at most once a day, with no cookies.
- **Podcasts.** Podcast feeds and episodes come from each podcast's own host.

Background App Refresh follows the system switch (Settings › General › Background App Refresh) and runs only when iOS gives Dispatch time. Dispatch adds no identifier, analytics or advertising of its own to any of these requests. The only credentials sent are the ones you gave a publisher or OpenAI, and each goes only to that company.

## YouTube videos

Dispatch plays YouTube videos inside the app with YouTube's embedded player, one of the YouTube API Services. When a YouTube video loads or plays, YouTube receives information about it directly from the player and may show ads in it. [Google's Privacy Policy](https://www.google.com/policies/privacy) covers how Google and YouTube use that information. The player keeps no YouTube cookies or website data between sessions.

Dispatch stores on your device only the lists of videos it shows, their pictures, your video playlist, BBC News's list of live streams with the one that last played in your region, and the length YouTube's player reports for each video you play. Each is fetched again from YouTube or dropped within 30 days, and YouTube's pictures are kept out of the app's web cache; a video you save stays in Saved until you remove it. They are never sent anywhere, and Delete All Data removes them. Videos from publishers, and YouTube's player, may include ads those third parties serve.

Using Dispatch means agreeing to the [YouTube Terms of Service](https://www.youtube.com/t/terms); see the [Terms of Use](https://liamwalsh-redirect.github.io/dispatch/terms).

## Other services Dispatch uses

To show you a story's full content, Dispatch also connects to:

- **X,** to show posts embedded in articles. It sends the post's number, with no cookies.
- **PressReader,** for the FT's print edition, its front page and its weekend magazines.
- **rss.app,** which carries one newsletter's feed (Superhuman AI), because the publisher has turned its own feed off.
- **Trinity Media and Dow Jones,** for some publishers' narration.
- **Publishers' author pages,** for a writer's photo and bio. Most are read with no cookies. When you open a writer's page for the FT, Bloomberg or The Wall Street Journal and Dispatch is missing their photo, title or bio, it loads that writer's page on the publisher's site once, the way it opens a story, with your sign-in to that publisher.
- **Charts and graphics** embedded in some stories, which load from their publisher in a web view that keeps no cookies or website data.
- **Podcast hosts.**

Each sees your IP address and the item requested, as any website would, and its own privacy policy applies. Dispatch sends them nothing else about you.

## AI Features and OpenAI

Dispatch's AI Suite (Summary, 5 Facts and 5 W's) runs on **Apple Foundation Models, on your device**. No network request is made for these tabs, and the article never leaves your device for them. Dispatch also uses Apple's on-device model to match stories in the FT's print edition to their web pages; that stays on your device too.

Apple Foundation Models is available on iOS 26 and later, on devices with Apple Intelligence. On devices without Apple Intelligence, the AI Suite tabs still appear but show **"Apple Intelligence isn't available on this device."** instead of a result. Nothing is sent anywhere in its place.

Apple Intelligence is a trademark of Apple Inc., registered in the U.S. and other countries.

**Listen** is the only feature that can use OpenAI, and only once you've added your own OpenAI API key:

- **Without a key,** Listen reads stories with Apple's on-device voices, or plays the publisher's own audio where there is one. Nothing leaves your device for narration, and Listen works fully without a key.
- **With your key** (Settings › Listening), Listen reads with OpenAI's voices instead of Apple's. Wherever Listen runs (in a story, Play All, CarPlay, Siri or a request from your Apple Watch), the story's text, which can begin with its headline and source, is sent to OpenAI in pieces of about 500 characters, with your chosen voice, model and speed. Choosing an OpenAI voice in Settings plays a short, fixed sample sentence through OpenAI. Remove the key to go back to Apple's voices.

In every case:

- **Your OpenAI API key is your own.** You create it at [platform.openai.com](https://platform.openai.com), pay OpenAI directly for what you use, and enter it in Dispatch. Dispatch keeps it in this device's Keychain, where it never moves to another iPhone, even from a backup; Remove Key or Delete All Data deletes it. The key never leaves your device except as the credential on your own requests to OpenAI.
- **Nothing about you is added.** No user identifier, device information, advertising ID, account information or email address is included in any request.
- **Dispatch operates no servers between you and OpenAI.** Your request goes straight from your device to api.openai.com.
- **OpenAI's privacy policy applies** to what's sent to its API. See [openai.com/policies/privacy-policy](https://openai.com/policies/privacy-policy) for how OpenAI handles it, including its default retention of up to 30 days for abuse monitoring (subject to OpenAI's policies, which may change).

If you don't add an OpenAI key, **nothing is ever sent to OpenAI.**

## Publisher Logins (Optional)

Some sources have paywalled stories (FT, WSJ, NYT and others). Dispatch lets you sign in to those publishers inside the app, on the publisher's own sign-in page, with subscriptions you already have.

The cookies a publisher sets when you sign in stay on your device. So that paywalled feeds and stories work without signing in again on every request, Dispatch reads those cookies from the device's cookie store when it makes a request to that publisher and sends them with that request. Dispatch never copies them off your device or sends them to anyone but the publisher that set them. Dispatch has no server to send them to.

When a publisher's row in **Settings › Sources › Log in to Sources** shows you're logged in, you can sign out there; signing out also removes the story text Dispatch kept from that publisher. You can also clear every publisher's cookies with **Settings › Privacy & Data › Delete All Data**, or by deleting the app.

## The Information

If you sign in to The Information's subscriber feed, your username and password are kept in this device's Keychain (never synced) and sent only to theinformation.com with each feed request. Remove them with Sign Out under **Settings › Sources › Log in to Sources › The Information**, or with Delete All Data.

## Notifications for Dispatches

If you turn on notifications for new picks (**Settings › Notifications › New Pick Alerts**), Apple's CloudKit keeps a subscription for your iCloud account so it can send them. Turning them off, or Delete All Data, removes it.

## Feedback

Send Feedback and "Found a bug? Tell me." open an email to dispatch.news@icloud.com in your mail app. The developer receives only what you write, your email address and, from Send Feedback, the app version in the subject line. Nothing is sent unless you send the email.

## Apple Watch, widgets and extensions

- **Apple Watch.** Your iPhone shares headlines, and the articles you open or save from the watch, with Dispatch on your Apple Watch, and Delete All Data clears the watch. When your iPhone can't send headlines, the watch can fetch two publishers' public feeds itself.
- **Widgets.** Widgets read headlines and saves from storage shared on this device. The Home Screen widget can also fetch a few publishers' public feeds itself, without your sign-ins.
- **Safari extension.** The Safari extension remembers, on this device, up to 100 pages where you closed its bar. It makes no network requests.
- **Share extension.** Open in Dispatch News, in the share sheet, opens a link in Dispatch and makes no network requests.

## Children's Privacy

Dispatch has no accounts and asks no one for personal information, so it does not knowingly collect information from children under 13.

## Compliance

- **GDPR (EU).** Dispatch itself holds no personal data about you: it has no accounts and no server that receives your reading. Article text you send to OpenAI with your own key is your own arrangement with OpenAI, under your agreement with them. YouTube's player and Google's video service are governed by Google's Privacy Policy.
- **CCPA (California).** Dispatch does not sell or share your personal information. When it asks Google's ad-insertion service for a Bloomberg video, it tells Google you've opted out of the sale of your personal information.
- **App Tracking Transparency (Apple).** Dispatch does not track you across apps or websites, so it shows no tracking prompt.

## App Store privacy label

Dispatch's App Store privacy label answers **"Yes"** to "Do you or your third-party partners collect data from this app?", for two reasons: OpenAI, when you add your own key for Listen, and YouTube's embedded player.

| Data type | Purpose | Linked to you | Used to track you | Why |
|---|---|---|---|---|
| Browsing History | App Functionality | Yes | No | Listen sends the story you're hearing to OpenAI with your own key, which is your OpenAI account. |
| Usage Data: Product Interaction | Analytics, Third-Party Advertising | No | No | YouTube's player |
| Usage Data: Advertising Data | Third-Party Advertising | No | No | YouTube's player, and the ads Google's service adds to Bloomberg's videos and the CBS News stream |
| Diagnostics: Performance Data | Analytics | No | No | YouTube's player |

Every other data type: not collected.

## Changes to This Policy

If this policy changes, the new version will be posted at [liamwalsh-redirect.github.io/dispatch/privacy](https://liamwalsh-redirect.github.io/dispatch/privacy) with a new date.

## Contact

For questions about this privacy policy:

Liam Walsh

Email: dispatch.news@icloud.com

See also: [Terms of Use](https://liamwalsh-redirect.github.io/dispatch/terms) · [Support](https://liamwalsh-redirect.github.io/dispatch/support)
