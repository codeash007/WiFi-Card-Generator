# WiFi Card Generator

This project provides a simple web-based tool to generate WiFi QR codes for easy sharing of network credentials. Users can input their WiFi network name (SSID) and password, and the application will dynamically generate a QR code that, when scanned by a smartphone, allows for quick connection to the specified WiFi network. The application also includes a print functionality to create physical WiFi cards.




## Tech Stack

This project is built using fundamental web technologies:

*   **HTML5**: For structuring the content and layout of the web page.
*   **CSS3**: For styling the application, ensuring a clean and user-friendly interface.
*   **JavaScript (ES6+)**: For dynamic functionality, including generating the QR code based on user input and handling the print functionality.
*   **QR Code API**: Utilizes `https://api.qrserver.com/v1/create-qr-code/` to generate QR codes from the provided WiFi credentials.




## Professional Setup and Usage

To set up and run this project professionally, follow these steps:

### 1. Clone the Repository (if applicable)

If this project were hosted on a version control system like Git, you would typically start by cloning the repository:

```bash
git clone <repository_url>
cd wifi-card-generator
```

Since this is a local project, ensure you have the `wifi-card-generator` directory in your desired location.

### 2. Project Structure

The project has a simple structure:

```
wifi-card-generator/
├── dist/
│   ├── index.html
│   ├── script.js
│   └── style.css
└── src/
    ├── index.html
    ├── script.js
    └── style.css
```

- The `src/` directory contains the development source files.
- The `dist/` directory contains the production-ready, minified, or bundled files (though in this simple project, they are identical to `src/`).

### 3. Running the Project

This is a client-side web application and does not require a backend server for basic functionality. You can open the `index.html` file directly in your web browser.

**Option 1: Directly Open `index.html`**

Navigate to the `dist` (or `src`) directory and open `index.html` with your preferred web browser. For example, if using a command line:

```bash
# For macOS/Linux
open dist/index.html

# For Windows
start dist/index.html
```

**Option 2: Using a Local Web Server (Recommended for Professional Development)**

For professional development and to avoid potential browser security restrictions (e.g., related to QR code API calls), it's recommended to serve the files using a local web server. Here are a few ways:

#### Using Python's Built-in HTTP Server

If you have Python installed, you can quickly spin up a simple HTTP server:

```bash
cd wifi-card-generator/dist  # or src
python3 -m http.server 8000
```

Then, open your web browser and go to `http://localhost:8000`.

#### Using Node.js `http-server` (if Node.js is installed)

First, install `http-server` globally:

```bash
npm install -g http-server
```

Then, navigate to your project directory and start the server:

```bash
cd wifi-card-generator/dist  # or src
http-server
```

This will typically serve the application on `http://localhost:8080`.

### 4. Generating and Printing WiFi Cards

1.  Open the application in your browser.
2.  Enter your WiFi network name (SSID) in the 'Network name' field.
3.  Enter your WiFi password in the 'Password' field.
4.  As you type, the QR code will automatically update.
5.  Click the 'Print Wifi Card' button to open your browser's print dialog. You can then print the card or save it as a PDF.




## Telegram Community

Join our Telegram community for support, updates, and discussions:

[Telegram Group](https://t.me/codeash1430)





