# Collision

A lightweight, privacy-first tool for digital technicians to scan Capture One session folders and detect duplicate frame numbers across directories — before they become a problem in delivery.

Vibe coded by [@lightisbeauty](https://www.instagram.com/lightisbeauty/)

## ⬇ Download & Run

1. Click `Collision.html` above → then click **Raw** → **Save As** to download
2. Double-click the saved file to open it in your browser
3. No internet required — runs entirely on your machine

> **Recommended GitHub repo description:**
> *Detect counter collisions and duplicate frame numbers across directories in Capture One sessions — runs locally, no install required*

---

## What it does

On fast paced jobs requiring file re-naming and a mix of card/tethered shooting, it's easy to accidentally lose track of the filename counter across various directories and end up with counter collisions — duplicate trailing numbers spanning multiple folders (e.g. `shot02_flatlay_2261.raf` and `shot12_stadium_2261.raf`). This tool surfaces those conflicts instantly.

- Scans all subfolders recursively
- Detects duplicate trailing frame numbers across any RAW format
- Groups consecutive duplicate runs by directory pairing to keep the report readable
- Lets you exclude specific directories before running the check (test shots, pre-light, etc.)
- Trash folders are always excluded automatically
- Cross-format collisions are flagged intentionally — a `1002.NEF` and a `1002.CR2` in different folders will still surface as a collision, since shared frame numbers can cause conflicts regardless of format

---

## Supported RAW formats

Canon, Nikon, Sony, Fuji, Phase One, Leica, Hasselblad, Olympus, Panasonic, Pentax, Samsung, Sigma, Mamiya, Kodak, Minolta, and more.

Full list: `CR2 CR3 NEF NRW ARW SRF SR2 RAF DNG ORF RW2 PEF SRW X3F 3FR MEF MOS IIQ RWL RAW RWZ KDC DCR MRW RW1 CAP EIP FFF MDC`

---

## How to use

1. Double-click `Collision.html` to launch in your default browser
2. Click **Select Session Folder** and point it at your Capture One session root
3. Check any directories you want to exclude from the scan
4. Click **Run Check**
5. Review duplicate groups and the directory report below

---

## Privacy

This app does **NOT** need or use internet access or transmit **ANY** information online. By design it only runs locally to ensure privacy and accessibility. No data ever leaves your machine.

---

## Browser compatibility

| Browser | Status |
|---|---|
| Safari | ✅ Tested |
| Firefox | ✅ Tested |
| Chrome | ✅ Tested |
| Edge | ✅ Should work |

---

## GitHub Topics

Add these topics to the repo for maximum discoverability:

`capture-one` `captureone` `duplicate` `counter` `collision` `digitech` `photography` `raw` `filename` `tethering` `digital-tech` `photo-production`

---

## Keywords

*Capture One duplicate finder · duplicate frame numbers · filename counter conflict · counter collision · Capture One session · RAW file naming · digital tech tool · tethered shooting*

---

## Changelog

### v1.1
- Added **Highest Counter File** stat panel — surfaces the filename with the highest trailing frame counter across all scanned RAW files
- Added **Directories involved** summary panel at the top of the directory report, listing all involved folder names with their paths and copy-path buttons
- Improved directory report layout: flattened to one row per directory with locked column alignment for Directory, Path, and Copy Path
- Renamed "Full Path" column label to "Path"

### v1.00
- Initial release under the Collision name
- Recursive RAW file scanning
- Duplicate frame number detection
- Directory exclusion panel
- Consecutive range collapsing
- Copy path to clipboard
- No-dupes state handling
- Embedded logo

---
