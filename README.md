![Version](https://img.shields.io/static/v1?label=voice-in-plus-contractions&message=0.2&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

# voice-in-plus-contractions:

## Purpose
Expand English contractions automatically when using Voice In Plus for dictation.
This supports the conversion of informal speech into formal prose.

## Disclaimer
This is a programming tool, not an educational tool.


## Voice In vs Voice In Plus
Voice In is a free plugin for Google Chrome that supports dication in the text areas of web pages.
This is where I draft most of my writing these days before it is pasted into a final document.
Voice In provides a Notepad for dication if you still need to get a favorite alternative like 750words.com.
It also works in Overleaf, Jupyter, and Colab.
The word error is about 2-4 percent, better than most alternative dictation software.
It does not do long hallucinations like chatbots, which I find to be annoying and a waste of my time.

Voice In Plus requires a modest subscription fee.
It adds support for custom commands.

## Library contents

- 186 common and not so common English contractions mapped to their expansions.

## Format of the library
The file format is comma-separated values (csv).
The first column has the voice commands in lowercase.
The second column has the text inserted and any action commands executed in between angular braces.
Multi-line text fragments are possible via the newline command (`\n`).

## Installation
1. Right-click on the plugin icon and select `Options`.
2. This act opens the Voice-in options page.
3. Click on `bulk add` button. A simple window with a plain text area will open.
4. Open the csv file in a text editor like VS Code. Select all, copy, and paste into the text area of the bulk add window.
5. Click the `add commands` button below the text area. The new commands are available for use.

## Related sites
- [Search for Voice In in the Chrome Store](https://chromewebstore.google.com/)
- [Full library of commands for Voice In Plus](https://github.com/MooersLab/voice-in-plus-commands)
- [Voice comoputing on MooersLab landing page](https://github.com/MooersLab/#voice-computing)

## Update History

|Version      | Changes                             | Date            |
|:-----------:|:-----------------------------------:|:---------------:|
| Version 0.1 | First posted 96 contractions.       | 2024 January 16 |
| Version 0.2 | Expanded to 186 contractions.      | 2024 April 5    |


## Funding sources
- NIH: R01 CA242845
- NIH: R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel)
- NIH: P20 GM103640 and P30 GM145423 (PI: A. West)


