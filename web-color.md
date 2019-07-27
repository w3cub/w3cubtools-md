## Web-safe colors

In the mid-90s, many displays were only capable of displaying 256 colors.<sup id="cite_ref-11" class="reference">[[11]](https://en.wikipedia.org/wiki/Web_colors#cite_note-11)</sup> These may be dictated by the hardware or changeable by a "color table". When a color is found (e.g., in an image) that is not one available, a different one had to be used. This can be done by either using the closest color, or by using [dithering](https://en.wikipedia.org/wiki/Dither "Dither").

There were various attempts to make a "standard" color palette. A set of colors was needed that could be shown without dithering on 256-color displays; the number 216 was chosen partly because computer operating systems customarily reserved sixteen to twenty colors for their own use; it was also selected because it allows exactly six equally spaced shades of red, green, and blue (6 × 6 × 6 = 216), each from 00 to FF (including both limits).

The list of colors is presented as if it had special properties that render them immune to dithering, but on 256-color displays applications can actually set a palette of any selection of colors that they choose, dithering the rest. These colors were chosen specifically because they matched the palettes selected by various browser applications. There were not very different palettes in use in different browsers.<sup class="noprint Inline-Template Template-Fact">[_[citation needed](https://en.wikipedia.org/wiki/Wikipedia:Citation_needed "Wikipedia:Citation needed")_]</sup>

"Web-safe" colors had a flaw in that, on systems such as [X11](https://en.wikipedia.org/wiki/X_Window_System "X Window System") where the palette is shared between applications, smaller color cubes (5×5×5 or 4×4×4) were allocated by browsers—the "web safe" colors would dither on such systems. Different results were obtained by providing an image with a larger range of colors and allowing the browser to [quantize](https://en.wikipedia.org/wiki/Color_quantization "Color quantization") the color space if needed, rather than suffer the quality loss of a double quantization.

As of 2011, personal computers typically<sup id="cite_ref-12" class="reference">[[12]](https://en.wikipedia.org/wiki/Web_colors#cite_note-12)</sup> have 24-bit ([TrueColor](https://en.wikipedia.org/wiki/True_Color "True Color")) and the use of "web-safe" colors has fallen into practical disuse.

The "web-safe" colors do not all have standard names, but each can be specified by an [RGB](https://en.wikipedia.org/wiki/RGB "RGB") triplet: each component (red, green, and blue) takes one of the six values from the following table (out of the 256 possible values available for each component in full 24-bit color).

<table class="wikitable"><caption>6 shades of each color</caption>

<tbody>

<tr>

<th scope="col">Key</th>

<th scope="col">Hex</th>

<th scope="col">Decimal</th>

<th scope="col">Fraction</th>

</tr>

<tr>

<td>0</td>

<td>00</td>

<td>0</td>

<td>0</td>

</tr>

<tr>

<td>3</td>

<td>33</td>

<td>51</td>

<td>0.2</td>

</tr>

<tr>

<td>6</td>

<td>66</td>

<td>102</td>

<td>0.4</td>

</tr>

<tr>

<td>9</td>

<td>99</td>

<td>153</td>

<td>0.6</td>

</tr>

<tr>

<td>C or (12)</td>

<td>CC</td>

<td>204</td>

<td>0.8</td>

</tr>

<tr>

<td>F or (15)</td>

<td>FF</td>

<td>255</td>

<td>1</td>

</tr>

</tbody>

</table>

The following table shows all of the "web-safe" colors. One shortcoming of the web-safe palette is its small range of light colors for webpage backgrounds, whereas the intensities at the low end of the range, such as the two darkest, are similar to each other, making them hard to distinguish.

<div className="text-right"> 
    [From wiki](https://en.wikipedia.org/wiki/Web_colors#Web-safe_colors)
</div>
