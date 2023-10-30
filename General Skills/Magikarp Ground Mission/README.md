## Magikarp Ground Mission
* Points: 30pt
* Tags: `General Skills`, `picoCTF 2021`
## Description
> Do you know how to move between directories and read files in the shell? Start the container, `ssh` to it, and then `ls` once connected to begin. Login via `ssh` as `ctf-player` with the password, `b60940ca`
Additional details will be available after launching your challenge instance.
## Hints
> * Finding a cheatsheet for bash would be really helpful!
## Solution
1. launch the instance and you'll get SSH and connect it with given id and password
2. `ls` to see what kind of files in there. open `1of3.flag.txt` by using `cat` and I got: `picoCTF{xxsh_`
 open `instructions-to-2of3.txt` and it's saying `Next, go to the root of all things, more succinctly `/``
 `cd /` and you do `cat 2of3.flag.txt` and I got: `0ut_0f_\/\/4t3r_`
open 'instructions-to-3of3.txt' and It's saying 'Lastly, ctf-player, go home... more succinctly `~`'
Do `cd ~` and you got 3of3.flag.txt and I got: `c1754242}`
## Flag
`picoCTF{xxsh_0ut_0f_\/\/4t3r_c1754242}`
