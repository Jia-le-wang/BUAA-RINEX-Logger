# Useful tools and software for high-precision positioning of low-cost smartphone

Here, we will share some datasets and scripting tools related to high-precision GNSS positioning, integrated navigation, and indoor positioning to reduce obstacles for interested researchers working with this data. These studies focus on smartphones, wearables and autonomous driving. The BUAA RINEX Logger, developed by Professor Shi Chuang's team at Beihang University, is a software that supports the acquisition and recording of multi-GNSS observations. The BUAA RINEX Logger supports the latest multi-frequency smartphone data logging and is compatible with Android 8.0 and above. The current support for recording data frequency is as follows:

![GNSS频率分布(1)](https://github.com/user-attachments/assets/9f601580-2598-44c1-9e7f-44a3fb0e52de)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
After installing the software, check the three buttons "Location", "Measurement" and "Rinex OBS" as shown in the figure below (left), and click "START LOG" (right) to start recording GNSS data. Then, in the folder directory of your Android phone, you can find the "gnss_log" folder, which contains the raw GNSS log, Fix log, and converted rinex files. The IMU data will be updated after the synchronization procedure is completed. Enjoy it!

![image](https://github.com/Jia-le-wang/BUAA-RINEX-Logger/assets/49149409/ac732ab3-b041-4fa1-bb3d-d95fc6be5a2f)   ![image](https://github.com/Jia-le-wang/BUAA-RINEX-Logger/assets/49149409/0c4dc693-369f-4b71-9110-a8bbf2238d36)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Recently, we focused on the big trouble that smartphones are having in urban navigation! Inaccurate urban positioning has been an ongoing problem with satellite navigation, prompting many attempts at solutions and revealing deep-rooted difficulties. Using an accurate 3D building model database, asymmetric NLOS propagation is modeled to correct for NLOS pseudo-range errors, thereby reducing the positioning error of the phone by more than 50%. We recommend that researchers consider using the 3D city model in the future, and here is an experimental case to demonstrate the powerful advantages of 3DMA GNSS:

![录制_2023_11_01_10_56_33_516](https://github.com/Jia-le-wang/Useful-tools-and-software-for-high-precision-positioning-of-low-cost-smart-devices/assets/49149409/14b6b590-676f-40d5-a11a-d99319bad58e)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Our latest powerful Foot-mounted Inertial Pedestrian Position System (FIPPS) can fully support various pedestrian gait patterns such as walking, running, elevators, escalators, and up and down stairs.The following is a case of pedestrian 3D positioning, where real-time high-precision indoor-outdoor seamless positioning is achieved by combining 3DMA PPP algorithm with foot-mounted inertial positioning:

![录制_2023_11_04_22_46_42_514](https://github.com/Jia-le-wang/BUAA-RINEX-Logger/assets/49149409/8489d172-cda1-4df3-aa02-a19cd8d5b243)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Citation

If you find this repository useful in your research or development, please consider citing our work:
1. Wang J, Shi C, Zheng F, et al. "Multi-frequency smartphone positioning performance evaluation: insights into A-GNSS PPP-B2b services and beyond." Satellite Navigation, 2024, 5(1):25. DOI:https://doi.org/10.1186/s43020-024-00146-5
2. Wang J, Zheng F, Hu Y, et al. "Instantaneous Sub-meter Level Precise Point Positioning of Low-Cost Smartphones." NAVIGATION: Journal of the Institute of Navigation, 2023, 70(4). DOI：https://doi.org/10.33012/navi.597
3. Wang J, Shi C, Xia M, et al. "Seamless Indoor–Outdoor Foot-Mounted Inertial Pedestrian Positioning System Enhanced by Smartphone PPP/3-D Map/Barometer." IEEE Internet of Things Journal, 2024, 11(7):13051-13069. DOI: https://doi.org/10.1109/JIOT.2023.3337393

Here is the BibTeX for citing these papers:

@article{wang2024multifrequency,
  title={Multi-frequency smartphone positioning performance evaluation: insights into A-GNSS PPP-B2b services and beyond},
  author={Wang, Jiale and Shi, Chuang and Zheng, Fei and others},
  journal={Satellite Navigation},
  volume={5},
  number={1},
  pages={25},
  year={2024}
}

@article{wang2023instantaneous,
  title={Instantaneous Sub-meter Level Precise Point Positioning of Low-Cost Smartphones},
  author={Wang, Jiale and Zheng, Fei and Hu, Ying and others},
  journal={NAVIGATION: Journal of the Institute of Navigation},
  volume={70},
  number={4},
  year={2023}
}

@article{wang2024seamless,
  title={Seamless Indoor–Outdoor Foot-Mounted Inertial Pedestrian Positioning System Enhanced by Smartphone PPP/3-D Map/Barometer},
  author={Wang, Jiale and Shi, Chuang and Xia, Ming and others},
  journal={IEEE Internet of Things Journal},
  volume={11},
  number={7},
  pages={13051--13069},
  year={2024}
}

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
As we refine the tools, we will continue to upload more useful processing scripts, datasets, and software to the GITHUB repository. We hope that our work can provide some references for relevant interested researchers in pedestrian navigation, indoor and outdoor seamless positioning, and integrated navigation.
If you have any questions during use, please do not hesitate to contact: wangjialea@gmail.com
