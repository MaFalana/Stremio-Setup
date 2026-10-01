# Suwatte Setup Guide

A step-by-step guide to set up **Suwatte**, an ad-free, open-source manga/comic/novel reader for iPhone and iPad. You add your own content sources, connect self-hosted servers, or load local files — all into one library that syncs over iCloud.

> Suwatte is just the reader. It ships with **no content** — you bring your own sources, servers, or files. Only read content you have the legal right to access in your region.

## Contents

- [What Suwatte does](#what-suwatte-does)
- [Requirements](#requirements)
- [Step 1 — Install Suwatte](#step-1--install-suwatte)
- [Step 2 — Add content (three ways)](#step-2--add-content-three-ways)
  - [A. Sources (community runners)](#a-sources-community-runners)
  - [B. Servers (Komga / Kavita / OPDS)](#b-servers-komga--kavita--opds)
  - [C. Local files](#c-local-files)
- [Step 3 — Set your reading mode](#step-3--set-your-reading-mode)
- [Step 4 — Sync & trackers](#step-4--sync--trackers)
- [Troubleshooting](#troubleshooting)
- [Resources](#resources)

## What Suwatte does

- **One library** — sources, servers, and local files all land in a single, searchable library.
- **Ad-free & open source** — [Suwatte on GitHub](https://github.com/Suwatte/Suwatte).
- **Global search** — search across all your installed sources at once.
- **Four reading modes** — Paged Manga (right-to-left), Paged Comic (left-to-right), Paged Vertical, and Vertical (webtoon) — set globally or per title.
- **iCloud sync** — library, collections, flags, and reading progress sync across your devices.
- **Trackers** — update matched entries on supported tracking services as you read.

## Requirements

- iPhone or iPad on **iOS 17 or later**.
- Free. App Store listing is available in the **US and Canada**; elsewhere, join via **TestFlight** (worldwide).

## Step 1 — Install Suwatte

Pick whichever matches your region:

- **App Store (US / Canada):** search "Suwatte" or get it from the [official site](https://suwatte.mantton.com/).
- **TestFlight (worldwide):** install Apple's TestFlight app, then join the [Suwatte beta](https://testflight.apple.com/join/qDyYMTLJ). TestFlight builds expire periodically and need re-updating, but it's the way to get Suwatte outside the US/Canada.

Open the app once installed — you'll land on an empty library until you add content in Step 2.

## Step 2 — Add content (three ways)

Suwatte supports three independent ways to fill your library. Use any mix of them.

### A. Sources (community runners)

Sources (also called "runners") are community-maintained connectors to online content. You install them from a **source list** (a URL that hosts a collection of runners).

1. In Suwatte, go to **Browse** (or **Settings → Runners / Sources**, depending on build).
2. Choose **Add Source List** and paste a runner-list URL. The one I use:
   ```
   https://bergelmir.mantton.com
   ```
3. Browse the list and **install** the individual sources you want.
4. Installed sources show up in **Browse** and in **Global Search**.

> `bergelmir.mantton.com` is a Mantton-hosted list (same author as Suwatte). Suwatte doesn't bundle sources, and runner lists aren't officially endorsed — install only what you trust, and keep lists updated since sources break when sites change. Official reference: [Sources guide](https://suwatte.mantton.com/).

### B. Servers (Komga / Kavita / OPDS)

If you self-host your own comic/manga library, connect it directly:

1. Go to **Settings → Servers** (or the server/connect option in the app).
2. Choose **Komga**, **Kavita**, or a generic **OPDS** feed.
3. Enter the server URL and your credentials.
4. Your server's library appears in Suwatte, and reading progress can sync back to Komga/Kavita.
   - Official reference: [Servers guide](https://suwatte.mantton.com/).

### C. Local files

For files already on your device or in iCloud/Files:

1. Go to the **local/files** section of the app.
2. Import or open **CBZ, CBR, PDF, or EPUB** files.
3. They join the same unified library, with bookmarks and "continue reading" support.
   - Official reference: [Files guide](https://suwatte.mantton.com/).

## Step 3 — Set your reading mode

Suwatte has four reading modes. Set a default for everything, or override per title:

| Mode | Use for |
| --- | --- |
| **Paged Manga** | Manga — pages turn right-to-left. |
| **Paged Comic** | Western comics — pages turn left-to-right. |
| **Paged Vertical** | Page-by-page but scrolling vertically. |
| **Vertical** | Webtoons / long-strip — continuous vertical scroll. |

Set it globally in **Settings → Reader**, or open a title → reader settings to override just that one.

## Step 4 — Sync & trackers

- **iCloud** — enable it so your library, collections, flags, and progress follow you across iPhone/iPad. (Make sure iCloud is signed in on the device.)
- **Servers** — progress can be sent back to Komga and Kavita.
- **Sources** — sources that support it receive your progress.
- **Trackers** — matched titles update their entries on supported tracking services as you read.

## Troubleshooting

- **A source stopped working** — sites change and break runners. Update your source list, or remove and reinstall the source. Check the community for a current/replacement list.
- **TestFlight build expired** — reopen TestFlight and update to the latest beta; TestFlight builds are time-limited.
- **Library didn't sync to another device** — confirm both devices are signed into the same iCloud account with iCloud enabled for Suwatte.
- **Server won't connect** — verify the URL (including http/https and port), credentials, and that the server is reachable from your device's network.

## Resources

- **Official site & guides** — [suwatte.mantton.com](https://suwatte.mantton.com/) (Sources, Servers, Files guides).
- **Source code** — [github.com/Suwatte/Suwatte](https://github.com/Suwatte/Suwatte).
- **TestFlight beta** — [join here](https://testflight.apple.com/join/qDyYMTLJ).
- **Source list in use** — `https://bergelmir.mantton.com` (add via **Add Source List** in Step 2).
- Community source/runner lists change over time and aren't officially endorsed; search the Suwatte community (GitHub, Discord) for the current recommended lists, and only install sources you trust.
