# Basic React Project Form

This project is for training only. Through this project, we learn to create input form web pages and display the result from user's input with a table. This project implement React-Hook, React-Router-DOM and React-Hook-Form.

## Preview

![Preview](./preview.png)

## How to Run this Project (Manual/Docker)

### Manually
1. Clone this project
```
git clone https://github.com/mdavindarinaldy/fgo24-react-form.git
```
2. Install dependencies
```
npm install
``` 
3. Run the project
```
npm run dev
```
4. Project will running on http://localhost:5173

### With Docker
1. Clone this project
```
git clone https://github.com/mdavindarinaldy/fgo24-react-form.git
```
2. Build image
```
docker build . -t ubuntu:form
```
3. Run image with docker
```
docker run -p 8080:80 -d ubuntu:form
```
4. Project will be running on http://localhost:8080

## Dependencies
This project using node.js to run, make sure to install node on your machine. Other than that, this project also using Vite, React, React Hook, React Hook Form, React Router DOM and ESLint.

## Basic Information
This project is part of training in Kodacademy Bootcamp Batch 24 made by Muhammad Davinda Rinaldy
