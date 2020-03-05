### About PW-Directory

Pw-Directory is the security tester's companion. It's a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more. The goal is to enable a security tester to pull this repository onto a new testing box and have access to every type of list that may be needed.

This project is maintained by @anibish

- - -

### Install

**Zip**
```
wget -c https://github.com/anibish/PW-Dictionary/archive/master.zip -O SecList.zip \
  && unzip SecList.zip \
  && rm -f SecList.zip
```

**Git (Small)**
```
git clone --depth 1 https://github.com/anibish/PW-Dictionary.git
```

**Git (Complete)**
```
git clone https://github.com/anibish/PW-Dictionary.git
```

**Kali Linux** ([Tool Page](https://tools.kali.org/password-attacks/seclists))
```
apt -y install seclists
```

- - -

### Attribution

See [CONTRIBUTORS.md](CONTRIBUTORS.md)

- - -

### Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)

- - -

### Similar Projects

* [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)
* [FuzzDB](https://github.com/fuzzdb-project/fuzzdb)

- - -



<sup>NOTE: Downloading this repository is likely to cause a false-positive alarm by your anti-virus or anti-malware software, the filepath should be whitelisted. There is nothing in SecLists that can harm your computer as-is, however it's not recommended to store these files on a server or other important system due to the risk of local file include attacks.</sup>
