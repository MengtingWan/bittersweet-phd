**Table of Contents:**

- [Python Visualization](#python-visualization)
  * [Matplotlib FAQ](#matplotlib-faq)
     + [Embed fonts in PDF](#embed-fonts-in-pdf)
     + [Compress PDF](#compress-pdf)
     + [Reduce spaces around images](#reduce-spaces-around-images)
     + [Colors](#colors)
  * [Useful Tutorials](#useful-tutorials)
     + [The Python Graph Gallery](#the-python-graph-gallery)
  * [Useful Packages](#useful-packages)
     + [Basics (matplotlib, pandas)](#basics--matplotlib--pandas-)
     + [Others (ggplot, seaborn)](#others--ggplot--seaborn-)
     + [Interactive (plotly)](#interactive--plotly-)

# Python Visualization

## Matplotlib FAQ

### Embed fonts in PDF
- [How to embed fonts in PDFs produced by matplotlib?](https://stackoverflow.com/questions/9054884/how-to-embed-fonts-in-pdfs-produced-by-matplotlib/22809802)

### Compress PDF
- [Reducing the size of pdf figure file in matplotlib](https://stackoverflow.com/questions/10685495/reducing-the-size-of-pdf-figure-file-in-matplotlib)

### Reduce spaces around images
- [Removing white space around a saved image in matplotlib](https://stackoverflow.com/questions/11837979/removing-white-space-around-a-saved-image-in-matplotlib/27227718)
  - lazy solution: [`plt.savefig('img.pdf', bbox_inches='tight')`](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.savefig.html) or [`plt.tight_layout()`](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.tight_layout.html)
  - customized solution: [`plt.subplots_adjust()`](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.subplots_adjust.html)

### Colors
- [Color Names](https://matplotlib.org/3.1.1/gallery/color/named_colors.html)
- [Color Maps](https://matplotlib.org/3.1.1/tutorials/colors/colormaps.html)

## Useful Tutorials

### The Python Graph Gallery
- [The Python Graph Gallery](https://python-graph-gallery.com)

## Useful Packages

### Basics (matplotlib, pandas)

- [matplotlib](https://matplotlib.org/)
- [pandas](https://pandas.pydata.org/)

### Others (ggplot, seaborn)

- [ggplot](http://ggplot.yhathq.com/)
- [seaborn](https://seaborn.pydata.org/)

### Interactive (plotly)

- [plotly](https://plot.ly/python/)




