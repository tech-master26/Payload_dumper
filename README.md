### **Payload Dumper - Extract IMG Files from OTA ZIPs**  

🚀 **Introducing Payload Dumper!** 🚀  

Easily extract `.img` files from **Android OTA update ZIPs** with this powerful and lightweight tool. Whether you're a developer, modder, or enthusiast, **Payload Dumper** makes it effortless to access system images from OTA packages.  

### ✨ **Features:**  
✅ Extract `.img` files from `payload.bin` inside OTA ZIPs  
✅ Fast and efficient processing  
✅ No root required  
✅ Simple and user-friendly interface  
✅ Works on most Android devices  

🔧 **How It Works:**  
1. Select your OTA ZIP file  
2. The app extracts the `payload.bin` file  
3. Extracts all `.img` files (system, boot, vendor, etc.)  
4. Ready to use for flashing or analysis!  

Perfect for **custom ROM developers**, **backup enthusiasts**, and anyone who needs quick access to OTA image files.  

📥 **Download now and take control of your OTA updates!**  
[GitHub Repository Link]  

Let me know if you want any modifications!


## payload dumper
used to extract image files from payload.bin file [ota firmware]

Prerequisites: python3

## Steps:
**[Download](https://github.com/termux/termux-app.git) termux universal debug.**

## Use following command:
*I have include all command in one line*

       apt update && apt upgrade -y && apt install -y git wget python zip unzip && git clone https://github.com/sirajul26/Payload_dumper.git
## Now goto The repositoriy
    cd Payload_dumper
## install requirments
    pip install -r requirments.txt

## extract your payload file
Extract **firmware** zip file and copy the extracted folder path

## Now Dump the payload 
**here paste your payload file path**
*eg.. /storage/emulated/0/Download/payload.bin*

       python pd.py (file path)payload.bin

## now your payload file will be extrected on the same path 
![image](https://github.com/sirajul26/Payload_dumper/reference_pics/1.1.png)
![image](https://github.com/sirajul26/Payload_dumper/reference_pics/1.2.png)
![image](https://github.com/sirajul26/Payload_dumper/reference_pics/2.1.png)
![image](https://github.com/sirajul26/Payload_dumper/reference_pics/2.2.png)
![image](https://github.com/sirajul26/Payload_dumper/reference_pics/3.1.png)
![image](https://github.com/sirajul26/Payload_dumper/reference_pics/3.2.png)
![image](https://github.com/sirajul26/Payload_dumper/reference_pics/3.3.png)
## Thank for using.
