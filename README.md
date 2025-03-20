# Identity-Aware AI 2025 Workshop Website

This repository contains the website for the Identity-Aware AI 2025 Workshop, to be held in conjunction with ECAI 2025.

## Website Structure

This is a Jekyll-based website hosted on GitHub Pages. The main components are:

- `_config.yml`: Main configuration file for the website
- `index.md`: Homepage content
- `*.md` files: Content pages (CFP, organization, etc.)
- `_layouts/`: Contains the HTML templates
- `_includes/`: Contains reusable HTML components
- `css/`: Contains stylesheets
- `images/`: Contains images and logos

## How to Update the Website

### Local Development

1. **Install Jekyll and dependencies**:
   ```bash
   # Install Ruby (if not already installed)
   sudo apt-get install ruby-full build-essential zlib1g-dev

   # Install Jekyll and Bundler
   gem install jekyll bundler

   # Install dependencies
   bundle install
   ```

2. **Run the website locally**:
   ```bash
   bundle exec jekyll serve
   ```
   This will start a local server at `http://localhost:4000` where you can preview your changes.

### Making Content Changes

1. **Edit Markdown files**: Most content is in Markdown files (`.md`). Edit these files to update the content.
   - `index.md`: Main page
   - `cfp.md`: Call for Papers
   - `organization.md`: Organizers information
   - `accepted.md`: Accepted papers (to be updated after notifications)
   - `faq.md`: Frequently Asked Questions
   - `travel_grant.md`: Travel grant information
   - `sponsors.md`: Sponsors information
   - `author.md`: Author guidelines

2. **Update dates**: Important dates are defined in `_layouts/default.html`. Update the following variables:
   ```liquid
   {% capture sub %}{{'Aug 29 2025' | date: '%s'}}{% endcapture %}
   {% capture not %}{{'Sep 26 2025' | date: '%s'}}{% endcapture %}
   {% capture cam %}{{'Oct 5 2025' | date: '%s'}}{% endcapture %}
   {% capture workshop %}{{'Oct 25 2025' | date: '%s'}}{% endcapture %}
   ```

3. **Update navigation**: The navigation menu is in `_includes/page-header.html`. Add or remove links as needed.

4. **Update configuration**: Site-wide settings are in `_config.yml`. Update the title, description, and other settings as needed.

### Adding Images

1. Place image files in the `images/` directory
2. Reference them in Markdown files using:
   ```markdown
   ![Alt text](/images/image-name.jpg)
   ```
   or in HTML:
   ```html
   <img src="{{ site.baseurl }}/images/image-name.jpg" alt="Alt text" width="300"/>
   ```

## Deployment

This website is automatically deployed using GitHub Pages:

1. **Commit and push changes**:
   ```bash
   git add .
   git commit -m "Update website content"
   git push origin main
   ```

2. **GitHub Actions** will automatically build and deploy the website to GitHub Pages.

3. **Check deployment status** in the "Actions" tab of the GitHub repository.

4. **View the live website** at `https://identity-aware-ai.github.io/`

## Adding New Pages

1. Create a new Markdown file in the root directory with the following front matter:
   ```markdown
   ---
   layout: page
   title: "Page Title"
   permalink: /page-url
   order: 1
   ---

   # Page Title
   Content goes here...
   ```

2. Add a link to the new page in `_includes/page-header.html`:
   ```html
   <a href="/page-url" class="btn">Page Title</a>
   ```

## Troubleshooting

- If the website doesn't build correctly, check the GitHub Actions logs for errors.
- For local development issues, check the Jekyll server output for error messages.
- Make sure all Markdown files have the correct front matter (the YAML section at the top).
