# Lightweight Server

## Pre-Requisites

- Node.js

## Setup

- Checkout this code and open the directory in your terminal.
- Install the server using: `npm install`.

## Usage

- Launch the server with: `npm run serve`
- The server will start at `localhost:8084`. 
- The browser will open to `./path/to/html/` where the `index.html` is located.

## Configuration

To change which path is launched, change the `serve` command in `package.json`.

```json
{
    "private": true,
    "scripts": {
        "serve": "http-server --port 8284 -o path/to/html/"
        // You can add further commands here if you wish to launch different pages.
    },
    "dependencies": {
        "http-server": "0.12.3"
    }
}
```