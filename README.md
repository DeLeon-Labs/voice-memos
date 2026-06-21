# Voice Memo

Voice Memo is a planned DeLeon Labs plugin for capturing spoken thought and
preparing it for deliberate use elsewhere without losing its connection to the
original audio.

## Status

Foundation. The product charter is defined; implementation has not started.

## Product boundary

Voice Memo owns recording, playback, transcript generation and correction, and
time-aligned audio references. It does not treat uncertain transcripts as
authoritative or assemble ecosystem-wide context.

## Ecosystem relationship

Voice Memo provides authorized audio references, transcript segments,
timestamps, and confidence metadata. Lighthouse can package them; Note Actions
can transform selected transcript material. The canonical charter and shared
contracts live in the [DeLeon Labs Manual](https://github.com/DeLeon-Labs/lab-manual).

## Next milestone

Prototype capture-to-transcript handoff with stable segment references,
correction metadata, and explicit source revocation behavior.
