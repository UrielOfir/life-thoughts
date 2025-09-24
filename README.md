# Life Thoughts

A public journal containing my personal thoughts and lessons learned about life, well-being, and personal growth.

## About This Site

This is a Jekyll-powered blog hosted on GitHub Pages. It serves as a personal space to document reflections, insights, and lessons learned throughout my journey of self-discovery and growth.

## Local Development

To run this site locally:

1. **Install Ruby** (version 3.0 or higher)
2. **Install dependencies**:
   ```bash
   bundle install
   ```
3. **Run the development server**:
   ```bash
   bundle exec jekyll serve
   ```
4. **View the site** at `http://localhost:4000`

## Adding New Posts

To create a new blog post:

1. Create a new file in the `_posts` directory
2. Use the naming convention: `YYYY-MM-DD-post-title.md`
3. Include front matter at the top:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD HH:MM:SS +0000
   categories: [category1, category2]
   ---
   ```
4. Write your content in Markdown below the front matter

## GitHub Pages Deployment

This site is configured to automatically deploy to GitHub Pages when changes are pushed to the main branch. The deployment is handled by GitHub Actions using the workflow in `.github/workflows/pages.yml`.

### Manual Setup for GitHub Pages

If you prefer to use GitHub's built-in Jekyll processing instead of GitHub Actions:

1. Go to your repository's Settings
2. Navigate to "Pages" in the sidebar
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"

Your site will be available at: `https://[username].github.io/[repository-name]`

## File Structure

```
├── _config.yml          # Jekyll configuration
├── _layouts/            # HTML templates
│   ├── default.html     # Main site layout
│   └── post.html        # Blog post layout
├── _posts/              # Blog posts
├── _site/               # Generated site (ignored by git)
├── .github/workflows/   # GitHub Actions workflows
├── about.md             # About page
├── index.html           # Homepage
├── Gemfile              # Ruby dependencies
└── .gitignore          # Git ignore rules
```

## Customization

- **Site title and description**: Edit `_config.yml`
- **Styling**: Modify the CSS in `_layouts/default.html`
- **Navigation**: Update the nav section in `_layouts/default.html`
- **Content**: Add new pages as `.md` or `.html` files in the root directory

## License

This project is open source and available under the [MIT License](LICENSE).
