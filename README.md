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
![Example Image](https://github.com/sirajul26/Payload_dumper/referance_img/1.png)

## Thank for using.
