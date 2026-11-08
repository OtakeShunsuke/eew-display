# EEW display (緊急地震速報 表示)

A full-screen 緊急地震速報（予報・警報） display meant to stay open on a Chromecast.
The page connects straight to the Wolfx JMA EEW WebSocket, so no computer has to stay on
once the page is loaded.

- Map: JMA earthquake forecast regions (細分区域), coloured by expected intensity.
  Regions JMA lists in the report use JMA's value (white outline); the rest are a simple estimate.
- P/S wave circles, follow-up report handling, original alert sounds, pre-recorded announcements.
- Demos: `?demo=replay` (real 2026-11-08 Kumamoto sequence, labelled 再現) and `?demo=drill` (labelled 訓練).

For reference only. Do not rely on it instead of official alerts.

Data: EEW feed by [Wolfx](https://wolfx.jp/) (JMA data); region shapes from
[JMA GIS data](https://www.data.jma.go.jp/developer/gis.html); prefecture outlines from
[dataofjapan/land](https://github.com/dataofjapan/land).
