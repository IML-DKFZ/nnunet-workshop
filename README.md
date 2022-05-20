# nnU-Net Workshop

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iml-dkfz/nnunet-workshop/blob/master/nnU-Net_Workshop.ipynb)

The goal of this tutorial is to give an overview of how nnU-Net can be easily used for segmentation tasks in the biomedical domain.

Further it shows how MITK can be used alongside nnU-Net to visualize and interpret the results of nnU-Net.

In the folder slides, the presentation about nnU-Net is stored alongside a setup guide.

## About nnU-Net
The nnU-Net is a toolkit to segment imaging data and was specifically designed for biomedical data.

It was designed by **Fabian Isensee** while pursuing his PhD at the [Medical Image Computing Division of the German Cancer Research Institute](https://www.dkfz.de/en/mic/index.php).

More information about nnU-Net, as well as the installation guide on your own workstation can be found on:
- Isensee, F., Jaeger, P. F., Kohl, S. A. A., Petersen, J. & Maier-Hein, K. H. [nnU-Net: a self-configuring method for deep learning-based biomedical image segmentation](http://www.nature.com/articles/s41592-020-01008-z). Nat Methods 18, 203–211 (2021).
- [nnU-Net GitHub Page](https://github.com/MIC-DKFZ/nnUNet)

## What is this Workshop all about?

The goal of this workshop is to allow end-users to understand how to use nnU-Net for their own applications.

It includes initial setup, and how to use nnU-Net in the Google Colab environment. 
Some steps are only needed for GoogleColab and will be explained, while others are generally applicable. 

Further it is advised to visualize the data with segmentations using the [MITK-Workbench](https://www.mitk.org/wiki/The_Medical_Imaging_Interaction_Toolkit_(MITK)), which is also developed in the Medical Image Computing Division of the German Cancer Research Institute - at least this is what we advocate.

- [MITK Workbench Download Link](https://www.mitk.org/wiki/Downloads)

### Requirements for Google Colab 
1. Google Account
   1. At least 4GB of free disk space
2. Visualization tool for volumetric data, we advise to use MITK.

### Some notes about the Workshop

This workshop was created by **Carsten Lüth**, a PhD student in the [Interactive Machine Learning Research Group](https://www.dkfz.de/en/interaktives-maschinelles-lernen/index.php) headed by Dr. Paul F. Jäger.

If you happen to find this workshop in any way useful, please share this version of it. 

## Further information

Further Information about nnU-Net is presented in the following lectures:
- [Lecture by Paul F. Jäger](https://www.youtube.com/watch?v=3po8qVzz5Tc&t=2196s)
- [Lecture by Fabian Isensee](https://www.youtube.com/watch?v=C6tpnJRpt90)

### MITK with nnU-Net
MITK has a new experimental feature which uses pretrained nnU-Net models as a segmentation tool.
This feature has been added since its release of version 2022.04.
For further information about this we refer to the [MITK Documentation}(https://docs.mitk.org/2022.04/org_mitk_views_segmentation.html#org_mitk_views_segmentationnnUNetTool).

---

<br>

<p align="left">
  <img src="https://polybox.ethz.ch/index.php/s/kqDrOTTIzPFYPU7/download" width="150"> &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Deutsches_Krebsforschungszentrum_Logo.svg/1200px-Deutsches_Krebsforschungszentrum_Logo.svg.png" width="500"> 
</p>

This library is developed and maintained by the Interactive Machine Learning Group of [Helmholtz Imaging](https://www.helmholtz-imaging.de/) and the [DKFZ](https://www.dkfz.de/de/index.html).