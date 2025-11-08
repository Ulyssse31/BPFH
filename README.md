# BPFH - Better Places For Humans

A GitHub Pages website for sharing projects and blog posts about creating better places for humans.

## Features

- 📝 **Blog Posts**: Share articles and insights
- 🚀 **Projects**: Showcase your work and initiatives
- 🎨 **Responsive Design**: Works on all devices
- 🔧 **Easy to Customize**: Built with Jekyll

## Local Development

To run this site locally:

1. Install Ruby and Bundler (if not already installed)
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Run the local server:
   ```bash
   bundle exec jekyll serve
   ```
4. Visit `http://localhost:4000` in your browser

## Adding Content

### Creating a New Blog Post

1. Create a new file in `_posts/` with the format: `YYYY-MM-DD-title.md`
2. Add front matter:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD HH:MM:SS -0000
   ---
   ```
3. Write your content using Markdown

### Creating a New Project

1. Create a new file in `_projects/` with a descriptive name: `project-name.md`
2. Add front matter:
   ```yaml
   ---
   layout: project
   title: "Project Name"
   description: "Brief description"
   technologies: ["Tech1", "Tech2"]
   github: "https://github.com/user/repo"  # optional
   demo: "https://demo-url.com"  # optional
   ---
   ```
3. Write your project details using Markdown

## GitHub Pages Deployment

This site is configured to work with GitHub Pages automatically:

1. Go to your repository Settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select the branch you want to deploy (e.g., `main` or `copilot/set-up-github-pages-repo`)
4. Click Save
5. Your site will be published at `https://[username].github.io/[repository-name]/`

## Customization

- **Site Settings**: Edit `_config.yml` to change site title, description, etc.
- **Styling**: Modify `assets/css/style.scss` to customize the appearance
- **Layouts**: Edit files in `_layouts/` to change page structure
- **Navigation**: Update the navigation in `_layouts/default.html`

## Structure

```
.
├── _config.yml          # Site configuration
├── _layouts/            # Page templates
│   ├── default.html     # Base layout
│   ├── home.html        # Home page layout
│   ├── page.html        # Standard page layout
│   ├── post.html        # Blog post layout
│   └── project.html     # Project layout
├── _posts/              # Blog posts
├── _projects/           # Project pages
├── assets/css/          # Stylesheets
├── index.md             # Home page
├── blog.md              # Blog listing page
└── projects.md          # Projects listing page
```

## License

Feel free to use this template for your own GitHub Pages site!
