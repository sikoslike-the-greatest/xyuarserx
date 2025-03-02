# xyuarserx
Just a simple dnsx output ipv4 python parser.
If doesnt work, try use -nc flag in dnsx

`-l <file>` to input from file (made with `dnsx -re > file`);
`-ro` use this flag with `dnsx -ro` input;
`-l/p/g` dont show local/private/global ips;
`-s` silent (dont show comments between ips like "GLOBAL");
`-d` flag to show hosts only (useful to match only global names and then spider them with httpx for example)
`-c` no color

workflow:
```
git clone https://github.com/sikoslike-the-greatest/xyuarserx.git
cd xyuarserx
chmod +x xyuarserx
subfinder -d $domain | dnsx -re | ./xyuarserx
```
![poc](poc.gif)
