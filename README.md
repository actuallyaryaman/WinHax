# WinHax
My go to windows tips and tricks.

---
## Adoptium JDK

https://adoptium.net/

## Windows Registry Commands

To reset the Windows Explorer context menu to default:

`reg.exe add "HKCU\Software\Classes\CLSID{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve
`
## HEVC Video Extension

https://app.box.com/s/rozwl3zsx6o90xw2568by61fhp3z3icw

## Prism Launcher Local Acc Bypass (Just Run the launcher once and close before executing)

`echo {"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "MSA"}],"formatVersion": 3} > %appdata%/PrismLauncher/accounts.json`

## Windows LTSC Official Download links:

https://massgrave.dev/windows_ltsc_links

## Activate Windows Using Massgrave

`irm https://get.activated.win | iex
`
## Enable MS Store in LTSC versions (Run pws as admnin)

`wsreset -i` or download from here https://github.com/stdin82/htfx/releases/tag/v0.0.24
