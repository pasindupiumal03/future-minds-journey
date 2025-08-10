# Future Minds Journey

An educational resource website focused on early childhood development and learning.

## Deployment on Vercel

This project is configured for easy deployment on Vercel. Follow these steps to deploy:

1. **Sign up/Login to Vercel**
   - Go to [Vercel](https://vercel.com) and sign up or log in with your GitHub, GitLab, or Bitbucket account.

2. **Import Project**
   - Click on "New Project"
   - Import your GitHub/GitLab/Bitbucket repository or drag and drop the project folder

3. **Configure Project**
   - Vercel will automatically detect the configuration from `vercel.json`
   - No build command is needed as this is a static site
   - Output directory: `/` (root)

4. **Deploy**
   - Click "Deploy"
   - Your site will be live at `https://your-project-name.vercel.app`

## Development

To run locally:

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npx serve
   ```

3. Open your browser to `http://localhost:3000`

## Project Structure

- `/` - Root directory with all HTML files
- `/css` - All CSS stylesheets
- `/js` - JavaScript files
- `/images` - Image assets
