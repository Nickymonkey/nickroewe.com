# nickroewe.com

Personal website built with Jekyll and hosted on GitHub Pages at [nickroewe.com](https://nickroewe.com).

## Project Structure

```
nickroewe.com/
├── _config.yml          # Jekyll configuration
├── _layouts/            # HTML layouts
│   ├── home.html        # Homepage layout
│   └── resume.html       # Experience page layout
├── _includes/            # Reusable components
│   └── header.html      # Site header/navigation
├── assets/               # Static assets
│   ├── css/             # Stylesheets
│   │   ├── home.css     # Homepage styles
│   │   └── resume.css   # Experience page styles
│   └── images/          # Images (profile, projects, etc.)
├── index.md             # Homepage content
├── experience.md        # Experience page content
├── Gemfile              # Ruby dependencies
└── README.md
```

## Local Development

```bash
bundle install
bundle exec jekyll build
bundle exec jekyll serve
```

Site will be available at `http://localhost:4000`.
