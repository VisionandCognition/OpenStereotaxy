# OpenStereotaxy

OpenStereotaxy is a collection of Python modules and add-ons that have been written to assist experimental neurophysiologists in planning stereotaxic surgical implantation of electrode chambers. To achieve this, we take advantage of various specialized open-source (GNU General Public License) software:
* [Slicer](https://www.slicer.org/) - for anatomical image registration, segmentation, and surface extraction
* [Blender](https://www.blender.org/) - for 3D virtual reconstruction and boolean subtraction operations
* [FreeCAD](https://www.freecadweb.org/) - for parametric generation of custom 3D-printable implants
* [MeshLab](http://www.meshlab.net/) - for cleaning and editing mesh surfaces prior to 3D-printing

Although there have been numerous previous efforts by neurophysiologists to program software for planning neural implantations [3-5], the results are not the most user friendly, frequently depend on licensed software (such as Matlab) and lack the level of online support that can be provided by more mature open-source projects with large user bases (such as those used here). On the other hand, commercial software and services [6-7] are costly and provide the researcher with less control than open-source alternatives. Aside form the use of MRI and CT data to inform surgical planning, there has been an increasing use of 3D-printing and computer-controlled machining technologies to prepare custom implants for neurophysiology research [8-10]. Catering for this need requires the use of parametric 3D-modelling and mesh editing softwares, for which there are fortunately several well-established and supported open-source options that can save researchers time and money.

---
## 3D Slicer

> David Gering presented the initial prototype of the Slicer software in his MIT Master's thesis in 1999 [1] based on the earlier experience of the research groups at MIT and Surgical Planning Lab (SPL) [2]. Subsequently, Steve Pieper assumed the role of the Chief Architect, commencing the work of transforming 3D Slicer into an industrial-strength package. Since 1999, Slicer has been under continuous development at the SPL under the leadership of Ron Kikinis. Today it is developed mostly by professional engineers in close collaboration with algorithm developers and application domain scientists, with the participation of Isomics Inc., Kitware Inc. and GE Global Research and with significant contributions from the growing Slicer community. Initially envisioned as a neurosurgical guidance, visualization and analysis system, over the last decade, Slicer has evolved into an integrated platform that has been applied in a variety of clinical and preclinical research applications, as well as for the analysis of nonmedical images. Improvement and maintenance of the software have been possible primarily through the support from the National Institutes of Health (NIH).

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

