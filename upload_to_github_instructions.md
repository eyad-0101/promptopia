# How to Upload Your Project to GitHub

## Steps to Upload Your Project

1. **Create a New Repository on GitHub**:
   - Go to GitHub and create a new repository.

2. **Initialize Git in the Local Project**:
   - Open the terminal in your project directory and run:
     ```
     git init
     ```

3. **Add Remote Repository**:
   - Link your local repository to the GitHub repository using:
     ```
     git remote add origin <repository-url>
     ```

4. **Add Files to Staging**:
   - Use the following command to stage all files for commit:
     ```
     git add .
     ```

5. **Commit Changes**:
   - Commit the changes with a message:
     ```
     git commit -m "Initial commit"
     ```

6. **Push to GitHub**:
   - Push the changes to the GitHub repository:
     ```
     git push -u origin main
     ```

Follow these steps to successfully upload your project to GitHub.
