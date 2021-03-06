# CNN_tablentennis

Implement with the idea in SO-DLT([Transferring Rich Feature Hierarchies for Robust Visual Tracking](https://arxiv.org/abs/1501.04587)).

And also Faster R-CNN([Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks](https://arxiv.org/abs/1506.01497))

# Installation

1. Clone this repo with the submodule, which is our fork from caffe.(TODO)
```
git clone --recursive <this repo>
```
2. `cd` to the customized caffe directory, install caffe using cmake, in order for our cpp interface to find the install path of caffe.
```
cd caffe
mkdir build
cd build
cmake ..
make all
make install
make runtest
```
3. Download our caffe model weights from...(TODO)

4. Run the jupyter notebook, or the cpp interface(TODO)

# Screenshots

See more detail in the jupyter notebook :)

output probability map

![probability map](http://7xrcar.com1.z0.glb.clouddn.com/prob_map.png)

regress a bounding box

![bounding box](http://7xrcar.com1.z0.glb.clouddn.com/regression.png)

tracking

![tracking](http://7xrcar.com1.z0.glb.clouddn.com/tracking.png)
