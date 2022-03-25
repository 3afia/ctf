# [OverTheWire](https://overthewire.org/wargames/)
### [Bandit](https://overthewire.org/wargames/bandit)


| Username | password | How to get the password  |
| ----------- | ----------- |----------- |
| bandit0 | bandit0 | from the website |
| bandit1 | boJ9jbbUNNfktd78OOpsqOltutMc3MY1 | `ls &&  cat readme` |
| bandit2 | CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9 | `cat ./\-` |
| bandit3 | UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK | `cat spaces\ in\ this\ filename` |
| bandit4 | pIwrPrtPN36QITSp3EQaw936yaFoFgAB | `ls -la * &&  cat inhere/.hidden` |
| bandit5 | koReBOKuIDDepwhWk7jZC0RTdopnAYKh | `file inhere/-file* &&  cat inhere/-file07` |
| bandit6 | DXjZPULLxYr17uwoI01bNLQbtFemEgo7 | `find . -size 1033c -exec cat 2>/dev/null {} \; ` |
| bandit7 | HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs | `find / -size 33c -user bandit7 -group bandit6 -exec cat 2> /dev/null {} \; ` |
| bandit8 | cvX2JJa4CFALtqS87jk27qwqGhBM9plV | `grep millionth data.txt` |
| bandit9 | UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR | `sort data.txt \| uniq -u` |
| bandit10 | truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk | `strings data.txt \| grep =` |
| bandit11 | IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR | `cat data.txt \| base64 -d` |
| bandit12 | 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu | `ROT13` |
| bandit13 | 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL | `cat data.txt \| xxd -r > data &&  -then gzip or bzip2 or tar` |
| bandit14 | 4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e | `chmod 0600 sshkey.private &&  ssh -i sshkey.private bandit14@bandit.labs.overthewire.org -p 2220` |
| bandit15 | BfMYroe26WYalil77FoDi9qh59eK5xNr | `echo 4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e \| nc localhost 30000` |
| bndit16 | cluFn7wTiGryunymYOu4RcffSxQluehd | `echo BfMYroe26WYalil77FoDi9qh59eK5xNr \| openssl s_client -connect localhost \| 30001 -ign_eof` |
| bandit17 | SSHKEY17 | `nmap -A -p 31000-32000 localhost && echo cluFn7wTiGryunymYOu4RcffSxQluehd \| openssl s_client -connect localhost:31790 -ign_eof && ssh -i sshkey17 bandit17@bandit.labs.overthewire.org -p 2220` |
| bandit18 | kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd | `diff password.old password.new` |
| bandit19 | IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x | `ssh bandit18@bandit.labs.overthewire.org -p 2220 "cat ~/readme"` |
| bandit20 | GbKksEFF4yrVs6il55v6gwY5aVje5f0j | `./bandit20-do cat /etc/bandit_pass/bandit2` |
| bandit21 | gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr | `echo GbKksEFF4yrVs6il55v6gwY5aVje5f0j \| nc -l localhost -p 5555 &; ./suconnect 5555` |
| bandit22 | Yk7owGAcWjwMVRwrTesJEwB7WVOiILLI | `cat /etc/cron.d/cronjob_bandit22 && cat /usr/bin/cronjob_bandit22.sh && cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv` |
| bandit23 | jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n | `cat /tmp/$(echo "I am user bandit23" \| md5sum \| cut -d ' ' -f 1)` |
| bandit24 | UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ | `mkdir /tmp/work && cd $_ &&  touch fetch.sh && touch pass.txt &&  echo -e '#!/bin/bash\ncat /etc/bandit_pass/bandit24 > /tmp/work/pass.txt' > fetch.sh &&  chmod 777 fetch.sh && chmod 666 pass.txt && cp fetch.sh /var/spool/bandit24 && cat pass.txt` |
| bandit25 | uNG9O58gUE7snukf3bvZ0rxhtnjzSGzG | [online tutorial](https://medium.com/secttp/overthewire-bandit-level-24-aaaaf795b701) |
| bandit26 | 5czgV9L3Xx8JPOyRbXh6lQbmIOWvPT6Z | `cat /etc/passwd \| grep bandit26 &&  cat /usr/bin/showtext &&  ls -la && cp bandit26_sshkey && chmod 0600 bandit26_sshkey &&  resize the window so that it enters more edit mode by pressing v &&  e: /etc/bandit_pass/bandit26` |
| bandit27 | 3ba3118a22e93127a4ed485be72ef5ea | `same as 26- resize window &&  press v &&  type :set shell=/bin/bash && :shell && ls -la && ./bandit27-do cat /etc/bandit_pass/bandit27` |
| bandit28 | 0ef186ac70e04ea33b4c1853d2526fa2 | `mkdir /tmp/work3 && cd $_ &&  git clone ssh://bandit27-git@localhost/home/bandit27-git/repo && cat repo/README ` |
| bandit29 | bbc96594b4e001778eee9975372716b2 | `mkdir /tmp/work4 && cd $_ &&  git clone ssh://bandit28-git@localhost/home/bandit28-git/repo && git log && git reset --hard c086d11a00c0648d095d04c089786efef5e01264 && cat repo/README.md` |
| bandit30 | 5b90576bedb2cc04c86a9e924ce42faf| `git like 27 &&  git branch -r &&  git checkout dev &&  git branch && git log -p -1` |
| bandit31 | 47e603bb428404d265f59c42920d81e5 | `git like 27 &&  git tag && git show secret` |
| bandit32 | 56a9bf19c63d650ce78e6ec0354ee45e | `git like 27 && echo "May I come in?" > key.txt; git add -f key.txt && git commit -m "hi" && git push` |
| bandit33 | c9c3199ddf4121b10cf581a98d51caee | `$0 && cat /etc/bandit_pass/bandit33` |

### The end :)
