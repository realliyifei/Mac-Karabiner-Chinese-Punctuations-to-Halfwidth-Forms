# Mac Karabiner Chinese Punctuations to Halfwidth Forms

When using Chinese in markdown and code, to speed the format switch of the halfwidth/fullwidth input, we can map each inputting punctuation to its haldwidth form by pressing function key `fn`.

当在markdown或者代码中运用中文时，为了更快地转换半角/全角（港台：半形/全形）的符号输入，我们可以通过按着`fn`键把对应正在输入的符号的形式变为半角。

---

## List of All Mapped Keys（映射的个键列表）:

`fn` key + 

- `，` -> `,`
- `。` -> `.`
- `；` -> `;`
- `：` -> `:`
- `“` -> `"`
- `”` -> `"`
- `‘` -> `'`
- `·` -> `` ` ``
- `～` -> `~`
- `！` -> `!` 
- `？` -> `?`
- `（` -> `(`
- `）` -> `)`
- `【` -> `[`
- `】` -> `]`
- `「` -> `{`
- `」` -> `}`
- `《` -> `<`
- `》` -> `>`
- `¥` -> `$` 
- `……` -> `^`
- `——` -> `_`

Notes: in the case of the multi-key values, we should type the key as usual first and then press `fn` key. For instance, when mapping `……` to `^`, we should type  `shift` + `6` + `fn`.

---

### Prerequisite（所需软件）: Karabiner

![karabiner-elements-logo](https://static.macupdate.com/products/25141/m/karabiner-elements-logo.png?v=1593415409)

**Download Link:** <https://pqrs.org/osx/karabiner/>

### Installation（安裝）:

- Download the json file from github
- Copy file to **~/.config/karabiner/assets/complex_modifications**
- Enable rule in the complex modifictaions tag in Karabiner
