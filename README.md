# manjaro-get-iso
Python script to download a named Manjaro ISO and verify the signature

## Usage
Ensure you have Python 3.11 and the Python requests module on your system.

1. Create a new file on your system
2. Copy the content of `get-iso`
3. Paste it into the new file
4. Save

Make the file executable and copy the file /usr/local/bin

    chmod +x get-iso && sudo cp get-iso /usr/local/bin

Run the file

    get-iso -h

See https://forum.manjaro.org/t/root-tip-utility-script-using-python-to-download-and-verify-a-manjaro-iso/146703 for more information
