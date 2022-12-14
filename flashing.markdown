---

layout: default
---
This tutorial assumes arduino IDE is already installed. If not, please go to
[arduino.cc](https://www.arduino.cc/en/software) for download and install instructions.

Flashing instructions:

1. Get hold of the code

   Code can be downloaded from [github repository](https://github.com/softica/controller-firmware).
   It can be cloned using git.
   It can also be downloaded in a compressed archive.
   It is recommended to use a tagged release version.

   ![step1](flashing/step1.png)

2. Open arduino IDE and load downloaded code to IDE

   ![step2](flashing/step2.png)


3. Connect the controller using USB cable.

   In the IDE it will show up as serial port.
   This tutorial was recorded on Ubuntu. In case of Windows the port will be in the form of COMx where x is a number.

   ![step3](flashing/step3.png)

4. Press 'upload' button to flash the controller

   ![step4](flashing/step4.png)

5. When flashing process is successful, controller will start running new code.

   ![step5](flashing/step5.png)
