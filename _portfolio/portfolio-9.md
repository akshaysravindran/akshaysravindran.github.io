---
title: "VitalSens"
excerpt: "Wearable devices for physiological vital signal measurement  <br/><br/><img src='/images/vital sense.PNG' width='500'/>"
collection: portfolio
---

These were some of the main projects I worked on during my one year research internship at Indian Institute of Technology, Madras under the Health Technology Innovation Center. My introduction to formal research started from the center. The center was directed by Dr. Mohansankar and I worked under the supervision of by Mr. Preejith S.P (Lead System Designer). <br>

# Projects
* **Estimating blood oxygen saturation using custom wearable device** <br>
  A wrist worn device with a custom finger probe assembly which can continuously measure SpO2 by eliminating motion artifacts using accelerometer data was developed. The accuracy of the device in measuring SpO2 values in the range 80-100 was validated using a Fluke ProSim 8 SpO2 simulator. The efficiency in eliminating motion corrupted signals was also validated in a controlled setting on 40 healthy volunteers.
  <br/><img src='/images/vital sense1.PNG' width="500"/>>
  
    
* **Cuffless blood pressure measurement using pulse transit time (PTT)**<br>
An prototype acquisition system  was made on perfboard which had a 3 channel Photoplethysmogram (PPG) and a single channel Electrocardiogram (ECG) which was put inside an insulated enclosure. A separate PCB was designed and manufactured which had provisions for acquiring 4 channels of PPG, 1 channel ECG and 1 channel accelerometer. The signals were interfaced with Labview and a VI was created to change the intensity and view the signals in real time. A separate VI was created which would load the saved data, does a zero phase low pass filtering, segmenting each cycle and identifies the a)valley point of PPG b)maximum of first derivative point on PPG c)intersection tangent point on PPG ,computes the Pulse Arrival Time (PAT) and PTT by comparing with the ECG and PPG signals and stores all these to a file. Analysis was also performed in matlab where in a script was made that would calculate the PAT and PTT from the acquired signals.<br>

* **EMG based Fatigue Detection**<br>
Guided a team of 4 interns from NIT Trichy on making a prototype of a device capable of detecting muscle fatigue from Electromyography (EMG) signals obtained from the muscle of interest. Testing a custom circuit board developed to collect EMG on 5 individuals and observed that there exists a reduction in the median frequency with time when one engages in intense exercise. <br>

* **Decoding hand movements from muscle activity using neural networks**<br><br>
Guided an intern on implementing gesture recognition from the acquired Electromyography (EMG) signals using Muscle sensor V3, corresponding to seven different movements. An Artificial Neural Network Model was implemented in Matlab to serve as the classifier. A test error rate of 4 percent was obtained.<br>



# Outputs: 
Preejith S, **Ravindran AS**, Hajare R, Joseph J, and Sivaprakasam M. A wrist worn SpO2 monitor with custom finger probe for motion artifact removal. 2016 38th Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC) 2016:5777–80. DOI: 10.1109/EMBC.2016.7592040.

