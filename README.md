# **Payload Dumper**
*Extract IMG Files from OTA ZIPs* 

![Payload Dumper](/reference_pics/Banner.png)  

> **Easily extract `.img` files from Android OTA ZIPs using Termux or the dedicated Android app!**  

---

## 🚀 **Features**  
✅ Extract `.img` files from `payload.bin` in OTA ZIPs  
✅ Works on **both Termux (CLI)** and **Android app (GUI)**  
✅ No root required  
✅ Simple and lightweight  
✅ Fast and efficient extraction  

---

## 📌 **Installation & Usage**  

###🔹 Method 1: 
**Using Termux (Command Line)**  

1️⃣ **Install Termux (if not installed)**  
**I have include all command in one line**

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
       
2️⃣ **Extract `.img` files from OTA ZIP**  
   ```bash
   python payload-dumper-go.py -i /path/to/your/ota.zip
   ```

3️⃣ **Find extracted images in the output directory**  

---

###🔹 Method 2: 
**Using Android App**  

1️⃣ **Download the Payload Dumper App**  
   📥 [Download APK](https://github.com/tech-master26/Payload_dumper/releases/)  

2️⃣ **Open the app and select your OTA ZIP file**  

3️⃣ **Tap "Extract" and let the magic happen!**  

4️⃣ **Find your `.img` files in the output folder**  

---

## 📸 **Screenshots**  
| Home Screen | Extraction in Progress | Extracted Files |
|-------------|----------------------|----------------|
| ![Home](/reference_pics/Home.jpg) | ![Extracting](/reference_pics/Extracting.jpg) | ![Files](/reference_pics/files.jpg) |

---

## 🛠 **Requirements**  
- **For Termux**: Python 3.6+  
- **For Android App**: Android 5.0+  

---

## ❓ **FAQ**  

🔹 **Where can I find the extracted `.img` files?**  
👉 The files will be saved in the app’s output folder or Termux’s working directory.  

🔹 **Does it require root?**  
👉 No, it works without root!  

🔹 **Can I use it to modify OTA images?**  
👉 Yes! Developers can modify and repack system images after extraction.  

---

## 📜 **License**  
This project is open-source and available under the **MIT License**.  

---

## 💬 **Support & Contributions**  
Found a bug or have a suggestion? Feel free to **open an issue** or **contribute** to the project on GitHub!  

📌 **GitHub Repository:** [Your GitHub Link]  

---




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

## now your payload file will be extrected on the same path 
![image](/reference_pics/1.1.png)
![image](/reference_pics/1.2.png)
![image](/reference_pics/2.1.png)
![image](/reference_pics/2.2.png)
![image](/reference_pics/3.1.png)
![image](/reference_pics/3.2.png)
![image](/reference_pics/3.3.png)
## Thank for using.
