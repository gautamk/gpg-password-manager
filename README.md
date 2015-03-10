# gpg-password-manager
A web-application which can manage passwords within an organisation and store it safely by encrypting it using GPG

- Each user has their own GPG key
- All passwords of a user are encrypted and stored using gpg
- Sharing works by decrypting it and re-encrypting it using the reciever's key
