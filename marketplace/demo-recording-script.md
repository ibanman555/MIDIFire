# MIDIFire functional demo recording

Record a continuous 30–60 second video. A phone recording that clearly shows both the Stream Deck and computer screen is ideal because it proves the physical key is triggering the MIDI messages. A screen recording is also acceptable if the key press and resulting log activity are unambiguous.

## Prepare

1. Open Stream Deck and place **MIDIFire → Fire MIDI** on a key.
2. Select a Bome virtual MIDI port as the **MIDI Output**.
3. Open Bome MIDI Translator and display its MIDI event log.
4. Configure the MIDIFire key as a Note message with Note Off on release, or use Raw MIDI with separate press and release values.
5. Set MIDIFire feedback to **Success and errors**.

## Record this sequence

1. Show the Stream Deck Property Inspector with **MIDIFire**, **Fire MIDI**, the selected Bome port, and the configured message visible.
2. Show the Bome MIDI log beside it or move the camera so the log is clearly readable.
3. Press and hold the Stream Deck key. Show the Note On or raw press bytes arriving in Bome.
4. Release the key. Show the Note Off or raw release bytes arriving in Bome.
5. Briefly show the green success feedback on the Stream Deck key.
6. Optionally switch the message type to **Raw MIDI / SysEx**, enter a complete message ending in `F7`, press the key, and show the SysEx bytes in Bome.
7. End on a clear view of MIDIFire in Stream Deck and the received messages in Bome.

## Recommended narration

“This is MIDIFire version 1.1.5 running in Stream Deck on Windows. The Fire MIDI action is assigned to this key and is sending to a Bome virtual MIDI port. Pressing the key sends the configured press message, and releasing it sends the release message. The received MIDI bytes are visible in Bome's event log. MIDIFire also supports Note, Control Change, Program Change, raw MIDI, and SysEx messages.”

## Export

- Filename: `MIDIFire-Functional-Demo.mp4`
- Format: MP4
- Keep the text and MIDI log legible.
- Do not edit out the transition between the physical key press and the log response.
- Attach this file directly to the email to `maker@elgato.com`.
