# hwinfo
hwinfo profiles of single board computers

## directions for adding profiles

1. clone repo
2. make a subdirectory under the form factor of the computer in question
3. capture output from
    + `dmesg`
    + `hwinfo`
    + `lscpu'
4. execute `neofetch`
    + grab a screen shot of the terminal window with the output of `neofetch`
5. copy README.md from another computer's directory
6. commit changes/additions
7. make pull request to main repo
