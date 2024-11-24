# welcome to my readme heck!!!!
- 💀 garb0 on web site, @username-garb0 here (howdy)
- 🤺 interested in mobile tools for web things for brain reasons. cheapmaxxing good, ease of access good.
- 😺 using things “wrong” is important too.
  - (+ it’s very fun)
    - (+ it’s very, very funny)
- 🛠️ hardware person, not a web dev!! electronics/EE tech/hw functional testing background. PIC stan 👺
- 🗣️ holler if you need user testing/functional testing
- i dont know how to use this web site as an individual, it intimidates me 😎🚬
- ...so i'm just gonna use this the way i want: mess time

# working on:
(mostly atproto/bluesky-related projects)

currently relying a lot on Skyfeed bc I am Not A Web Dev, definitely need to be hosting my own feeds, should probably figure out how to use open search??

## scam watch, scamdb
this is my main project right now.

### scam watch
- [x] use scam detection feeds to detect possible scam content. check user behavior & posts to avoid listing false positives; only list if certain.
- [x] ✍️ scam huntin’:
  1. keep running notes.
  2. manually save archives using bsky API to get data -> back up w/ free public .warc tools. I don't archive every scam account I see, gotta be kind to the archive sites.
  3. add new actors to list(s).
  4. adjust detection feeds as needed.
  5. repeat forever
- [x] ✍️ scamdb: save and organize identifiers.
#### TODO:
- [x] define external list format for mobile-friendly spreadsheet use
- [x] back up include, exclude Skyfeed regex
  - [ ] copy to blocklists, keep backups of feeds *in atproto*
  - [ ] is there a way to sync back to atproto for people who still want to use Skyfeed or Ozone?
- [x] log list additions
  - [ ] automatically
- [x] LOG POSTS BY FEED
  - [ ] all of em tho + automatically
- [ ] host own feeds
  - [ ] rework includes/excludes in something that isn't rust regex lol
- [ ] ❗ scriptdb from logs ❗ (it's a neat dataset)
  - [ ] set up list to enable scriptdb read access if trusted

### watch tool
- [ ] sync atproto lists to external lists
- [ ] don't toss scam data after takedowns!! that's useful stuff, they come right back!!
- [ ] flag if mod action taken...? (labels, takedowns) (no firehose needed)
  - [ ] charts/visuals would be sick here, esp for schedules/volume
- [ ] make a simple feed display
  - [ ] filter already-prepared data by user or key word/phrase (quick piles/subfeeds)
  - [ ] "add to lists" button & batch archival button should display next to the got dang posts
  - [ ] stick an "add note" button in there, note -> external
  - [ ] click/keypress to indicate read -> functionally a bookmark system
    - [ ] if known identifier(s) used -> eyes pile/subfeed
    - [ ] if read -> read pile/subfeed
    - [ ] ❗ keypress flagging would be so nice, could do cli + if embed or image -> visual quick-check pile/subfeed
- [ ] make a simple searchActors display (https://docs.bsky.app/docs/api/app-bsky-actor-search-actors) (it's so good)
- [ ] probably keep a very very strict list for access or keep private cos uhhhhhhhhhhHHHH

### scamdb
#### TODO:
- [ ] ✍️ update spreadsheet w/ mid-november notes
- [ ] set up actual database: category, identifiers, grouping, archive links
  - [ ] timestamps, post frequency, theme frequency, key phrase highlights
- [ ] sync notes & db
  - [ ] ❗ sync “🗞️👹” with scamdb identifier data ❗
- [ ] create external review zone for new “🗞️👹” hits (flag if direct match and new acct)
  - [ ] total # accounts counter by group
    - [ ] interaction circles but for scammers (target heatmaps?)
    - [ ] shift tracker
- [ ] ❓ external-only repeat target|victim field (w/ archive links or at least timestamps for log)

## list tools
- [ ] ✍️ atproto lists (incl. following, followers) <-> CSV, mobile-friendly spreadsheets
- [x] external list backups
  - [ ] publish backup tool (give the user a copy or a link to mobile-friendly view w/ toggles etc)
- [ ] ❓ list from feed tool might not be great to share

## list merge tool
#### TODO:
- [ ] multiple list -> big blocklist tool (keeps detection criteria behind an effort-barrier)
  - [ ] figure out a way to handle big numbers (respect rate limits) (or say no)
- [ ] include fields for list purpose, source, date added, reason for adding account, archive link(s).
  - [ ] auto-populate fields when importing user lists from normal bluesky/atproto

## لـ اصدقائي - tools for my friends 🍉
### جمع وتخزين وحفظ - archive tools 🍉
- [x] opt-in public, periodic .warc saves. be extremely clear about what is public.
  - [ ] automate this and email links/backups.
    - [ ] if that isn't realistic, automate reminders and send links/backups.
      - [ ] try conifer/archival tools -> physical safekeeping if necessary.
- [ ] write a guide for preserving digital memories more privately. google accounts can be deleted after inactivity or bad luck -> try conifer free tier and signed-in archive.org collections. (will have to test once signups are open again.)  -> ask trusted organizations to hang on to collections.
- [ ] "everyday life" is full of evidence, this testimony is vital. it can help now, and it may help during rebuilding.

### مطبات السرعة - DIY speed bumps - unfollow non-mutuals/unfollow many accounts 🍉
### TODO:
- [ ] unfollow non-mutuals webapp, must work on mobile without a good connection
  - [ ] automate repo download & processing... later
  - [ ] test functions for mutual detection while authed
  - [ ] test rate limit math *without touching bsky*
    - [ ] carefully test, provide on-bsky status updates in case of labels/mid-operation bans
  - [ ] test multiple removal sessions - should this be set and forget or come back and remove n per day?
    - [ ] how long does auth last for? set and forget is easier on people
      - [ ] what if someone wants to cancel?
      - [ ] provide before lists & lists unfollowed 

- [x] : yeh it werks
- [ ] ✍️: currently working manually/locally, but needs to be automated
- [ ] : got notes but nothin' that works yet
- ^ i said everything above in a nice person voice, ok?? saying NO to web site dis course


<!---
username-garb0/username-garb0 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
