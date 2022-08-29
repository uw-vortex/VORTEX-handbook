# Equipment list

**This is a living document and will be updated periodically as we get more equipment in the lab**

This resource provides an overview of the equipment in the lab, directions to find operating manuals and SOPS, as well as instructions how to book equipment for testing. We invite both internal VORTEX Lab users, as well as external visitors to take a look and see what our lab has to offer.

## Ultrasounds & Accessories
**USPlatform**: This open-platform ultrasound from US4US allows us complete access to the raw radiofrequency data of our acquisitions, thereby allowing highly customizable data processing and analysis solutions. We work in collaboration with Dr. Alfred Yu in Electrical & Computer Engineering to process this data into pixel-level blood velocity information for vector flow imaging, vector projectile imaging, blood velocity waveform reconstruction, and much more. Given the flexibility in beamforming, we are able to acquire images at upwards of 1000 fps as a high frame rate ultrasound (HiFRUS) modality, which allows high temporal sensitivity to intra-beat vascular dynamics.

**Mindray M5**: This clinical ultrasound is a piece of legacy equipment from Dr. Rich Hughson and is the workhorse behind the conventional ultrasound measures performed in the lab. We have linear and cardiac probes, in addition to audio export to send Doppler information to expert data processing software.

**Vivid iq**: This clinical ultrasound is a small portable unit that is the workhorse of the lab. We have linear and sector probes for vascular and cardiac imaging. Extremely versatile, the Vivid is mostly used to measure arterial and venous diameters and blood velocities using B-mode, Doppler, and Duplex imaging.

**ProbeFix Dynamic**: This custom probe holder from Usono is designed to work with a variety of ultrasound probes during exercise. We are excited to start working with this equipment and will be happy to share the accuracy and feasibility of the device in the next few years.

## Pulse Wave Analysis
**NIHem Workstation**: This workstation from Cardiovascular Engineering Inc. is dedicated to comprehensive pulse wave acquisition and analysis. The unit includes two fingertip tonometers, central data acquisition unit, brachial blood pressure cuff with integrated  microphone, as well as an analysis Tablet on a portable stand. This unit is capable of measuring carotid-femoral pulse wave velocity (cfPWV), pressure wave decomposition (Pf and Pb), and characteristic impedance (Zc).

## Software
**SpecTat**: We use an in-house vascular speckle-tracking program for arterial wall kinematic analyses, and was developed in MATLAB by Jimmy Tat, MD, in 2013. In brief, this program identifies up to two rectangular regions of interest and tracks pixel positions over time to measure 2D wall displacement (axial and radial directions). Speckle-tracking is one of the only methods to measure carotid artery longitudinal wall motion and is a cornerstone of our post-processing tools in the lab.

**FloWave**: We have chosen to use an open-source edge-detection software to analyze arterial diameters in the lab. FloWave is coded in MatLab and is a versatile program that can be customized for different ultrasound models. Like any edge-detection software, it searches for high contrast borders between the arterial lumen and intima-media complex to denote wall boundaries. FloWave differs from commercially-available programs because it is FREE and the lab has the necessary programming expertise to run in-house analysis and post-processing of arterial diameter waveform information. The software has been validated on arterial phantoms, with additional details found in Coolbaugh et al. (2016) J Appl Physiol 121(4):849-857 https://doi.org/10.1152/japplphysiol.00819.2015.
