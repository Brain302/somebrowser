# somebrowser
openworm time browser functional design concept (for brevity only AVBL, AVBR left into brain. 2 big yellow columns in top left corner. 2 perspectives of the worm are given - from side and from top)
<br><img src= "https://github.com/Brain302/somebrowser/blob/master/worm_void.jpg?raw=true">
<br>which is 3D (worm2D diagram vs time) representation of this chart
<br><img src="https://github.com/openworm/OpenWorm/blob/master/img/neuron-activity.png?raw=true" width=200>
<br>the main purpose is to help to trace signals through connectome. some tools are added to find possible links starting from the neuron selected.
<br>simple exampl from DD1:
<br><img src ="https://github.com/Brain302/somebrowser/blob/master/worm_DD1_cascade.jpg?raw=true">
<br>more complicated cascade from AVBL:
<br><img src ="https://github.com/Brain302/somebrowser/blob/master/worm_ABVL_cascade.jpg?raw=true">
<br>all potential links can be hinted between neurons. or all links (which is messy)
<br><img src = "https://github.com/Brain302/somebrowser/blob/master/worm_connectome.jpg?raw=true">
<br>slices are also provided to if this would help to clear the mess. Number of slices can be chosen (here 5). And start number gradually changed from 0 to 50 which can make it a movie-like mode
<br><img src = "https://github.com/Brain302/somebrowser/blob/master/worm_slices.jpg?raw=true">
<br>because of the file's light weight could be added to docker experiment output
<br>
<br>html file attached, however it was created only for screenshot purposes and might not work. the main purpose is to discuss what functioalities can be added and where it can be used, which 3D framework fits the best (currently three.js), and its possible input data sources
