# JATE - Progressive Web App Text Editor

JATE (Just Another Text Editor) is a Progressive Web App (PWA) text editor built using JavaScript, Webpack, and other web technologies. It allows users to create, edit, and save text documents, providing an offline-capable and installable experience.

## Features

- **Offline Capabilities:** JATE is designed to work offline, allowing users to access their documents even when there's no internet connection.
- **Installable:** Users can install JATE on their devices, making it readily available from the home screen.
- **Manifest File:** The project includes a Web App Manifest file for configuring the PWA's appearance on the user's device.
- **Service Worker:** A service worker is implemented to enable background synchronization and improve performance.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/FrattiJ/PWA-TextEditor
   cd PWA-TextEditor
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

### Usage

1. Build the project:

   ```bash
   npm run build
   ```

2. Start the development server:

   ```bash
   npm start
   ```

   The app will be accessible at `http://localhost:3000` by default.

### Deployment

To deploy the project, you can use hosting services like Netlify, Vercel, or GitHub Pages. Ensure your hosting provider supports PWAs.

## Contributing

If you'd like to contribute to JATE, feel free to open an issue, create a pull request, or reach out to the project maintainers.

## Deployed

Deployed at https://pwa-texteditor-33ju.onrender.com/ using Render
