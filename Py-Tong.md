Py-Tong
--
Start by opening puTTy then :
```
cd /home/user/yournick
touch here.txt
nano script.sh
```
Inside, write :
```
!#bin/bash/
deadline=$((seconds+15))
while [ $seconds -lt $deadline ]
do
        echo "s" >>  here.txt
        sleep 0.005
done
```
This script add "s" during 15 seconds in *here.txt*
```
chmod 777 here.txt
chmod 777 script.sh
./script.sh
```
Quickly in an other terminal : ``./pytong  /home/user/yournick/here.txt``
