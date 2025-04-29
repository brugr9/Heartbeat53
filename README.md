# Unreal Engine Project "Heartbeat" &ndash; Readme

* Author: Copyright 2025 Roland Bruggmann aka brugr9
* Profile on Epic Games Marketplace FAB: [https://www.fab.com/sellers/brugr9](https://www.fab.com/sellers/brugr9)
* Profile on Epic Developer Community: [https://dev.epicgames.com/community/profile/PQBq/brugr9](https://dev.epicgames.com/community/profile/PQBq/brugr9)

---

![Animation Screenshot of Map_LSL_Demo PIE, Heartbeat Update](Docs/MapLSLDemoPIE-HeartbeatUpdate.gif)

![UE Project Heartbeat in Epic Games Launcher](Docs/UEProjectHeartbeat-EpicGamesLauncher.png "UE Project Heartbeat in Epic Games Launcher")

Unreal Engine Project "Heartbeat" &mdash; Heart Rate Monitoring Integration

<div style='page-break-after: always'></div>

## Description

An Unreal&reg; Engine project as proof-of-concept for receiving physiological data from Polar&reg; H10 heart rate monitor.

* Index Terms:
  * Physiological Measuring, Electrocardiogram, Heart Rate Monitoring
  * Integration, Messaging, Internet of Things, Machine to Machine
* Technology:
  * Unreal Engine, Polar H10 HR Sensor with Chest Strap, Bluetooth, Lab Streaming Layer

* Tags: UE, PolarH10, ECG, HR, HRM, BLE, LSL, IOT, M2M

---

<div style='page-break-after: always'></div>

## Table of Contents

<!-- Start Document Outline -->

* [1. Concept](#1-concept)
* [Appendix](#appendix)
  * [Acronyms](#acronyms)
  * [Glossary](#glossary)
    * [HRM – Heart Rate Variability](#hrm--heart-rate-variability)
    * [HRM – RR Interval](#hrm--rr-interval)
  * [A. References](#a-references)
  * [B. Readings](#b-readings)
  * [C. Acknowledgements](#c-acknowledgements)
  * [D. Attribution](#d-attribution)
  * [E. Disclaimer](#e-disclaimer)
  * [F. Citation](#f-citation)

<!-- End Document Outline -->

<div style='page-break-after: always'></div>

## 1. Concept

<div style='page-break-after: always'></div>

## Appendix

### Acronyms

* BLE &mdash; Bluetooth Low Energy
* bpm &mdash; Beats per Minute
* ECG &mdash; Electrocardiogram
* HR &mdash; Heart Rate
* HRM &mdash; Heart Rate Monitor
* HRV &mdash; Heart Rate Variability
* IBI &mdash; Interbeat Interval
* IOT &mdash; Internet of Things
* LSL &mdash; Lab Streaming Layer
* M2M &mdash; Machine to Machine
* PIE &mdash; Play-in-Editor
* PoC &mdash; Proof-of-Concept
* PS &mdash; PowerShell
* RRI &mdash; RR Interval
* UE &mdash; Unreal Engine

<div style='page-break-after: always'></div>

### Glossary

#### HRM &ndash; RR Interval

The RR interval RRI is an interbeat interval IBI, more precisely the time elapsed between two successive R-waves of the QRS signal on the electrocardiogram, in milliseconds [ms] (cp. [10] and [11]).

#### HRM &ndash; Heart Rate Variability

In a healthy person, the heart does not beat with a fixed frequency, i.e. with a resting pulse of, for example, 60 heartbeats per minute, each beat does not occur after exactly one second or 1000 milliseconds. Fluctuations of 30 to 100 milliseconds in the heartbeat sequence occur as a natural mode of operation of the heart.

> *Heart rate variability (HRV) is the amount by which the time interval between successive heartbeats (interbeat interval, IBI) varies from beat to beat. The magnitude of this variability is small (measured in milliseconds), and therefore, assessment of HRV requires specialized measurement devices and accurate analysis tools. Typically HRV is extracted from an electrocardiogram (ECG) measurement by measuring the time intervals between successive heartbeats [...].*
*Heart rate variability in healthy individuals is strongest during rest, whereas during stress and physical activity HRV is decreased. The magnitude of heart rate variability is different between individuals. High HRV is commonly linked to young age, good physical fitness, and good overall health.*
(Kubios, cp. [12]).

<div style='page-break-after: always'></div>

### A. References

* [1] Polar Electro: **Polar H10**. Heart Rate Sensor with Chest Strap, Online: [https://www.polar.com/en/sensors/h10-heart-rate-sensor](https://www.polar.com/en/sensors/h10-heart-rate-sensor)
* [2] **Lab Streaming Layer**. Website, Online: [https://labstreaminglayer.org/](https://labstreaminglayer.org/)
* [3] **Lab Streaming Layer**. Documentation, Online: [https://labstreaminglayer.readthedocs.io/](hthttps://labstreaminglayer.readthedocs.io/)
* [4] **Lab Streaming Layer**. Repository, Online: [https://github.com/sccn/labstreaminglayer](https://github.com/sccn/labstreaminglayer)
* [10]  **RR Interval**. In: ScienceDirect. From: Principles and Practice of Sleep Medicine (Fifth Edition), 2011. Online: [https://www.sciencedirect.com/topics/nursing-and-health-professions/RR-interval](https://www.sciencedirect.com/topics/nursing-and-health-professions/RR-interval)
* [11] Mike Cadogan: **R wave Overview**. February 4, 2021. In: Live In The Fastlane &ndash; ECG Library, ECG Basics. Online: [https://litfl.com/r-wave-ecg-library/](https://litfl.com/r-wave-ecg-library/)
* [12] **Heart Rate Variability**. In: Website of Kubios Oy, Section "HRV Resources". Online: [https://www.kubios.com/about-hrv/](https://www.kubios.com/about-hrv/)

### B. Readings

* Ch&#281;&cacute;, A.; Olczak, D.; Fernandes, T. and Ferreira, H. (2015). **Physiological Computing Gaming - Use of Electrocardiogram as an Input for Video Gaming**. In: Proceedings of the 2nd International Conference on Physiological Computing Systems - PhyCS, ISBN 978-989-758-085-7; ISSN 2184-321X, pages 157-163. DOI: [10.5220/0005244401570163](http://dx.doi.org/10.5220/0005244401570163)

* [Kothe2024] Kothe, Christian et al., 2024: **The Lab Streaming Layer for Synchronized Multimodal Recording**. In: bioRxiv. Cold Spring Harbor Laboratory. DOI: 10.1101/2024.02.13.580071, Online: [https://www.biorxiv.org/content/early/2024/02/14/2024.02.13.580071](https://www.biorxiv.org/content/early/2024/02/14/2024.02.13.580071), eprint: [https://www.biorxiv.org/content/early/2024/02/14/2024.02.13.580071.full.pdf](https://www.biorxiv.org/content/early/2024/02/14/2024.02.13.580071.full.pdf)

### C. Acknowledgements

* Logo: "**A red heart with a heartbeat to the right**", by Diego Naive / Joe Sutherland, June 6, 2018. Online: [https://de.wikipedia.org/wiki/Datei:Red_heart_with_heartbeat_logo.svg](https://de.wikipedia.org/wiki/Datei:Red_heart_with_heartbeat_logo.svg), licensed [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/).
* 3D Model: "**Heart**", by phenopeia, January 16, 2015. Online: [https://skfb.ly/CCyL](https://skfb.ly/CCyL), licensed [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/).

<div style='page-break-after: always'></div>

### D. Attribution

* The word mark Unreal and its logo are Epic Games, Inc. trademarks or registered trademarks in the US and elsewhere.
* The word mark Polar and its logos are trademarks of Polar Electro Oy.
* The Bluetooth word mark and logos are registered trademarks owned by Bluetooth SIG, Inc.
* Windows and PowerShell are registered trademarks of Microsoft Corporation.
* From the Website of Lab Streaming Layer: "The Lab Streaming Layer was originally created by Christian Kothe while at the Swartz Center for Computational Neuroscience at the University of California, San Diego. The project is currently maintained by an international team of developers (see contributors), with contributions from LSL community users and hardware/software vendors." "The LSL project has been funded in part by the Army Research Laboratory (under Cooperative Agreement Number W911NF-10-2-0022) and the National Institute of Neurological Disorders and Stroke (grant 3R01NS047293-06S1)."

### E. Disclaimer

This documentation has **not been reviewed or approved** by the *Food and Drug Administration FDA* or by any other agency. It is the users responsibility to ensure compliance with applicable rules and regulations&mdash;be it in the US or elsewhere.

### F. Citation

To acknowledge this work, please cite

> Bruggmann, R. (2025): Unreal&reg; Engine Project "Heartbeat" [Computer software], Version v5.3.0. Licensed under Creative Commons Attribution-ShareAlike 4.0 International. Online: https://github.com/brugr9/Heartbeat53

```bibtex
@software{Bruggmann_Heartbeat_2025,
  author = {Bruggmann, Roland},
  year = {2025},
  version = {v5.3.0},
  title = {{Unreal Engine Project 'Heartbeat'}},
  url = {https://github.com/brugr9/Heartbeat53}
}
```

---
<!-- Footer -->

[![Creative Commons Attribution-ShareAlike 4.0 International License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)

*Unreal&reg; Engine Project "Heartbeat"* &copy; 2025 by [Roland Bruggmann](https://dev.epicgames.com/community/profile/PQBq/brugr9) is licensed under [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/)
