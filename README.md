# xyuarserx
Just a simple dnsx output ipv4 python parser.

`-l <file>` to input from file (made with `dnsx -re > file`)

workflow:
```
git clone https://github.com/sikoslike-the-greatest/xyuarserx.git
cd xyuarserx
chmod +x xyuarser
subfinder -d $domain | dnsx -re | ./xyuarserx
```
![poc](poc.gif)
