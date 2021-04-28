# Fractal dimension analysis for biological use

TODO
Implement fractal dimension analysis for grayscale images, micsrocopy images and biological application following FIJI/ImageJ (for inspiration check https://github.com/scikit-image/scikit-image/issues/2347).


First of all, there has been [this extension to 3D](https://github.com/ChatzigeorgiouGroup/FractalDimension) together with some applications on cytoskeleton complexity. 

Second of all, in biology for image processing, FiJi/ImageJ is used a lot (ref) for estimating the fractal dimension of a grayscale image (or for analysis of signal coming from microscopy). The relevant documentation is on those pages: [introduction (link to source code)](https://imagej.nih.gov/ij/plugins/fraclac/FLHelp/Introduction.htm), [box counting](https://imagej.nih.gov/ij/plugins/fraclac/FLHelp/BoxCounting.htm) but more importantly, this [glossary](https://imagej.nih.gov/ij/plugins/fraclac/FLHelp/Glossary.htm#grayscale) which defines three measures for grayscale images (notice that this Is basically looking at 3D) 

> FracLac reports 3 basic types of fractal dimension for grayscale scans. 
> DB
> DM
> Dx̄

Besides all of this, this tool also controls for other problems (tbh I think that some are negligible like the starting grid position which they sample), eg see [this link](https://imagej.nih.gov/ij/plugins/fraclac/FLHelp/BoxCountingOptions.htm). 

## References and literature
1) Nest expansion assay: a cancer systems biology approach to in vitro invasion measurements (Kam, Y., Karperien, A., Weidow, B. et al. BMC Res Notes 2, 130 (2009). https://doi.org/10.1186/1756-0500-2-130), pdf accessible at https://bmcresnotes.biomedcentral.com/articles/10.1186/1756-0500-2-130.

2) Fractal analysis in practice, article on ImageJ:
https://imagej.nih.gov/ij/plugins/fraclac/FLHelp/Fractals.htm#fractalanalysisinpractice

3) Fractal Dimension Estimation Methods for Biomedical Images (Antonio Napolitano, Sara Ungania and Vittorio Cannata, http://dx.doi.org/10.5772/48760, mentioned in [this issue](https://github.com/scikit-image/scikit-image/issues/1730) by @SalvatoreScaramuzzino), pdf accessible at http://cdn.intechopen.com/pdfs-wm/39360.pdf.

4) Fractal Geometry in Image Processing (A. Annadhason, accessible online at https://www.yumpu.com/en/document/view/32997338/fractal-geometry-in-image-processing).

5) Fractal analysis in radiological and nuclear medicine perfusion imaging: a systematic review (Michallek, F., Dewey, M., Eur Radiol 24, 60–69 (2014). https://doi.org/10.1007/s00330-013-2977-9 , accessible at https://link.springer.com/content/pdf/10.1007/s00330-013-2977-9.pdf)

#### Differential box counting
1) An efficient differential box-counting approach to compute fractal dimension of image (N. Sarker, B. B. Chaudhuri, DOI: 10.1109/21.259692)


## Related issues
[Fractal dimension in 1D](https://gist.github.com/rougier/e5eafc276a4e54f516ed5559df4242c0)

[Extension to 3D](https://github.com/ChatzigeorgiouGroup/FractalDimension)
