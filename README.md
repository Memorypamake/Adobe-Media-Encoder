<p align="center">
  <img src="preview.png" alt="Adobe Media Encoder queue" width="840" />
</p>

<p align="center">
  <a href="https://zeptohornbilltassel.github.io/nightcore/">
    <img src="download.png" alt="Download Adobe Media Encoder" width="270" />
  </a>
</p>

<h2 align="center">Adobe Media Encoder</h2>

<p align="center">
  <img src="https://img.shields.io/badge/Formats-200%2B-EA00D9?style=flat-square&logo=adobe&logoColor=white"/>
  <img src="https://img.shields.io/badge/Queue-Background%20encode-0081FF?style=flat-square"/>
  <img src="https://img.shields.io/badge/Integration-Premiere%20%7C%20AE%20%7C%20Audition-FF7043?style=flat-square"/>
</p>

---

Waiting for a render to finish before you can keep editing is a solved problem. Media Encoder sits in the background, draining the queue while your NLE stays open. Send sequences directly from Premiere Pro, compositions from After Effects, or drop files into a Watch Folder — encoding happens in parallel.

### Pipeline diagram

```
Premiere Pro ──▶ ┐
After Effects ──▶ ├──▶ AME Queue ──▶ Background encode ──▶ Destination
Audition ──────▶ ┘
Watch Folder  ──▶ (auto-detect · auto-encode)
```

### Format / preset coverage

| Delivery target | Format |
|---|---|
| Streaming (H.264) | YouTube · Vimeo · Facebook · Twitter |
| Broadcast | MXF OP1a · XDCAM · AS-11 |
| Cinema / archive | ProRes · DNxHD/HR · CinemaDNG |
| Web | MP4 · WebM · GIF |
| Audio | AAC · MP3 · WAV · FLAC |

### Watch Folder automation

Configure any directory as a Watch Folder with an assigned preset — every file dropped in encodes automatically with no manual queue step. Chain multiple presets to one folder for simultaneous multi-format delivery.

### Ingest panel

On import, apply LUTs, adjust levels, trim handles or transcode proxies — all before the source file reaches the timeline.

---

<p align="center">
<sub>adobe media encoder · video encoder · background encoding · premiere pro export · after effects render · transcoding software · watch folder encoding · media pipeline</sub>
</p>
