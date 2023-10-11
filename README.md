# OLFWWMOT
Orthogonalized layer features with Wavelet for Multi-Object Tracking
We basically base on the architecture of FairMOT (https://github.com/ifzhang/FairMOT.git) 

Here is an example of our Object Layering's main process:
![Fig1](https://github.com/BrandonYan113/OLFWWMOT/blob/main/Fig1.bmp)
Two red boxes in the image intersect, and there is mutual fusion of the feature representations based on the target center. The yellow arrow represents a tow-dimensional orthogonal decomposition, which ensures orthogonal complementarity between targets in different layers. The blue arrow represents non-maximum suppression between detections in different layers.

Here is our backbone framework:
![Fig3](https://github.com/BrandonYan113/OLFWWMOT/blob/main/Fig3.bmp)
Our architecture performs different tasks at different resolutions.

Below are our best results in the MOT20 benchmarks:
![MOT20result](https://github.com/BrandonYan113/OLFWWMOT/blob/main/MOT20result.PNG)
For more competition details, you can visit the MOTChallenge benchmark website at (https://motchallenge.net), where you can find information about our model called OLFWMOT.
