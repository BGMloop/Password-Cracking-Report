# Password-Cracking-Report
The topics discussed revolved around how I did the hashing and the challenges I ran into using Hashcat

# Extract & Crack 15 Password Hashes
![Screen Shot 2025-01-17 at 2 14 07 AM](https://github.com/user-attachments/assets/1967563d-275c-4b5e-a4f8-a81e96a0eb28)

# Memorandum

From: Bwalya M.
Subject: Password Cracking Report 
Date: 11/30/2022

The Windows XP password hash files which I used to access the System and SAM files was the Ophcrack rainbow table from the XP German (7.4GB) folder. The XP German folder had hash tables with special characters, mixedalphanum, alphanum, numbers, and dictionary-based characters, but the length is 16 characters for length NT hashes. The same methods that a hacker would use to steal the passwords in a live situation. I was able to crack 15 password hashes, but it took me a week to get them all since every time I was able to access them on the Kali VM in VirtualBox was only when I had access to the UNT lab computers.
The Lab on Password cracking help that I got with Hashcat is known for being the fastest password recovery tool due to its design which is for solving complex passwords in a very quick time. With features like wordlist and brute force attacks is how all the passwords are solved in Hashcat. So, I decided to make a wordlist of all the Charlie Brown words from the thanksgiving movie. Is how I approach my attempt to solve the passwords, since I used hashcat to attempt to solve Charlie Brown hash maps, so I had to do research on how to use it. I downloaded it into my Kali Linux VM VirtualBox system. I struggled at the beginning because this was my first time using Hashcat.
The topics discussed revolved around how I did the hashing and the challenges I ran into. I was unable to access Oracle VM VirtualBox on my EliteBook DESKTOP-22TK996 which is currently running on Windows 10 Home. Looking it up on google told me a lot about what it requires to
get Oracle VM VirtualBox working again when you run into errors. It is tough and not easy. I think there's a difference between on a Windows 7 and newer system, because an old processor such as Windows 7 is a better fit to run LM and NT Hash than if I were to do it on a newer system due to errors which a newer system would run into.
Then I needed to watch YouTube videos on how to solve my computer issue, but I was unable to solve the problem which prompted me to attempt this lab on my Mac instead. Even though it was tough, the apple processor is an M1. Which required me to look up instructions for Kali on Mac processor M1. I needed VMware to solve my problem which left me even more confused on how to get Kali working on my Mac. So, I ended up giving up on using my mac when I decided I would drive from McKinney to Denton every day for 2 weeks when I didn't have class. The computer lab in Denton was only open from 9am to 10pm, so a lot of the days I would have to restart the process of using Ophcrack.
The Lab on password cracking was very enlightening on the necessary qualifications, the perceived files that a hacker could steal to access the passwords in a live situation, and the specific physical XP system based on if the system is online or if a weak security plan is weak. A hacker could obtain the passwords by reading the fire walls and seeing if the security plan hasn't changed since you’ve had the computer.
The purpose of this lab on password cracking was to gain some insight on life after college from a cyber security professional major. I tried to soak up everything necessary that Professor Hoffman said in the Windows password cracking demo - Ophcrack on Kali so I could carry it over. I was able to walk away with a new mindset on what it takes to succeed in the field of Penetration Tester.
