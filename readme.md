# Evasion
The goal of this project is to understand the methods of hackers who bypass anti-viruses, so also to understand how antivirus works in a little more advanced way than mal-track.

## Audit 
### [Audit Questions](https://github.com/01-edu/public/tree/master/subjects/cybersecurity/evasion/audit)
### [Audit Video](https://youtu.be/T8oxhKJ62gM)
#### Video disclaimer - I wait from 1:38 to 2:58 for 101 seconds to complete, so you can skip that.

- Is the student able to explain how the Anti-Viruses detect the viruses?
    - it scans programs and files as they enter your device and compares them to known viruses, or it scans programs already on your device, looking for any suspicious behavior.

- Is the student able to explain clearly how he can bypass the Anti-Viruses?
    - Adding 100MB of memory is enough to discourage any emulation AV out there.
    - Most anti viruses scan files for a certain amount of time, so waiting for 100 seconds will bypass most AVs. 
    - Doing a basic operation for a sufficient number of time. In this case we use a for loop to increment 100001 times a counter. This is enough to bypass AVs.

- Is the student able to explain clearly how his program works?
    - I take an executable file, encrypt its content and make a program that decrypts it.

## Bonus

First I uploaded `mal-track.exe` from previous task to [Virustotal](https://www.virustotal.com/gui/home/upload). As you can see it's almost detected by every AV.   
<img src="https://01.kood.tech/git/juss/evasion/raw/branch/master/images/malexe.png" width="1000" heigth="400"/>     

Then I uploaded my `encrypted_mal-track.exe` and it's only detected by only 6 AVs.   
<img src="https://01.kood.tech/git/juss/evasion/raw/branch/master/images/encrypted_malexe.png" width="1000" heigth="400"/>     

##
### Author: [Juss](https://01.kood.tech/git/juss)