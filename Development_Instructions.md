# Viewing a Website Locally Using Python

## Prerequisites
- Ensure Python is installed (version 3.x recommended)
- Navigate to the project's root directory in the terminal

## Starting a Local Server
### Using Python 3
Run the following command in the terminal:
```sh
python -m http.server 8000
```
This will serve files from the current directory at `http://localhost:8000`.

## Stopping the Server
Press `CTRL + C` in the terminal to stop the server.

# Pulling Changes from the Repository
```sh
git pull
```

# Committing and Pushing Changes
1. Add all changes:
   ```sh
   git add .
   ```
2. Commit changes with a message:
   ```sh
   git commit -m "Describe your changes here"
   ```
3. Push changes to the main branch:
   ```sh
   git push origin main
   ```
