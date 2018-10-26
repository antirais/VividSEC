# VividSEC

Sublime Text 3 plugin for [SEC](https://simple-evcorr.github.io/) rules.

This plugin provides:

1. basic syntax highlighting
2. basic tab completion
3. snippets for pattern types

Filenames with '.sec' extension are automatically recognized.

### Tab completions

| Rule type             | Tab trigger           |
|:----------------------|----------------------:|
| Calendar              | cal                   |
| EventGroup            | evg                   |
| Jump                  | jump                  |
| Options               | opt                   |
| Pair                  | pair                  |
| PairWithWindow        | pww                   |
| Single                | sin                   |
| SingleWith2Thresholds | sw2                   |
| SingleWithScript      | swscr                 |
| SingleWithSuppress    | swsup                 |
| SingleWithThreshold   | swt                   |
| Suppress              | sup                   |

## Installation

This plugin isn't currently ready to be installed automatically by Package Control.
Please use this GitHub URL to manually add a new repository:

Preferences -> Package Control: Add Repository -> https://github.com/antirais/VividSEC.git

### Alternative installation

1. clone this repository
2. move all files to Sublime Text Packages folder: e.g. ~/.config/sublime-text-3/Packages/VividSEC
3. restart Sublime Text
