Use Wireshark, follow the conversation, follow the 9002 stream is the packet to find the file.des3 file, remember to save as raw 
```bash
openssl des3 -d -salt -in file.des3 -out file.txt -k supersecretpassword123
```
