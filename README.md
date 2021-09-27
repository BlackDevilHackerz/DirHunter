

<br>Simple directory brute-force tool written with python.<br>

- [X] Usage before install: ```python3 dh.py --url [url] --wordlist [wordlist_file] --status 2xx 3xx --thread 100```
- [X] Usage after install: ```dh --url [url] --wordlist [wordlist_file] --status 2xx 3xx --thread 100```


# Setup
<b>Necessary python modules</b>: ```tqdm``` and ```argparse```<br>
<b>Installation of python modules</b>: ```pip3 install -r requirements.txt```<br>

# Arguments  
- --url: Specify target url. Example => http://192.168.1.1
- --wordlist: Select wordlist file. Example => /usr/share/wordlists/dirb/common.txt
- --status: Filter status codes. Example => 200 301 403
- --thread: Number of threads. Example => 100
- --install: Install DirHunter on your system.


