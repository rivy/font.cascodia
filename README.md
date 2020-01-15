<!-- markdownlint-disable header-increment no-trailing-punctuation -->
<!-- spell-checker:ignore markdownlint -->

<!-- spell-checker:ignore Cascadia Cascodia Delugia Hanselman Powerline repo useb -->

# Cascadia Code + Nerd Fonts

> Inspired by [Scott Hanselman](https://www.hanselman.com/blog/PatchingTheNewCascadiaCodeToIncludePowerlineGlyphsAndOtherNerdFontsForTheWindowsTerminal.aspx) and [Alistair Young](https://github.com/microsoft/cascadia-code/issues/10?WT.mc_id=-blog-scottha#issuecomment-532969414).

Can we add Nerd Fonts to the [Cascadia Code](https://github.com/microsoft/cascadia-code) font using GitHub Actions?

The answer, it turns out, is yes.

[Adam Cooper](https://github.com/adam7) wrote a [blog post with more details](https://admcpr.com/2019/10/07/automating-the-patching-of-cascadia-code-to-include-nerd-fonts/)[`@`](https://archive.is/b8op3)<!-- {a:.link-archival} --> about how this works.

[![Actions Status](https://github.com/rivy/font.cascodia/workflows/Generate%20Fonts/badge.svg)](https://github.com/rivy/font.cascodia/actions)

> Cascadia now [bundles Powerline symbols](https://github.com/microsoft/cascadia-code/issues/10) so you almost definitely don't need to use this. Just grab the PL version from the latest [Cascadia release](https://github.com/microsoft/cascadia-code/releases).

### How to use

You can download the patched font from the [Releases page](https://github.com/rivy/font.cascodia/releases) of this repo and install them as you would any other font. Once installed the font can be referenced as `Cascodia NF`. So if, for example, you want to use it in Windows Terminal you should add this line to your profiles.json

`"fontFace" : "Cascodia NF",`
