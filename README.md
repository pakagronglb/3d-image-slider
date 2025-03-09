# 3D Image Slider with React Three Fiber 🏙️

A stunning 3D image slider built with React Three Fiber and custom shaders, featuring smooth transitions, interactive hover effects, and beautiful UI animations.


This project was inspired by [Wawa Sensei's R3F Ultimate Guide](https://wawasensei.dev/). Special thanks to Wawa Sensei for the amazing course and tutorials.

## Features 🚀

- Responsive 3D image slider with custom shader transitions
- Interactive hover effects with dynamic displacement
- Smooth spring-based animations using Framer Motion
- Beautiful UI with animated text and background colors
- Rounded corners using fragment shaders
- Unique frozen transition effect using displacement textures

## Technologies Used 💻

- React
- Three.js
- React Three Fiber (R3F)
- Framer Motion
- Tailwind CSS
- Custom GLSL Shaders

## Getting Started ⚙️

### Prerequisites

- Node.js (v14 or higher)
- Bun (v1.2.2 or higher)

### Installation 📦

1. Clone the repository:
```bash
git clone https://github.com/pakagronglb/3d-image-slider.git
cd 3d-image-slider
```

2. Install dependencies:
```bash
bun install
```

3. Start the development server:
```bash
bun run dev
```

## Project Structure ⚙️

```
3d-image-slider/
├── src/
│   ├── components/
│   │   ├── ImageSlider.jsx
│   │   └── Slider.jsx
│   ├── hooks/
│   │   └── useSlider.js
│   └── App.jsx
├── public/
│   ├── textures/
│   │   └── optimized/
│   └── displacement/
└── README.md
```

## Implementation Details 📍

### Custom Shader Material

The project uses a custom shader material for creating unique transition effects:

- Smooth transitions between images using mix and noise functions
- Interactive hover effects with dynamic displacement
- Rounded corners using signed distance functions (SDF)
- Displacement mapping using custom textures

### State Management

- Uses Zustand for global state management
- Manages slide transitions and UI animations
- Handles image preloading and texture management

### Responsive Design

- Adapts to different screen sizes
- Maintains image aspect ratio
- Optimized for both desktop and mobile devices

## Credits 🙏🏻

This project was created following [Wawa Sensei's R3F Ultimate Guide](https://wawasensei.dev/). The course provides in-depth knowledge about Three.js and React Three Fiber, making complex 3D web development accessible to everyone.

## License 📝

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙏🏻

- [Wawa Sensei](https://wawasensei.dev/) for the amazing course and tutorials
- [Three.js](https://threejs.org/) for the 3D graphics library
- [React Three Fiber](https://docs.pmnd.rs/react-three-fiber) for the React renderer
- [Framer Motion](https://www.framer.com/motion/) for smooth animations
- [Tailwind CSS](https://tailwindcss.com/) for styling
