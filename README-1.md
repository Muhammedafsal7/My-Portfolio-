# Muhammed Afsal A — Portfolio Website

A single-page personal portfolio built with plain HTML and CSS — no frameworks, no build step. Just open `index.html` in a browser.

## About

This site introduces Muhammed Afsal A, a B.Tech Computer Science & Engineering student at **JCET (Jawaharlal College of Engineering & Technology), Lakkidi, Ottapalam**, currently in Semester 3. It highlights his interests in Artificial Intelligence, Programming, Web Development, and Cybersecurity.

## Sections

| Section | Description |
|---|---|
| **Hero** | Name, tagline, profile photo, and quick links to LinkedIn and Projects |
| **About** | A short personal introduction |
| **Skills** | Interests and skills grouped into Core Interests, Building & Developing, Security & Systems, and Currently Learning |
| **Projects** | Project showcase cards (currently placeholders — ready to fill in with real project details) |
| **Education** | Academic background, including the college name |
| **Certifications** | Achievements, courses, and competitions (currently placeholders) |
| **Contact** | LinkedIn link and a call-to-action card |

## Tech Details

- **Format:** Single self-contained `index.html` file
- **Fonts:** Poppins (headings) and Inter (body text), loaded from Google Fonts
- **Styling:** Custom CSS — gradient blobs, pill badges, rounded cards, hover animations
- **Photo:** Embedded directly in the HTML as a base64 image, so the file works standalone with no extra assets to manage
- **Responsive:** Adapts down to mobile screen sizes
- **Accessibility:** Visible keyboard focus states; animations respect `prefers-reduced-motion`

## How to Use

1. Open `index.html` in any web browser to preview it.
2. To publish it online, upload `index.html` to any static hosting service (GitHub Pages, Netlify, Vercel, etc.) — no extra setup required since the photo is embedded.
3. To edit content, open `index.html` in a text editor and update the text inside the relevant `<section>` blocks:
   - **Projects:** replace the placeholder titles/descriptions in the `id="projects"` section
   - **Certifications:** replace the placeholder cards in the `id="certifications"` section
   - **Contact:** update the LinkedIn link or add more contact methods in the `id="contact"` section

## Customization Tips

- **Colors:** All accent colors (indigo, coral, teal, yellow, pink) are defined once at the top of the CSS in the `:root` block — change them there to re-theme the whole site.
- **Fonts:** Swap the Google Fonts `<link>` and the `font-family` values in the CSS to use different typefaces.
- **Photo:** To use a new photo, replace the base64 string in the `<img src="data:image/jpeg;base64,...">` tag in the hero section.

---

© 2026 Muhammed Afsal A — JCET, Lakkidi, Ottapalam
