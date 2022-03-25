# [Over The Wire](https://overthewire.org/wargames/)
## [Leviathan](https://overthewire.org/wargames/leviathan/)

| Username  |  Password | How to get the password  |
| :------------ | :------------ | :------------ |
| leviathan0  |  leviathan0 |  `#password obtained from webpage` |
|   leviathan1|  rioGegei8m | `cd .backup; grep "leviathan" bookmarks.html` |
|   leviathan2| ougahZi8Ta  | `gdb ./check; disas main; b *main(wherever the strcmp address is); x/s $(lea  before strcomp) this will give you the password; ./check passwrod; find / -name leviathan2; cat /etc/leviathan_pass/leviathan2`  |
|   leviathan3|  Ahdiemoo1j |  `mkdir /tmp/ee && cd $_; ln -s /etc/leviathan_pass/leviathan3 .;touch "get leviathan3";~/printfile "get leviathan3"` |
|   leviathan4| vuH0coox6m  | `gdb -q level3; disas main -> disas do_stuff; b *dostuff+strcomp; check for lea x/s -> password; find / -iname $(whoami) -exec cat {} \;`  |
|   leviathan5| Tith4cokei  |`cd .trash; ./bin; then covert from binary to ascii`    |
|   leviathan6|  UgaoFee4li |  ` ln -s /etc/leviathan_pass/leviathan6 /tmp/file.log; ./leviathan5` |
|   leviathan7|  ahy7MaeBo9 |   `used ltrace;gdb; eventually bruteforce; for i in (seq 0000 9999); do echo $i; ./leviathan6; done; find / -iname $(whoami) -exec cat {} \;`|



##The end :)
