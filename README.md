# Simple WebAuthn Server Example

This project demonstrates a simple implementation of WebAuthn (Web Authentication API) using Express.js and the `@simplewebauthn/server` package. It allows users to register and authenticate using WebAuthn-compatible authenticators, such as security keys or built-in platform authenticators (like Windows Hello or Touch ID).

## Features

- **User Registration**: Register a new user with a username and password.
- **Passkey Registration**: Generate and verify a WebAuthn registration challenge.
- **User Authentication**: Generate and verify a WebAuthn authentication challenge.

## Prerequisites

- Node.js (v14 or later)
- npm or yarn

## Getting Started

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/HashirImteyaz/web_authentication
    cd webauthn-example
    ```

2. Install dependencies:

    ```bash
    npm install
    # or
    yarn install
    ```

### Running the Server

Start the Express server:

```bash
npm start
# or
yarn start
