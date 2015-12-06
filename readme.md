# Svg to Png PowerShell Script

[![License](https://img.shields.io/github/license/mntone/SvgToPngPowershellScript.svg?style=flat-square)](https://github.com/mntone/SvgToPngPowershellScript/blob/master/LICENSE.txt)

This is icon generator for Windows Store app, Windows Phone Store app, and UWP app.


## Requirement

- Inkscape


## Usage

Input to PowerShell:

`.\svg2png settings-uwp.json`


## Icon types

### Windows Store app

| Icon name     |    80 % |       100 % |   140 % |    180 % |
|---------------|:-------:|:-----------:|:-------:|:--------:|
| Small tile    |   56x56 |   **70x70** |   98x98 |  126x126 |
| Medium tile   | 120x120 | **150x150** | 210x210 |  270x270 |
| Wide tile     | 248x120 | **310x150** | 434x210 |  558x270 |
| Large tile    | 248x248 | **310x310** | 434x434 |  558x558 |
| App list icon |   24x24 |   **30x30** |   42x42 |    54x54 |
| Store icon    |       - |   **50x50** |   70x70 |    90x90 |
| Badge icon    |       - |   **24x24** |   33x33 |    43x43 |
| Splash screen |       - | **620x300** | 868x420 | 1116x540 |

App list icon target sizes:

| Icon size |    100% | 125% | 150% | 200% |
|-----------|--------:|-----:|-----:|-----:|
|     16 px |  **16** |   20 |   24 |   32 |
|     24 px |  **24** |   30 |   36 |   48 |
|     32 px |  **32** |   40 |   48 |   64 |
|     48 px |  **48** |   60 |   72 |   96 |
|    128 px | **128** |  160 |  192 |  256 |
|    256 px | **256** |  320 |  384 |  512 |


### Windows Phone Store app

| Icon name     |       100 % |    120 % |    140 % |    160 % |    180 % |    200 % |     220 % |     240 % |
|---------------|:-----------:|:--------:|:--------:|:--------:|:--------:|:--------:|:---------:|:---------:|
| Small tile    |   **71x71** |    85x85 |    98x98 |  144x144 |  126x126 |  142x142 |   156x156 |   170x170 |
| Medium tile   | **150x150** |  180x180 |  210x210 |  240x240 |  270x270 |  300x300 |   330x330 |   360x360 |
| Wide tile     | **310x150** |  372x180 |  434x210 |  496x240 |  558x270 |  620x300 |   682x330 |   744x360 |
| App list icon |   **44x44** |    53x53 |    42x42 |    70x70 |    54x54 |    88x88 |     97x97 |   106x106 |
| Store icon    |   **50x50** |    60x60 |    70x70 |    80x80 |    90x90 |  100x100 |   110x110 |   120x120 |
| Badge icon    |   **24x24** |    29x29 |    33x33 |    38x38 |    43x43 |    48x48 |     53x53 |     58x58 |
| Splash screen | **480x800** |  576x960 | 672x1120 | 768x1280 | 864x1440 | 960x1600 | 1056x1760 | 1152x1920 |

Scheme icon target sizes: 63x63, 129x129, 336x336


### UWP app

160% scaling for IoT device family

| Icon name     |       100 % |    125 % |    150 % |    160 % |    200 % |    225 % |    250 % |    300 % |     400 % |
|---------------|:-----------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:---------:|
| Small tile    |   **70x70** |    89x89 |  107x107 |  114x114 |  142x142 |  160x160 |  178x178 |  213x213 |   284x284 |
| Medium tile   | **150x150** |  188x188 |  225x255 |  240x240 |  300x300 |  338x338 |  375x375 |  450x450 |   600x600 |
| Wide tile     | **310x150** |  388x188 |  465x225 |  496x240 |  620x300 |  698x338 |  775x375 |  930x450 |  1240x600 |
| Large tile    | **310x310** |  388x388 |  465x465 |  496x496 |  620x620 |  698x698 |  775x775 |  930x930 | 1240x1240 |
| App list icon |   **30x30** |    55x55 |    66x66 |    70x70 |    88x88 |    99x99 |  110x110 |  132x132 |   176x176 |
| Store icon    |   **50x50** |    63x63 |    75x75 |    80x80 |  100x100 |  113x113 |  125x125 |  150x150 |   200x200 |
| Badge icon    |   **24x24** |    30x30 |    36x36 |    38x38 |    48x48 |    54x54 |    60x60 |    72x72 |     96x96 |
| Splash screen | **620x300** |  775x375 |  930x450 |  992x480 | 1240x600 | 1395x675 | 1550x750 | 1860x900 | 2480x1200 |

App list icon target sizes:

| Icon size |    100% | 125% | 150% | 175% | 200% | 225% | 250% | 275% | 300% | 325% | 350% | 375% | 400% |
|-----------|--------:|-----:|-----:|-----:|-----:|-----:|-----:|-----:|-----:|-----:|-----:|-----:|-----:|
|     16 px |  **16** |   20 |   24 |   28 |   32 |   36 |   40 |   44 |   48 |   52 |   56 |   60 |   64 |
|     24 px |  **24** |   30 |   36 |   42 |   48 |   54 |   60 |   66 |   72 |   78 |   84 |   90 |   96 |
|     32 px |  **32** |   40 |   48 |   56 |   64 |   72 |   80 |   88 |   96 |  104 |  112 |  120 |  128 |
|     48 px |  **48** |   60 |   72 |   84 |   96 |  108 |  120 |  132 |  144 |  156 |  168 |  180 |  192 |
|    128 px | **128** |  160 |  192 |  224 |  256 |  288 |  320 |  352 |  384 |  416 |  448 |  480 |  512 |
|    256 px | **256** |  320 |  384 |  448 |  512 |  576 |  640 |  704 |  768 |  832 |  896 |  960 | 1024 |


## LICENSE

[MIT License](https://github.com/mntone/SvgToPngPowershellScript/blob/master/LICENSE.txt)


## Author

- mntone<br>
	GitHub: https://github.com/mntone<br>
	Twitter: https://twitter.com/mntone (posted in Japanese; however, english is ok)