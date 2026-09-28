# Halloween

Optional Halloween mod for Tiny Engineer: a pumpkin head, a lamp, and cauldron pieces. Printable parts and Fusion source are under [`3d_models/`](3d_models/).

## Audio

Alternate speaker clips are in [`assets/`](assets/). The set replaces `welcome`, `attention`, `error`, and `abort`. `bell` and `dead` stay the stock files. Transcripts and cue marks are in [`assets/README.md`](assets/README.md).

Build and flash this overlay with `custom_audio_mod = halloween` in [`platformio.ini`](../../platformio.ini), then `pio run -t upload`. See [docs/flash.md](../../docs/flash.md).
