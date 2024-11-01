# [Erisevka](https://panukettu.github.io/erisevka-monospace)

My monospace font for terminals and editors.

It is a customized build of [Iosevka](https://github.com/be5invis/Iosevka).

| Family         | Description                  |
| -------------- | ---------------------------- |
| Erisevka       | for editors                  |
| Erisevka Term  | for terminal, narrow symbols |
| Erisevka Fixed | for pure fixed width         |

<table>
<thead>
	<tr>
		<th>Weights</th>
		<th>Widths</th>
		<th>Slopes</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td>Thin</td>
		<td>Ultra-Condensed</td>
		<td>Italic</td>
	</tr>
	<tr>
		<td>ExtraLight</td>
		<td>Extra-Condensed</td>
		<td>Oblique</td>
	</tr>
	<tr>
		<td>Light</td>
		<td>Condensed</td>
		<td></td>
	</tr>
	<tr>
		<td>SemiLight</td>
		<td>Semi-Condensed</td>
		<td></td>
	</tr>
	<tr>
		<td>Regular</td>
		<td>Normal</td>
		<td></td>
	</tr>
	<tr>
		<td>Book</td>
		<td>Semi-Extended</td>
		<td></td>
	</tr>
	<tr>
		<td>Medium</td>
		<td>Extended</td>
		<td></td>
	</tr>
	<tr>
		<td>SemiBold</td>
		<td>Extra-Extended</td>
		<td></td>
	</tr>
	<tr>
		<td>Bold</td>
		<td></td>
		<td></td>
	</tr>
	<tr>
		<td>ExtraBold</td>
		<td></td>
		<td></td>
	</tr>
	<tr>
		<td>Heavy</td>
		<td></td>
		<td></td>
	</tr>
</tbody>
</table>

## Usage

#### VSCode

```jsonc
// settings.json

/**
 * PostScript name works too:
 *
 * "editor.fontFamily": "Erisevka-Book-Semi-Condensed"
 */
"editor.fontFamily": "Erisevka",

/**
 * ligatures, optional
 */
"editor.fontLigatures": "'dlig'"
```

#### WezTerm

**NOTE:** [Super TTC will rekt startup](https://github.com/wez/wezterm/issues/3890), use TTF instead.

```lua
-- wezterm.lua

config.font = wezterm.font {
    family = 'Erisevka Term',
    weight = 450,
    style = 'Normal'
}

config.window_frame = {
    font = wezterm.font {
        family = 'Erisevka',
        weight = 550,
        stretch = 'SemiCondensed'
    }
}
```

#### Kitty

```bash
kitten choose-fonts
```
