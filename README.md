# Transmogrify

Convert files by renaming them.

Transmogrify is a macOS menu bar app that watches folders and converts files when you change the file extension in Finder.

Example:
Rename `photo.png` to `photo.jpg` and the file is converted.

There’s no app window, import step, or export step. Your filesystem is the interface.

---

## Installation

1. Download the latest `.dmg` from the Releases page
2. Open it
3. Drag **Transmogrify** into `/Applications`
4. Launch it once from Applications

After that it lives in the menu bar.

---

## First run

On first launch, Transmogrify will ask which folders it’s allowed to watch.

Only files inside those folders are touched.
You can add or remove folders later from the menu bar.

Nothing is uploaded anywhere. All conversion happens locally.

---

## Troubleshooting

**The app won’t open**
- Make sure it’s in `/Applications`
- If macOS blocks it:
  - System Settings → Privacy & Security
  - Allow Transmogrify
  - Try again

**I don’t see anything**
- There’s no window.
- Look for the icon in the menu bar (top right).

**Renaming doesn’t do anything**
- The file has to be inside a watched folder
- You need to actually change the extension (`.png` → `.jpg`)
- If the contents don’t match the extension, Transmogrify converts the file to match

**Undo**
- Open the menu bar icon
- Use Undo or Conversion History to restore the original file

---

## About this build

This repository hosts a direct-download build for people who don’t want the Mac App Store.

There’s also a Mac App Store version if you prefer sandboxing and automatic updates.

---

## More info

https://transmogrifyapp.com

---

## License

The Transmogrify app itself is proprietary.
Bundled third-party components are licensed separately. See `NOTICE.txt`.