Surface-defined ROIs
====================

pycortex supports a method of defining surface ROIs using Inkscape. The ROIs are rendered as surface textures in the viewers, and roi masks can be extracted using helper functions.


Extracting ROI masks for existing ROIs
--------------------------------------

If ROIs have already been defined for a given subject, volume masks can be 
retrieved for them using the ``cortex.get_roi_mask`` and 
``cortex.get_roi_masks``.
