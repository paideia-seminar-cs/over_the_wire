Level 0

ssh -p 2220 bandit0@bandit.labs.overthewire.com

password is bandit0

cat README will display the answer

answer:  boJ9jbbUNNfktd78OOpsqOltutMc3MY1

---

Level 1

ssh -p 2220 bandit1@bandit.labs.overthewire.com

password is previous answer

need to read a file named -

cat ./-   will display the answer

answer:  CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

---

Level 2

ssh -p 2220 bandit2@bandit.labs.overthewire.com

password is previous answer

cat spaces\ in\ this\ filename will display the answer

answer:  UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

---

Level 3

ssh -p 2220 bandit2@bandit.labs.overthewire.com

password is previous answer

cd inhere

next password is in a hidden file.  use ls -a to find it

cat .hidden will display the answer

answer:  pIwrPrtPN36QITSp3EQaw936yaFoFgAB

---

Level 4

ssh -p 2220 bandit4@bandit.labs.overthewire.com

password is previous answer

cd inhere

only one of the files is human readable.  It has the password.  You can cat each one.  Use the up arrow to scroll through previous commands

answer:  koReBOKuIDDepwhWk7jZC0RTdopnAYKh

---

