# Brainlab

1.**Description of the platform/product**:
 * **name and version of the software**: Brainlab SmartBrush 2.1 and Brainlab SmartViewer 3.1; SmartViewer can only display DICOM SEG; SmartBrush can create SEG and display them, however SmartViewer displays them much better
 * **free?** no
 * **commercial?** yes
 * **open source?** no 
 * **what DICOM library do you use?** [Merge DICOM Toolkit](http://www.merge.com/Solutions/Toolkits/Merge-DICOM-Toolkit.aspx), however the toolkit does not provide API for handling DICOM SEG objects, so all of the features related to handling DICOM SEG had to be implemented

2.**Description of the relevant features of the platform**: 
 * **are both single and multiple segments supported?** Current version of Brainlab SmartBrush can write only single-segment objects, but reads both single- and multi-segment 
 * **how are the overlapping segments handled?** User can see the outline of the contour.

 * **do you support both BINARY and FRACTIONAL segmentation types?** Brainlab always exports segmentations as FRACTIONAL type and RLE-compressed
 * **do you render the segment using the color specified in the DICOM object?** *TBD*
 * **how do you communicate segment semantics to the user?** *TBD*
 * **how do you support the user in defining the semantics of the object at the time segmentation is created?** *TBD*

3.**Read task**: load each of the DICOM SEG datasets that accompany the imaging series into your platform

**Test dataset #1**

| Test dataset | Result of rendering |
| -- | -- |
| 3D Slicer | <img src="./brainlab/brainlab-read-lidc.png" width=250> |

**Test dataset #2**

| Test dataset | Result of rendering |
| -- | -- |
| Brainlab | <img src="./brainlab/brainlab-read-seg2.png" width=250> |

**Test dataset #3**

| Test dataset | Result of rendering |
| -- | -- |
| 3D Slicer | <img src="./brainlab/brainlab-read-hnc.jpg" width=250> <img src="./brainlab/brainlab-read-hnc-measurements.jpg" width=250>|

**Test dataset #4**

| Test dataset | Result of rendering |
| -- | -- |
| 3D Slicer | <img src="./brainlab/brainlab-read-prostate.jpg" width=250> |


4.**Write task**




