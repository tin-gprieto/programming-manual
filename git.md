# Git

## Authentification

[https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent]

1. Open git bash in the computer to authenticate
2. Paste

    ssh-keygen -t ed25519 -C "your_email@example.com"

3.Type a secure passphrase
4. Copy the SSH public key to [https://github.com/settings/ssh/new]
   
    cat ~/.ssh/id_ed25519.pub
