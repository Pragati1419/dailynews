# React Newspaper App

This is a React web application that displays the latest news of the day, using the [Hacker News API](https://github.com/HackerNews/API).

The UI is designed in a way that resembles a traditional newspaper, with headlines, subheadings, and articles displayed in columns.

# File Tree
```
Daily-Newspaper
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── .env
├── yarn.lock
├── public
│   ├── image2.jpg
│   ├── index.html
│   └── manifest.json
└── src
    ├── App.js
    ├── index.js
    ├── sun-log.png
    └── serviceWorker.js
    └── Components
    |   ├── comp-1.js
    |   ├── comp-2.js
    |   ├── comp-3.png
    |   └── comp-4.js
    |   └── comp-5
    |   ├── component.css
    |   ├── innerComp2.js
    |   ├── main-comp.js
    |   ├── upperComp.js
    └── Containers
    |   ├── storyCont.js
    └── Services
    |   ├── hacknApi.js
    └── Stories
        ├── story.js
        ├── story.css
 ```
 
 
## Getting Started

To run this app on your local machine, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Run `npm install` to install the project dependencies.
4. Run `npm start` to start the development server.
5. Open `http://localhost:3000` in your web browser to view the app.

## Features

This app allows users to:

- View the latest news stories from the Hacker News API.
- Sort the news stories by date, popularity, or number of comments.
- Click on a news story to view the full article.

## Technologies Used

- React
- Axios (for making HTTP requests to the Hacker News API)
- CSS (for styling the UI)

## Screenshot of Project

![Screenshot (646)](https://user-images.githubusercontent.com/92241659/223613106-04899d3c-0fef-4265-997b-11074de0b6ea.png)



## License

This app is licensed under the [MIT License](https://opensource.org/licenses/MIT).
