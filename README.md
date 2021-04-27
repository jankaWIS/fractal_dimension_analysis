# Fractal dimension analysis for biological use
Implement fractal dimension analysis for grayscale images, micsrocopy images and biological application following FIJI/ImageJ (for inspiration check https://github.com/scikit-image/scikit-image/issues/2347).



Fractal Geometry in Image Processing by A. Annadhason ([online](https://www.yumpu.com/en/document/view/32997338/fractal-geometry-in-image-processing)).

First of all, there has been [this extension to 3D](https://github.com/ChatzigeorgiouGroup/FractalDimension) together with some applications on cytoskeleton complexity. 

Second of all, in biology for image processing, FiJi/ImageJ is used a lot (ref) for estimating the fractal dimension of a grayscale image (or in my case for analysis of signal coming from microscopy). The relevant documentation is on those pages: [box counting](https://imagej.nih.gov/ij/plugins/fraclac/FLHelp/BoxCounting.htm) but more importantly, this [glossary](https://imagej.nih.gov/ij/plugins/fraclac/FLHelp/Glossary.htm#grayscale) which defines three measures for grayscale images (notice that this Is basically looking at 3D) 
> FracLac reports 3 basic types of fractal dimension for grayscale scans. 
> DB
> DM
> Dx̄

Besides all of this, this tool also controls for other problems (tbh I think that some are negligible like the starting grid position which they sample), eg see [this link](https://imagej.nih.gov/ij/plugins/fraclac/FLHelp/BoxCountingOptions.htm). 

## Reference
For more reference as requested, see this paper:
https://bmcresnotes.biomedcentral.com/articles/10.1186/1756-0500-2-130
or this article
https://imagej.nih.gov/ij/plugins/fraclac/FLHelp/Fractals.htm#fractalanalysisinpractice
or what has been mentioned in the related issue by @SalvatoreScaramuzzino :
http://cdn.intechopen.com/pdfs-wm/39360.pdf




## Related issues
[Fractal dimension in 1D](https://gist.github.com/rougier/e5eafc276a4e54f516ed5559df4242c0)
[Extension to 3D](https://github.com/ChatzigeorgiouGroup/FractalDimension)
