# Fractal dimension analysis for biological use

TODO
Implement fractal dimension analysis for grayscale images, micsrocopy images and biological application following FIJI/ImageJ (for inspiration check https://github.com/scikit-image/scikit-image/issues/2347).


First of all, there has been [this extension to 3D](https://github.com/ChatzigeorgiouGroup/FractalDimension) together with some applications on cytoskeleton complexity. 

Second of all, in biology for image processing, FiJi/ImageJ is used a lot (ref) for estimating the fractal dimension of a grayscale image (or for analysis of signal coming from microscopy). The relevant documentation is on those pages: [introduction (link to source code)](https://imagej.nih.gov/ij/plugins/fraclac/FLHelp/Introduction.htm) or [pdf summary with links](https://www.researchgate.net/profile/Audrey-Karperien/publication/258341589_FracLac_for_ImageJ/links/0c9605285e41abf78f000000/FracLac-for-ImageJ.pdf), [box counting](https://imagej.nih.gov/ij/plugins/fraclac/FLHelp/BoxCounting.htm) but more importantly, this [glossary](https://imagej.nih.gov/ij/plugins/fraclac/FLHelp/Glossary.htm#grayscale) which defines three measures for grayscale images (notice that this Is basically looking at 3D) 

> FracLac reports 3 basic types of fractal dimension for grayscale scans. 
> 
> DB
> 
> DM
> 
> Dx̄

Besides all of this, this tool also controls for other problems (tbh I think that some are negligible like the starting grid position which they sample), eg see [this link](https://imagej.nih.gov/ij/plugins/fraclac/FLHelp/BoxCountingOptions.htm). 

#### Source code ImageJ 
* Fractal dimension, Fractal count: [Github repo](https://github.com/perchrh/ImageJFractalDimension), [Github-fractal count](https://github.com/perchrh/ImageJFractalDimension/blob/master/FractalCount_.java), [summary page for imageJ pugins](http://www.pvv.org/~perchrh/imagej/fractal.html).
* 

## References and literature
1) Nest expansion assay: a cancer systems biology approach to in vitro invasion measurements (Kam, Y., Karperien, A., Weidow, B. et al. BMC Res Notes 2, 130 (2009). https://doi.org/10.1186/1756-0500-2-130), pdf accessible at https://bmcresnotes.biomedcentral.com/articles/10.1186/1756-0500-2-130.

2) Fractal analysis in practice, article on ImageJ:
https://imagej.nih.gov/ij/plugins/fraclac/FLHelp/Fractals.htm#fractalanalysisinpractice

3) Fractal Dimension Estimation Methods for Biomedical Images (Antonio Napolitano, Sara Ungania and Vittorio Cannata, http://dx.doi.org/10.5772/48760, mentioned in [this issue](https://github.com/scikit-image/scikit-image/issues/1730) by @SalvatoreScaramuzzino), pdf accessible at http://cdn.intechopen.com/pdfs-wm/39360.pdf. **Recommended to read**, Matlab implementation and algorithm description.

4) Fractal Geometry in Image Processing (A. Annadhason, accessible online at https://www.yumpu.com/en/document/view/32997338/fractal-geometry-in-image-processing).

5) Fractal analysis in radiological and nuclear medicine perfusion imaging: a systematic review (Michallek, F., Dewey, M., Eur Radiol 24, 60–69 (2014). https://doi.org/10.1007/s00330-013-2977-9 , accessible at https://link.springer.com/content/pdf/10.1007/s00330-013-2977-9.pdf).

6) MULTIFRAC: An ImageJ plugin for multiscale characterization of 2D and 3D stack images (Iván .G.Torreab, Richard J.Heckc, A.M.Tarquisdef, SoftwareX
Volume 12, July–December 2020, 100574, https://doi.org/10.1016/j.softx.2020.100574, pdf accessible at https://reader.elsevier.com/reader/sd/pii/S2352711020302879?token=13BA7120C8771C204919EE98C9D9F7D45100EACF82804A60E139E10499A15BD0D083862DE89818D7D5C8440B23BCB850&originRegion=eu-west-1&originCreation=20210428074543).


(Another) Dynamics of Forest Fragmentation and Connectivity Using Particle and Fractal Analysis (Andronache, I., Marin, M., Fischer, R. et al., Sci Rep 9, 12228 (2019). https://doi.org/10.1038/s41598-019-48277-z, pdf accessible at https://www.nature.com/articles/s41598-019-48277-z.pdf).


#### Differential box counting
1) An efficient differential box-counting approach to compute fractal dimension of image (N. Sarker, B. B. Chaudhuri, DOI: 10.1109/21.259692)


## Related issues
[Fractal dimension in 1D](https://gist.github.com/rougier/e5eafc276a4e54f516ed5559df4242c0)

[Extension to 3D](https://github.com/ChatzigeorgiouGroup/FractalDimension)
