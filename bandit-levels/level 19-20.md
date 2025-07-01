OverTheWire Level 19-20 🪴
-------
I first approached this level by checking my home directory as always.
```
ls -l
```
I then saw that there was a file called bandit20-do and was unsure what it was so I did the following.

```
file bandit20-do 
```
I then got this message returned

<img width="488" alt="image" src="https://github.com/user-attachments/assets/1853548f-a99b-4956-875b-dea6df084fda" />

It says it's executable so I ran the file and another message returned.

<img width="193" alt="image" src="https://github.com/user-attachments/assets/36d4f713-c7a0-4a51-a8b1-487befa34b9d" />


After running the example I was given, more information was returned

<img width="427" alt="image" src="https://github.com/user-attachments/assets/fd452b0c-a809-4536-9c68-b32259a0a468" />

I then used this file as a superuser to run cat on where the password was. (The file shows what the euid was)

<img width="311" alt="image" src="https://github.com/user-attachments/assets/94f00697-5a09-4fd1-82bd-80113c590b34" />

And there we go!

I then ssh'd into bandit20 to proceed to the next level.

