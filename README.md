#### Introduction
This is a server which is created using nodejs and express to serve documentation files written in markdown. You are suppose to put all markdown files inside the docs folder in the project directory. The server will serve the markdown files as html files. You can navigate and choose all your markdown files from the list to view them. To view your markdown file go to the path `http://localhost:8080/docs?name=[name of the file]`.

#### Setup
1. Clone the repository
2. Run `npm install`
3. `ln -s [path to docs directory] docs`  **create a softlink locally for navigation from server**
4. Run `npm run start:dev`  **(for development)**
5. Run `npm run start`  **(for production)**
6. Open your browser and navigate to `http://localhost:8080/`
7. For opening a specific file use `http://localhost:8080/docs?name=[name of the file]`
