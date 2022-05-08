# Surface Mining Screening

This notebook demonstrates a method for identifying areas of surface mining activity. The notebook combines methods based on vegetation loss and water detection. 

Although the notebook aids in detecting these areas, further verification by government agencies or institutions are required to validate the operations on the ground.

The notebook uses Normalised Difference Vegetation Index (for sentinel-2) or the Radar Vegetation Index (for sentinel-1) to determine vegetation loss, where loss occurs if the change in vegetation index is negative. DE Africa's WOfS product is used to identify water.

The final product identifies pixels that exhibit vegetation loss, and the presence of water.

In most cases, these algorithms can be used to identify clusters of pixels that have experienced change and allow targeted investigation of those areas by local or regional governments.