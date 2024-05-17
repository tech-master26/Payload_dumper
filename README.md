## payload dumper
used to extract image files from payload.bin file [ota firmware]

Prerequisites: python3

## Steps:
1. [install]() termux
2. 

        cd payload_dumper

3. Extract firmware zip file and copy payload.bin into payload_dumper folder

4. run

        python payload_dumper.py payload.bin

    all image files will be extracted into the current directory
