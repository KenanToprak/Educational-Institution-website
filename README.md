# Educational Institution Website

A responsive static Turkish website template for an educational institution / university entrance exam (YKS) prep center, built with plain HTML5, CSS3, and lightweight vanilla JavaScript.

## Pages & Structure

- `index.html`: Home page with hero banner, upcoming events, success story quote, animated statistics counters, strategy cards, and contact form.
- `akademik.html`: Academic programs overview (9th–12th grade & graduate YKS tracks) and institutional resources.
- `hakkimizda.html`: About page covering mission/vision, institutional strengths (Font Awesome icons), teaching staff, and gallery.
- `detayli_bilgi.html`: Contact & inquiry page with address/hours, embedded Eskişehir map, and callback request form.
- `style.css`: Shared responsive stylesheet (`992px` tablet and `768px` mobile breakpoints, reduced-motion support).
- Image assets: `mainbackground.jpg`, `mezunlar.jpg`, `info.jpg`, `derslik.jpg`, `photoexample1.jpg`, `photoexample2.png`, and `handsup.jpeg` (currently unused backup asset kept in repository).

## Local Preview

Serve the repository over HTTP using Python's built-in server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/index.html` in a browser.

## Notes

- **Static Forms**: Contact and callback forms on `index.html` and `detayli_bilgi.html` handle submissions client-side with an inline confirmation message; connect a backend endpoint or form service before deploying for real data capture.
- **External Assets**: Google Fonts, Font Awesome 6.4.0 CDN, Google Maps embed, and `placehold.co` sample images on `akademik.html` / `hakkimizda.html` require internet access (and placeholder images can be swapped with local photography).
