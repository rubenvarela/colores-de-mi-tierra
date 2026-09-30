# Los colores de mi tierra

In 1991, Harris Paints ran an ad before the movies in Puerto Rico with a song that names seven colors of the island. This project gives each color a full set of codes, measured from photos of the real thing it is named after, and compares it with the paint as the ad showed it.

The site is published at <https://rubenvarela.github.io/los-colores-de-mi-tierra/>.

## Start here

- **[The colors](https://rubenvarela.github.io/los-colores-de-mi-tierra/colores-de-mi-tierra-reales.html).** Each color measured from photos of the real thing, with HEX, RGB, HSL, Lab, OKLCH and CMYK codes. The ad's own value is kept on each card as an alternate.
- **[As the ad recorded them](https://rubenvarela.github.io/los-colores-de-mi-tierra/colores-de-mi-tierra.html).** The same seven colors sampled from the ad's video frames, with the frame each one came from and how it compares with the real thing.
- **[How it was built](summary.md).** Sources, methods, findings and limits, with every final value in one document.

## The seven colors

| Color | HEX | Based on |
| --- | --- | --- |
| Frambuesa piragua | `#C03621` | estimate, checked against 1 photo |
| Blanco coco | `#DDDFE0` | 7 photos, weak because the color is nearly gray |
| Amarillo mangó | `#DEA71E` | 10 photos |
| Verde quenepa | `#708839` | 3 photos, indicative |
| Azul adoquines | `#6F7781` | 10 photos, weak because the color is nearly gray |
| Rojo flamboyán | `#D32E1D` | 15 photos |
| Turquesa mar Caribe | `#5A9797` | 9 photos |

## What we found

- Every color in the ad leans the same way in hue, by about 13° on average. The reds read orange, the yellow a little greener, and the green and the turquesa bluer.
- The ad's whites and blacks stay neutral, so the video has no overall color cast. A tint error in the 1991 tape transfer would fit this pattern, but the data can't prove it.
- Wikimedia Commons has only one usable photo of a frambuesa piragua, so that color is an estimate. It is the ad's value with the average lean removed, and it lands within ΔE 2.5 of that one photo.
- Blanco coco and azul adoquines are nearly gray, so camera white balance decides most of their values. Verde quenepa rests on photos from 3 photographers.

[Watch the ad on YouTube](https://www.youtube.com/watch?v=6O6Xl9RFoJs).

## Files

- `index.html` is the start page of the site.
- `colores-de-mi-tierra-reales.html` has the colors measured from the real things.
- `colores-de-mi-tierra.html` has the colors as the ad recorded them.
- `summary.md` is the full write-up, and `summary.html` is the same text as a web page.

Each page is a single self-contained HTML file that works offline. Click any code to copy it.

## Credits

The ad and the song belong to Harris Paints. Orlando Lagomarsino wrote the lyrics, Alberto Carrión wrote the music, and Darvel García sang it. The reference photos come from Wikimedia Commons. These pages show only the colors measured from them, and each card links every photo with its photographer and license. The small video stills show where each sample in the ad came from.
