# Getting Started

## Server Requirements
- [NodeJs](https://nodejs.org/en/)
- [Database Server](#)

## Global Setup
> after install node package manager following these steps

Install Globallay Kasfy
```bash
# linux, ubuntu, and mac using with "sudo"
sudo npm install -g kasfy

# windows must run cmd with administrator permission 
npm install -g kasfy
```

> Navigate your like path after run this command to clone kasfy latest repository you need name

```bash
kasfy create AwesomeApp   

# OR

kasfy new AwesomeApp
```
> 'AwesomeApp' is sample name. 

## Setup Project
Navigate your new kasfy project
```bash
cd AwesomeApp

# Create .env file from .env.example
# Linux OR Mac
cp .env.example .env

#Windows
copy .env.example .env
```

Next install NPM Dependencies
```bash
npm install
```

### Local Development Server
If you have NodeJS installed locally and you would like to use NodeJS's built-in development server to serve your application, you may use the serve kasfy command. This command will start a development server at http://localhost:5050:
> you can change default port on .env file `PORT=5050`

```bash
npm start
```

