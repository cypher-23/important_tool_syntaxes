gobuster

normal scanning : **gobuster dir -u urlname -w /path/to/word-list**

```bash
gobuster dir -u http://url_name/ -w /path_to_wordlist
```

scanning for particular extensions: **gobuster dir -u urlname -w /path/to/word-list  -x php,txt etc**

```bash
gobuster dir -u http:// url_name/ -w /path_to_wordlist -x php,txt,etc...
```

scanning with a timeout: **gobuster dir -u urlname -w /path/to/word-list -t 1000 {also called no of threads}**

```bash
gobuster dir -u urlname -w /path/to/word-list -t 1000 {also called no of threads}
```

DNS enum: **gobuster vhost -v -w /home/username/SecLists/Discovery/DNS/subdomains-top1million-5000.txt -u http://workers.htb -o vhosts.txt**

```bash
gobuster vhost -v -w /home/username/SecLists/Discovery/DNS/subdomains-top1million-5000.txt -u http://workers.htb -o vhosts.txt
```