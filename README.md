                                               Antivirus 


What is an AV?


Antivirus as the name suggest is any tool designed or intended to block,remove malicious software. Detecting malvare is done using two techniques. Each technique 
has its own advantages and disadvantages. Heruistic scanning and signature based. Signature based scanning involves  comparing each file's hash with the one present in the database. The most reliable form of hash is SHA256 because has a length of 64 bits and takes longer amount of time to be crack. This technique is advantageous because 
each file's signature is unique, has high processing speed and has a low rate of false positives. The biggest disadvantage is that if a malicious threat actor changes
the contents of a file,the entire hash changes. This would mean that the file would not be caught by AV's software using this technique because these vendors would 
simply not have the updated hash present in the database because the time they change it , it would be too late. There is however a more reliable form of detection. Heriustic analysis decompiles the binary  and compares it with some well known assembly  code intructions present in the DB. Using this method assures that there is 
less false positives and has a incredibility high rate of detection compared to signature based detection. The two types of heruistic scanning involves static and 
dynamic. Static scanning involves checking the contents of a potentially malicious file without executing it and dynamic involves the execution of the binary and allows the malvare analyst working in the AV firm to analyse the network traffic, registry changes or any file modification action which has taken place.This allows the researcher to determine the next course of action with the goal of preventing any future infections. However, only in rare cases there is a very slight chance that this sort of detection fails. To conclude, there is no 100% secure way of detecting any malicous software as hackers are continuosly learning their mistakes and creating constanly evolving piece of malicous software. All we can say is that in today's time and age ,the need for Cyber Security or AI intelligence will never die...


Why an Antivirus ?

After a long period of planning and deciding  what language to  use and all that shennagins, i had finally decided to create an antivirus which is going to be windows only for now and going to be designed in the C# programming language. I decided to make an AV because i found this topic really excting and intriging. I have  an Antivirus called Windows Defender  on my computer and was fascinated on how it reacts to malicous software.The way it quarantines malvare is executing is truly fascinating and better than all wonders in this world. I really want to follow this passion and will certainly make an attempt to follow this if any future opportunities arise.  



Why C#?
Because it is just amazing....


Method of Detection

. Signature based detection
(I am just learning how these things work so i decided to take baby steps by starting of from scratch.)



