# Useful-tools-and-software-for-high-precision-positioning-of-low-cost-smart-devices

Here, we will share some datasets and scripting tools related to high-precision GNSS positioning, integrated navigation, and indoor positioning to reduce obstacles for interested researchers working with this data. These studies focus on smartphones, wearables and autonomous driving. The BUAA RINEX Logger, developed by Professor Shi Chuang's team at Beihang University, is a software that supports the acquisition and recording of GNSS observations across the constellation and at all frequencies. The BUAA RINEX Logger supports the latest quad-band smartphone data logging and is compatible with Android 8.0 and above. The current support for recording data frequency is as follows:

![image](https://github.com/Jia-le-wang/Useful-tools-and-software-for-high-precision-positioning-of-low-cost-smart-devices/assets/49149409/84746908-2f25-492b-8acf-0617dd897ccd)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
When using the BUAA RINEX Logger, open the Location, mearement, and RINEX buttons. You can choose the recording time in the software, for example 1 hour. Then, in the folder directory of your Android phone, you can find the gnss_log folder, which contains the raw GNSS log, Fix log, and converted rinex files. The IMU data will be updated after the synchronization procedure is completed.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Recently, we focused on the big trouble that smartphones are having in urban navigation! Inaccurate urban positioning has been an ongoing problem with satellite navigation, prompting many attempts at solutions and revealing deep-rooted difficulties. Using an accurate 3D building model database, asymmetric NLOS propagation is modeled to correct for NLOS pseudo-range errors, thereby reducing the positioning error of the phone by more than 50%. We recommend that researchers consider using the 3D city model in the future, and here is an experimental case to demonstrate the powerful advantages of 3DMA:

![录制_2023_11_01_10_56_33_516](https://github.com/Jia-le-wang/Useful-tools-and-software-for-high-precision-positioning-of-low-cost-smart-devices/assets/49149409/14b6b590-676f-40d5-a11a-d99319bad58e)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
The following is a case of pedestrian 3D positioning, where high-precision indoor and outdoor seamless positioning is achieved by combining 3DMA PPP with pedestrian inertial positioning:
![Uploading 录制_2023_11_04_22_00_31_322 (1).gif…]()

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
As we refine the tools, we will continue to upload more useful processing scripts, datasets, and software to the GITHUB repository. We hope that our work can provide some references for relevant interested researchers in pedestrian navigation, indoor and outdoor seamless positioning, and integrated navigation.
If you have any questions during use, please do not hesitate to contact: wangjialea@gmail.com
