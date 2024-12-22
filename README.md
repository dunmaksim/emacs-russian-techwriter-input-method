# GNU Emacs input method for technical writers

## Installing

1. Add to `init.el`:

    ```emacs-lisp
    (use-package russian-techwriter-input-method
      :ensure t
      :custom
      (default-input-method 'russian-techwriter))

1. Toggle input method with **[C-\\]** keybinding.

## Using

Unlike the `russian-computer` input method included in the standard Emacs package, this package provides support for ligatures. The list of supported ligatures is present below. To insert a ligature press the `[/]` key (to the right of `[ю]`), the enter the desired sequence of characters.

## Ligatures

### Dash

| Sequence | Replace char | Description |
|:--------:|:------------:|-------------|
| `[/-]`   | –            | EN DASH     |
| `[/--]`  | ‒            | FIGURE DASH |
| `[/---]` | —            | EM DASH     |

### Quotation marks

| Sequence | Replace char | Description                                |
|:--------:|:------------:|--------------------------------------------|
| `[/,,]`  | „            | DOUBLE LOW-9 QUOTATION MARK                |
| `[/,]`   | ‚            | SINGLE LOW-9 QUOTATION MARK                |
| `[/``]`  | ‘            | LEFT SINGLE QUOTATION MARK                 |
| `[/']`   | ’            | RIGHT SINGLE QUOTATION MARK                |
| `[/``]`  | “            | LEFT DOUBLE QUOTATION MARK                 |
| `[/'']`  | ”            | RIGHT DOUBLE QUOTATION MARK                |
| `[/<<]`  | «            | LEFT-POINTING DOUBLE ANGLE QUOTATION MARK  |
| `[/>>]`  | »            | RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK |

### Points and bullets

| Sequence | Replace char | Description                         |
|:--------:|:------------:|------------------------------------|
| `[/*]`   | •            | Bullet                                |
| `[/.]`   | ․            | Point                               |
| `[/..]`  | ‥            | Двоточие                            |
| `[/...]` | …            | Многоточие                          |

### Numbers and paragraphs

| Sequence | Replace char | Description |
|:--------:|:------------:|-------------|
| `[/&]`   | §            | Paragraph   |
| `[/#]`   | №            | Number      |
| `[/no]`  | №            | Number      |

### Vallets and trademarks

| Sequence | Replace char | Description         |
|:------------------:|:-------------:|------------------|
| `[/c]`             | ©             | Copyright        |
| `[/tm]`            | ™             | Trademark        |
| `[/reg]`           | ®             | Reserved         |
| `[/eu]`            | €             | Euro             |
| `[/ru]`            | ₽             | Russian rouble   |
| `[/ce]`            | ¢             | Cent             |
| `[/te]`            | ₸             | Kazakhstan tenge |

### Fractions

| Sequence | Replace char |
|:--------:|:------------:|
| `[/78]`  | ⅞           |
| `[/58]`  | ⅝           |
| `[/38]`  | ⅜           |
| `[/18]`  | ⅛           |
| `[/56]`  | ⅚           |
| `[/16]`  | ⅙           |
| `[/45]`  | ⅘           |
| `[/35]`  | ⅗           |
| `[/25]`  | ⅖           |
| `[/15]`  | ⅕           |
| `[/23]`  | ⅔           |
| `[/13]`  | ⅓           |
| `[/34]`  | ¾            |
| `[/12]`  | ½            |
| `[/14]`  | ¼            |

### Romanian numbers

| Sequence  | Replace char |
|:---------:|:------------:|
| `[/RI]`   | Ⅰ            |
| `[/RII]`  | Ⅱ            |
| `[/RIII]` | Ⅲ            |
| `[/RIV]`  | Ⅳ            |
| `[/RV]`   | Ⅴ            |
| `[/RVI]`  | Ⅵ            |
| `[/RVII]` | Ⅶ            |
| `[/RVIII]`| Ⅷ            |
| `[/RIX]`  | Ⅸ            |
| `[/RX]`   | Ⅹ            |
| `[/RXI]`  | Ⅺ            |
| `[/RXII]` | Ⅻ            |
| `[/ri]`   | ⅰ            |
| `[/rii]`  | ⅱ            |
| `[/riii]` | ⅲ            |
| `[/riv]`  | ⅳ            |
| `[/rv]`   | ⅴ            |
| `[/rvi]`  | ⅵ            |
| `[/rvii]` | ⅶ            |
| `[/rviii]`| ⅷ            |
| `[/rix]`  | ⅸ            |
| `[/rx]`   | ⅹ            |
| `[/rxi]`  | ⅺ            |
| `[/rxii]` | ⅻ            |
