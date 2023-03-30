## An evaluation of the Action Potential Shape discrimination between cell-types

This series of notebooks is the start of an analysis of APs derived from Electrophysiological Recordings In general APs were extracted using our recently developed Tool BiophysicalEssentials (BPE).Since BPE is still in active development, currently the code cannot be shared, we will let you know whenver it is possible to use BPE and the corresponding GUI! 
<br>
his Notebooks will be later implemented in the BPE Toolsuite, whenever validated with more data, corresponding to different cell types. For this recordings are currently ongoing.

In general waveforms look like this:
<img src="/Images/APshape.png" alt="Alt text" title="Action Potential Shape between two Cell types">
As you can see from the shapes, there are distinct differences in the shape of an AP from different type of neurons. This aims to collect multiple shapes from different cell types and provided an atlas for these cell types.

We further were able to discriminate these characterstics by certain parameters extracted from these APs.
<br>
<img src="/Images/APMarkerPCA.png" alt="Alt text" title="PCA between cell types based on AP markers">
<br>
In addition we started building classifiers to extract meaningfull features that might be most important in the discrimination process. This will be extended whenever more data is collected here and will be provided as in-build classifier in *BPE*. 
<br>
Here an example classifier 
<br>
<img src="/Images/DecisionTreeBounds.png" alt="Alt text" title="Discriminate Features from APs">
<br>
This will also help to see if we can predict certain diseases just by the nature of the spike wave occurence.

