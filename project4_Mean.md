## **Documentation for Project 4 MEAN Stack Deployment**

### nodejs Installation and Adding Certificates
`sudo apt update`

`sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates`

`curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash - `

`sudo apt install -y nodejs`

![nodeJs Installed](./Images/nodejs_installation.png)
![Certificate Added](./Images/adding_certificates.png)

### MongoDB Installation and Running 
`sudo apt install -y mongodb`

`sudo service mongodb start`

`sudo systemctl status mongodb`

`mkdir Books && cd Books`

`npm init`

`vi server.js`

![MongoDB-Installed](./Images/mongodb_installation.png)
![Server.js](./Images/server.js.png)

### NPM Installation and body parser
`sudo apt install -y npm`

`sudo npm install body-parser`

![NPM-Installed](./Images/npm_installation.png)
![Body-Parser Installed](./Images/body_passer_installation.png)

## Step 2

### Mongoose Installation
`sudo npm install express mongoose`

`mkdir apps && cd apps`

`vi routes.js`

`mkdir models && cd models`

`vi book.js`

`mkdir public && cd public`

`vi script.js`

`vi index.html`

`node server.js`

![Mongoose-Installed](./Images/express%26mongoose_installation.png)
![Book.js](./Images/book.js.png)
![script.js](./Images/script.js.png)
![routes.js](./Images/routes.js.png)
![html](./Images/index.html.png)

### Book Register app Live on web

![Apache running](./Images/apache_up%26running.png)
![Server Success](./Images/server_succes.png)
![Success](./Images/project4_success.png)