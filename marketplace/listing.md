# MIDIFire — Marketplace listing

## Submission fields

- **Product name:** MIDIFire
- **Category:** Music
- **Price:** Free
- **Platform:** Windows
- **Author / organization:** Koop
- **Support URL:** https://github.com/ibanman555/MIDIFire/issues
- **Setup guide:** https://github.com/ibanman555/MIDIFire#readme
- **Source code:** https://github.com/ibanman555/MIDIFire

## Description — paste this into Maker Console

MIDIFire turns Elgato Stream Deck keys into a flexible MIDI controller for Windows. Send commands to DAWs, software instruments, synthesizers, guitar processors, lighting, show-control software, and physical or virtual MIDI ports. It supports Note On/Off, Control Change, Program Change, raw MIDI, and System Exclusive (SysEx).

Add the Fire MIDI action to a key, choose an output, select a message type, and enter the values. Settings save automatically with each key.

Trigger DAW transport, record, markers, mute, solo, automation, presets, and other functions. Raw mode can send button-style HUI or Mackie Control/MCU message bytes when supported by the DAW. MIDIFire sends commands; it does not emulate a complete bidirectional control surface.

Route MIDIFire into optional Bome MIDI Translator for workflows beyond MIDI. Translate messages into keystrokes, mouse actions, application focus, macros, logic, and timed actions—for example, selecting a tab or clicking a control with no MIDI mapping or useful shortcut.

Features include separate press/release messages, raw hexadecimal data, SysEx, automatic Note Off or CC value 0 on release, and optional success/error feedback.

Includes one Fire MIDI action. Requires Windows 10+, Stream Deck 6.9+, and a Windows MIDI output. Bome MIDI Translator is optional and sold separately.

MIDIFire is an independent project and is not affiliated with or endorsed by Elgato. Stream Deck is a trademark of Elgato.

## Release notes — 1.1.5

Renamed the plugin to MIDIFire and refreshed the Marketplace presentation. Corrected and synchronized the five-pin MIDI DIN artwork across the Stream Deck key, app icon, category icon, thumbnail, and demo media. Updated the gallery to keep all text centered and contained within its panels. Includes MIDI Note, CC, Program Change, raw MIDI, and SysEx support; selectable Windows MIDI outputs; optional press/release messages; and visible success/error feedback.

## Submission checklist

- Upload `com.koop.streamdeck-midi.streamDeckPlugin` as the product file.
- Upload `thumbnail.png` as the 1920 × 960 thumbnail.
- Upload all three `gallery-*.png` files as gallery items.
- Upload `app-icon-288.png` as the 288 × 288 app icon.
- Email `MIDIFire-Demo.mp4` to `maker@elgato.com` with the Marketplace review request.
- Confirm that the Maker Console organization name is exactly `Koop`, matching the manifest Author field.
- In the **Versions** tab, choose **Submit new version**. Do not upload this file through the rejected 1.1.4 revision dialog.
