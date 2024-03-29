# WiFiMobNet-WiFi-Camera-Data-Fusion-based-Object-Detection-Motion-Estimation-via-Multimodal-Model

* This repository is part of an early-stage WiFi and camera data fusion-based human detection and motion estimation project. Through the '*Project Manual.doc*', you can utilize the initial project after adjusting it to the environment.
* The goal of our research is to develop a multimodal-based computer vision technology to detect and track objects beyond walls by adding IEEE 802.11 standard WiFi signals.
  
* An multimodal approach that additionally utilizes WiFi signals can complement problems such as obstacles and object obscuration that occur in existing camera-based security and computer vision through the radio frequency (RF) signal characteristics.

* Personally, I hope that this approach and research will be further activated as a practical way to prevent crime in areas where CCTV deployment is restricted to protect personal information.

# Project Members
#### [Youngwoo Oh (M.S. student, Project leader from May 2023 to Feb. 2024 (for 9 months))](https://ohyoungwoo.com/)
- Integrated data fusion between WiFi signals and captured video from the router and cameras by developing the [Linux toolkit codes](https://github.com/FIVEYOUNGWOO/IEEE-802.11n-CSI-Camera-Synchronization-Toolkit).
- Responsible for data fusion and SW/HW configuration.
- Reproduced a Teacher-Student approach to robustly detect and track objects beyond walls and obstacles.
- Wrote papers for the [2024 Winter Conference on Korea Information and Communications Society (KICS)](https://conf.kics.or.kr/) titled "*Collection and Analysis of CSI in IEEE 802.11n Wireless LAN Environments for WiFi Signal-Based Human Mobility Detection (special session)*" and "*Design and Implementation of a Multi-Modal Learning Model for RF-Based Object Tracking Methods (recent results)*".
- Wrote 2023,2024 R&D proposal related to this project. Our team plan to "*multiple edge-based multi-modal federated learning approachs*" to expand this project with [Prof. Ramesh Rao](https://scholar.google.co.kr/citations?user=l-WGj3AAAAAJ&hl=ko&oi=ao) from [Qualcomm institue](https://qi.ucsd.edu/about/leadership/).
- Expect to extended federated-multimodal approach get benefit a diversity data-paired samples, training efficient, and zero-configuration on similar scenario and space. Suggested our future work and planning such as cloud-edge arhietecture-based federated multimodal learning, multiple Teacher-Student network AI modeling, and computing board-based edge device configulation to our team.
- Considered a [Up-board](https://up-board.org/up/specifications/)-based multiple edge configulation, which can support a compatiable Intel WiFi LAN 5300 (IWL 5300).

#### Islam Helemy (Ph.D. student, Project member)
- Responsible for the development of the Multi-modal AI and the pre-processing to generate training data pairs (CSI samples-captured images).
- He will receive a *project leader* position on this future project after Feb. 2024.

#### Iftikhar Ahmad (Ph.D. student, Project member)
- Focused on developing and investigating the Teacher network in the multi-modal AI model.

#### Manal Mosharaf (M.S. student, Project member)
- Engaged in developing and investigating the Student network in the multi-modal AI model.
- Responsible for a anaysis of WiFi signal features according to human pose, movement.
