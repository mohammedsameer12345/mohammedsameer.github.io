# AI Edits - Modern AI Editing Platform

A stunning 3D website showcasing an AI-powered editing platform with beautiful graphics and animations.

## Features

- Interactive 3D background with Three.js
- Smooth animations with Framer Motion
- Responsive design for all devices
- Modern UI with gradients and glass morphism effects
- React + TypeScript for robust development

## Prerequisites

- Node.js (14.0.0+)
- npm or yarn

## Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/ai-edits.git
cd ai-edits
```

2. Install dependencies
```bash
npm install
# or
yarn install
```

3. Start the development server
```bash
npm start
# or
yarn start
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Important Note About 3D Text

The 3D text feature requires a font file in JSON format. You need to:

1. Download a font file (Inter Bold is used in this project)
2. Convert it to JSON format using a tool like [facetype.js](https://gero3.github.io/facetype.js/)
3. Place the converted JSON file in `public/fonts/Inter_Bold.json` 

## Build for Production

```bash
npm run build
# or
yarn build
```

## Technologies Used

- React
- TypeScript
- Three.js
- React Three Fiber
- React Three Drei
- React Spring
- Framer Motion

## License

MIT