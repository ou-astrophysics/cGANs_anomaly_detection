# cGANs_astronomy
# The Application of cGANs in Astronomy
This repository contains materials covered in *The Application of cGANs* talk in the Deep and Shallow Learning Session of the National Astronomy Meeting from 3rd-7th July 2023. 
\
Contained, in this repository, is a walk through of how to create galaxy cutouts using the JWST CEERS NIRcam imaging data, specifically the public data release 0.5. However, this method of creating cutouts can be used on other imaging data provided raw data and a matching data kernel.
\
The source code for the conditional GAN is also contained within this repository in the form of a walk-through tutorial. If you wish to implement the cGAN with your own data, please see the below section on file structure.

## Data Resources
To follow the Crop_PSF_Match notebook, the [Cosmic Evolution Early Release Survey (CEERS) data realease 0.5](https://ceers.github.io) can be found on the CEERS website [here](https://ceers.github.io/dr05.html). 
\
Data can be downloaded from the above link.

## Data Preparation for the cGAN
You can use the Source Detection and Aperture Photometry notebook to generate the data for the cGAN. This will generate files for each waveband with a *'.fits'* extension containing individual galaxy images. To use the cGAN, the data is loaded from each individual waveband file. An example folder structure is shown below:
\
<img width="472" alt="Dataset-layout" src="https://github.com/RubyPC/cGANs_in_astronomy/assets/106536925/99a173b6-2802-4867-bc4d-2755acb77dfb">


## Some Useful Links
* [JWST User Documentation](https://jwst-docs.stsci.edu/)
* [JWST NIRcam Imaging Information](https://jwst-docs.stsci.edu/jwst-near-infrared-camera)

### References
* [CEERS](https://ceers.github.io)
* [Image-to-Image Translation with conditionl Adversarial Networks](https://doi.org/10.48550/arXiv.1611.07004)
* [Generative Adversarial Networks](https://doi.org/10.48550/arXiv.1406.2661)
