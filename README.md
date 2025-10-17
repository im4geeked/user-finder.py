# user-finder.py
I got bored so I made a tool that checks if usernames are valid on 10+ domains 

## Usage
Just use the simple menu!   
`root@im4geeked:~# python3 user-finder.py`
```
[*] A simple OSINT tool that is made to scan for usernames on over 10 websites
[?] Enter username: testuser
[*] Enumerating username testuser...
[+] Reddit: https://www.reddit.com/user/testuser
[+] Youtube: https://www.youtube.com/@testuser
[+] Instagram: https://www.instagram.com/testuser
[+] Pinterest: https://www.pinterest.com/testuser
[+] Pastebin: https://pastebin.com/u/testuser
[+] Replit: https://replit.com/@testuser
[+] Gitlab: https://gitlab.com/testuser
[+] Tiktok: https://www.tiktok.com/@testuser
```

## Installation 
### 1. Clone the repository
```
git clone https://github.com/im4geeked/user-finder.git
cd user-finder
```
### 2. Install dependencies

### Windows
```
pip install -r requirements.txt
```
### Linux
#### Ubuntu/Debian
```
sudo apt install python3-requests python3-colorama
```
#### Arch
```
sudo pacman -S python-requests python-colorama
```
#### Fedora/RHEL/CentOS
```
sudo dnf install python3-requests python3-colorama
```
#### OpenSUSE
```
sudo zypper install python3-requests python3-colorama
```

### 3. Run the script
```
python3 user-finder.py
```

## **Requirements:**  
> - Python 3.8 or higher  
> - Internet connection  
> - `requests` and `colorama` (installed via `requirements.txt`)

**Note:** On Windows, you may see colored output only after running `init(autoreset=True)` (already handled in the script)

## Disclaimer

This tool should be only used for when playing OSINT style CTFs, research, or educational purposes only
Use it responsibly and only on usernames you have permission to scan on
