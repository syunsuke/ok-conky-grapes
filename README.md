# conky-grapes

**The Github repository is only a mirror, only for visibility purppose.** I use GitLab CE for my own projects (which now has mirroring feature on Community Edition).

You can authenticate on [my gitlab server](https://gitlab.nomagic.uk/popi/conky-grapes) using your Github or Gitlab account to submit issues or merge requests.

## Fork

I forked this from Popi to host my own config and have my settings in it. You're free to use it however you like.

Source [POPI gitlab server](https://gitlab.nomagic.uk/popi/conky-grapes)

![Image](https://github.com/user-attachments/assets/a3f120c7-961d-4310-851d-4ee7e96af17d)
> This is My Conky

### Updates
- 2025-03-02: I forked as ok-conky-grapes from original conky-grapes 

## What is it
This repository aims at providing you everything you need to be able to **very quickly** build a fantastic grape-shaped lua/ conky adapted to your machine including:
* Metrics on temperature, cpu (maximum fixed to 8 cpu to display), disks (maximum 3 filesystem), memory (ram and swap), networking (we select the interface used as default gateway),
and battery when relevant.
* Visual monitoring for high temperature, low disk space and low battery charge (orange is warning, red is critical)
* A set of pre-defined colours that allows to easily adapt your settings to different backgrounds (colors can be added/ changed in the python file fairly easily).
* Possibility to select different colors for the rings, the section titles, and the text.

_note: the limits on cpu and filesystems are for display reason._

![](https://pic.nomagic.uk/W9MjLPJF)
> This is Original

## Why use it
To tune up your desktop of course! It is under [GPLv3 License](gpl-3.0.txt), so feel free to use, study, improve and share as you please.


## How to use it
* If you already know your way around, all you need is:
  - install conky-full
  - clone this repo to ~/.conky/ok-conky-grapes
  - install the fonts
  - use `create_config.py` to generate your configuration (use `-h` to display help)
  - enjoy color combinations and spend a fairly big amount of time looking at those magic rings

```
 -----------------------------
< ALL GLORY TO THE HYPNOTOAD! >
 -----------------------------
        \   ^__^
         \  (@@)\_______
            (__)\       )\/\
             U ||----w |
                ||     ||
```

* If you haven't used or set up any conky before, please go to the [Wiki](https://gitlab.nomagic.fr/popi/conky-grapes/wikis/home) page (that you can also edit with your inputs!)
