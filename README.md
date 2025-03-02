# SimpleWebServer-GoLang

This is a simple web server implemented in Go. It serves static files from the `./static` directory and handles specific routes for form submissions and greetings.

## Features

- Serves static files from the `./static` directory.
- Handles form submissions at the `/form` endpoint.
- Responds with a greeting at the `/hello` endpoint.

## Usage

1. Place your static files in the `./static` directory.
2. Run the server using the following command:

   ```sh
   go run main.go