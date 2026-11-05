# Steam games on YouTube · October 2026: method

How the numbers in the October 2026 report were made. The report itself is at [gamecontour.com/reports/2026-10](https://gamecontour.com/reports/2026-10).

## Window and dataset

- **Window:** 1–31 October 2026, UTC days.
- **Channels:** 13,080 gaming YouTube channels tracked by GameContour on 31 October. This is a curated set of channels, not all of YouTube; every number in the report describes these channels only.
- **Videos:** videos those channels published from 1 to 31 October. 93,180 of them were matched to a Steam game, from 8,446 channels, covering 6,966 games.
- **Steam data:** our copy of the Steam catalog (release dates, prices, tags).

The report measures attention on YouTube: which games these channels made videos about, and how many views those videos got. It does not measure sales, wishlists, player counts or YouTube as a whole.

## Matching videos to games

Each video is matched to the Steam game it covers. A video counts as coverage when it has exactly one matched Steam game and the match is either automatic or confirmed by a reviewer. Videos matched to more than one game, or with an unclear match, are left out.

## Views on new videos

"Views on October videos" (views on new videos) are the views gained by 31 October on videos published 1–31 October. Views on older videos are not counted, so a game does not rank high because its back catalogue keeps earning views.

We read view counts for each video once a day and add up the daily gains inside the window.

- **Late-month videos.** A video published on 30 October has had about one day to gain views; one published on 1 October has had a month. Games covered mostly at the end of the month are understated.
- **Snapshot cadence.** From 29 October, videos older than 14 days that gain under 500 views a day are read weekly instead of daily. Some October videos had no reading on 31 October, so a small number of views fall outside the window. We estimate this at under 0.3% of all views on October videos. Day-7 views and launch-week counts are not affected.

## Spike

A game is marked as a Spike when more than 60% of its views on October videos come from one video. A Spike means one creator's hit, not broad coverage.

## Watched more than the channel's usual

For each video we take its views 7 days after publishing (the reading closest to day 7, within a day either side) and divide them by the median day-7 views of that channel's videos. A ratio of 1.5× means the video got 50% more views in its first week than that channel usually does.

- Only channels with at least 3 videos with a day-7 count are included.
- The channel's median uses its videos published from early September, the start of our daily readings.
- Day 7 has to fall inside the window, so this uses only videos published 1–25 October.
- A game's ratio is the median over its videos. Games are ranked only if at least 10 channels covered them.

## Release stage

A game is **unreleased** if it has no release date or a release date after 31 October. Demos and playtests are counted with unreleased games.

Our copy of the Steam catalog can lag behind recent releases. All 73 games marked unreleased or demo among the top 500 by views on October videos were checked on their Steam store pages on 2 November 2026. Seven had already been released in October and were corrected. Corrected dates are listed below. Games outside the top 500 were not checked.

| Steam app | Game | Release date (Steam) |
|---|---|---|
| 5341070 | The Wrong Way | 21 Oct 2026 |
| 5372620 | Pikabuu: Home | 24 Oct 2026 |
| 3370490 | Giggleland | 26 Oct 2026 |
| 4732690 | Arknights: Endfield | 15 Oct 2026 |
| 3055670 | Risk of Rain 2: Hallowed Concepts | 8 Oct 2026 |
| 4252340 | CPM 2 | 8 Oct 2026 |
| 4977840 | Otherside Tapes: Favela | 22 Oct 2026 |

## Release year

Games are grouped by release date: unreleased or demo, released in October 2026, rest of 2026, 2024–25, 2020–23, before 2020. Shares are of all views on October videos.

## Channel language

Channel language is the language we detect for each channel. 4.1% of views on October videos came from channels with no detected language; they are left out of the language card. The language card ranks games by views, so a game covered by a few large channels can lead a language.

## Price bands

Price bands use each released game's current USD price on Steam: free, under $10, $10–20, $20–40, $40 and over. Games without a USD price are left out. Unreleased games are left out.

For each band we compare views per video with the average for all released games. A band at 1.79× got 79% more views per video than average.

To check that a band's result is not one creator's hit, we recalculate it without the band's single most-viewed video, and again without the top 1% of videos overall. For games under $10, the ratio is 1.79× with all videos, 1.84× without the band's top video, and 1.45× without the top 1% of videos.

## Horror

A game counts as horror when Horror is among its top 5 Steam tags. The share of channels is out of the channels that made at least one video about a Steam game in October.

## Launch week

For games released 1–24 October (so each has 7 full days after release inside the window):

- **Launch-week channels and videos:** videos published in the 7 days from the release date.
- **Videos before release:** videos published in the 14 days before the release date, counted from all of the game's videos, including those from September.

Both windows have a fixed length around each game's own release date.

## Same views, very different coverage

Pairs of games from the top 200 by views on October videos with views within 12% of each other, where one game had at least 10 times as many channels as the other. Four pairs were chosen by hand, after checking that the top video of each narrow-side game is about that game.

## What the report does not measure

- Sales, wishlists, revenue or player counts.
- YouTube as a whole: only the 13,080 tracked channels.
- Other platforms, such as Twitch or TikTok.
- Change over time. October is the first report; from November, each report compares with the month before.

## Data

The underlying data (per-video views, video and channel identifiers, the matched dataset) is not published. The report shows aggregate findings only.

The numbers were computed once from a data export taken on 1 November 2026 and will not be revised.

## Questions

If you want a specific game or tag checked, or think a match is wrong, contact us through [gamecontour.com](https://gamecontour.com).
