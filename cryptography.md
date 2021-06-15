# **CRYPTOGRAPHY**

**CHALLENGE :Mod 26**

**DESCRIPTION:**

Cryptography can be easy, do you know ROT13 is? cvpbPGS{arkg\_gvzr\_V&#39;yy\_gel\_2\_ebhaqf\_bs\_ebg13\_jdJBFOXJ}

**SOLUTION:**

When we visit the challenge website they have given a rot13 encrypted text which i decoded using a linux command:

echo &quot;rot13 encoded text&quot; |tr &#39;A-Za-z&#39; &#39;N-ZA-Mn-za-m&#39;

Then i got the flag.

**FLAG:** picoCTF{next\_time\_I&#39;ll\_try\_2\_rounds\_of\_rot13\_wqWOSBKW}

**CHALLENGE :Easy1**

**DESCRIPTION:**

The one time pad can be cryptographically secure, but not when you know the key. Can you solve this? We&#39;ve given you the encrypted flag, key, and a table to help UFJKXQZQUNB with the key of SOLVECRYPTO. Can you use this [table](https://jupiter.challenges.picoctf.org/static/1fd21547c154c678d2dab145c29f1d79/table.txt) to solve it?.

**SOLUTION:**

When i opened the task i found a file attached to that which contains a table so i checked the encrypted word in that text in each rows using the key in the same row. Then I found the flag combining the words I got after decrypting.

**FLAG:** picoCTF{CRYPTOISFUN}

**CHALLENGE:13**

**DESCRIPTION:**

Cryptography can be easy, do you know what ROT13 is? cvpbPGS{abg\_gbb\_onq\_bs\_n\_ceboyrz}

**SOLUTION:**

When we visit challenge they have given a rot13 encrypted text which i decoded using a linux command:

**echo &quot;rot13 encoded text&quot; | tr &#39;A-Za-z&#39; &#39;N-ZA-Mn-za-m**&quot; to get the flag.

**FLAG:** picoCTF{not\_too\_bad\_of\_a\_problem}