# Railway Array API

A simple Express API for managing an in-memory task array. It was created as a Railway deployment demo.

## Run locally

```bash
npm install
npm start
```

The server runs on `http://localhost:3000` by default.

## API endpoints

| Method | Endpoint | Description |
|---|---|---|
| `GET` | `/` | Check that the API is running |
| `GET` | `/api/tasks` | Get all tasks |
| `POST` | `/api/tasks` | Create a task with a JSON `title` |
| `DELETE` | `/api/tasks/:id` | Delete a task by ID |

Tasks are stored in memory and reset whenever the server is restarted or redeployed.
