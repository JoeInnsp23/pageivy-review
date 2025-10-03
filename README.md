# Page Ivy Theme Review

Website theme comparison for Page Ivy Accountants & Business Advisors.

## 🎨 Themes Included

1. **AstroWind** - Blog & content focused theme
2. **Foxi** - Modern agency design
3. **Sassify** - SaaS landing page
4. **CodeStitch** - Accounting services focused

## 🚀 Deployment

This repository is deployed using Coolify with Docker & Nginx.

### Docker Build

```bash
docker build -t pageivy-review .
docker run -p 80:80 pageivy-review
```

### Live URL

- **Main Navigation**: `https://review.pageivy.com/`
- **AstroWind**: `https://review.pageivy.com/astrowind/`
- **Foxi**: `https://review.pageivy.com/foxi/`
- **Sassify**: `https://review.pageivy.com/sassify/`
- **CodeStitch**: `https://review.pageivy.com/codestitch/`

## 📁 Structure

```
pageivy-review/
├── Dockerfile              # Nginx container
├── nginx.conf              # Nginx routing config
├── public/
│   ├── index.html         # Main navigation page
│   ├── astrowind/         # Built AstroWind theme
│   ├── foxi/              # Built Foxi theme
│   ├── sassify/           # Built Sassify theme
│   └── codestitch/        # Built CodeStitch theme
└── README.md
```

## 🛠️ Tech Stack

- **Docker** - Containerization
- **Nginx** - Web server
- **Astro** - Static site generator (for all themes)
- **Coolify** - Self-hosted deployment platform

## 📝 Notes

- All themes built with `base` path configured for subdirectories
- Nginx serves each theme from its subdirectory
- SSL handled automatically by Coolify
- Optimized with gzip compression and caching headers

---

**Page Ivy** | Accountants & Business Advisors for the Creator Economy
