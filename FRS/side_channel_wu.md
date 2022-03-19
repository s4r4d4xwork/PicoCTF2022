This is bit tricky, you should know how timing attack side channel work: 

[2018-02-05-AhmadAshraff.pdf](https://github.com/s4r4d4xwork/PicoCTF2022/files/8309382/2018-02-05-AhmadAshraff.pdf) 

It's PIN 8bit so it's just num 0-9 and have 8 numbers so it's easy to do.
I think the code is check one by one form left to right so if the number is correct it will output the significant time gap between old and new input.
Use this code to estimate the time of running forgram until you have access:
```bash
time printf 'xxxxxxxx' | ./pin_checker
```

Good luck!
Flag: ```picoCTF{t1m1ng_4tt4ck_914c5ec3}```
