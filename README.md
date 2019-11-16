# RT6-Parking-Config
RT6 Parking Sensor volume change without needed to go to a main dealer. 


# Steps:
- Extract the Mirascript archive on your USB key and keep only the "RT6_USERCOM.CMD" file in the "CMD" folder.
- Make Sure to remove the System Volume Information Folder! by doing RmDir /s /q "z:\System Volume Information
- Connect the USB key to the RT6 and answer "YES" to the request to execute the script.
- The script will ask to launch the command "WRITE", answer "NO".
- The script will then ask to launch the command "READ", answer "YES".
- Wait for the script to finish executing before unplugging the USB key.
- Extract the archive of "DATEXPLORER".
- Launch "DATEXPLORER.exe" and click on "Load Config"
- Select "RT6_2xx-user_config.dat.cfg" file.
- Click on "Load Dat" and select "User_config.dat" file on the root of the USB key
- Navigate to the relevant section and change the values.
- Click "Save" Remove the System Volume Information Folder again like above and remove USB key.
- Connect the USB key to the RT6, it will ask to execute the script "USERCOM", answer "YES".
- The script will ask to launch the command "WRITE", answer "YES".
- Wait until the RT6 displays a message asking to restart. DO NOT ANSWER YES. Press the eject button for 10 seconds until the RT6 restarts.


