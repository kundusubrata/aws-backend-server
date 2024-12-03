
# Basic Backend Server

This is a basic backend server built with Node.js and Express.js using Javascript. It provides several API routes for testing purposes, including fetching todos, calculating sums, and generating random notifications.

## Prerequisites

- NVM(Node Version Manager) [NVM Installation guide](https://codedamn.com/news/nodejs/nvm-installation-setup-guide)
- Git
	```
	nvm --version
	nvm ls-remote
	nvm install node
	node -v
	npm -v
	```
## Installation && Running the Server
```
git clone https://github.com/kundusubrata/aws-backend-server.git
cd aws-backend-server
npm install 
npm run dev
```
The server will run on `http://localhost:8080`.

## API Endpoints
1. Get a Specific Todo: http://localhost:8080/todo?id=2
2. Get Random Todos: http://localhost:8080/todos
3. Calculate Sum of Two Numbers: http://localhost:8080/sum?a=2&b=3
4. Calculate Simple Interest: http://localhost:8080/interest?principal=100&rate=5&time=2
5. Get Random Notifications: http://localhost:8080/notifications
