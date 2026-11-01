# Fonts bundled with Isekubed

Both faces below are redistributed unmodified inside this mod's jar. Every line quoted here was read
out of the `name` table of the font file itself, not from a web page — so it is what the file claims,
not what a search result claimed.

**Neither font has been modified.** That matters: both licences reserve the family name, and a
modified copy would have to be renamed before it could be redistributed.

---

## Saira SemiCondensed Light — `saira.ttf`

The face the Eye of Loot draws in (`eye.json`).

```
Copyright   Copyright 2020 The Saira Project Authors
            (https://github.com/Omnibus-Type/Saira)
Designer    Hector Gatti with collaboration of the Omnibus-Type team
Vendor      Omnibus-Type — http://www.omnibus-type.com
Trademark   Saira is a trademark of Omnibus-Type
Version     1.101
License     This Font Software is licensed under the SIL Open Font License, Version 1.1.
            This license is available with a FAQ at: https://scripts.sil.org/OFL
```

**SIL OFL 1.1** permits bundling in and selling with software, so shipping it in a mod jar — paid or
free — is squarely allowed. Its conditions are that this notice travels with the font, that the font
is not sold on its own, and that a *modified* copy is renamed.

## Ubuntu Mono Regular — `ubuntu_mono.ttf`

The alternative face (`eye_mono.json`), shipped so switching is one constant in `EyeFont` rather than
a rebuild.

```
Copyright   Copyright 2011 Canonical Ltd. Licensed under the Ubuntu Font Licence 1.0
Designer    Dalton Maag Ltd — http://www.daltonmaag.com/
Trademark   Ubuntu and Canonical are registered trademarks of Canonical Ltd.
Version     0.80
```

**Ubuntu Font Licence 1.0** likewise permits redistribution inside software, requires this notice to
travel with it, and requires a renamed copy if the font is modified.

---

## The licence texts

`OFL.txt` and `UFL.txt` sit beside the fonts in this directory, and both ship inside the jar. That is
the part neither TTF can carry itself: a font file embeds a one-line summary of its licence in its
`name` table and nothing more, so the texts have to travel separately.

`verifyEyeFontResolves` requires both to be present and over 2 KB. The length floor is there because an
empty file satisfies an existence check and is exactly what a half-finished copy-paste leaves behind —
and a jar that ships the faces without their licences is a breach that renders perfectly.
