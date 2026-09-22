# MIDIFire 1.1.5 Marketplace resubmission

## Important version choice

Submit **1.1.5 as a new version** in Maker Console. Do not select **Revise version** on the rejected 1.1.4 entry. The plugin manifest reports version `1.1.5.0`, so Maker Console will reject that package if it is uploaded as a revision of 1.1.4.

If the existing Maker Console product title still says **Koop MIDI**, ask `maker@elgato.com` to rename the product to **MIDIFire**. Uploading the plugin does not change the Maker Console product title. The rename request is included in `reviewer-email.txt`.

## Product identity

- Marketplace name: **MIDIFire**
- Plugin name shown in Stream Deck: **MIDIFire**
- Action name: **Fire MIDI**
- Version: **1.1.5** (`1.1.5.0` in the plugin manifest)
- Maker / author: **Koop**

The internal identifier `com.koop.streamdeck-midi` remains unchanged so existing Stream Deck installations and assigned actions continue to work. It is not the public product name.

## Files to upload

- Plugin: `com.koop.streamdeck-midi.streamDeckPlugin`
- App icon: `app-icon-288.png`
- Thumbnail: `thumbnail.png`
- Gallery 1: `gallery-1-midi-messages.png`
- Gallery 2: `gallery-2-raw-sysex.png`
- Gallery 3: `gallery-3-feedback.png`

All Marketplace images use the required dimensions:

- App icon: 288 × 288 PNG
- Thumbnail: 1920 × 960 PNG
- Gallery images: 1920 × 960 PNG

## Maker Console steps

1. Open the existing product in Maker Console. If its title is still **Koop MIDI**, keep using that product record for now and request the rename by email.
2. Replace the description with the text under **Description — paste this into Maker Console** in `listing.md`.
3. Open **Media** and replace the app icon, thumbnail, and all three gallery images with the files listed above.
4. If the old gallery order remains, remove all old gallery items and add the new files in numerical order.
5. Open **Versions** and select **Submit new version**.
6. Upload `com.koop.streamdeck-midi.streamDeckPlugin`.
7. Enter version 1.1.5 release notes from `listing.md`.
8. Submit the new version for review.
9. Record the functional demonstration described in `demo-recording-script.md`.
10. Email that recording to `maker@elgato.com` as `MIDIFire-Functional-Demo.mp4`, using `reviewer-email.txt` as the message.

`MIDIFire-Demo.mp4` is a Marketplace-style preview slideshow. It may be used as optional promotional media, but it does not replace the functional demonstration requested by the reviewer.

## Final checks

- The Maker Console product title says **MIDIFire**, not Koop MIDI.
- The new entry says version **1.1.5**.
- The description begins with plain, unformatted text.
- Three new gallery images are visible and all text remains inside its panels.
- The functional demo visibly shows a configured action, a key press/release, and the resulting MIDI bytes in Bome's log.
- `MIDIFire-Functional-Demo.mp4` is attached to the reviewer email.
