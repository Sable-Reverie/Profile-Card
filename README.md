# Animated Profile Card Template ✨

A highly animated, single-file, open-source profile card. Perfect for developers looking to create a stunning and interactive landing page for their GitHub profile.

---

### Live Demo

**[View Live]** - (https://sableprofile.netlify.app/)

---

## Features

This isn't just a static card. It's packed with features to impress visitors:
- ✅ **Interactive 3D Tilt Effect:** The card tilts and reacts to the user's cursor.
- ✅ **Live Spotlight Glow:** A soft light follows the cursor across the card.
- ✅ **Constellation Particle Background:** A beautiful, animated "neural network" of particles flows in the background.
- ✅ **Chromatic Animated Border:** The card's border slowly cycles through a vibrant rainbow of colors.
- ✅ **Typing Animations:** Your name and tagline are typed out in a "hacker" style.
- ✅ **Revealable "About" Section:** A hidden section smoothly reveals more information at the click of a button.
- ✅ **Fully Responsive:** Looks great on both desktop and mobile devices.
- ✅ **Single File:** Everything is contained in one `index.html` file. No complex setup required!

---

## How to Customize 🛠️

All you need to do is edit the **`index.html`** file. Here are the specific lines to change to add your own information.

| What to Change | File | Line Number (Approx.) | Instructions |
| :--- | :--- | :--- | :--- |
| **Page Title** | `index.html` | 6 | Change the text inside the `<title>` tag to your name. |
| **Profile Picture** | `index.html` | 104 & 144 | Replace the placeholder URL in **both** the `.card-background` CSS rule and the `<img>` tag with a link to your profile picture. |
| **Your Name** | `index.html` | 147 | Change the text inside the `<h1>` tag to your full name. |
| **Name Animation** | `index.html` | 166 | In the `@keyframes typing-name` rule, change `width: 14ch;` to match the **exact number of characters** (including spaces) in your name. |
| **Your Tagline** | `index.html` | 297 | In the `<script>` section, change the text for the `aboutTextContent` variable to your desired tagline or short bio. The animation will adapt automatically. |
| **GitHub Link** | `index.html` | 154 | In the `<a>` tag inside the `.github-link-container`, replace the `#` with the full URL to your GitHub profile. |
