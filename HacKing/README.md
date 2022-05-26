# HacKing CheatSheets

- Passwords HacKing
  - Crack Zip notes
    - Install zip cracking tools
      - `sudo apt update`
      - `sudo apt install john fcrackzip wordlists`
    - First make it readable by john the ripper
      - `zip2john secret_files.zip > hash.txt`
    - Then crack it with your wordlist
      - `john --wordlist=/usr/share/wordlists/rockyou.txt hash.txt`

