# Cosmic Theme for Oh My Posh

A modern, space-inspired prompt theme for Oh My Posh with a clean two-line layout and cosmic color scheme.

## Variants

- `cosmic.omp.json`: Shows current folder name for cleaner output
- `cosmic_v2.omp.json`: Shows full path for detailed navigation

## Features

- 🚀 Clean two-line layout with rounded ends
- 📂 Smart path display (folder/full-path variants)
- 🔄 Git status integration with branch and file indicators
- ⏱️ Command execution time tracking
- 📅 Date and time display
- 🎨 Space-inspired color scheme
- ➡️ Gradient command prompt arrows

## Installation

Choose your preferred variant and add to your PowerShell profile:

```powershell
oh-my-posh init pwsh --config ~/Desktop/themes/cosmic.omp.json | Invoke-Expression
# or
oh-my-posh init pwsh --config ~/Desktop/themes/cosmic_v2.omp.json | Invoke-Expression
