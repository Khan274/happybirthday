# Happy Birthday - Cinematic Web Experience 🎉

A romantic, dreamy, cinematic one-page birthday experience designed to make someone feel truly special. Built as a single self-contained HTML file with smooth animations, thoughtful transitions, and heartfelt messaging.

## Features

- **Mobile-first responsive design** - Optimized for 9:16 portrait (mobile) and scales beautifully to desktop
- **Single-file architecture** - Everything contained in one HTML file for easy sharing
- **Cinematic auto-animations** - Story unfolds automatically after the first click
- **Typed text effects** - Romantic messages appear letter-by-letter
- **Ambient audio** - Subtle background tones that start after user interaction
- **Accessibility** - ARIA labels, keyboard navigation, and reduced-motion support
- **Customizable** - Easy configuration for names, ages, and surprise links

## Live Demo

Simply open `index.html` in any modern web browser. No build process or dependencies required!

## Customization

Open `index.html` and find the `CONFIG` object at the top of the `<script>` section (around line 437):

```javascript
const CONFIG = {
    RECIPIENT_NAME: "Beautiful Soul",      // Change to recipient's name
    RECIPIENT_AGE: 25,                      // Update their age
    SURPRISE_URL: "https://...",            // Link for final surprise button
    SCENE_TIMINGS: {                        // Adjust timing between scenes (ms)
        scene1: 4000,
        scene2: 6000,
        scene3: 5000,
        scene4: 6000,
        scene5: 8000,
        scene6: 5000,
    },
    TYPING_SPEED: 80,                       // Speed of typing animation (ms per character)
    USE_AUDIO: true                         // Enable/disable ambient audio
};
```

### Customizing the Message

To personalize the letter content, find the `letter-body` section (around line 395):

```html
<div class="letter-body" id="letter-content">
    <p>Your personal message here...</p>
    <p>Add more paragraphs as needed...</p>
</div>
```

## Scene Flow

The experience follows this cinematic sequence:

1. **Scene 0** - Welcome screen with "Click to Begin" button
2. **Scene 1** - Personalized greeting with typing animation
3. **Scene 2** - Age countdown with glowing numbers
4. **Scene 3** - Polaroid-style memory card
5. **Scene 4** - Custom poetry with staggered fade-in
6. **Scene 5** - Personal letter on textured paper
7. **Scene 6** - Heartfelt confession with typing effect
8. **Scene 7** - Final birthday message with surprise link

## Technical Details

- **Zero dependencies** - Pure HTML, CSS, and vanilla JavaScript
- **Progressive enhancement** - Graceful degradation for no-JS scenarios
- **Browser compatibility** - Modern browsers (Chrome, Firefox, Safari, Edge)
- **Performance** - Optimized for 60fps animations on mobile
- **File size** - ~13KB uncompressed, works offline

## Accessibility Features

- Semantic HTML with proper ARIA labels
- Keyboard navigation support (Tab, Enter, Space)
- `prefers-reduced-motion` media query support
- High contrast ratios for text readability
- Screen reader friendly structure

## Deployment

### Option 1: Direct File Sharing
Simply send the `index.html` file - it works standalone!

### Option 2: GitHub Pages
1. Upload to a GitHub repository
2. Enable GitHub Pages in Settings
3. Share the live URL

### Option 3: Any Web Host
Upload `index.html` to any static hosting service (Netlify, Vercel, etc.)

## Browser Support

- Chrome/Edge: 90+
- Firefox: 88+
- Safari: 14+
- Mobile browsers: iOS Safari 14+, Chrome Android 90+

## Design Inspiration

This experience draws inspiration from:
- Cinematic film opening sequences
- Handwritten love letters
- Premium greeting card design
- Modern micro-interaction patterns

## Color Palette

- **Dreamy Pink**: #FFB6C1
- **Soft Purple**: #E6E6FA
- **Rose Gold**: #B76E79
- **Deep Black**: #1a1a1a
- **Cream**: #FFF5EE
- **Gold Shimmer**: #FFD700

## License

Free to use and customize for personal, non-commercial birthday wishes. Attribution appreciated but not required.

## Credits

Created with care for those special moments when you want to make someone smile.

---

Made with 💕 for unforgettable birthdays