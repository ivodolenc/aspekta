# Aspekta Sources

This directory contains the primary source files essential for development, export, and maintenance purposes. These files are not intended for direct usage in production environments.

All typeface files intended for production use are located in the [fonts](../fonts/) directory, organized by format for easy integration and accessibility.

## Aspekta

### Base Source

This file serves as the `base` source for the typeface, containing all editable paths and glyphs. Any modifications or updates to the typeface must be applied here, ensuring all structural elements remain intact. Shapes must retain all overlaps, as this is crucial for maintaining consistency and developing new forms.

#### Why Are There Overlaps in the Base Source File?

Overlapping shapes in the base source provide additional flexibility when constructing various components and refining forms. This approach ensures consistency throughout the typeface and significantly streamlines development, maintenance and expanding processes. By preserving overlaps, designs can be easily adapted and improved without losing the shape of the structure, making it easy to experiment and iterate.

## AspektaVF

### Variable Source

This is basically a `mirrored` version of the `base` source, specifically designed for Variable Font development. All modifications applied to the base source are manually duplicated here, ensuring consistency across different font variations. Unlike the base source, this file does not retain overlaps, as Variable Fonts require clean, non-overlapping shapes for proper interpolation and smooth transitions between weight, width, and other axes.

#### Why Are There No Overlaps in the Variable Source File?

For instance, if text needs to be expanded to vector outlines, such as for printing or cutting applications, the preserved overlaps must be properly handled to avoid excessive complexity. Certain printers or cutting machines may struggle with overlapped paths, requiring manual adjustment or merging of shapes before final output.

Overlaps can introduce potential issues with interpolation or dynamic animations, especially when adjusting font widths in small units. Ensuring clean paths in such cases helps maintain smooth transitions and accurate visual representations across different font variations.

## Font Info

- Aspekta™ Typeface
- Static + Variable Font
- Open Font License (OFL) v1.1
- Copyright © Ivo Dolenc

## Masters

- Thin - 100
- Regular - 400
- Black - 900

## Metrics

- Units per Em: 1000
- Ascender: 1100 / 0
- Cap Height: 720 / 12
- x-Height: 520 / 12
- Baseline: 0 / -12
- Descender: -330 / 0
- Italic Angle: 0°
- y-Bottom: -200 / -12

## Stems

**Thin - 100**

- hStem0: 30
- hStem1: 31
- vStem0: 32
- vStem1: 33

**Regular - 400**

- hStem0: 80
- hStem1: 82
- vStem0: 84
- vStem1: 92

**Black - 900**

- hStem0: 162
- hStem1: 182
- vStem0: 188
- vStem1: 212

## Exports

**Static Instances**

- Weights 50-1000

**Variable Range**

- Weights 100-900

## Formats

- Static fonts in `.otf` format
- Static fonts in `.ttf` format
- Variable font in `.ttf` and `.woff2` formats
- Web fonts in `.woff2` format

## Stylistic Sets

- `aalt` - Access All Alternates
- `ccmp` - Glyph Composition / Decomposition
- `locl` - Localized Forms
- `case` - Case-Sensitive Forms
- `ss01` - Stylistic Set 1 (Alternative a)
- `ss02` - Stylistic Set 2 (Alternative l)
- `ss03` - Stylistic Set 3 (Alternative t)
- `ss04` - Stylistic Set 4 (Alternative u)
- `ss05` - Stylistic Set 5 (Alternative y)
- `ss06` - Stylistic Set 6 (Alternative G)
- `ss07` - Stylistic Set 7 (Alternative J)
- `ss08` - Stylistic Set 8 (Alternative R)
- `ss09` - Stylistic Set 9 (Alternative 3,6,9)
- `ss10` - Stylistic Set 10 (Alternative 1,4)
- `ss11` - Stylistic Set 11 (Alternative @)
- `ss12` - Stylistic Set 12 (Alternative ¢,$,€,£)
- `ss13` - Stylistic Set 13 (Alternative ©,®,℗)
- `ss14` - Stylistic Set 14 (Alternative ™,℠)

## Sponsors

<br>

<p align="center">
  <a title="Hypernym Studio" href="https://github.com/hypernym-studio">
    <picture>
      <source media="(prefers-color-scheme: dark)" width="258" srcset="../../media/hypernym-logo:dark.svg">
      <source media="(prefers-color-scheme: light)" width="258" srcset="../../media/hypernym-logo:light.svg">
      <img alt="Hypernym Studio" width="258" src="../../media/hypernym-logo:dark.svg">
    </picture>
  </a>
  <picture>
    <source media="(prefers-color-scheme: dark)" width="258" srcset="../../media/sponsor-logo:dark.svg">
    <source media="(prefers-color-scheme: light)" width="258" srcset="../../media/sponsor-logo:light.svg">
    <img alt="Become a Sponsor" width="258" src="../../media/sponsor-logo:dark.svg">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" width="258" srcset="../../media/sponsor-logo:dark.svg">
    <source media="(prefers-color-scheme: light)" width="258" srcset="../../media/sponsor-logo:light.svg">
    <img alt="Become a Sponsor" width="258" src="../../media/sponsor-logo:dark.svg">
  </picture>
</p>

## License

Developed in 🇭🇷 Croatia, © Ivo Dolenc.

Released under the [OFL 1.1](LICENSE.txt) license.
