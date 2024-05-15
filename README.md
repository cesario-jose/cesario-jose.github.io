# Jose Cesario Pinto Personal Website

Welcome to the repository for my personal website. This site is built with Jekyll and hosted with GitHub Pages.

## Structure

- `_config.yml`: Contains configuration settings for the Jekyll site.
- `index.md`: The homepage of the website.
- `_layouts`: Directory containing layout templates.
- `_posts`: Directory for blog posts or updates.
- `assets`: Contains static files like images and stylesheets.

## Setup

To run this website locally, you'll need to install Ruby and Jekyll. After that, you can clone this repository and run the following commands:

```bash
gem install jekyll bundler
bundle exec jekyll serve


### Setting Up Your Website with Jekyll

1. **Install Jekyll and Bundler:**
   - If you don't have Ruby installed, you'll need to install it first.
   - Install Jekyll and Bundler via the command line:
     ```bash
     gem install jekyll bundler
     ```

2. **Create Your Jekyll Site:**
   - Create a new Jekyll site at `./your-site-name`:
     ```bash
     jekyll new your-site-name
     ```
   - Navigate into your new directory:
     ```bash
     cd your-site-name
     ```

3. **Customize Your Site:**
   - Edit `_config.yml` to manage settings like your title, email, description, etc.
   - Create or update `index.md` for your homepage.
   - Add new posts in the `_posts` directory.
   - Customize the layout files in `_layouts` as needed.

4. **Build and Run Locally:**
   - Build the site and make it available on a local server:
     ```bash
     bundle exec jekyll serve
     ```
   - Browse to `http://localhost:4000`.

5. **Push to GitHub:**
   - Initialize a git repository if you haven't already:
     ```bash
     git init
     ```
   - Add and commit your changes.
   - Create a repository on GitHub and push your local repository.
   - Set up GitHub Pages in the repository settings to point to your main branch.

6. **Customize Further:**
   - You can add more pages, integrate other Jekyll themes, or even customize the CSS and JavaScript files in the `assets` directory.

This setup will create a simple but customizable personal website hosted on GitHub Pages. If you want more specific features or layouts, consider exploring Jekyll themes that match the style of the example you provided.
