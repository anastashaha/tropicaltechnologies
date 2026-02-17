# Node Landing Site

This project is a simple Node.js website featuring a mobile-responsive landing page. The landing page includes a background image and a logo that serves as both the favicon and is displayed at the center of the page.

## Project Structure

```
node-landing-site
├── public
│   ├── index.html        # HTML structure for the landing page
│   ├── css
│   │   └── styles.css    # CSS styles for the landing page
│   ├── js
│   │   └── main.js       # JavaScript for interactive features
│   └── images
│       ├── texture_background.jpeg  # Background image
│       └── pattern_logo.png         # Logo and favicon
├── server.js            # Entry point for the Node.js server
├── package.json         # npm configuration file
├── .gitignore           # Files and directories to ignore by Git
└── README.md            # Project documentation
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd node-landing-site
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Run the server:**
   ```
   node server.js
   ```

4. **Open your browser:**
   Navigate to `http://localhost:3000` to view the landing page.

## Features

- Mobile-responsive design
- Background image for the landing page
- Centered logo that serves as a favicon
- Basic JavaScript functionality for interactivity

## Technologies Used

- Node.js
- Express
- HTML
- CSS
- JavaScript

## License

This project is licensed under the MIT License.