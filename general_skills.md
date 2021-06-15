# **GENERAL SKILLS**

**CHALLENGE :Wave a flag**

**DESCRIPTION:**

Can you invoke help flags for a tool or binary? [This program](https://mercury.picoctf.net/static/beec4f433e5ee5bfcd71bba8d5863faf/warm) has extraordinarily helpful information...

**SOLUTION:**

When we open the task there is a program file attached to it so i downloaded and run following commands:

$ chmod +x warm

$ ./warm -h

It will give the flag as output.

**FLAG:** picoCTF{b1scu1ts\_4nd\_gr4vy\_616f7182}

**CHALLENGE :Static ain&#39;t always noise**

**DESCRIPTION:**

Can you look at the data in this binary: [static](https://mercury.picoctf.net/static/66932732825076cad4ba43e463dae82f/static)?This [BASH script](https://mercury.picoctf.net/static/66932732825076cad4ba43e463dae82f/ltdis.sh) might help!

**SOLUTION:**

When i opened the task I found a shell script and another static file so i run the shell script giving the argument as the file name static after that it output two files in which one text file with a messed up text and i used the following command to find the flag:

Cat &quot;textfile&quot; | grep &quot;pico&quot;

**FLAG:** picoCTF{d15a5m\_t34s3r\_f5aeda17}

**CHALLENGE :NIce netcat...**

**DESCRIPTION:**

There is a nice program that you can talk to by using this command in a shell: $ nc mercury.picoctf.net 7449, but it doesn&#39;t speak English..

**SOLUTION:**

When we connect to the mercury.picoctf.net we find a long list of numbers which can be ascii or decimal so i tried decoding the text with a online decimal to text converter and ascii decoder so when i used ascii decoder i got the flag.

**FLAG:** picoCTF{g00d\_k1tty!\_n1c3\_k1tty!\_f2d7cafa}
