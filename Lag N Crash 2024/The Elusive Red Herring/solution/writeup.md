# Solution

the name of the challenge should be a red flag (pun intended) that the qr code is not the main focal point of the question. If you try to reconstruct the QR code, you will get a fake flag.

After noticing the size of the file, if you binwalk it you will see that it is hiding a couple of files inside.

![](C:\Users\mintymacbook\Downloads\LNC2024-Submission-Template-main\The%20Elusive%20Red%20Herring\solution\screenshot1.png)

extracting the folder inside you'll see that there are 5 files hidden inside of the zip

![](C:\Users\mintymacbook\Downloads\LNC2024-Submission-Template-main\The%20Elusive%20Red%20Herring\solution\screenshot2.png)

in red herring 4 there is another zip, which contains a zip file with 10k folders, each with fake flags.

![](C:\Users\mintymacbook\Downloads\LNC2024-Submission-Template-main\The%20Elusive%20Red%20Herring\solution\screenshot3.png)

either by writing code to filter out all the fake flags, or if they choose to manually go and check every file (insanity), they will find the flag in folder 6970 with the flag.

![](C:\Users\mintymacbook\Downloads\LNC2024-Submission-Template-main\The%20Elusive%20Red%20Herring\solution\Screenshot%202023-11-30%20151421.png)