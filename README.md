## Frontend
    cd into the main file and npm install
    if using WSL or a VM, create .env file and add CHOKIDAR_USEPOLLING=true
    npm start

## Backend
    create a mongodb atlas instance and get the connection uri (can also locally install)
    cd into backend folder 
    create .env file (fill out ATLAS_URI)
    npm install
    nodemon server.js