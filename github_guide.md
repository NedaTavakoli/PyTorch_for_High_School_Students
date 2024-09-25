
# GitHub Guide for High School Students

This guide will help you get started with using GitHub to work on existing projects and create your own repositories.

## 1. Working on Existing Repositories

If you want to contribute to an existing project on GitHub, you can follow these steps:

### Cloning a Repository
Cloning a repository means downloading a copy of a project from GitHub to your local machine. Here’s how:

1. Open a terminal (or command prompt) on your computer.
2. Run the following command to clone the repository:
   ```bash
   git clone https://github.com/username/repository-name.git
   ```
3. This will download the project to your computer. You can now work on the project locally.

### Making Changes and Pushing to GitHub
After making changes to the project, you can save and upload them back to GitHub by following these steps:

1. **Add the changes**: Add the changes you made to be committed:
   ```bash
   git add .
   ```
2. **Commit the changes**: Commit the changes with a message describing what you did:
   ```bash
   git commit -m "Your descriptive message"
   ```
3. **Push the changes**: Push the changes to GitHub:
   ```bash
   git push
   ```

## 2. Creating Your Own Repository on GitHub

You can create your own project (called a repository) on GitHub by following these steps:

### Creating a New Repository

1. Go to [GitHub](https://github.com), log in, and click the green **New** button on the left sidebar.
2. Choose a name for your repository and select "Public" so that others can see it.
3. You can initialize the repository with a **README** file, which is used to describe your project.
4. Click **Create repository** to finish.

### Uploading Files to Your Repository

Once your repository is created, you can upload files from your local machine:

1. On the GitHub page for your repository, click the **Add file** button and select **Upload files**.
2. Drag and drop the files from your computer, or select them manually.
3. Once the files are uploaded, click **Commit changes**.

### Pushing Changes to Your Repository

After creating your repository, you can clone it to your local machine using:
```bash
git clone https://github.com/your-username/your-repository.git
```

Then follow the same steps as above to make changes, commit them, and push them back to GitHub.

## Additional Resources

- [GitHub Docs](https://docs.github.com/en): Learn more about GitHub’s features and tools.
- [Markdown Guide](https://www.markdownguide.org/): Learn how to write documentation and README files using Markdown.
