## Magikarp Ground Mission
* Points: 30pt
* Tags: `General Skills`, `picoCTF 2021`
## Description
> Do you know how to move between directories and read files in the shell? Start the container, `ssh` to it, and then `ls` once connected to begin. Login via `ssh` as `ctf-player` with the password, `b60940ca`
Additional details will be available after launching your challenge instance.
## Hints
> * Finding a cheatsheet for bash would be really helpful!
## Solution
1. Launch the instance and establish an SSH connection using the provided ID and password.
2. Use the following commands to explore the files and retrieve the flag:
* Run ls to list the files in the current directory.
* Open `1of3.flag.txt` using the cat command: `cat 1of3.flag.txt`. You get the partial flag: **`picoCTF{xxsh_`**
3. Open `instructions-to-2of3.txt` to get further instructions: `cat instructions-to-2of3.txt`. It says, **"Next, go to the root of all things, more succinctly /."**
4. Navigate to the root directory using the `cd /` command.
5. Retrieve the second part of the flag by using the cat command to open `2of3.flag.txt`: `cat 2of3.flag.txt`. You get the partial flag: `0ut_0f_\/\/4t3r_.`
6. Open `instructions-to-3of3.txt` to get the final instructions: `cat instructions-to-3of3.txt`. It says, **"Lastly, ctf-player, go home... more succinctly ~."**
7. Navigate to your home directory using the `cd ~` command.
8. Retrieve the third and final part of the flag by using the cat command to open `3of3.flag.txt`: `cat 3of3.flag.txt`. You get the partial flag: `c1754242}`.
9. Combine the three partical flags to complete the flag.
## Flag
`picoCTF{xxsh_0ut_0f_\/\/4t3r_c1754242}`
