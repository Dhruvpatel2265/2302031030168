### **GitHub Setup and First Push Guide**

This guide will help you create a GitHub account, set up Git Bash, clone a repository, and push your first file using Git.

---

## **1. Create a GitHub Account**

1. Go to [GitHub](https://github.com/).
2. Click on **Sign Up**.
3. Enter a **username, email address, and password**.
4. Follow the instructions and verify your email.
5. Your GitHub account is now created.

---

## **2. Install and Set Up Git Bash**

1. Download **Git** from the official website: [Git for Windows](https://git-scm.com/downloads).
2. Install Git using the default settings.
3. Open **Git Bash** and configure Git with your GitHub credentials:

   ```sh
   git config --global user.name "Your Name"
   git config --global user.email "your-email@example.com"
   ```

4. Verify the configuration:

   ```sh
   git config --list
   ```

---

## **3. Clone a Repository**

1. Go to your GitHub repository.
2. Click on the **Code** button and copy the repository URL.
3. Open **Git Bash** and navigate to the folder where you want to clone the repository:

   ```sh
   cd path/to/your/folder
   ```

4. Clone the repository:

   ```sh
   git clone https://github.com/your-username/repository-name.git
   ```

5. Navigate into the cloned repository:

   ```sh
   cd repository-name
   ```

---

## **4. Add Your First File and Push It to GitHub**

1. Create a new file inside the repository folder:

   ```sh
   echo "Hello, GitHub!" > first-file.txt
   ```

2. Check the current status of your repository:

   ```sh
   git status
   ```

3. **Stage (Add) the file**:

   ```sh
   git add first-file.txt
   ```

4. **Commit the file with a message**:

   ```sh
   git commit -m "Added my first file"
   ```

5. **Push the file to GitHub**:

   ```sh
   git push origin main
   ```

   If your branch is named `master` instead of `main`, use:

   ```sh
   git push origin master
   ```

---

## **5. Verify the Changes on GitHub**

1. Go to your repository on GitHub.
2. Refresh the page and check if the `first-file.txt` appears.
3. 🎉 **Congratulations! You've successfully pushed your first file to GitHub.**

---
