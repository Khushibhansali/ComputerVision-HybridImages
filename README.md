**Hybrid Images**

The goal of this project was to implement image filtering and use it to create hybrid images using a simplified version of the SIGGRAPH 2006 paper by Oliva, Torralba, and Schyns. Hybrid images are static images that change in interpretation as a function of the viewing distance. The basic idea is that high frequency tends to dominate perception when it is available, but, at a distance, only the low frequency (smooth) part of the signal can be seen. By blending the high frequency portion of one image with the low-frequency portion of another, you get a hybrid image that leads to different interpretations at different distances.

For the purposes of the project, we picked the following values: 
Left Image Sigma 1.5, Right Image Sigma 5.1, Left Image Kernel Size 7, Right Image Kernel Size 8, Left Image low pass, Right Image high pass, Mix-in ratio 0.5, Scale factor 1.5
