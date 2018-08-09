# PsyDream

It uses a convolutional neural network to find and enhance patterns in images via algorithmic pareidolia
 , thus creating a dream-like hallucinogenic  and psycahdelic appearance in the deliberately over-processed images.
 
 The software is designed to detect faces and other patterns in images, with the aim of automatically classifying images.
 However, once trained, the network can also be run in reverse, being asked to adjust the original image slightly so that a given output neuron (e.g. the one for faces or certain animals) yields a higher confidence score. This can be used for visualizations to understand the emergent structure of the neural network better, and is the basis for the DeepDream concept
 . However, after enough reiterations, even imagery initially devoid of the sought features will be adjusted enough that a form of pareidolia results, by which psychedelic and surreal images are generated algorithmically. The optimization resembles Backpropagation
 , however instead of adjusting the network weights, the weights are held fixed and the input is adjusted. 
