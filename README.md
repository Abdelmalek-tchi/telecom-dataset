# Telecom Non-Periodic Dataset

The dataset is split into two RAR volumes due to file size constraints.

- 	elecom_non_periodic_dataset.part01.rar (24 MB)
- 	elecom_non_periodic_dataset.part02.rar (2.6 MB)

Download **both** files, then use one of the methods below to extract.

---

## Method 1 — WinRAR (GUI)

1. Install [WinRAR](https://www.win-rar.com/)
2. Place both .part01.rar and .part02.rar in the **same folder**
3. Right-click 	elecom_non_periodic_dataset.part01.rar → **Extract Here**
4. WinRAR automatically detects the second volume

## Method 2 — Command-line RAR

`ash
rar x telecom_non_periodic_dataset.part01.rar
`

## Method 3 — 7-Zip

1. Install [7-Zip](https://www.7-zip.org/)
2. Right-click 	elecom_non_periodic_dataset.part01.rar → **7-Zip** → **Extract Here**

Or via CLI:

`ash
7z x telecom_non_periodic_dataset.part01.rar
`

## Method 4 — Merge manually, then extract

Use this if your RAR tool does not support multi-volume archives:

`ash
# Linux / macOS
cat telecom_non_periodic_dataset.part01.rar telecom_non_periodic_dataset.part02.rar > merged.rar
`

`powershell
# Windows PowerShell
Get-Content telecom_non_periodic_dataset.part01.rar, telecom_non_periodic_dataset.part02.rar -Encoding Byte -Raw | Set-Content merged.rar -Encoding Byte
`

Then extract merged.rar with any tool that handles .rar files.

---

**Output:** 	elecom_non_periodic_dataset.csv (~398 MB)