# Valentine Surprise 

A small Valentine-themed interactive surprise page built as a single-file web experience. The project opens with a floating card, animated hearts, a decorative tree scene, sound effects, and a playful yes/no interaction flow.

## Live Experience

The page is designed to:

- show a romantic animated landing scene
- reveal a surprise card after the intro animation
- flip the card open on tap/click
- play light sound effects using the Web Audio API
- celebrate a **Yes!** response with confetti and a success overlay
- redirect to a Google Form after the celebration

## Features

- Animated sky background with a glass-style transition
- Decorative SVG tree scene with heart-shaped leaves
- Falling heart particles across the screen
- 3D flipping Valentine card
- Playful **Yes** / **No** buttons
- Button evasive behavior on **No** for a fun interaction
- Confetti burst on success
- Gentle built-in audio cues
- Mobile responsive layout

## Tech Stack

This project uses only front-end web technologies:

- **HTML**
- **CSS**
- **JavaScript**
- **SVG** for the tree artwork
- **Web Audio API** for sound effects

## Project Structure

```text
index.html
README.md
```

The entire experience lives in `index.html`, including the styles and scripts.

## How It Works

1. The card falls into view after the page loads.
2. The background shifts into a soft glass effect.
3. Falling hearts begin animating on the screen.
4. Tapping the front of the card flips it open.
5. Choosing **Yes!** triggers confetti and a celebration overlay.
6. The user is then redirected to a Google Form.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/burnedglitchy/valentine-surprise.git
cd valentine-surprise
```

### 2. Open the page

Open `index.html` directly in your browser, or serve it with any static server.

For example, with VS Code Live Server or a simple local server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Customization

You can personalize the surprise by editing `index.html`:

- Change the opening message
- Replace the Valentine text on the back of the card
- Update the redirect link to your own Google Form
- Adjust colors, animation timing, or audio behavior
- Swap out the emoji and text to match your style

The redirect URL is defined near the top of the script:

```js
const googleFormURL = 'https://forms.gle/L7MS4ekVSDdCYscn6';
```

## Deployment

This project is ready for GitHub Pages or any static hosting service.

### GitHub Pages

1. Push the repository to GitHub.
2. Go to **Settings → Pages**.
3. Select the branch containing `index.html`.
4. Save and wait for the site to publish.

## Notes

- The page is optimized for a playful one-page experience.
- Audio starts only after user interaction, which matches browser autoplay rules.
- The **No** button is intentionally mischievous and moves around on hover/touch.

## License

No license has been added yet. Add one if you want others to reuse or modify the project.
