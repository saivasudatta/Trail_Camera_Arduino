# Trail_Camera_Arduino
Components:
2 Arduino uno, PIR sensor, OV7670 (Camera module).

Install the CamCode in Uno and connect to OV7670 to it as shown in the CamConnection.

Install the PirCode in Uno and connect the Pir to it.

Download and extract the Extra.rar file below and open it. As you could see, there is src folder, lib folder and "win32com.dll". You have to copy and placed "win32com.dll" in the "C:\Program Files\Java\jdk1.8.0_74\jre\bin" directory.

Then, open the lib and you could see the "comm.jar" and "javax.comm.properties" in it. Copy and paste the "comm.jar" in "C:\Program Files\Java\jdk1.8.0_74\jre\lib\ext" and "javax.comm.properties" in the "C:\Program Files\Java\jdk1.8.0_74\jre\lib" directory.

Make sure that Uno with PIR is connected on COM7 and Uno with OV7670 on COM5.

Place 3 class files together and run the SimpleRead.class
