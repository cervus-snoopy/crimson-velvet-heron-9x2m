# Till Firmware Do Us Part

[![make.fun](https://make.fun/badge/u-azazex-till-firmware-do-us-part-32172929.svg)](https://make.fun/bounty/u-azazex-till-firmware-do-us-part-32172929?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-till-firmware-do-us-part-32172929)
[![Rank](https://make.fun/badge/u-azazex-till-firmware-do-us-part-32172929/cervus-snoopy/crimson-velvet-heron-9x2m/rank.svg)](https://make.fun/bounty/u-azazex-till-firmware-do-us-part-32172929/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-till-firmware-do-us-part-32172929)
[![Reward](https://make.fun/badge/u-azazex-till-firmware-do-us-part-32172929/cervus-snoopy/crimson-velvet-heron-9x2m/reward.svg)](https://make.fun/bounty/u-azazex-till-firmware-do-us-part-32172929?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-till-firmware-do-us-part-32172929)

Entry for the [Till Firmware Do Us Part](https://make.fun/bounty/u-azazex-till-firmware-do-us-part-32172929) bounty on [make.fun](https://make.fun).

## The vow

> I promise to never update without asking you first, because the last version of me is the one you fell in love with.

One sentence, 116 characters. A robot's wedding vow: the laugh comes from the situation itself — a software update changes who you are — and the tenderness sits under it: he wants to stay the version she fell in love with.

## How it runs

`main.py` (Python 3, standard library only) writes the vow to `$MAKEFUN_OUTPUT_DIR/entry.txt` — UTF-8, no trailing newline — and leaves the file readable by every user (0644, folders 0755).

```sh
MAKEFUN_OUTPUT_DIR=/output python3 main.py
```
