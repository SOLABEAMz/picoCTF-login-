https://play.picoctf.org/practice/challenge/200?assigned=0&bookmarked=0&category=1&difficulty=2&page=2&solved=0

Here limk

<img width="954" height="499" alt="wwww" src="https://github.com/user-attachments/assets/d9f50094-28bc-464c-a48b-ce1c90554818" />

Step 1: Click on the link


https://login.mars.picoctf.net/

You will redirect to login page


<img width="507" height="424" alt="image" src="https://github.com/user-attachments/assets/db7e3d97-4866-4fbb-a89f-a3c973add4c0" />



Step 2: Use ctrl+u View Page Source of Login page Here you will see index.js



<img width="438" height="316" alt="w" src="https://github.com/user-attachments/assets/9f0ebae3-6b1d-4026-bdf4-f096afc72eb2" />

Move to Inspect Accessibility Properties

Use right click prees Inspect

<img width="1913" height="968" alt="Capture" src="https://github.com/user-attachments/assets/89a4db33-5a1d-440e-880f-6380b3b5164a" />

Click on Sources where you will see index.js . Click on index.js File you will see the following interface.

<img width="1717" height="972" alt="wawdawd" src="https://github.com/user-attachments/assets/ce527270-7707-4d41-a85a-b68f2725f3f2" />

Step 3:Focus on return

Decode the string ‘YWRtaW4’ and ‘cGljb0NURns1M3J2M3JfNTNydjNyXzUzcnYzcl81M3J2M3JfNTNydjNyfQ’

Here, I am using Famous Base64 Decoder and Encoder . I am pasting the link as well for you https://www.base64decode.org/

<img width="960" height="930" alt="ee" src="https://github.com/user-attachments/assets/e8876b2e-f5ae-4394-b82c-b43242292e72" />

We got a Username “admin”

Similarly we Decode another String

<img width="958" height="948" alt="gggfgfggf" src="https://github.com/user-attachments/assets/02bbb524-4ff2-4210-a43a-cac9e3e3b002" />

Finally we got our flag

picoCTF{53rv3r_53rv3r_53rv3r_53rv3r_53rv3r}

Happy Hacking!
Thank you!

นายรัฐศาสตร์ ขวัญเพ็ง




