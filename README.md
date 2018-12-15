# A Beginner's Guide to recent Artificial Intelligence Research Papers
*This guide is intended to introduce students of the field to various recent developments that I find particularly cool, relevant or interesting. Rather than provide an in-depth evaluation and analysis of the theories discussed, this guide simply provides a high-level overview suitable for gaining an intuitive understanding.*


* **April 2018, ProGanSR**: To acheive super-resolution, which allows the conversion of low-resolution images to higher-resolution ones, this paper recommends improving the image resolutions through a progressive method. It takes several intermediate steps where the image produced is slightly better than the predecessor, a known as 'curriculum learning'. The paper  uses a GAN rather than simply a CNN. Compared to state-of-the-art models, the images produced using the method proposed in this paper are comprehended with a slightly lower accuracy, however they are produced at 5 times the speed.


* **June 2018, RF-Pose**: The paper provides accurate human pose estimation through walls and occlusions. It leverages the fact that wireless signals in the WiFi frequencies traverse walls and reflect off the human body, and uses a deep neural network approach that parses such radio signals to estimate 2D poses. The pose estimation works well regardless of the lighting conditions, and can also detect multiple humans. In the network, there is a teacher network that looks at the colour image of the wall, and predicts the pose that the human is in. There is also a student network that has the signal as an input, and it learns what the different distributions mean, and how they relate to different human positions and poses. The teacher network shows the student network the correct results, and the student learns how to produce them from radio signals instead of images.


* **August 2018, Phrank**: The algorithm produced automates the most labor-intensive part of genetic diagnosis, that of matching a patient’s genetic sequence and symptoms to a disease described in the scientific literature. Without computer help, this match-up process takes 20 to 40 hours per patient - the process involves the expert looking at a list of around 100 of the patient’s suspicious-looking mutations, making an educated guess about which one might cause disease, checking  scientific literature, and then moving on to the next one. The algorithm developed by Bejerano’s team cuts the time needed by 90 percent. The algorithm’s name, Phrank, a mashup of “phenotype” and “rank,” gives a hint of how it works: it compares a patient’s symptoms and gene data to a medical-literature knowledge base, and then simply generates a ranked list of which rare genetic diseases are most likely to be responsible for the symptoms. Phrank, on average, ranked the true diagnosis 4th on the list of potential diagnoses it generated. 
