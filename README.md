# Ubuntu-WebCam-Fix-for-Acer-AN515-58-
This is instruction repo for fixing the webcam which dosent work in ubuntu 22.04 in Acer Nito 5 Laptops and also others

## 🛠 Fix for Quanta HD User Facing Webcam (0408:4035) Not Detected on Linux
This guide helps resolve the issue where the Quanta HD User Facing webcam (`0408:4035`) fails with the error:

1. **Enable source repositories**  
   Edit `/etc/apt/sources.list` and ensure the `deb-src` lines for your Ubuntu release are uncommented:
   ```bash
   sudo nano /etc/apt/sources.list
   # Remove any leading `#` from lines like:
   deb-src http://archive.ubuntu.com/ubuntu focal main restricted universe multiverse

   
