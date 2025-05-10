# Deploying to GitHub Pages

Follow these steps to deploy the Mayuge Light Secondary School website to GitHub Pages:

## Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in to your account
2. Click on the "+" icon in the top-right corner and select "New repository"
3. Name your repository (e.g., `mayuge-light-ss` or `school-website`)
4. Add a description (optional): "Official website for Mayuge Light Secondary School"
5. Select "Public" visibility
6. Click "Create repository"

## Step 2: Upload Your Website Files

### Option 1: Using Git (Recommended)

If you have Git installed on your computer:

1. Open a terminal or command prompt
2. Navigate to your website directory containing all the HTML, CSS, and other files
3. Initialize a Git repository:
   ```
   git init
   ```
4. Add all files to the repository:
   ```
   git add .
   ```
5. Commit the files:
   ```
   git commit -m "Initial website upload"
   ```
6. Link your local repository to GitHub:
   ```
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
   ```
   (Replace YOUR-USERNAME and YOUR-REPOSITORY-NAME with your actual GitHub username and repository name)
7. Push your files to GitHub:
   ```
   git push -u origin main
   ```
   (If you're using an older version of Git, you might need to use `master` instead of `main`)

### Option 2: Using GitHub Web Interface

1. In your repository, click on "uploading an existing file" link
2. Drag and drop all your website files or click "choose your files" to select them
3. Add a commit message like "Initial website upload"
4. Click "Commit changes"

## Step 3: Configure GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to the "GitHub Pages" section
4. In the "Source" dropdown, select "main" branch (or "master" if that's what you used)
5. Click "Save"
6. Wait a few minutes for GitHub to build your site

## Step 4: Access Your Website

After GitHub finishes building your site, you'll see a message that says:
"Your site is published at https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/"

Click on the link to view your published website!

## Making Updates

Whenever you want to update your website:

1. Make changes to your local files
2. Commit and push the changes to GitHub:
   ```
   git add .
   git commit -m "Description of changes"
   git push
   ```
3. GitHub will automatically rebuild your site with the changes

## Custom Domain (Optional)

If you have a custom domain (e.g., mayugelightss.ac.ug):

1. Go to your repository "Settings"
2. Scroll to "GitHub Pages" section
3. Under "Custom domain", enter your domain name
4. Click "Save"
5. Follow GitHub's instructions to configure your DNS settings

## Need Help?

If you need assistance with the deployment process, please refer to the [official GitHub Pages documentation](https://docs.github.com/en/pages).