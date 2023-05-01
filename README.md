This is a file encryption tool developed using Python
AES has been used for file encryption

GreeshGrypt.py is the main program which implements the File encryption and decryption using AES-CFB mode.
Execute the GreeshGrypt.py file
A GUI application (built using the Tkinter library) opens for user.
User provides the file location or can browse the file. Then provide a secret key.
Now, User can encrypt the provided file by clicking encrypt button.
A message prompts to user after a successful file encryption.

This encrypted file can be seen in the folder with .encr as extension.
To decrypt this file user need to choose it or browse the file and provide same pass key.
To decrypt click on decrypt button on GUI.
This will decrypt the file with a name called <file-name>_decrypted and prompts with a message after it generates the decrypted file.
The file can be decrypted successfully only when pass-key provided matches with the pass-key used during encryption.
