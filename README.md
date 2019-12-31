# ntlm_crack 
ntlm_crack is a tool that recovers a password by cracking a supplied NTLM hash.

**Author**: [th3jiv3r][twitter]

### New Features!
  -provide any wordlist to the tool to start recovering passwords by cracking a supplied NTLM hash!

### Installation
```sh
$ go get github.com/stacktitan/smb
$ git clone https://github.com/goodlandsecurity/ntlm_crack.git
$ cd ntlm_crack 
$ go build ntlm_crack.go
```

### Example Use:  
  - *ntlm_crack wordlist.txt Administrator example.com <NTLM_HASH>*

#### License
  - GNU General Public License v3.0


[twitter]: <https://twitter.com/th3_jiv3r>
