
The main goal is to recognize patterns in particle events in neutrino detectors of liquid argon using the new algorithms based on tensor networks. We have the training and test images from  http://deeplearnphysics.org/.

The images are simulations of recordings of neutrino events topologies in a liquid argon detector. Examples of these recordings in a real experiments (ProtoDUNE) are here: https://www.youtube.com/watch?v=gI-u6j_tp1I.

Events are storaged in the following page: https://www.phy.bnl.gov/twister/bee/set/protodune/gallery/event/list/



WORKFLOW:
=========



Tasks 1:

Study available open-source algorithms of TN for MNIST:

-MPS @ Pytorch (https://github.com/jemisjoky/TorchMPS)

-Tensor networks @ Tensorflow (link is coming)

Note: Here, someone can study more in-depth all libraries and classes of these backends

Tasks 2:

-Develop the tutorials of http://deeplearnphysics.org/

Mainly:

a) Interpret the data readers of images

b)  Browsing and semantic segmentation

c) Convolutional neural networks for training and testing 

These tutorials need the following background programs:

*ROOT (>6.0)

*Larcv2

*Tensorflow

*Pytorch

Tasks 3:

-Merge algorithms of MPS and TN to classify neutrino events using the open data from DL physics  http://deeplearnphysics.org/.

-Evaluate the possibility of incorporating DMRG in the optimization tasks
