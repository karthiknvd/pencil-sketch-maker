# Pencil Sketch Converter

A sleek, futuristic, single-file web application that instantly transforms any uploaded image into a realistic pencil sketch using pure HTML5 Canvas and CSS filters—no frameworks, no backend, no external libraries.


## Features

- **Instant Pencil Sketch Effect**: Utilises advanced Canvas compositing (`color-dodge`) with grayscale conversion, inversion, and Gaussian blur to create authentic dark pencil lines on a light paper-like background.
- **Futuristic Cyberpunk UI**: Glassmorphism cards, neon glows, animated gradients, hover effects, and sci-fi typography powered purely by CSS.
- **Fully Client-Side**: Everything runs in the browser—zero server processing, no data upload, complete privacy.
- **Responsive Design**: Optimised for both desktop and mobile devices.
- **One-Click Download**: Save the generated sketch as a high-quality PNG.
- **Clean File Upload**: Custom neon-styled button with no visible default browser file input elements.
- **Favicon Support**: Neon pencil icon displayed in browser tabs.

## Live Demo

Visit the deployed application:  
https://pencil-sketch-converter.vercel.app

## How It Works

1. Click **"Choose Image"** and upload any photo (JPG, PNG, etc.).
2. The app automatically resizes the image (max width 800px) for optimal performance.
3. The pencil sketch is generated instantly using:
   - Grayscale base layer
   - Inverted + blurred overlay with `color-dodge` blending
   - Light paper background
4. Compare side-by-side with the original.
5. Download the sketch or reset to start over.

## Technology Stack

- HTML5 Canvas for image processing
- CSS3 (glassmorphism, gradients, animations, backdrop-filter)
- Vanilla JavaScript (no frameworks)
- Single `pencil.html` file – fully self-contained

## Deployment

Deployed on Vercel as a static site:  
https://pencil-sketch-converter.vercel.app

To deploy your own copy:
1. Fork or clone this repository
2. Push to GitHub
3. Import into Vercel (auto-detects static site)
4. Live in seconds!

Alternatively, simply open `pencil.html` in any modern browser—no server required.

## Browser Support

Works on all modern browsers supporting:
- HTML5 Canvas
- CSS `backdrop-filter`
- CSS Filters (`blur`, `grayscale`, `invert`)

Recommended: Chrome, Firefox, Edge, Safari (latest versions)

## Credits

- Built with pure passion for client-side web artistry
- Pencil sketch algorithm inspired by classic Photoshop techniques
- Futuristic UI design crafted for immersive visual experience

---

**Transform your photos into art — instantly, privately, beautifully.**

⭐ Star this repo if you like it!  
Feel free to contribute or suggest improvements.
