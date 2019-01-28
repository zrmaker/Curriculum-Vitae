# Renyuan Zhang (Leo), Ph.D.

Ph.D. in Electrical and Computer Engineering
University of Arizona
Tucson, AZ 85721

```
Phone: (520) 878-8630
Email: ryzhang@email.arizona.edu
LinkedIn: https://www.linkedin.com/in/zrmaker/
GitHub: zrmaker
```
## Objective

```
Seeking full time opportunity in automotive radar, radar signal processing and autonomous driving. Expected
to graduate May 2019.
```
## Education

```
Ph.D. in Electrical and Computer Engineering Aug. 2015 - Present
University of Arizona
Research interest: radar signal processing, micro-Doppler signatures, sensor fusion, non-coherent integration,
machine learning, synthetic aperture radar.
```
```
M.S. in Optical Sciences Aug. 2013 - Aug. 2015
University of Arizona
Research interest: optical imaging, medical imaging, optical coherence tomography.
```
```
B.S. in Optoelectronic Engineering Sept. 2009 - June 2013
Chongqing University
```
```
Udacity Self-Driving Car Nanodegree Oct. 2017 - Sep. 2018
Udacity
```
## Professional Experience

```
Research Assistant at Department of Electrical and Computer Engineering 2015 - Present
Advisor: Dr. Siyang Cao,University of Arizona.
```
- Developing multi-target multi-input camera-radar fusion and classification.
- Researching non-synchronized incoherent MIMO radar angle resolution improvements.
- Researching radar point cloud clustering and detection by machine learning method.
- Developing CUDA algorithms on radar signal processing.
- Researching on radar target clustering and classification.
- Achieved human behavior detection via CNN using micro-Doppler signatures by mmWave radar.
- Realized radar interference detection, classification and mitigation using SVM.
- Completed 3D imaging millimeter wave circular SAR using single transceiver and compressed sensing.

```
Sensor Engineer Intern at TuSimple Sept. 2017 - Mar. 2018
TuSimple LLC©R, Tucson, AZ.
```
- Developed and evaluated Autoliv©R77 GHz multi-mode radar ROS driver.
- Developed Bosch©R77 GHz long-range radar and mid-range radar ROS driver.
- Evaluated Delphi©R77 GHz electronic scanning radar.
- Finished Hokuyo©R URG-04LX-UG01 Scanning Laser Rangefinder development and truck trailer moni-
    tor/filter project.
- Written industrial radar signal filtering and target recognition.

```
Research Assistant of Nonlinear Optics at College of Optical Sciences 2014 - 2015
Advisor: Dr. Khanh Kieu,University of Arizona.
```
- Developed and analyzed with hospitals using fiber based SD-OCT.


## Skills

```
Programming: Python, Mathworks©R MATLAB, R, NI LabVIEW, C/C++/C#, JAVA.
Sensors: Radar, LiDAR, CMOS camera, CCD camera, sonar, microphone and Microsoft©RKinect.
Machine Learning: SVM, ANN, CNN, RNN,k-NN,k-means, naive Bayes, decision tree and mixture model
(Gaussian).
CAD & Production: SOLIDWORKS, Autodesk©R AutoCAD and Adobe©R Creative Cloud (Photoshop, Illus-
trator, Premiere Pro).
RF & EM: ANSYS©REM suite and Keysight©RADS.
Operating Systems: Windows and Ubuntu.
Embedded Systems: NI©R control and acquisition suites and Arduino.
Others: Digital signal processing (DSP), imaging processing, robotic operating system (ROS),
Nvidia©R CUDA, source control (git) and controller area network (CAN).
Algorithms: C++ library for DSP on mmWave radar; SLAM; point cloud machine learning; radar
micro-doppler signatures.
```
## Projects

```
Non-synchronized integration using multiple FMCW MIMO radars
```
- In this project, the non-synchronized integration of multiple frequency-modulated continuous-wave (FMCW)
    radars is presented. A phase error deduction method on different nonsynchronized radars using trust-
    region-reflective least squares algorithm is introduced. Better angle of arrival (AoA) estimation, better an-
    gular resolution and better side lobes deduction are realized in experimental result. Therefore, integrating
    multiple independent radar systems to emulate a large aperture is achieved.
- Paper:
    **R. Zhang** and S. Cao, "Non-Synchronized Integration using Multiple Radars via Least Squares Fitting," 2019
    IEEE Radar Conference. (submitted Oct. 2018) mmWave radar.

```
Human behavior detection and classification using micro-Doppler signature
```
- A real-time behavior detection system using millimeter wave (mmWave) radar is presented in this project.
    Radar is used to sense the micro-Doppler information of targets. A convolution neural network (CNN) is
    further implemented in the detecting and classifying the human motion behaviors using this information.
    Both the convolution layers and architecture of CNNs are presented. The analysis on loss and accuracy of
    training results are also shown. The experimental result indicates a precise determination of human motion
    behavior detection using the proposed system.
- Paper:
    **R. Zhang** and S. Cao, "Real-time Human Motion Behavior Detection via CNN using mmWave Radar,"IEEE
    Sensors Letters.
    F. Jin, **R. Zhang** et al., "Multiple Patients Behavior Detection in Real-time using mmWave Radar and Deep
    CNNs,"2019 IEEE Radar Conference. (submitted Oct. 2018)

```
Radar point cloud clustering and machine learning
```
- In this project, a robust and adaptive radar point cloud clustering algorithm, named radar elliptical density-
    based spatial clustering of applications with noise (REDBSCAN), is presented. The proposed algorithm
    shows a better clustering results for adapting to arbitrary shape of targets as well as any number of targets
    comparing with traditional clustering methods. The algorithm is presented, and is implemented in exper-
    iments using the state-of-art millimeter wave (mmWave) radar sensor with multiple-input multiple-output
    (MIMO) antennas. The related signal processing chain and the clustering outcomes are also discussed.
- Paper:
    **R. Zhang** and S. Cao, "Robust and Adaptive Radar Elliptical Density-Based Spatial Clustering and Labelling
    for mmWave Radar Point Cloud Data,"2019 IEEE Radar Conference. (submitted Oct. 2018)

```
Automotive radar interference detection, classificationa and mitigation
```
- The project studies classification of the automotive radar interference waveforms via support vector machine
    (SVM). Automotive radar implemented in advanced driver assistance systems (ADASs) is an essential sen-
    sor in road traffic safety, e.g., moving target indication, collision avoidance and enhanced navigation system.
    However, radar-to-radar interference is inevitable as the number of automotive radar increases. Our work


```
shows different types of radar-to-radar interference with analyzing the received signal. Providing linear
frequency modulated transmitting (LFM) signal, filtering and dechirping techniques, the classification of
six different types of radar-to-radar interference are presented and analyzed. Time-frequency domain signal
and range-doppler profiles of different types of interference are simulated. The machine learning classifier
of SVM of multi-class high-dimensional waveform data classification is used to classify different interfer-
ence waveforms and noninterference waveforms. Random produced dataset is cross validated through the
SVM classifier. Different types of interference prediction accuracies are shown and verified by the proposed
method. The confusion matrix of interference and noninterference, detecting different types of interference
and classifying all incoming receiving signal are presented.
```
- Paper:
    **R. Zhang** and S. Cao, "Support vector machines for classification of automotive radar interference," 2018
    IEEE Radar Conference (RadarConf18), Oklahoma City, OK, 2018, pp. 0366-0371.

3D imaging millimeter wave circular synthetic aperture radar

- In this project, a newmillimeter wave 3D imaging radar is proposed. The user just needs to move the
    radar along a circular track, a high resolution 3D imaging can be generated. The proposed radar uses
    the movement of itself to synthesize a large aperture in both the azimuth and elevation directions. It can
    utilize inverse Radon transform to resolve 3D imaging. To improve the sensing result, compressed sensing
    approach is further investigated. The simulation and experimental result further illustrated the design.
    Because a single transceiver circuit is needed, a light, affordable and high resolution 3D mmWave imaging
    radar is illustrated.
- Paper:
    **R. Zhang** and S. Cao, "3D Imaging Millimeter Wave Circular Synthetic Aperture Radar,"Sensors, vol. 17,
    no. 6, p. 1419, June 2017.
    **R. Zhang** and S. Cao, "Compressed Sensing For Portable Millimeter Wave 3D Imaging Radar,"2017 IEEE
    Radar Conference (RadarConf), Seattle, WA, USA, May 2017, pp. 0663-0668.
    **R. Zhang** and S. Cao, "Portable Millimeter Wave 3D Imaging Radar,"2017 IEEE Radar Conference (RadarConf),
    Seattle, WA, USA, May 2017, pp. 0298-0303.

Optical coherence tomography

- Spectral Domain Optical Coherence Tomography (SD-OCT) is introduced in this project. In comparison to
    the first generation Time Domain Optical Coherence Tomography (TDOCT), SD-OCT is superior in terms
    of its capturing speed, signal to noise ratio, and sensitivity. The SD-OCT has been widely used in both
    clinical and research imaging. The primary goal of this research is to design and construct a Spectral
    Domain Optical Coherence Tomography system which consists of a fiber-based imaging system and a
    line scan CCD-based high-speed spectrometer, and is capable of imaging and analyzing biological tissue
    at a wavelength of 1040 nm. Additionally, a NI LabVIEW software for controlling, acquiring and signal
    processing is developed and implemented. An axial resolution of 16.9 micrometer is achieved, and 2-D
    greyscale images of various samples have been obtained from our SD-OCT system. The device was initially
    calibrated using a glass coverslip, and then tested on multiple biological samples, including the distal end
    of a human fingernail, onion peels, and pancreatic tissues. In each of these images, both tissue and cell
    structures were observed at depths of up to 0.6 millimeter. The A-scan processing time is 8.445 millisecond.
    Our SD-OCT system demonstrates tremendous potential in becoming a vital imaging tool for clinicians and
    researchers.
- Thesis:
    **R. Zhang** and K. Kieu, "Fiber Based Spectral Domain Optical Coherence Tomography: Mechanism and
    Clinical Applications,"University of Arizona, 2015.

Multi-target multi-input camera-radar sensor fusion and classification

- In this project, comprehensive sensor fusion by automotive radar and camera is studied. Motion based
    multi-target tracking and classification is achieved. Implemented micro-Doppler signature machine learn-
    ing, region CNN and YOLO allows the target recognition and classification. In this project, the better target
    detection and tracking and the better target recognition and classification using dual sensors are realized.
- Paper in progress.

CUDA on radar signal processing


- Using CUDA libray to optimize radar signal processing chain is fully researched in this project. Improved
    automotive radar algorithms are coded via C and Python. The time cost for signal processing is largely
    reduced and the mass processing to obtain range-Doppler-azimuth response and STAP is greatly improved
    in this project.

```
Smart antenna on automotive radars
```
- In this project, a circular smart antenna for automotive radar is designed. The smart antenna can enhance
    the receiving power from designated directions. The antenna pattern and array factors are presented.

```
Automotive radar SAR terrain mapping
```
- The synthetic aperture terrain mapping by emulating multiple apertures over automotive patch antenna is
    achieved in this project. The automotive radar is fused with GPS and IMU to get the ground truth. The
    automotive radar terrain mapping is conducted on autonomous driving test vehicle of ECE department of
    University of Arizona.

## Publications

Journal Articles

```
R. Zhang and S. Cao, "Real-time Human Motion Behavior Detection via CNN using mmWave Radar,"IEEE
Sensors Letters.
R. Zhang and S. Cao, "3D Imaging Millimeter Wave Circular Synthetic Aperture Radar,"Sensors, vol. 17, no. 6,
p. 1419, June 2017.
```
Proceedings

```
R. Zhang and S. Cao, "Non-Synchronized Integration using Multiple Radars via Least Squares Fitting," 2019
IEEE Radar Conference. (submitted Oct. 2018)
R. Zhang and S. Cao, "Robust and Adaptive Radar Elliptical Density-Based Spatial Clustering and Labelling
for mmWave Radar Point Cloud Data,"2019 IEEE Radar Conference. (submitted Oct. 2018)
F. Jin, R. Zhang et al., "Multiple Patients Behavior Detection in Real-time using mmWave Radar and Deep
CNNs,"2019 IEEE Radar Conference. (submitted Oct. 2018)
R. Zhang and S. Cao, "Support vector machines for classification of automotive radar interference,"2018 IEEE
Radar Conference (RadarConf18), Oklahoma City, OK, 2018, pp. 0366-0371.
R. Zhang and S. Cao, "Compressed Sensing For Portable Millimeter Wave 3D Imaging Radar,"2017 IEEE Radar
Conference (RadarConf), Seattle, WA, USA, May 2017, pp. 0663-0668.
R. Zhang and S. Cao, "Portable Millimeter Wave 3D Imaging Radar,"2017 IEEE Radar Conference (RadarConf),
Seattle, WA, USA, May 2017, pp. 0298-0303.
```
Dissertation and Thesis

```
R. Zhang and K. Kieu, "Fiber Based Spectral Domain Optical Coherence Tomography: Mechanism and Clinical
Applications,"University of Arizona, 2015.
```
