# 20Feb_1

A beginner-friendly Node.js tutorial server built with the [Express.js](https://expressjs.com/) framework. This project hosts two HTTP GET endpoints that return plain-text responses.

## Prerequisites

- **Node.js** v18 or higher (v20 LTS recommended)
- **npm** (comes bundled with Node.js)

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd 20Feb_1
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

   This will install Express.js and any other required packages listed in `package.json`.

## Starting the Server

Run the following command to start the server:

```bash
npm start
```

The server will start and listen on **port 3000**. You should see a confirmation message in the terminal.

Alternatively, you can start the server directly with:

```bash
node index.js
```

## Endpoints

| Method | Path       | Response       |
|--------|------------|----------------|
| GET    | `/`        | `Hello world`  |
| GET    | `/evening` | `Good evening` |

## Example Usage

Once the server is running, you can test the endpoints using a browser or cURL:

```bash
curl http://localhost:3000/
```

Returns: `Hello world`

```bash
curl http://localhost:3000/evening
```

Returns: `Good evening`