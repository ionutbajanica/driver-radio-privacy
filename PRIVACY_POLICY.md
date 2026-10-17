# Privacy Policy for Driver Radio

**Effective date:** 8 September 2026  
**Last updated:** 17 October 2026

Driver Radio is an Android internet-radio application developed and maintained by **Ionut Bajanica, an
independent developer** (referred to in this policy as “I”, “me”, or “the developer”). This policy
explains what information Driver Radio handles, why it is handled, where it goes, how long it is
kept, and the choices available to you.

Driver Radio has no developer-operated server, user accounts, advertising, analytics, or tracking
SDK. Most app data stays on your device. Internet radio cannot work entirely offline, however, so
the app must communicate directly with the radio directory, radio stations, artwork hosts, Google
Play, and—only when you choose certain song actions—Apple, Shazam, YouTube, or another app or web
browser.

## 1. Who is responsible for Driver Radio

Driver Radio is provided by Ionut Bajanica as an independent developer, not by a company or radio station.
For privacy questions, requests, or complaints, use the public contact mechanism at:

<https://github.com/ionutbajanica/driver-radio-privacy/issues>

Please do not include passwords, payment details, precise location, private listening history, or
other sensitive personal information in a public GitHub issue. A private contact method can be
arranged through the issue if needed.

Driver Radio is not affiliated with radio-browser.info, any listed radio station, Apple, Shazam,
YouTube, Google, or vehicle manufacturers unless expressly stated otherwise.

## 2. Information stored on your device

Depending on the features you use, Driver Radio stores the following information locally:

- favourite stations, their order, and any favourite-list names you create;
- custom station names and stream addresses that you add;
- recently selected stations;
- song titles, artists, station names, and timestamps obtained from station-provided stream
  metadata, with the readable song-history log limited to the latest 1,000 entries;
- saved filter presets, home-language choices, theme and other app settings;
- cached directory results and technical information needed to improve startup and reliability;
- a local Boolean record of whether Google Play most recently confirmed the PRO entitlement; and
- widget state needed to show and control current playback.

This information is used only to provide the features you request. It is not sent to the developer
and is not used for advertising, analytics, profiling, or sale.

The app may read the device's ambient-light sensor when the related appearance feature is enabled.
That reading is processed on the device, is not used to determine location, and is not transmitted
or retained as a sensor history.

## 3. Information sent when you use online features

### 3.1 Radio directory searches and browsing

Driver Radio obtains station information from the community-run
[radio-browser.info](https://www.radio-browser.info/) network. When you browse or search, the app
sends the directory request needed to return results. Depending on what you enter or select, this
can include:

- a station-name search term;
- country, language, category/tag, codec, quality, and sorting filters;
- pagination and result-limit parameters; and
- an app-identifying User-Agent containing the Driver Radio name and app version.

The app does not add your name, email address, account ID, advertising ID, or other developer-created
user identifier to these requests. Like any internet service, the receiving mirror necessarily
receives network information such as your IP address and may infer an approximate location from it.
The independent radio-browser.info mirror operators control their own server logs and retention.
The developer does not receive or have access to those logs.

### 3.2 Station selection reports

When you select a directory station for playback, Driver Radio sends that station's public UUID to
radio-browser.info's click endpoint. The directory asks clients to do this so its community
popularity ordering reflects actual station selections. The report contains the station UUID and
normal network/request information; Driver Radio does not attach an account, advertising ID, or
developer-generated user identifier. The app limits repeated reports during a running app process.

This report tells the receiving directory mirror that somebody using a particular network address
selected that station. It is not used by the developer for analytics, advertising, or profiling,
and the developer does not receive the directory's server logs.

### 3.3 Radio streams, playlists, and artwork

When you play a station, your device connects directly to the station's stream host or playlist
host. When artwork is shown, your device connects directly to the artwork host named by the
directory or station. If you add a custom station, the device connects to the address you supplied.

Those independent hosts receive the requested address and ordinary network information, including
your IP address, and may receive standard HTTP headers. They may keep their own logs under their own
terms. Driver Radio and its developer do not control those hosts or receive their logs.

Some community radio streams, playlists, redirects, and artwork are available only over unencrypted
HTTP. Driver Radio permits such connections for compatibility. Information transferred over HTTP,
including the station or artwork requested and stream metadata returned, is not protected against
observation or alteration in transit. Directory discovery and the Apple lookup described below use
HTTPS, but the security and privacy practices of each third-party host remain its responsibility.

### 3.4 Song lookup and external-app actions

Driver Radio does not continuously identify music through your microphone and does not request the
microphone permission.

If you expressly open a Shazam match action for a displayed or logged song, Driver Radio sends the
song title and artist derived from the station's stream metadata to Apple's iTunes Search service
over HTTPS. This request is made only for the action you selected; it is not prefetched or uploaded
in the background. Apple returns candidate song information, which the app uses to construct a
Shazam song-page link. Apple may receive your IP address and request information and handles it
under [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

If you choose to open or search for a song in Shazam, YouTube Music, YouTube, or a browser, Driver
Radio passes or opens the relevant title, artist, search text, or URL as part of that explicit
action. The selected external app or website then handles information under its own policy. See
[Shazam & Privacy](https://www.shazam.com/privacy/summary/) and
[Google's Privacy Policy](https://policies.google.com/privacy).

Opening Shazam from the Now Playing screen starts the separate Shazam application when installed;
Shazam, not Driver Radio, controls any microphone access or audio recognition performed there.

### 3.5 Google Play Billing

The optional Driver Radio PRO unlock is a one-time digital purchase processed by Google Play
Billing. Google handles payment credentials and the financial transaction. Driver Radio does not
receive or store your card or bank details.

Google Play provides the app with the product identifier, purchase status, purchase token,
acknowledgement state, and related technical response information required to complete, acknowledge,
and restore the purchase. The app processes that information to determine entitlement and stores a
Boolean entitlement result locally. It does not send purchase information to a developer server,
because no such server exists. Google handles purchase information under
[Google's Privacy Policy](https://policies.google.com/privacy) and the terms applying to Google Play.

### 3.6 The Driver Radio website

This policy also covers the Driver Radio website at <https://driver-radio.boiob-tech.com/>, which
holds a landing page for the Android app. The site is a set of static files: no
developer-written code runs on a server, and the site has no accounts, analytics, advertising,
cookies, or tracking. Its fonts, icons and scripts are all served from the site itself. The one
exception is the small “Built by BOIOB Tech” badge in the footer: an image loaded from
<https://boiob-tech.com/>, the developers' company website, which is also hosted by Cloudflare and
likewise has no analytics, request logging, cookies or tracking. The image is requested without
telling that site which page it appeared on. No other company is contacted when a page loads.

The site is hosted by **Cloudflare, Inc.** Like any web host, Cloudflare necessarily receives your IP
address and ordinary request information (such as the page requested, browser User-Agent and time)
in order to deliver the site and protect it from abuse. Cloudflare processes that information under
its own [privacy policy](https://www.cloudflare.com/privacypolicy/). The developer has not enabled
any Cloudflare analytics, request logging or log export for the site, and does not receive or store
visitors' IP addresses.

The landing page plays no radio, stores nothing about you, and contacts no radio directory,
station or artwork host.

Until 17 October 2026 the site also offered a browser version of the player. If you used it, the
data it kept (favourites, recently selected stations, settings and the offline station cache) is
still in your browser's own storage for this site (IndexedDB and local storage). It never left your
browser and the developer cannot see or retrieve it. To erase it, clear this site's data in your
browser settings.

## 4. Android backup and device transfer

Driver Radio allows eligible on-device user data—principally favourites, favourite-list names,
custom stations, recently selected stations, and song history—to participate in Android's
platform-managed cloud backup or device-to-device transfer when those services are enabled in your
Android settings.

The app excludes its settings file, directory caches, local PRO-entitlement cache, and the widget's
entitlement mirror from backup and device transfer. Google, the device manufacturer, or the transfer
provider controls the backup service, account association, encryption, retention, and deletion—not
the Driver Radio developer. The developer cannot see, retrieve, or delete your Android backup.

You can manage Android backup through your device and Google Account settings. Disabling backup does
not necessarily delete an existing backup immediately; consult your platform provider's controls
and retention terms.

## 5. Exporting and importing favourites

If you choose to export favourites, Driver Radio creates a file at the location you select through
Android's system document interface. The file can contain station names, UUIDs, stream and artwork
addresses, country/language details, tags, and list information. Driver Radio does not upload that
file. You control where it is stored and whether it is shared.

When you import a favourites file, the app reads the file you selected and stores valid station
entries locally. You should import only files from sources you trust.

## 6. Permissions

Driver Radio requests only permissions needed for its functions:

- **Internet and network state:** to find stations, load artwork, play streams, perform a chosen song
  lookup, and communicate with Google Play;
- **foreground service and media playback:** to continue user-requested playback while the app is in
  the background or the screen is off;
- **wake lock:** to support reliable playback.

The app displays an ongoing media-session playback notification and media controls. Android exempts
media-session notifications from the Android 13 notification runtime permission, so Driver Radio
does not request `POST_NOTIFICATIONS`.

Driver Radio does not request location, contacts, microphone, camera, phone, SMS, advertising ID, or
broad file-storage permissions. File import and export use Android's system picker, which gives the
app access only to the file or destination you choose.

## 7. What the developer does not do

The developer does not:

- operate a backend that receives app usage or listening history;
- require or offer a Driver Radio account;
- include advertising, analytics, tracking, or crash-reporting SDKs;
- sell or rent personal information;
- use app data for behavioural advertising or cross-app tracking;
- access precise or approximate device location through Android location APIs;
- access the microphone, camera, contacts, call logs, messages, or advertising ID; or
- make automated decisions about you or build a user profile.

## 8. Purposes and legal bases

Where data-protection law requires a legal basis, the app's limited processing is based on:

- **performance of the service you request:** processing local data and making directory, stream,
  artwork, lookup, external-action, backup, and billing requests needed to provide the feature you
  chose; and
- **legitimate interests:** sending the station UUID selection report needed to support the
  community directory's popularity data and using minimal technical information to keep the app
  reliable, balanced against the limited nature of the data and the absence of a developer user
  profile.

Where the app hands information to a third party at your explicit request, that party may act as an
independent controller under its own privacy policy and legal bases.

## 9. Retention and deletion

### Data controlled by the app on your device

Local data remains until one of the following occurs:

- you remove a favourite, custom station, list, or saved preset;
- you use an available clear-history control;
- the app automatically trims a bounded history or replaces an expired cache;
- you clear Driver Radio's storage in Android settings; or
- you uninstall the app, subject to any separate Android-managed backup.

Because Driver Radio has no accounts or developer backend, there is no server-side Driver Radio
account or personal-data record for the developer to delete. To erase all active on-device Driver
Radio data, use Android Settings > Apps > Driver Radio > Storage > Clear storage, or uninstall the
app. To address copies held in Android backup, use the backup controls provided by Google or your
device manufacturer.

### Data controlled by third parties

Directory mirrors, station/playlist/artwork hosts, Cloudflare (the website host), Google, Apple,
Shazam, YouTube, GitHub, and other apps or websites may retain request or account information under
their own policies. The Driver Radio developer cannot access or delete information held
independently by those services. Contact the relevant provider if you wish to exercise rights over its records.

## 10. Security

Driver Radio minimizes data by avoiding accounts, a developer backend, advertising, tracking, and
unnecessary permissions. Local app data is protected by Android's application sandbox, subject to
the security of your device. HTTPS is used for the radio directory and Apple lookup. Google Play
Billing uses Google's service and security controls.

As explained above, some third-party radio and artwork hosts support only HTTP. No internet or local
storage method can be guaranteed completely secure. Keep Android updated, use a secure screen lock,
and avoid adding custom stations you do not trust.

## 11. International data transfers

The radio directory mirrors, station hosts, artwork hosts, Cloudflare, Google, Apple, Shazam, YouTube,
GitHub, and other services you choose may operate in countries outside your own. Requests may
therefore be processed internationally under those providers' terms and safeguards. The developer does not
operate an intermediary server or select the physical location of community station and artwork
hosts.

## 12. Your privacy rights

Depending on where you live, you may have rights to information, access, correction, deletion,
restriction, objection, portability, withdrawal of consent, or complaint to a data-protection
authority.

The developer generally holds no server-side personal data that can be searched by identity. Most
Driver Radio data is under your direct control on the device as described in section 9. You may
contact the developer through the mechanism in section 1 if you have a privacy question or believe
the app itself is processing information incorrectly. The developer may need enough information to
understand and answer the request, but will not ask for unnecessary identity, payment, or listening
details.

For information held by an independent third party, direct the request to that provider. If you are
in the United Kingdom, you may also complain to the
[Information Commissioner's Office](https://ico.org.uk/make-a-complaint/). If you are in the EEA,
you may complain to your local supervisory authority.

## 13. Children

Driver Radio is intended for drivers and a general adult audience. It is not directed to children
under 13, and the developer does not knowingly collect personal information from children through a
Driver Radio account or backend because neither exists. Live third-party radio content is not
selected or controlled by the developer and may not be suitable for children. A parent or guardian
with a concern may contact the developer using section 1.

## 14. Third-party content and services

Station listings, stream metadata, broadcasts, playlists, and artwork are supplied by independent
third parties. Their presence in Driver Radio does not mean the developer operates, endorses, or can
control them. Third-party availability, content, security, privacy practices, and legal terms can
change without notice. Review the relevant provider's terms before using an external service.

## 15. Changes to this policy

This policy may be updated when Driver Radio's features, data handling, third-party services, or
legal obligations change. The effective and last-updated dates at the top will be revised. Material
changes will be communicated through an appropriate app or store-listing notice when required.

The version published at
<https://github.com/ionutbajanica/driver-radio-privacy/blob/main/PRIVACY_POLICY.md> is the current
public version. Older versions remain available through that repository's Git history.

