# PLP Basic Git Assignment

## Basic Git and GitHub Workflow

#### Introduction
- Git is a distributed version control system that allows developers to collaborate on projects efficiently. 
- GitHub is a platform that hosts Git repositories and facilitates collaboration among developers. 

#### Use of Personal Access Token (PAT)
- PAT are used as an alternative to passwords when authenticating with GitHub via the command line or third-party applications. 
- They provide a secure way to access GitHub repositories without using your account password. 
- Below is how to create and use a PAT:

1. **Creating a PAT key**:
   - Go to your GitHub account settings.
   - Navigate to the "Developer settings" section.
   - Click on "Personal access tokens" and then "Generate new token".
   - Select the scopes (permissions) required for your token.
   - Click "Generate token" and make sure to copy it. 
**Note: Treat your tokens like passwords and keep them secret.**

1. **Using the PAT**:
   - When prompted for a password during Git operations, use your GitHub username and the PAT as the password.
   - For example, if your username is `username` and your PAT is `your-token`, you would use:
     ```
     Username: username
     Password: your-token
     ```

#### Creating a Repository
1. **Initialize a Repository**: Create a new directory for your project and initialize a Git repository:
2. **Add Files**: Add files to the repository:
3. **Commit Changes**: Commit the added files with a descriptive message:

#### Working with Branches
1. **Create a Branch**: Create a new branch for your feature or bug fix:
2. **Make Changes**: Make changes to your files.
3. **Stage and Commit**: Stage and commit your changes:
4. **Merge Changes**: Merge your changes back to the main branch:
5. 
#### Collaborating on GitHub
1. **Push Changes**: Push your commits to GitHub:
2. **Pull Changes**: Pull changes from GitHub to sync your local repository:
