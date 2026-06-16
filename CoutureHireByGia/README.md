# Couture Hire by Gia

A starter static website for **Couture Hire by Gia** — a designer dress and
accessory hire business.

## Structure

```
CoutureHireByGia/
├── index.html   # Single-page site (hero, collection, how it works, about, contact)
├── style.css    # Elegant warm/blush theme
└── README.md
```

## Sections

- **Hero** — brand intro and primary calls to action
- **Collection** — categories of pieces available for hire
- **How It Works** — browse, book, wear, return
- **About** — the brand story
- **Contact** — a hire enquiry form (wired for Netlify Forms)

## Running locally

It's a static site — just open `index.html` in a browser, or serve the folder:

```bash
cd CoutureHireByGia
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

The contact form uses [Netlify Forms](https://docs.netlify.com/forms/setup/)
(`data-netlify="true"`). Deploy the folder to Netlify and enquiries will appear
in the Forms section of the site dashboard.
