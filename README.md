![Version](https://img.shields.io/static/v1?label=voice-in-plus-contractions&message=0.3&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

# Expansions of English contractions for Voice-In Plus

## Purpose
Automatically expand English contractions when using Voice In Plus for dictation.
This supports converting informal speech into formal prose.

## Disclaimer
This is a programming tool, not an educational tool.


## Voice In vs Voice In Plus
Voice In is a free Google Chrome plugin that supports dictation in web page text areas.
This is where I draft most of my writing these days before pasting it into a final document.
Voice In provides a Notepad for dictation if you need an alternative to write-honey.com or 750words.com.
It also works in the web version of Grammarly, Overleaf, Jupyter, and Colab.
The word error is about 2-4 percent, better than most alternative dictation software.
It does not do long hallucinations like chatbots, which waste my time.

Voice In Plus requires a modest subscription fee.
It adds support for custom commands.

## Library contents

- 186 common and not-so-common English contractions mapped to their expansions.

## Format of the library
The file format is comma-separated values (CSV).
The first column has the voice commands in lowercase.
The second column contains the inserted text and any action commands in angle brackets.
Multi-line text fragments are possible via the newline command (`\n`).

## Installation
1. Right-click on the plugin icon and select `Options`.
2. This action opens the Voice-in options page.
3. Click on the `bulk add` button. A simple window with a plain text area will open.
4. Open the CSV file in a text editor like VS Code. Select all, copy, and paste it into the bulk add window's text area.
5. Click the `add commands` button below the text area. The new commands are now available.

## Use with other software

You can use this CSV file with other software to replace contractions with their expansions.

## Related sites
- [Search for Voice In in the Chrome Store](https://chromewebstore.google.com/)
- [Full library of commands for Voice In Plus](https://github.com/MooersLab/voice-in-plus-commands)
- [Voice computing on MooersLab landing page](https://github.com/MooersLab/#voice-computing)
- [expand-contractions-el for Emacs on MooersLab](https://github.com/MooersLab/expand-contractions-el)

## Update History

|Version      | Changes                             | Date            |
|:-----------:|:-----------------------------------:|:---------------:|
| Version 0.1 | First posted 96 contractions.       | 2024 January 16 |
| Version 0.2 | Expanded to 186 contractions.       | 2024 April 5    |
| Version 0.3 | Expanded to 243 contractions.       | 2026 Octiber 25 |

## Funding sources
- NIH: R01 CA242845
- NIH: R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel)
- NIH: P20 GM103640 and P30 GM145423 (PI: A. West)


