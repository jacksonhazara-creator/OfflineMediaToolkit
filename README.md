# Offline Media Toolkit

22 tools for video, audio, pictures and PDFs in one Windows app. Everything runs on your PC: no files are
uploaded and no internet connection is needed (except for updates).

- **Video:** convert, shrink to a size (e.g. for e-mail), trim with a live preview, video → GIF, subtitles, join files
- **Audio:** video → audio, convert, fix the volume, tags & cover pictures
- **Pictures:** images → PDF, PDF → images, convert / resize (and remove hidden location data), remove backgrounds
- **PDF:** merge, split, compress, passwords, rotate / delete / reorder pages, page numbers & watermarks, extract
  pictures, make scans searchable (text recognition in 11 languages)
- Queue, presets, a watch folder that converts new files by itself, drag & drop, right-click "Open with"
- Three looks: Modern, Performance and iOS (Apple colours, pill buttons, coloured tool icons), each light or dark, with accent colours
- Updates itself

## Install

1. Download **OfflineMediaToolkit-Setup-x.y.z.exe** from [Releases](../../releases/latest).
2. Run it. You don't need administrator rights. Windows may show "Windows protected your PC" because the
   installer has no paid publisher certificate: click **More info**, then **Run anyway**.

## Update

In the app: **Settings → Updates → Update**. It downloads the newest version from this page, installs it and opens
again; your settings, presets and recent jobs are kept. The app also tells you in its log when a new version is
waiting. You only need the installer once.

## Safety

Every update is signed with the publisher's private key. The app refuses any installer that has been changed or
that someone else signed, even if it was uploaded here.

## Requirements

Windows 10 or 11 (64-bit). Everything else is included: .NET, FFmpeg, ImageMagick, Tesseract language data and
an offline background-removal model.

The PDF engine is MuPDF.NET by Artifex Software, Inc., used under the Artifex Community License (non-commercial
use); its license and the other third-party notices are installed with the app.
