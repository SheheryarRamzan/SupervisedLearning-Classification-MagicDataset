# SupervisedLearning-Classification-MagicDataset
Explore the world of classification algorithms with our open-source repository! This project focuses on supervised learning techniques to classify the MagicDataset, allowing users to experiment with various classifiers. Train and evaluate models on this dataset to gain insights into classification performance.

There is a gamma telescope with all the high-energy particles hitting the detector. It records specific patterns of how light hits the camera and we can use properties of those patterns to predict what type of particle caused that radiation whether it was a hadron or gamma particle. 

Dataset link: https://archive.ics.uci.edu/dataset/159/magic+gamma+telescope

Attribute Information

    1.  fLength:  continuous  # major axis of ellipse [mm]
    2.  fWidth:   continuous  # minor axis of ellipse [mm] 
    3.  fSize:    continuous  # 10-log of sum of content of all pixels [in #phot]
    4.  fConc:    continuous  # ratio of sum of two highest pixels over fSize  [ratio]
    5.  fConc1:   continuous  # ratio of highest pixel over fSize  [ratio]
    6.  fAsym:    continuous  # distance from highest pixel to center, projected onto major axis [mm]
    7.  fM3Long:  continuous  # 3rd root of third moment along major axis  [mm] 
    8.  fM3Trans: continuous  # 3rd root of third moment along minor axis  [mm]
    9.  fAlpha:   continuous  # angle of major axis with vector to origin [deg]
   10.  fDist:    continuous  # distance from origin to center of ellipse [mm]
   11.  class:    g,h         # gamma (signal), hadron (background)

   g = gamma (signal):     12332
   h = hadron (background): 6688
