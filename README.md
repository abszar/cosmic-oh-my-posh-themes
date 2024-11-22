# Cosmic Theme for Oh My Posh

A modern, space-inspired prompt theme for Oh My Posh with a clean two-line layout and cosmic color scheme.

cosmic
![cosmic](https://github.com/user-attachments/assets/38ce4eef-9971-4b08-a173-4183ea342e5f)
cosmic V2
![cosmic V2](https://github.com/user-attachments/assets/b6df63cf-78ec-472d-a62a-140c825a0f27)

## Prerequisites

Before installing the theme, make sure you have Oh My Posh installed. For Windows installation instructions, visit:
[Oh My Posh Windows Installation Guide](https://ohmyposh.dev/docs/installation/windows)

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
oh-my-posh init pwsh --config "C:\Program Files (x86)\oh-my-posh\themes\cosmic.omp.json" | Invoke-Expression
# or
oh-my-posh init pwsh --config "C:\Program Files (x86)\oh-my-posh\themes\cosmic_v2.omp.json" | Invoke-Expression
