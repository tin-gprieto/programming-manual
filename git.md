# Git

## Authentification

[https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent]

1. Open git bash in the computer to authenticate
   
3. Paste the next command to generate SSH public key

        ssh-keygen -t ed25519 -C "your_email@example.com"


3. Press enter to save the key in /home/<user>/.ssh/id_ed25519
   
5. Type a secure passphrase

6. Copy the SSH public key to [https://github.com/settings/ssh/new]
   
        cat ~/.ssh/id_ed25519.pub
