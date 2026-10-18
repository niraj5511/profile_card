# Profile Card

A simple, responsive profile card with an initials avatar, role, short bio, skill tags, and two action buttons. Built with plain HTML and CSS. No frameworks, no JavaScript, no build step.


## Features

- Centered card with a gradient initials avatar
- Name, role, and bio sections
- Skill tags shown as rounded pills
- "Follow" (filled) and "Message" (outlined) buttons
- Hover effects: the card lifts and the buttons change color
- Automatic dark mode through `prefers-color-scheme`
- Responsive layout: on screens 400px wide or smaller, the card widens to 90% and the buttons stack vertically

## Tech Stack

- HTML5
- CSS3 (flexbox, grid, gradients, transitions, media queries)

## Project Structure

```
profile_card/
├── index.html   # Card markup
└── style.css    # Layout, theme, hover effects, dark mode, responsive rules
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/niraj5511/profile_card.git
   cd profile_card
   ```
2. Open `index.html` in your browser.

No installation or build is needed.

## Customization

- **Your details:** edit the initials, name, role, bio, and skill list in `index.html`.
- **Links:** replace the `href="#"` on the "Follow" and "Message" buttons with real URLs (for example a profile link or a `mailto:` address).
- **Colors:** the accent color is `#6366f1` (with `#4f46e5` on hover) in `style.css`. Replace these values to change the theme.

## Known Limitations

- The "Follow" and "Message" buttons are placeholders (`href="#"`) and do nothing yet.
- The name, role, and bio are sample content.
- The avatar shows initials only, not an image.
