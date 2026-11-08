# Changelog

## Unreleased

## Etch 1.0.2 — 08-Nov-2026
- Free plan limits: 15 tag source lookups, 5 exports, 3 Check-up fixes, 3 select-all duplicates, 3 statistics copies and 3 Compare copy-alls a day, and up to 8 action groups. Counted by the engine (a reload can't reset them), back to full at local midnight; a warning when one is left, then Etch Pro opens on that feature with today's allowance as coloured meters. Pro, owner and developer Macs have no limits. Editing, saving, renaming, covers, actions, converters, filters and playlists stay unlimited for everyone.
- Check for updates: reads the feed (ipconfig.co.network, then GitHub), shows coloured release notes, downloads with a progress bar and a step-by-step log, checks the SHA-256, the signature and that the new Etch is signed by the same identity, then swaps itself and reopens. A quiet daily check can be turned off; any version can be skipped.
- Etch Pro: plans from the dashboard, sign-in by emailed code, redeem codes, subscriptions (cancel at period end) and Macs on the plan. Licences are Ed25519-signed, bound to this Mac and work offline until they expire. The owner's Mac is Pro by itself. Everything Mp3tag-class stays free; Pro adds the batch tools.
- About Etch now has tabs: Etch, The creator (photo, experience, education, skills, NewsCraft World Report), Recommended apps (live from the dashboard, each with its Pour command) and Licences.
- A Pro chip on the toolbar; Etch Pro, About the Creator and Recommended Apps in the menus; 19 new sounds, each with its own drawing; 15 new drawn icons.

- First release of Etch, a small, fast audio tag editor for Macs with Apple silicon.
- Reads and writes tags in MP3, AAC/M4A/MP4, FLAC, Ogg Vorbis, Opus, Speex, WMA, Monkey’s Audio, Musepack, WavPack, True Audio, WAV, AIFF, DSF, DSDIFF and Matroska/WebM — ID3v1, ID3v2.3/2.4, APEv2, Vorbis comments, MP4, ASF, RIFF INFO; custom fields and multiple values kept.
- Batch editing in the tag panel with “< keep >” for mixed values; editing right in the list; Extended Tags for every field.
- Converters: Tag → Filename (with folders), Filename → Tag, Filename → Filename, Text file → Tag, Tag → Tag, and Auto-numbering — each with a live preview.
- Format strings with %fields%, file information, 67 $functions, [optional parts] and 'literal text'.
- Action groups with 19 action types (format, replace, regular expressions, case, guess values, split, merge, remove fields, import text, covers in and out, adjust covers, fix text encoding, playlists, export), quick actions and previews.
- Tag sources: MusicBrainz, Discogs and Apple Music, with track pairing and cover download.
- Covers: view, add, replace, reorder, resize, square, crop, convert, export, copy; thumbnails in the list.
- Filter with HAS, IS, MATCHES, GREATER, LESS, EQUAL, MISSING, PRESENT, AND, OR, NOT.
- Exports with templates ($loop, one file per album or folder), playlists (.m3u8, generator, automatic), copy as text.
- Undo for saves and renames, remove tags by type, ID3v2.3/2.4 and ID3v1 choices, keeps file dates if asked.
- Drop folders on the window or the Dock icon, “Open With” from Finder, Mp3tag-style /fp: /fn: /add start-up arguments.
- Every action has its own sound and self-drawing picture; light and dark themes; start-up animation.
