# Stripe API Server Setup
This guide explains how to set up and run the server script to use the Stripe API. Make sure this server is running before using the main app.

Prerequisites
Node.js: Ensure that Node.js is installed on your system. You can download it from Node.js Official Site.
Stripe API Key: This script uses Stripe's test API key (sk_test_...). Ensure you have a valid test key from your Stripe Dashboard.
Setup Instructions
Clone or download the repository containing this server script.

Navigate to the directory containing the server script:
```bash
cd path/to/server/script
```

Install dependencies: Run the following command to install the required Node.js packages:
```bash
npm install express stripe
```
Run the server: Start the server by executing:

```bash
node server.js
```
The server will start listening on port 4242 and display the message:

```csharp
Node server listening on port 4242!
```
