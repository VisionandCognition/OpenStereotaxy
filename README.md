# OpenStereotaxy

![](https://user-images.githubusercontent.com/7523776/42511893-1bef386e-8421-11e8-8138-aefb5ad0968b.png)

OpenStereotaxy is a collection of Python modules and add-ons that have been written to assist experimental neurophysiologists in planning stereotaxic surgical implantation of electrode chambers. To achieve this, our pipeline takes advantage of multiple specialized open-source (GNU General Public License) software:
* [3D Slicer](https://www.slicer.org/) - for anatomical image registration, segmentation, and surface extraction
* [Blender](https://www.blender.org/) - for 3D virtual reconstruction and boolean subtraction operations
* [FreeCAD](https://www.freecadweb.org/) - for parametric generation of custom 3D-printable implants
* [MeshLab](http://www.meshlab.net/) - for cleaning and editing mesh surfaces prior to 3D-printing

Although there have been numerous previous efforts by neurophysiologists to program software for planning neural implantations [3-5], the results are not the most user friendly, frequently depend on licensed software (such as Matlab) and lack the level of online support that can be provided by more mature open-source projects with large user bases (such as those used here). On the other hand, commercial software and services [6-7] are costly and provide the researcher with less control than open-source alternatives. In addition to the use of MRI and CT data to inform surgical planning, there has been an increasing use of 3D-printing and computer-controlled machining technologies to prepare custom implants for neurophysiology research [8-10]. Catering for this need requires the use of parametric 3D-modelling and mesh editing softwares, for which there are fortunately several well-established and supported open-source options that can save researchers time and money.

These software have several advantageous features in common. They are all: 
* open-source (free)
* cross-platform (work on all operating systems)
* Python scriptable (for automating specific tasks)
* supported by large online user communities
* under continuous development

![](https://user-images.githubusercontent.com/7523776/42489006-9960bd72-83d6-11e8-8c6b-b15b245d1f48.png)

---
## 3D Slicer

3D Slicer was started by [David Gering](http://people.csail.mit.edu/gering/) in 1999 during his Master's degree at MIT and Harvard's [Surgical Planning Lab (SPL)](https://www.spl.harvard.edu/) [1]. Subsequently, Steve Pieper took over the project of developing 3D Slicer into an industrial-strength package, and Slicer has been under continuous development at the SPL under Ron Kikinis since. It is developed by professional engineers with the participation of commercial partners and contributions from the user community. It was initially envisioned as a neurosurgical guidance, visualization and analysis system, but has evolved to support a variety of clinical and basic research applications, as well as for the analysis of nonmedical images. Improvement and maintenance of the software have been possible primarily through the support from the National Institutes of Health (NIH).

---
## FreeCAD

FreeCAD was started by [Jürgen Riegel](https://www.freecadweb.org/wiki/History) in 2001 as a Graphical Object Modeler (GOM), with the idea to use Qt, Python and Cas.CADE - a previously commercial CAD-Kernel that became the open-source [OpenCascade](https://www.opencascade.com/) in 1999. It has been under constand development since, and was added to Debian and Ubuntu repositories in 2009-2010. 

---
## Blender

Blender was started by [Ton Roosendaal](https://www.blender.org/foundation/history/) in 1995, and initially developed through commercial funding. In 2002 Roosendal founded the non-profit Blender Foundation, which funded continued development of Blender as open-source software under the GNU General Public License.  

---

### References

[1] [Gering DT, Nabavi A, Kikinis R, Grimson WEL, Hata N, Everett P, Jolesz F, Wells WM (1999). An Integrated Visualization System for Surgical Planning and Guidance Using Image Fusion and Interventional Imaging. MICCAI 1999, 809-819.](https://link.springer.com/chapter/10.1007/10704282_88)

[2] [Grimson E, Leventon M, Ettinger G, Chabrerie A, Ozlen F, Nakajima S, et al.
Wells WM, Colchester A, Delp S (Eds.), Clinical experience with a high precision image-guided neurosurgery system. Proc of MICCAI'98, Vol. 1496, Springer-Verlag, Berlin/Heidelberg (1998), pp. 63-73](https://link.springer.com/chapter/10.1007/BFb0056188)

[3] [Daye PM, Monosov IE, Hikosaka O, Leopold DA, Optican LM (2013). pyElectrode: An open-source tool using structural MRI for electrode positioning and neuron mapping. J.Neurosci.Methods, 213,1: 123-131.](https://www.sciencedirect.com/science/article/pii/S0165027012004797)

[4] [Ohayan S, Tsao DY (2012). MR-guided stereotactic navigation. J.Neurosci.Methods, 204,2: 389-397.](https://www.sciencedirect.com/science/article/pii/S0165027011007084?via%3Dihub)

[5] [Murphy AP (2014). ElectroNav: A Matlab toolbox for MRguided electrode navigation. https://github.com/MonkeyGone2Heaven/ElectroNavToolbox](https://github.com/MonkeyGone2Heaven/ElectroNavToolbox)

[6] [BrainSight](https://www.rogue-research.com/veterinary/research/)

[7] [Gray Matter Research](https://www.graymatter-research.com/design-and-modeling/)

[8] [Johnston JM, Cohen YE, Shirley H, Tsunada J, Bennur S, Christison-Lagay K, Veeder CL (2016). Recent refinements to cranial implants for rhesus macaques (Macaca mulatta). Lab Anim (NY). 45(5): 180-6.](https://www.nature.com/articles/laban.997)

[9] [Mulliken GH, Bichot NP, Ghadooshahy A, Sharma J, Kornblith S, Philcock M, Desimone R (2015). Custom-fit radiolucent cranial implants for neurophysiological recording and stimulation. J. Neurosci. Methods. 241: 146–154.](https://www.sciencedirect.com/science/article/pii/S0165027014004324)

[10] [Chen X, Possel JK, Wacongne C, van Ham AF, Klink C, Roelfsema PR (2016). 3D printing and modelling of customized implants and surgical guides for non-human primates. J. Neurosci. Methods, 286: 38-55.](https://www.sciencedirect.com/science/article/pii/S0165027017301322)

[11] [McMahon DBT, Bondar IV, Afuwape OAT, Ide DC, Leopold DA (2014). One month in the life of a neuron: longitudinal single-unit electrophysiology in the monkey visual system. J.Neurophysiol., 112(7): 1748-1762.](https://www.physiology.org/doi/abs/10.1152/jn.00052.2014)

