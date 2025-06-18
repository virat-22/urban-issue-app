# Smart Urban Issue Reporting System

A web application for reporting, tracking, and resolving urban issues using AI prioritization and real-time updates.

## Features
- User registration and login
- Report issues with location and photos
- Admin dashboard for issue management
- Real-time map and notifications

## Project Structure
```
urban-issue-app/
│
├── public/
│   ├── images/           # Place your images here
│   ├── index.html
│   ├── register.html
│   ├── report.html
│   ├── dashboard.html
│   └── ...
│
├── src/
│   ├── js/
│   │   ├── report.js
│   │   ├── dashboard.js
│   │   └── auth.js
│   └── css/
│       └── styles.css
│
├── server.js             # Express server
├── package.json
└── README.md
```

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher)

### Installation
1. Clone this repository or download the source code.
2. Open a terminal in the project directory.
3. Install dependencies:
   ```
   npm install
   ```

### Running the App
Start the server:
```
npm start
```

Visit [http://localhost:3000](http://localhost:3000) in your browser.

## Customization
- Place your images in `public/images/`.
- Update HTML, CSS, and JS in the `public/` and `src/` folders as needed.

## License
MIT 