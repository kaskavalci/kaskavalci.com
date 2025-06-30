# Simple Landing Page Jekyll Theme

A clean, modern, and easy-to-use landing page theme for Jekyll. Perfect for portfolios, resumes, and personal sites.

## Features
- Responsive, modern design
- Easy configuration via `_config.yml`
- Portfolio section
- Social/profile links
- Customizable with your own content and styles

## Getting Started

1. **Clone or fork this repository**
2. **Install Jekyll** (see [Jekyll docs](https://jekyllrb.com/docs/installation/))
3. **Edit `_config.yml`** with your own info (name, email, social links, portfolio, etc.)
4. **Add your profile photo** to `assets/profile-photo.jpg`
5. **Run locally:**
   ```
   bundle install
   bundle exec jekyll serve
   ```
6. **Visit** `http://localhost:4000` to see your site!

## Configuration
Edit `_config.yml` to set your:
- Name, tagline, description
- Social links (GitHub, LinkedIn, Twitter, Blog, Resume)
- Portfolio projects (title, description, image, links)

## Customization
- **Profile photo:** Replace `assets/profile-photo.jpg`
- **Portfolio images:** Add images to `assets/` and update `image_url`
- **Colors & styles:** Edit `assets/css/theme.css`

## Using as a Remote Theme
You can use this as a remote theme by adding to your `_config.yml`:
```yml
remote_theme: your-github/landingpage-theme
```

## License
MIT. Have fun and make it your own!
