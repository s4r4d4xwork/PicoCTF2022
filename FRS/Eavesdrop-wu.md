Use Wireshark, follow the conversation, follow the 9002 stream is the packet to find the hex string ( the file.des3 file), remember to change value to raw and save it as .des3 file . **DO NOT COPY PASTE THE VALUE TO NEWIFLE OR SAVE IT IN WIRESHARK AS OTHER TYPE BECAUSE YOU JUST COPY ITS STRING NOT ITS HEXDATA AND THE WIRESHARK USE HEXDATA TO SAVE FILE NOT VALUE so change it to raw type before save it!**

![image](https://user-images.githubusercontent.com/101840614/158945276-13eaf7ef-1746-460c-9803-332d642810e5.png)


```bash
openssl des3 -d -salt -in file.des3 -out file.txt -k supersecretpassword123
```

Flag will be in output file "file.txt"

Flag: ```picoCTF{nc_73115_411_0ee7267a}```
