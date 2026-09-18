# 🎙️ Podzilla

**Podzilla** is a one-page website for a podcast run by a small group of friends — *"here to entertain and hear your opinions about anything."* It introduces the show, the topics it covers, and the team behind it.

🌐 **Live site:** [baboosh617.github.io/Podzilla](https://baboosh617.github.io/Podzilla/)

## Sections

- **Hero** — full-screen slider: *"Say hello to Podzilla"*
- **Who Are We** — the show's goal, mission, approach and process
- **Things We Talk About** — Movies, Gaming, Anime and Current Affairs, each with a pop-up description
- **Meet Our Team** — the hosts, with photos
- **Get In Touch With Us** — contact form for topic ideas, takes and questions

## Tech Stack

- HTML5 and CSS3
- jQuery 3.7 with plugins: FlexSlider (hero slider), Magnific Popup (pop-ups), Waypoints (nav highlighting), FitText and jQuery Validate
- Font Awesome icons, Merriweather and Raleway fonts
- [Web3Forms](https://web3forms.com) for the contact form (no server needed)

## Running Locally

It's a static site with no build step. Serve the folder with any static server:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Contact Form Setup

The contact form sends messages through [Web3Forms](https://web3forms.com), which works on GitHub Pages.

1. Go to [web3forms.com](https://web3forms.com), enter the email address that should receive messages, and copy the access key they send you.
2. In `js/main.js`, replace `YOUR_WEB3FORMS_ACCESS_KEY` with your key.

The access key is safe to publish, because it only allows sending messages *to* you. Until a key is set, the form shows a "not set up yet" message instead of failing silently.

## Project Structure

```
Podzilla/
├── index.html          # The whole one-page site
├── Pod-merch           # Placeholder page for future merch
├── css/                # Base, layout, vendor styles, Font Awesome
├── fonts/              # Merriweather and Raleway webfonts
├── js/                 # jQuery, plugins and main.js (incl. contact form)
└── images/             # Hero, topic and team photos
```

## Credits

Built on the **KREO** template by [StyleShout](http://www.styleshout.com/), released under the [Creative Commons Attribution 3.0 License](http://creativecommons.org/licenses/by/3.0/). See `readme.txt` for the full template licence. Photos from Unsplash and Pexels.
