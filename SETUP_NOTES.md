# Setup Instructions for AI Edits Website

This document provides additional guidance for setting up and running the AI Edits website.

## Getting Started

1. Install dependencies:
   ```
   npm install
   ```

2. Start the development server:
   ```
   npm start
   ```

## Font Setup for 3D Text

The 3D text component requires a font file in JSON format. To set this up:

1. Download the Inter Bold font from Google Fonts: https://fonts.google.com/specimen/Inter
2. Go to https://gero3.github.io/facetype.js/ to convert the font
3. Upload the `.ttf` or `.otf` file 
4. Download the JSON file
5. Rename it to `Inter_Bold.json`
6. Place it in the `public/fonts/` directory

Without this file, the site will automatically fall back to a standard text component, but the 3D effect will be missing.

## Troubleshooting

- If you see errors about missing Three.js components, make sure all dependencies are properly installed
- If the 3D scene is slow, try reducing the complexity in the Scene3D.tsx file
- For deployment, follow standard React build procedures as outlined in the main README

## Additional Resources

- Three.js Documentation: https://threejs.org/docs/
- React Three Fiber Documentation: https://docs.pmnd.rs/react-three-fiber/
- Framer Motion Documentation: https://www.framer.com/motion/ 