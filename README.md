# EntPack
installation script a pack of entertainment apps for PX50 Atlas OS

## This installation apps includes:
  - NewPipe
  - Netflix
  - Disney+ Hotstar
  - MSTV
  - Equalizer
  - AIMP Player

## Note:This installation method requires 7zip to be installed on your computer. Please download and install 7zip from [here](https://www.7-zip.org/) if you don't have it already.

## Steps
1.  Download installation script [here.](https://drive.google.com/file/d/1doxtPZtGx0Rfzw1rYA1vz0mbx5xQMiFW/view?usp=share_link)
2.  Extract the downloaded file to the root directory of your USB drive.
3.  Open the folder named **app** and then locate the **APK** file. Right-click on the APK file, choose **7zip**, and select **Open**.
<img src="https://user-images.githubusercontent.com/124480402/222107456-c997757f-6345-4d81-89d2-2d2491274caf.JPG" width=50% height=30%>

4. Locate the **lib** folder as shown in the image above, and open the **arm64-v8a** subfolder. You should see a number of files with the extension `.so`. Copy or drag and drop these files to the `lib64` folder that you extracted earlier.
5. Repeat step 4 for any additional APK files you wish to install. If an APK file does not have a **lib** folder, there is no need to copy any **.so** files.
6. After finishing all steps, plug the USB drive into the USB port on the IHU and wait for the IHU to reboot itself. Once the reboot is complete, you can safely remove the USB drive.
7. If you can see that the new apps have been installed,then you can consider the installation to be successful.
