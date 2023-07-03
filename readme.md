# TIFC2DEV-ISD4 - GitHub

## Objectives
- Create their ssh key, and share it with GitHub.
- Create a GitHub Repository
  - **Do not initialize it**.
- Initialise and commit the changes in Replit.
- Copy the commands to push changes!


## Walk-Through
### Step 1) Have a GitHub and Replit Account
- Signup for GitHub
  - Login and have it on standby
- Signup for Replit
  - Login and have it on standby

### Step 2) Pair SSH from Replite to Github.
- **On** Replit go to your activity page []
  - Open your Shell and type
    - `ssh-keygen`
      - Press enter at all prompts
  - Check if your Public Key generated.
    - `cat ~/.ssh/id_rsa.pub`
      - If you see any text & numbers, copy it for GitHub.
- **Switch/Open** GitHub
  -  click your avatar in the top-right
  -  click Settings
  -  SSH and GPG keys
      - Click New SSH Key
      - Copy and paste the public key
      - Save

### Step 3) Creating a Repository on GitHub
- In GitHub click your avatar in the top-right click Plus
  - Click on Create Repository
    - **Warning** Do not initialize it
  - Copy the commands related to pushing an existing repository to another system.
    - This code will be used on replit.

### Step 4) Connecting and configuring GitHub with Replit's Git
- **Switch** to Replit
  - Open Shell in Replit
- Set up your git Username and Email by using these command:
  - `git config —-global user.name "your name"`
  - `git config —-global user.email "your email"`

### Step 5) Initialise and commit the changes in Replit.
- Initialise your git on replit
  - `git init`
- Add your new files to the staging area
  - `git add --all`
- Committ your first committ
  - `git committ -m "First commit"`
- - Copy and paste the commands from GitHub to your shell.
  - Ex:
    - `git remote add origin git@github.com:<GitHub username>/<Repository name>.git`
    - `git branch -M main`
    - `git push -u origin main`

### Step 6) Make 2nd committ and push it to Github
- Open up ReadMe.md
  - Add any random text like here
    - [Add text here]
- Git add, then committ
  - `git add --all`
  - `git committ -m "Second committ"`
- Push your commit to your GitHub
  - `git push`
