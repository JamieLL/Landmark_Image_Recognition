## Building An Accurate Detector for Masked Faces in the Pandemic Era

#### Summary
Since we have seen the first Covid case in the U.S. back in March, it has already been eight months. In a time of deep uncertainty, people learned to cope with coronavirus by wearing masks, washing hands, and keeping social distances. However, with cooler weather and pandemic fatigue, we have seen spikes in both cases and hospitalization worldwide.

To help society to mitigate the spread of Covid-19 and to raise people's awareness of the importance of wearing masks, we proposed a method of using an algorithm at the entrances of public places, such as markets, grocery stores, and offices, to monitor whether people wear masks. The algorithm is also designed to remind them if they did not follow the experts' mask-wearing guidelines, that is, not wear masks correctly. Furthermore, the face recognition model can recognize people’s faces and give their names as well.

In the first phase, we have already reached 99.6% accuracy of predicting whether people have worn a mask or not from static images. In the second phase, we searched for two new datasets with better quality for our purposes, the MAFA for wearing correctness check and the MFR2 for masked face recognition.

We also further utilized the algorithm that we raised in phase one to build and train three new classifiers, including wearing correctness, unmasked face recognition and masked face recognition. In the end, we tried to deploy the models in a near real-world scenario to detect multiple faces from a surveillance camera, suggest whether each of the people captured in the images wears the mask and wears it correctly and bring out their names.
