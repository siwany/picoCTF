## Wave a flag
* Points: 20pt
* Tags: `General Skills`, `picoCTF 2021`
## Description
> Can you look at the data in this binary: [static](static)? This [BASH script](ltdis.sh) might help!
## Hint
> N/A
## Solution
1. Start by reading through the `ltdis.sh` file and discover that you can utilize the `strings` command to extract information from the file and execute the command: `strings static | grep pico`
2. This command searches for the term `pico` within the `static` file
## Flag
`picoCTF{d15a5m_t34s3r_f6c48608}`


