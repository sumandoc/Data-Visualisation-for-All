### Well-designed chart

1. For long labels, use horizontal bar charts instead of vertical column charts.

2. Order categories logically -- either alphabetically, by value, or sequentially -- depending on your data story. 
Choose colors wisely. Use color to logically organize your data. Avoid random colors or bad combinations from 
opposite sides of the color wheel (such as red/green). Instead, use contrast (such as color vs gray) to call attention to your data story.

3. Avoid “chart junk” -- such as 3D perspective, shadows, and unnecessary ornaments -- which distract readers from your data story.
Never use 3D unless you are plotting three-dimensional data.

4. Beware of pie charts. Most readers cannot accurately estimate sizes of different slices.
Consider other ways to show part-to-whole relationships, such as bar/column charts, or stacked bar/column charts.




#### Converting image to 300dpi




```
convert -units PixelsPerInch input.png -density 300 output.png
```

For PNG to TIFF conversion use: 

```
convert -set units PixelsPerInch input.png -density 300 output.tiff
```

Reducing size of file:

```
convert -strip -quality 90 big-image.jpg new-image.jpg
```

