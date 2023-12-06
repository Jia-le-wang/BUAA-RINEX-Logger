# Useful tools and software for high-precision positioning of low-cost smart devices

Here, we will share some datasets and scripting tools related to high-precision GNSS positioning, integrated navigation, and indoor positioning to reduce obstacles for interested researchers working with this data. These studies focus on smartphones, wearables and autonomous driving. The BUAA RINEX Logger, developed by Professor Shi Chuang's team at Beihang University, is a software that supports the acquisition and recording of GNSS observations across the constellation and at all frequencies. The BUAA RINEX Logger supports the latest quad-band smartphone data logging and is compatible with Android 8.0 and above. The current support for recording data frequency is as follows:

![image](https://github.com/Jia-le-wang/Useful-tools-and-software-for-high-precision-positioning-of-low-cost-smart-devices/assets/49149409/84746908-2f25-492b-8acf-0617dd897ccd)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
When using the BUAA RINEX Logger, open the Location, mearement, and RINEX buttons. You can choose the recording time in the software, for example 1 hour. Then, in the folder directory of your Android phone, you can find the gnss_log folder, which contains the raw GNSS log, Fix log, and converted rinex files. The IMU data will be updated after the synchronization procedure is completed.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Recently, we focused on the big trouble that smartphones are having in urban navigation! Inaccurate urban positioning has been an ongoing problem with satellite navigation, prompting many attempts at solutions and revealing deep-rooted difficulties. Using an accurate 3D building model database, asymmetric NLOS propagation is modeled to correct for NLOS pseudo-range errors, thereby reducing the positioning error of the phone by more than 50%. We recommend that researchers consider using the 3D city model in the future, and here is an experimental case to demonstrate the powerful advantages of 3DMA GNSS:

![录制_2023_11_01_10_56_33_516](https://github.com/Jia-le-wang/Useful-tools-and-software-for-high-precision-positioning-of-low-cost-smart-devices/assets/49149409/14b6b590-676f-40d5-a11a-d99319bad58e)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
The following is an experiment conducted in Beijing's harsh urban canyon environment, where the green dots represent LOS satellites, the red dots represent NLOS satellites, and the yellow dots represent Edge satellites. Because of the tall and dense buildings on both sides, there are only a few satellite signals available. Through the 3DMA PPP algorithm, the positioning accuracy of the Xiaomi Mi8 smartphone and the low-cost septentrio receiver has been improved by more than 50%.

![Honeycam 2023-12-04 13-52-18 (2)](https://github.com/Jia-le-wang/BUAA-RINEX-Logger/assets/49149409/29d0c963-2f36-4709-b5b5-960f71ea4450)


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Our latest powerful adaptive zero-speed detection algorithm can fully support various pedestrian gait patterns such as walking, running, elevators, escalators, and up and down stairs.The following is a case of pedestrian 3D positioning, where high-precision indoor and outdoor seamless positioning is achieved by combining 3DMA PPP with pedestrian inertial positioning:

![录制_2023_11_04_22_46_42_514](https://github.com/Jia-le-wang/BUAA-RINEX-Logger/assets/49149409/8489d172-cda1-4df3-aa02-a19cd8d5b243)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
As we refine the tools, we will continue to upload more useful processing scripts, datasets, and software to the GITHUB repository. We hope that our work can provide some references for relevant interested researchers in pedestrian navigation, indoor and outdoor seamless positioning, and integrated navigation.
If you have any questions during use, please do not hesitate to contact: wangjialea@gmail.com
