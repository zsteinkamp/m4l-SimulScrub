# SimulScrub (Max for Live)

- `SimulScrub.amxd` is an unfrozen `.amxd` (32-byte header + patcher JSON); `voice.maxpat` is the `poly~` voice (one per slice). Each voice uses `grooveduck2`, the Cycling '74 example abstraction (Max `Examples/sequencing-looping/audio-rate-sequencing-looping/lib/`), not a file in this repo.
- GitHub releases of this repo are consumed by the `plugins` website (`../plugins`), so only publish M4L device releases here.
- The VST3/AU port lives in a separate repo, `../juce-SimulScrub` ([zsteinkamp/juce-SimulScrub](https://github.com/zsteinkamp/juce-SimulScrub)). Its `CLAUDE.md` documents the DSP behavior derived from this patch; keep the two in sync when changing the device's audio behavior.
