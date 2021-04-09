---
title: "EEG based Gait Decoding"
excerpt: "An empirical comparison of neural networks and machine learning algorithms for EEG gait decoding  <br/><br/><img src='/images/avatar.png' width='500'/>"
collection: portfolio
---

# Summary
Previous studies of Brain Computer Interfaces (BCI) based on scalp electroencephalography (EEG) have
demonstrated the feasibility of decoding kinematics for lower limb movements during walking. In this
computational study, we investigated offline decoding analysis with different models and conditions
to assess how they influence the performance and stability of the decoder. Specifically, we conducted
three computational decoding experiments that investigated decoding accuracy: (1) based on delta
band time-domain features, (2) when downsampling data, (3) of different frequency band features.
In each experiment, eight different decoder algorithms were compared including the current stateof-
the-art. Different tap sizes (sample window sizes) were also evaluated for a real-time applicability
assessment. A feature of importance analysis was conducted to ascertain which features were most
relevant for decoding; moreover, the stability to perturbations was assessed to quantify the robustness
of the methods. Results indicated that generally the Gated Recurrent Unit (GRU) and Quasi Recurrent
Neural Network (QRNN) outperformed other methods in terms of decoding accuracy and stability.
Previous state-of-the-art Unscented Kalman Filter (UKF) still outperformed other decoders when using
smaller tap sizes, with fast convergence in performance, but occurred at a cost to noise vulnerability.
Downsampling and the inclusion of other frequency band features yielded overall improvement in
performance. The results suggest that neural network-based decoders with downsampling or a wide
range of frequency band features could not only improve decoder performance but also robustness with
applications for stable use of BCIs.

<br/><img src='/images/avatar.png' width='500'/>"

# Outputs:
Nakagome S, Luu TP, He Y, **Ravindran AS**, and Contreras‐Vidal JL. An empirical comparison of neural net‐
works and machine learning algorithms for EEG gait decoding. Scientific Reports 2020;10:1–17. DOI:
10.1038/s41598‐020‐60932‐4.

