# Simply Live Setlist

A phone-friendly page that shows each gig's setlist with a reference link for every song.

**Open it:** https://davytan07.github.io/simplylivesetlist/

It reads two Google files live every time it opens. Nothing needs updating here when a setlist changes.

- **Setlist doc**: the songs, keys and singers for each date
- **Repertoire sheet** ("SIMPLY LIVE Repertoire" tab): the `LINKS` column, plus any links in the columns after it

Both files must stay shared as *Anyone with the link can view*. To point the page at different files, change `SOURCES` at the top of the script in `index.html`.

Songs highlighted in yellow have no link yet. Either the song isn't in the sheet, or its row has no link. Add one to the sheet and it shows up the next time someone opens the page.

`t2s.js` is a Traditional → Simplified Chinese character table generated from [OpenCC](https://github.com/BYVoid/OpenCC) (Apache-2.0). It lets 後來 in the doc match 后来 in the sheet.
