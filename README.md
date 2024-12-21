# xyuarserx
Just a simple dnsx output ipv4 python parser.

`-l <file>` to input from file (made with `dnsx -re > file`);
`-ro` use this flag with `dnsx -ro` input;
`-l/p/g` dont show local/private/global ips;
`-s` silent (dont show comments between ips like "GLOBAL");

workflow:
```
git clone https://github.com/sikoslike-the-greatest/xyuarserx.git
cd xyuarserx
chmod +x xyuarserx
subfinder -d $domain | dnsx -re | ./xyuarserx
```
![poc](poc.gif)
