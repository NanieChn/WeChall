Training: Warchall - The Beginning
--
In this challenge, it's better to use *lower-case letters* in your username. The reason is simply to avoid conversion errors because your username will be converted to lowercase, mentioned the subject. After the form, it's also better to keep to the time limit of *one minute* before to enter the next command in your terminal or in puTTY :
```
ssh -p 19198 username@warchall.net
```
Then, you can enter your password and try :
``ls``. You can see these folders : *WELCOME.md, level, www, www_access.log* and *www_error.log*. If you read *WELCOME.md* and follow the instructions from``cat WELCOME.md``, you can already find the flag of the **level 4** in */home/user/yournick/level/04_kwisatz/README2.md*. You don't have *permission* to read *README2.md* and you will use the command``chmod +r README2.md``

Now, use``cd /home/level``to go */home/level*, the place where are the others flags.

For the **level 0**, you can just go in *00_welcome* and display the content of *README.md* with``cd 00_welcome.md``and``cat README.md``

Next, go back in */home/level* and in *01_choice_tree* for the **level 1**. You can see so many folders inside and with``cd``,``ls``and``cat``, you should be able to find the flag in */blue/hats/grey/solution/patience/SOLUTION.txt*

Do``ls -a``to appear *.porb*, an *hidden folder* in */home/level/02*. Then ``cat .solution``inside.

The commands to find the flag for **level 3** are :
```
cd /home/level/03
cat .bash_history
``` 
For the **level 5** :
```
cd /home/level/05_privacy
cat README.md
```
Now, you can input in order these passwords without the quotes.
