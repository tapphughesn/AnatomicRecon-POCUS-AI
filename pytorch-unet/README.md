## pytorch-unet

This directory will hold the pytorch version of the unet we will use in our pipeline, as well as all python scripts concerned with the unet. PyTorch and monai will be used.

### TODO

- write scripts for testing different training strategies
  - special kernel weights loss (domain knowledge) since data is correlated in axis 0 but not so much axis 1
  - downsample images to rectangles to aggregate information in axis 0 closer together
