1. Open GitBash
2. Create .ssh folder into C:\Users\<User_Name>.
3. Go to .ssh folder.
4. generate ssh-key using the below command
   ssh-keygen -t ed25519 -C "your-mail@example.com"
5. It prompts for the file_name , optional to provide filename.
   if we did nt give it will create with the file 

   id_ed25519 (creates 2 files one for public key & private key)
6. Provide password for the key file(remember this password).
7. Copy the id_ed25519.pub key to the github account.
   Go to https://github.com/settings/keys add SSH Key.
8. Set up is completed.

Can clone the projects using SSH option easily.