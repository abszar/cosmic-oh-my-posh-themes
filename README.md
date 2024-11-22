# Cosmic Theme for Oh My Posh

A modern, space-inspired prompt theme for Oh My Posh with a clean two-line layout and cosmic color scheme.

cosmic
![cosmic](https://github.com/user-attachments/assets/1a58ae40-74d3-41b0-ab73-19c28996898f)
cosmic V2
![cosmic V2](https://github.com/user-attachments/assets/89b598ff-bfae-4215-9266-ba0cae07616a)
cosmic V2
![cosmic V3](https://github.com/user-attachments/assets/593125e5-3e28-4327-9c97-3b3b250f1918)


## Prerequisites

Before installing the theme, make sure you have Oh My Posh installed. For Windows installation instructions, visit:
[Oh My Posh Windows Installation Guide](https://ohmyposh.dev/docs/installation/windows)

## Variants

- `cosmic.omp.json`: Shows current folder name for cleaner output
- `cosmic_v2.omp.json`: Shows full path for detailed navigation
- `cosmic_v3.omp.json`: Shows path with house icon (🏠), folder icons (📂), and elegant double arrows (»), all properly spaced for maximum readability

## Features

- 🚀 Clean two-line layout with rounded ends
- 📂 Smart path display (folder/full-path/icons variants)
- 🔄 Git status integration with branch and file indicators
- ⏱️ Command execution time tracking
- 📅 Date and time display
- 🎨 Space-inspired color scheme
- ➡️ Gradient command prompt arrows

## Installation

Choose your preferred variant and add to your PowerShell profile:

```powershell
oh-my-posh init pwsh --config "C:\Program Files (x86)\oh-my-posh\themes\cosmic.omp.json" | Invoke-Expression
# or
oh-my-posh init pwsh --config "C:\Program Files (x86)\oh-my-posh\themes\cosmic_v2.omp.json" | Invoke-Expression
# or
oh-my-posh init pwsh --config "C:\Program Files (x86)\oh-my-posh\themes\cosmic_v3.omp.json" | Invoke-Expression
