# Topics

## MR Basics

- MRI_magic: What is the measured signal  
- From signal to image
- MR Glossary

## Data Structure and Organization

- Dicom to Nifti
- Interacting with neuroimaging data
- BIDS
- Defacing

## Preprocessing

- Structural images
  - Intensity correction (bias (field) correction, inhomogeniety correction)
  - Brain extraction
	- Spatial Normalization
	- Segmentation and Parcellation
- Functional images
  - Distortion correction
  - Motion estimates
  - Slice timing
  - Co-registration 
  - Spatial normalization
  - Smoothing
- How to do all of this: `fmriprep`
  - Steps it runs
  - Outputs
- Quality control 
  - MRI-QC: sMRI Quality Control  
  - QC of fmriprep outputs

## Data analysis 

- Encoding
  - GLM
    - Design matrix
    - Convolution and filtering
	- How to deal with RT
- Decoding (MVPA)
  - [pyMVPA](http://www.pymvpa.org/)
  - [Brainiak](https://brainiak.org/)
- RSA
	- [One example toolbox](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003553)
- Intersubject synchronization
- Latent state discovery

## Visualization

## Data sharing/finding

- [Openneuro](https://openneuro.org/)
- [Neurovault](https://neurovault.org/)
- [Neurosynth](https://neurosynth.org/)
  - [Neurosynth Compose](https://compose.neurosynth.org/)
- [Neuroquery](https://neuroquery.org/)

## Getting help

- [Neurostars](https://neurostars.org/)

## Resources

https://dartbrains.org/content/intro.html  
https://naturalistic-data.org/content/intro.html  
https://mriquestions.com/  
https://miykael.github.io/nipype_tutorial/  
https://carpentries-incubator.github.io/SDC-BIDS-sMRI/  
https://lukas-snoek.com/NI-edu/