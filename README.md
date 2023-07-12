## Introduction

Encrypt files and then send them over the internet securely. The files are encrypted using the AES-256-CTR algorithm. Neither files nor passwords are stored on our server.

![Screenshoot](screenshoot.png?raw=true)

## How To Use

1. Open https://encryption-site-nextjs.vercel.app 
2. Select a file (under 1MB), input your password then click on Encrypt button. Your encrypted file will be downloaded automatically.
3. Send your friend your encrypted file. Then they can decrypt it using your password.

## Caveat

This project is deployed on the Vercel platform, and Vercel's serverless function restricts file uploads to a size under 1MB.

