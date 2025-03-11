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

# Update Web-Server
## Connect to server using ssh
1. In a terminal run the following command:
   ```sh
   ssh wwacaser@159.203.78.216
   ```
2. You should see something like this:
   `Welcome to Ubuntu 22.04.5 LTS (GNU/Linux 5.15.0-130-generic x86_64)`
3. Change into the website folder
   ```sh
   cd ~/selah_website
   ```
4. pull changes
   ```sh
   git pull
   ```
5. copy changes to var repo
   ```sh
   sudo cp * /var/www/html/selahdegering.com/
   ```
6. You will be prompted to enter a password, it will not show you the password, and when you type a character nothing will appear, hit enter when done entering the password. The password is stored in our password manager under selahdegering.som. Copy and paste may not work so you may need to manually enter it.

