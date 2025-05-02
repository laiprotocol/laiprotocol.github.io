# LAI Protocol Website

This repository contains the source code for the LAI Protocol Foundation website, hosted at [laiprotocol.org](https://laiprotocol.org).

## Technology Stack

- **Jekyll**: Static site generator
- **Hyde**: Jekyll theme
- **GitHub Pages**: Hosting platform

## Local Development

### Prerequisites

- Ruby (version 2.5.0 or higher)
- RubyGems
- Bundler

### Setup

1. Clone this repository:
   ```
   git clone https://github.com/laiprotocol/laiprotocol.github.io.git
   cd laiprotocol.github.io
   ```

2. Install dependencies:
   ```
   bundle install
   ```

3. Run the site locally:
   ```
   bundle exec jekyll serve
   ```

4. Open your browser and navigate to `http://localhost:4000`

### Adding Content

#### Blog Posts

Create new blog posts by adding Markdown files to the `_posts` directory. The filename should follow the format: `YYYY-MM-DD-title.md`. For example:

```
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS -0000
categories: category-name
---

Your content here...
```

#### Pages

Add new pages by creating Markdown files in the root directory. Include front matter at the top:

```
---
layout: page
title: "Page Title"
permalink: /page-url/
---

Your content here...
```

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the main branch. No additional steps are required for deployment.

## Custom Domain

The site is configured to use the custom domain [laiprotocol.org](https://laiprotocol.org). The DNS settings are managed separately.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.