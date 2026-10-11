# Writers Block releases

Writers Block is a free Mac app for screenwriters. Click an empty paragraph in
Final Draft, press Command-Option-D and talk through the scene. Press it again
and the scene lands at your cursor as Final Draft paragraphs: scene heading,
action, character, parenthetical and dialogue. Speech recognition and
formatting both run on your Mac.

Download it from https://mindinmotionsoftware.com/#writers-block or from
[Releases](https://github.com/MIM18-code/writers-block-releases/releases).

This repository holds the signed and notarized disk images, their checksums
and the build recipe for the bundled FFmpeg. It has no app source.

## Requirements

- An Apple Silicon Mac with macOS 14 Sonoma or later
- About 8 GB free for the two models
- [Ollama](https://ollama.com/download/mac), a free app that runs the writing
  model. The first-launch setup window links to it and downloads the model.

## Licenses

Writers Block is MIT licensed, copyright MindInMotion LLC, and comes without
warranty. The app bundles Python and its packages, each under its own license
(listed inside the app in `Contents/Resources/Licenses/`), and an audio-only
FFmpeg under the LGPL 2.1 or later. Each release attaches
`WritersBlock-<version>-ffmpeg-build.tar.gz` with the script and pinned sources
that build that FFmpeg.
