# 🎙️ Podzilla

**Podzilla** is a one-page website for a podcast run by a small group of friends — *"here to entertain and hear your opinions about anything."* It introduces the show, the topics it covers, and the team behind it.

🌐 **Live site:** [baboosh617.github.io/Podzilla](https://baboosh617.github.io/Podzilla/)

## Sections

- **Hero** — full-screen slider: *"Say hello to Podzilla"*
- **Who Are We** — the show's goal, mission, approach and process
- **Things We Talk About** — Anime, Gaming, Movies and Current Affairs
- **Portfolio** — image gallery with pop-up previews
- **Meet Our Team** — the hosts, with photos
- **Get In Touch With Us** — contact form and contact details

## Tech Stack

- HTML5 and CSS3
- jQuery with plugins: FlexSlider (sliders), Magnific Popup (lightbox), Waypoints (scroll animations), FitText and jQuery Validate
- Font Awesome icons, Merriweather and Raleway fonts
- PHP (`inc/sendEmail.php`) for the contact form

## Running Locally

It's a static site, so you can just open `index.html` in a browser. To test the contact form you need a PHP server:

```bash
php -S localhost:8000
```

Then visit <http://localhost:8000>.

> **Note:** GitHub Pages doesn't run PHP, so the contact form won't send email on the live site.

## Project Structure

```
Podzilla/
├── index.html          # The whole one-page site
├── Pod-merch           # Placeholder page for future merch
├── css/                # Base, layout, vendor styles, Font Awesome
├── fonts/              # Merriweather and Raleway webfonts
├── js/                 # jQuery, plugins and main.js
├── images/             # Hero, portfolio and team photos
└── inc/sendEmail.php   # Contact form handler
```

## Credits

Built on the **KREO** template by [StyleShout](http://www.styleshout.com/), released under the [Creative Commons Attribution 3.0 License](http://creativecommons.org/licenses/by/3.0/). See `readme.txt` for the full template licence. Photos from Unsplash and Pexels.
