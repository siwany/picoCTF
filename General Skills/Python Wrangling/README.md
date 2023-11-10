## Python Wrangling
* Points: 10pt
* Tags: `General Skills`, `picoCTF 2021`
## Description
> Python scripts are invoked kind of like programs in the Terminal... Can you run [this Python script](ende.py) using [this password](pw.txt) to get [the flag](flag.txt.en)?
## Hints
> * Get the Python script accessible in your shell by entering the following command in the Terminal prompt: $ wget https://mercury.picoctf.net/static/b351a89e0bc6745b00716849105f87c6/ende.py
> * $ man python
## Solution
1. The usage_msg line in ende.py provides usage instructions for the script. It specifies that you can use -e for encoding and -d for decoding. (The flag flie having the `en` extension suggests that it's encoded and needs to be decoded)
2. Decode the flag file: `python3 ende.py -d flag.txt.en`
3. Provide the password you've just found in "pw.txt."
## flag
picoCTF{4p0110_1n_7h3_h0us3_67c6cc96}
