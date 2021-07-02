# Crypto Room
# [Crypto TryHackME](./https://tryhackme.com/room/encryptioncrypto101)
## Task 2  Key terms

### Q1:Are SSH keys protected with a passphrase or a password?
A:PassPhrase
## Task 3  Why is Encryption important?

### Q2:What does SSH stand for?
A:Secure Shell

### Q3:How do webservers prove their identity?
A:certificates

### Q4:What is the main set of standards you need to comply with if you store or process payment card details?
A:PCI-DSS
## Task 4  Crucial Crypto Maths.

### Q5:What's 30 % 5?
A:0
### Q6:What's 25 % 7?
A:4
### Q7:What's 118613842 % 9091
A:3565

## Task 5:Types of Encryption

### Q8:Should you trust DES? Yea/Nay?
A:Nay.

### Q9:What was the result of the attempt to make DES more secure so that it could be used for longer?
A:Triple DES.

### Q10:Is it ok to share your public key? Yea/Nay?
A:Nay.

## Task 6  RSA - Rivest Shamir Adleman

### Q11:p = 4391, q = 6659. What is n?
A:29239669

## Task 8  Digital signatures and Certificates

### Q12:What company is TryHackMe's certificate issued to?
A:
1. By pressing on the lock button in the url tab.
2. We will find that the certificate used "CloudFlare"

## Task 9  SSH Authentication
### Q13:What algorithm does the key use?
A:
1. After downloading the file.
2. We will find the file made by RSA Key.

### Q14:Crack the password with John The Ripper and rockyou, what's the passphrase for the key?
A:
1. Open john the ripper.
2. Use this Command "/usr/share/john/ssh2john.py [downloaded file location] > [new file name]"
3. john [new file name] --worldlist=[rockyou.txt file location].

### Q15:You have the private key, and a file encrypted with the public key. Decrypt the file. What's the secret word?
A:
1. Firstly use kalil linux.
2. Secondly use this command"gpg --import tryhackme.key", Then you will find the key.
3. Thirdly go message.gpg, we will find RSA key.
4. Finally we will find the Encrypted file is "Pineapple".