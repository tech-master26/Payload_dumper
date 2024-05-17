## payload dumper
used to extract image files from payload.bin file [ota firmware]

Prerequisites: python3

## Steps:
1. [Download](https://github.com/termux/termux-app.git) termux universal debug.

## Use following command:
I have include all command in one line
''' apt update && apt upgrade -y && apt install -y git wget python zip unzip && git clone https://github.com/sirajul26/Payload_dumper.git
'''

3. Extract firmware zip file and copy payload.bin into payload_dumper folder

4. run

        python payload_dumper.py payload.bin

    all image files will be extracted into the current directory
