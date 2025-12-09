# Winter School 2025: Basic Astro Tutorial

---
Let us assume we want to study an object in the sky. For example, consider Abell 2744, a cluster of 
galaxies. Now, let us ask some questions.
   - **How does Abell 2744 look in the sky?**
      - Abell 2744 is a cluster of galaxies, and it cannot be seen with the naked eye. 
      - We need a telescope (don't try to build a new one).
      - Find which of the existing telescopes has already observed/seen it. 

   - **Where to look?**
      - Depends on wavelength coverage. 
      - Let us restrict ourselves to optical and infrared. 
      For this, we go to MAST (https://mast.stsci.edu/portal/Mashup/Clients/Mast/Portal.html)
      - Abell 2744 was also targeted under the Hubble Frontier Field (HFF) program 
      (https://archive.stsci.edu/prepds/frontier/).
   
   - **Visualisation: HST vs JWST**
      - Data format: .fits
      - Please install these tools: 
         - DS9 (https://sites.google.com/cfa.harvard.edu/saoimageds9/about)
         - TOPCAT (https://www.star.bris.ac.uk/~mbt/topcat/)
      
      - Please download the HST data from HFF website (https://archive.stsci.edu/prepds/frontier/) 
      or click on the following links:
         - [F814W Link](https://archive.stsci.edu/pub/hlsp/frontier/abell2744/images/hst/v1.0-epoch2/hlsp_frontier_hst_acs-60mas-selfcal_abell2744_f814w_v1.0-epoch2_drz.fits)
         - [F105W link](https://archive.stsci.edu/pub/hlsp/frontier/abell2744/images/hst/v1.0-epoch1/hlsp_frontier_hst_wfc3-60mas_abell2744_f105w_v1.0_drz.fits)
         - [F160W link](https://archive.stsci.edu/pub/hlsp/frontier/abell2744/images/hst/v1.0-epoch1/hlsp_frontier_hst_wfc3-60mas_abell2744_f160w_v1.0_drz.fits)

      - For JWST data, please use this website, https://jwst-uncover.github.io/ , or click on the 
      links below:
         - [F115W link](https://s3.amazonaws.com/grizli-v2/JwstMosaics/v7/abell2744clu-grizli-v7.0-f115w-clear_drc_sci.fits.gz)
         - [F150W link](https://s3.amazonaws.com/grizli-v2/JwstMosaics/v7/abell2744clu-grizli-v7.0-f150w-clear_drc_sci.fits.gz)
         - [F277W link](https://s3.amazonaws.com/grizli-v2/JwstMosaics/v7/abell2744clu-grizli-v7.0-f277w-clear_drc_sci.fits.gz)

   
   - **Visualisation: Data analysis**
      - Python (Matplotlib, Numpy, Astropy)