## Nice netcat...
* Points: 15pt
* Tags: `General Skills`, `picoCTF 2021`
## Description
> There is a nice program that you can talk to by using this command in a shell: $ nc mercury.picoctf.net 35652, but it doesn't speak English...
## Hints
> * You can practice using netcat with this picoGym problem: `what's a netcat`?
> * You can practice reading and writing ASCII with this picoGym problem: `Let's Warm Up`
## Solution
Open the terminal and type
`$ nc mercury.picoctf.net 35652`
and you are going to to get the number lists and convert it using this online ascii to string converter: [Online string tools](https://onlinestringtools.com/convert-ascii-to-string)
![ASCII conversion](image.png)

## Flag
`picoCTF{g00d_k1tty!_n1c3_k1tty!_9b3b7392}`