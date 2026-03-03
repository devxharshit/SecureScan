# SecureScan

SecureScan is a lightweight web vulnerability scanner built using Node.js and Express.

## Features
- HTTPS detection
- Security header analysis
- Information leakage detection
- SSRF protection
- DNS resolution validation

## Tech Stack
- Node.js
- Express
- Axios
- DNS module

## How to Run

npm install
node server.js

## API Endpoint

POST /api/scan

Body:
{
  "url": "https://example.com"
}
