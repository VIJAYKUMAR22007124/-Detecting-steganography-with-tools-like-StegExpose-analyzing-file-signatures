# Detecting-steganography-with-tools-like-StegExpose-analyzing-file-signatures
## AIM:
To detect hidden data using steganography detection tools like StegExpose and analyze file signatures for authenticity and manipulation.

## DESIGN STEPS:
### Step 1:
Install StegExpose or use the JAR version to detect steganography in image files.

### Step 2:
Run StegExpose on a directory of suspected image files using the command:

### Step 3:
Analyze file signatures using tools like file, binwalk, or xxd to check for inconsistencies or embedded content.

## PROGRAM:
StegExpose and File Signature Analysis Commands

```
sudo apt update
sudo apt install steghide
steghide --version 
steghide embed -cf im.jpg -ef hn.txt
steghide extract -sf im.jpg
cat hn.txt
steghide info im.jpg
file im.jpg
binwalk im.jpg

```

## OUTPUT:
List of Images with Steganography Detection Scores and File Signature Details

![image](https://github.com/user-attachments/assets/91696bc4-66aa-49a6-a18e-8858afa4f4f8)

![image](https://github.com/user-attachments/assets/e2e1609c-c9ca-4eca-96f9-ecd30031175f)

![image](https://github.com/user-attachments/assets/96337ffe-eab7-48b4-8d54-384c52a58a7b)

![image](https://github.com/user-attachments/assets/982d1d44-9733-4914-9caf-f2e741fe0aca)

![image](https://github.com/user-attachments/assets/99e05394-678e-4641-b39a-c5bcfb0dc8a3)

![image](https://github.com/user-attachments/assets/11cc5ce6-df5a-4905-9cb7-6493870e1b74)


## RESULT:
Hidden data was successfully detected and file signatures were analyzed for irregularities.
