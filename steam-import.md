---
title: "Steam import: fill a grid from your playtime"
description: How to make your Steam game details public on desktop and in the Steam mobile app, copy your profile link, and fix a failed Steam import on my9games.cc.
permalink: /steam-import/
---

my9games.cc can read your Steam library and start your grid with the games you really played, sorted by hours. This page covers the two things Steam needs from you first, then what happens after the import.

There are three places with a Steam button:

| Where | What you get |
|---|---|
| [my9games.cc/steam](https://my9games.cc/steam) | One finished image of your most played games, in one step. See [HOW TIME FLIES?](../how-time-flies/) |
| **Import from Steam** in the [grid maker](https://my9games.cc/) | The same games in the editor, so you can swap, reorder and restyle |
| **Import from Steam** in the [tier list maker](https://my9games.cc/tier) | Your 30 most played games waiting to be ranked |

All three take the same input and follow the same rules.

## Step 1: make "Game details" public

Steam only shares a game list that is public. Your profile itself can stay private; only **Game details** matters.

**On a computer (Steam app or browser)**

1. Click your profile name at the top, then **Profile**.
2. Click **Edit Profile**, then **Privacy Settings** on the left.
3. Set **Game details** to **Public**.
4. Under it, make sure **Always keep my total playtime private** is **not** ticked. Otherwise Steam lists your games with zero hours and the import cannot sort them.

**On a phone (Steam Mobile app)**

1. Tap your avatar, then open your profile.
2. Choose **Edit Profile**, then **Privacy Settings**. The app opens the same settings page as the website.
3. Set **Game details** to **Public** and leave **Always keep my total playtime private** unticked.

Shortcut for either: sign in to Steam in a browser and open `steamcommunity.com/my/edit/settings`.

my9games reads the list once. You can switch Game details back to private right after; nothing is kept.

## Step 2: copy your profile link

- **Steam Mobile app**: tap your avatar → **Profile** → the share button → copy the link.
- **Steam on a computer**: click your avatar → **Profile**, then right-click anywhere on the page → **Copy Page URL**.
- **Browser**: copy the address bar while you are on your profile.

Any of these forms works:

- `https://steamcommunity.com/id/yourname`
- `https://steamcommunity.com/profiles/7656119…` (the 17-digit SteamID64)
- just the custom name (`yourname`) or just the 17-digit number

Your custom name is the part after `/id/` in your link. It is not the same as your display name, which other people can also use.

## Step 3: import

Paste the link and press **Import** (or **Make mine** on /steam).

![The Import from Steam dialog in the grid maker]({{ '/assets/img/grid-steam-dialog.jpg' | relative_url }}){: width="476" height="360" loading="lazy"}

The checkbox **Add my games to the HOW TIME FLIES? ranking** is on by default. Untick it if you would rather keep your games out of the public totals; [how that ranking works](../how-time-flies/#the-ranking).

## What the import puts in your grid: the 10-hour rule

The grid does not always stay at nine. It grows to fit how you play:

- every game you played for **10 hours or more** gets a cover,
- with **at least 9** covers (a light player still gets a full 3×3),
- and **at most 20** (a 5×4 grid).

So someone with 14 games over ten hours gets 14 covers. The grid maker also renames the grid to "HOW TIME FLIES?" and switches to the borderless style, since a Steam grid reads best as a wall of covers. Change either if you like.

![After an import: hours on every cover, the rest of the library below]({{ '/assets/img/grid-steam-imported.jpg' | relative_url }}){: width="624" height="1376" loading="lazy"}

### Swap games in from the rest of your library

Your next most played games (up to your top 50) wait under the grid in **More from your Steam library**, each with its hours. Tap one, then tap the cover it should replace. You can still search for any game too, including console games Steam never saw.

### Hours on the covers

Each cover shows your hours in the corner. Keep **Show Steam hours** ticked to have them in the downloaded image and the shared link, or untick it for a plain grid.

### Adding or removing games on /steam (up to 25)

On [my9games.cc/steam](https://my9games.cc/steam) the list under the image is called **More from your library**. A tick marks the games already in the picture. Tap a game to add it or take it out; the counter shows how many are picked, up to **25** (a 5×5 grid).

## When the import fails

| Message | What to do |
|---|---|
| "That Steam profile's game details are private" | Set **Game details** to **Public** (step 1) and try again. |
| "Steam is hiding the hours played on that profile" | Untick **Always keep my total playtime private** in the same Privacy Settings. |
| "No Steam profile found for that link or name" | Check the link. If you typed a name, use the custom name from your profile link, not your display name, or paste the full link instead. |
| "That Steam library has no games yet" | The account owns no games, or you pasted a different account's link. |
| "None of the games in that Steam library are in our catalog yet" | Rare; it happens with libraries of only tools, demos or very small games. Search your games by hand instead. |
| "Too many Steam imports today" | There is a daily limit per visitor. Try again tomorrow. |

![The private-library message on /steam]({{ '/assets/img/steam-private-error.jpg' | relative_url }}){: width="704" height="313" loading="lazy"}

**A game is missing?** Soundtracks, tools, demos and a few very small games are not in the catalog, so they are skipped and the next game moves up. Free-to-play games count once you have launched them.

**Ready?** [Import from Steam in the grid maker →](https://my9games.cc/) or [get the one-step image →](https://my9games.cc/steam)
