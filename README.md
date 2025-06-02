# Personal Academic Website - Inderjeet Singh

This is my personal academic website built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme, customized for academic use.


## Structure

```
.
├── content/          # All website content
│   ├── about/       # About page
│   ├── publications/# Research publications
│   ├── research/    # Research areas and interests
│   ├── projects/    # Research projects
│   ├── teaching/    # Teaching experience
│   └── news/        # News and updates
├── static/          # Static files (images, PDFs)
├── themes/          # Hugo themes (PaperMod)
└── hugo.toml        # Site configuration
```

## Local Development

1. Install Hugo (v0.147.7 or later):
   ```bash
   brew install hugo
   ```

2. Clone the repository:
   ```bash
   git clone --recurse-submodules https://github.com/intherejeet/intherejeet.github.io.git
   cd intherejeet.github.io
   ```

3. Run the development server:
   ```bash
   hugo server -D
   ```

4. View the site at `http://localhost:1313`

## Deployment

The site is automatically built and deployed to GitHub Pages using GitHub Actions when changes are pushed to the `main` branch.

## Customization

- **Site Configuration**: Edit `hugo.toml` for site-wide settings
- **Custom CSS**: Add styles to `assets/css/extended/custom.css`
- **Content**: Add/edit markdown files in the `content/` directory
- **Images**: Place images in `static/images/`

## Adding Content

### New Publication
```bash
hugo new publications/year-paper-title.md
```

### News Post
```bash
hugo new news/date-title.md
```

## License

The content of this website is © Inderjeet Singh. The underlying theme is MIT licensed.

## Acknowledgments

- Built with [Hugo](https://gohugo.io/)
- Theme: [PaperMod](https://github.com/adityatelange/hugo-PaperMod) by Aditya Telange
