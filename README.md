## Coppercube-Plugin for the free easy-to-use 3D engine from (http://Anbiera.com)



### Description:
Action triggered from currentNode will distibute gems or other items in a circular fashion over a terrain from mCentrNode at max iRadius.

### Inputs:
var | data type | description
--- | --------- | ------------
iRadius | integer | - Max bJewel distance from mCenterNode.
mCentrNode | meshNode | - Center position of circular distribution.
fLibrary | folderNode | - Jewel types (Billboard Nodes) grouped together that will be Clone-ed and parented for active use.
fTreasure | folderNode | - Created bGemNodes Parented to this Folder for active use.
sMannaData | string | - Of arbitrary length, out of Capital Letters coding for goody type.  - For performance sake length should be kept under 50 Letters or so, depending of target platform.
iMannaHeight | integer | - Height to lift lift billboard Jewels off ground.

### outputs:
* there is no return value
