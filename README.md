# WWWizard
It's a script designed for enumerating vulnerable web paths that an attacker can exploit.
It also comes with others tools such as brute-force attacks on login pages and sql injection.

## Features
- Detection of common web misconfigurations
- Path and directory enumeration
- Brute-force on web login pages
- Input validation and SQL injection checks

## Legal Notice
this toolkit is intended **only for authorized security testing** on
systems you own or have explicit permission to test.

## Installation
- git clone https://github.com/lostgem04/WWWizard.git
- cd WWWizard
- pip install -r requirements.txt

## Usage

- python wwwizard.py --scan http://example.com 

- python wwwizard.py --brute http://example.com -w wordlist.txt --data "user=admin&password=$psswrd"

- python wwwizard.py --fuzzing http://example.com -w wordlist.txt


