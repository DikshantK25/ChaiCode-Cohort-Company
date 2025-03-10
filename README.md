# ChaiCode-Cohort-Company

## Welcome to Git and GitHub at ChaiCode Cohort! ☕️

### Introduction  
Welcome to ChaiCode! Git and GitHub are the backbone of our development workflow. Git helps track code changes, while GitHub enables seamless collaboration. This guide will get you up and running with both tools in no time. Let’s brew some code!  

---

## Basics of Git and GitHub  
### What is Git?  
Git is a **version control system** that tracks changes to your code. Think of it as a time machine for your projects!  

### What is GitHub?  
GitHub is a platform where teams host, review, and collaborate on code. It’s where we share our "chai recipes" (projects) and work together.  

---

## Installation and Setup  

### Step 1: Install Git  

#### **Windows**  
1. Download Git from [git-scm.com](https://git-scm.com/).  

![Git Installation on Windows](https://media.geeksforgeeks.org/wp-content/uploads/20241206182446410213/gitwindows0.webp)

2. Run the installer and follow the prompts (keep default settings). 
   - Choose a text editor like Vim, Notepad++, or Visual Studio Code.
   - Ensure Git is added to your system PATH (recommended for command-line usage).
   - Select the default option (OpenSSL) for secure Git communication.
   - Use "Checkout Windows-style, commit Unix-style line endings" for compatibility.

3. Verify installation by opening Command Prompt and typing:
   ```bash
   git --version
   ```

![Verify Git Installation](https://media.geeksforgeeks.org/wp-content/uploads/20241206183109013872/verify2.webp)

---

### macOS Installation  

#### **Option 1: Install Git via Mac App Store**  
1. **Open the Mac App Store**:  
   - Launch the App Store from your Dock or via Spotlight Search.  
   - Alternatively, visit the [Mac App Store website](https://apps.apple.com).  

![Mac App Store Website](https://media.geeksforgeeks.org/wp-content/uploads/20241206173516480528/apple2.webp)  

2. **Search for Git**:  
   - Type "Git" in the search bar.  
   - Select a Git client like **GitUp** or another GUI tool with Git support.  

![Search for Git](https://media.geeksforgeeks.org/wp-content/uploads/20241206173719624171/apple33.webp)  

3. **Install and Verify**:  
   - Click **Get** or **Install** to download the app.  
   - After installation, open Terminal and verify Git:  
     ```bash  
     git --version  
     ```  
   
![Verify Git Installation](https://media.geeksforgeeks.org/wp-content/uploads/20241206172846695430/verify3.webp)  

---

## Git Installation on Ubuntu  

### Step 1: Update System Packages  
Before installing Git, update your system:
```bash  
sudo apt update  
sudo apt upgrade -y  
```  

![Update Ubuntu Packages](https://media.geeksforgeeks.org/wp-content/uploads/20241227174453118353/install.webp)

### Step 2: Install Git  
Install Git using the `git-all` package:
```bash  
sudo apt install git-all  
```  

![Install Git on Ubuntu](https://media.geeksforgeeks.org/wp-content/uploads/20241227174453118353/install.webp)

### Step 3: Verify Installation  
Check if Git is installed correctly:
```bash  
git --version  
```  
Example output:
```  
git version 2.34.1  
```  

![Check Git Version](https://media.geeksforgeeks.org/wp-content/uploads/20241227174530156014/version.webp)

---

### Step 4: Configure Git  
Set your username and email (use your ChaiCode credentials):  
```bash  
git config --global user.name "Your Name"  
git config --global user.email "your.email@example.com"  
```  

Verify your configuration:  
```bash  
git config --global --list  
```  

![Git Configuration](/images/git-config.png)  

---

### Step 5: Create a GitHub Account  
1. Go to [github.com](https://github.com/).  
2. Click **Sign Up** and follow the steps.  
3. Enable **Two-Factor Authentication (2FA)** for security (required at ChaiCode).  

![GitHub Signup Page](/images/github-signup.png)  

