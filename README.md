# Random-Website
A random website.

## Getting Started for New GitHub Users


Before contributing, make sure **Git** is installed on your device.


### Installing Git


#### Windows
1. Open **Command Prompt** or **PowerShell**.
2. Run this command to install Git:
    ```bash
    winget install --id Git.Git -e --source winget
    ```
3. Verify Git installation:
    ```bash
    git --version
    ```
If it shows a version number (e.g., `git version 2.52.0`), Git is installed successfully.


#### macOS
```bash
brew install git
```

#### Linux (Debian/Ubuntu)
```bash
sudo apt update
sudo apt install git
git --version
```


---


## Cloning the Repository


To work on this project, first **clone the repo** to your local machine:


```bash
git clone https://github.com/Ducktavian/Random-Website.git
cd Random-Website
```


---


## Keeping Your Repo Up-to-Date


Before you start editing, make sure your local copy is up-to-date:


```bash
git pull origin main
```


> **Tip:** Replace `main` with your branch name if different.


---


## Making Changes


1. Edit or add files in the project as needed (features, styling, random experiments… whatever you like!).
2. Check which files have changed:
    ```bash
    git status
    ```
3. Stage your changes:
    ```bash
    git add .
    ```
4. Commit your changes with a clear message:
    ```bash
    git commit -m "Add feature XYZ or fix bug ABC"
    ```
5. Push your changes to GitHub:
    ```bash
    git push origin main
    ```


---


## Best Practices


- Pull updates before starting your work to avoid conflicts.
- Write clear commit messages.
- Make small, focused commits for easier collaboration.


---


## License


Feel free to use and modify this project for fun! ✨


