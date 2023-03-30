# ZCore Network (ZCN) validator JSON KEY

### Install Docker Desktop
https://www.docker.com/products/docker-desktop/

### Download this repository and extract:
https://github.com/mosqueiro/zcore-getkey/archive/refs/heads/main.zip

### Commands
- Open ```.env``` with text editor and edit with your privatekey and password (leave the private key blank to generate a new)

- Delete the contents of the ```generate``` folder (don't delete the folder)

- Run ```docker compose up``` command in the folder where you extracted this repository[^1]

[^1]: _If you don't want to use docker and you have nodejs installed, just type in the root of the directory: ```node index.js YOUR_PASSWORD YOUR_PRIVATEKEY```_


- The files required for the ZCore validator will be generated in the folder ```generate```:

![address](https://github.com/zcore-network/genkey/raw/main/images/generate.png)

- Copy and SAVE in a secure location the generated address, privatekey and password:

![address](https://github.com/zcore-network/genkey/raw/main/images/docker.png)

- Copy the content folder ```generate``` and paste in the root folder of the validator repository