# 🎵 Audio Spectrum 3D

> An immersive 3D audio spectrum visualizer built with **Three.js**, featuring real-time WebAudio API integration, dynamic particle effects, and interactive controls. Upload any audio file or use microphone input to visualize sound in stunning 3D.

## ✨ Features

- **Real-time Audio Analysis**: Leverages Web Audio API for live frequency analysis
- **3D Visualization**: Interactive 3D scene with Three.js rendering
- **Multiple Visualization Modes**:
  - Spectrum Bars: Classic frequency-based bar visualization
  - Waveform: Real-time waveform display
  - Particle System: Dynamic particles responding to audio
  - Orbit Mode: 360° immersive experience
- **Audio Input Options**:
  - Upload MP3, WAV, OGG, or FLAC files
  - Microphone input for live visualization
- **Interactive Controls**:
  - Rotate and zoom the 3D scene
  - Adjust smoothing and sensitivity
  - Toggle visualization modes
  - Real-time FPS counter
- **Theme Support**: Dark theme optimized for immersive viewing
- **Responsive Design**: Works on desktop and mobile devices
- **Performance Optimized**: 60 FPS visualization with WebGL rendering

## 🚀 Live Demo

[View Live Demo](https://snakeeye-sudo.github.io/audio-spectrum-3d/)

## 📥 Installation

### Option 1: Use Online
Simply visit the [live demo](https://snakeeye-sudo.github.io/audio-spectrum-3d/) and start visualizing!

### Option 2: Local Setup

```bash
# Clone the repository
git clone https://github.com/SnakeEye-sudo/audio-spectrum-3d.git

# Navigate to directory
cd audio-spectrum-3d

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

## 🎮 How to Use

1. **Upload Audio**:
   - Click the "Upload File" button and select an audio file
   - Or grant microphone access to visualize live audio

2. **Control Visualization**:
   - **Mouse**: Drag to rotate, Scroll to zoom
   - **Spacebar**: Play/Pause audio
   - **M**: Toggle visualization modes
   - **S**: Toggle smoothing
   - **T**: Change color themes

3. **Adjust Settings**:
   - Sensitivity slider: Adjust frequency response intensity
   - Smoothing slider: Control animation smoothness
   - Resolution dropdown: Choose quality level

## 🛠️ Tech Stack

- **Three.js**: 3D graphics rendering
- **Web Audio API**: Real-time audio analysis
- **TypeScript**: Type-safe JavaScript
- **Vite**: Fast build tool and dev server
- **GSAP**: Smooth animations
- **Tailwind CSS**: Modern styling

## 📁 Project Structure

```
src/
├── components/
│   ├── Visualizer.ts       # Main 3D scene
│   ├── AudioAnalyzer.ts    # Web Audio API wrapper
│   ├── SpectrumBars.ts     # Bar visualization
│   ├── ParticleSystem.ts   # Particle effects
│   └── Controls.ts         # UI controls
├── shaders/
│   ├── vertex.glsl         # Vertex shaders
│   └── fragment.glsl       # Fragment shaders
├── styles/
│   └── main.css            # Global styles
└── main.ts                 # Entry point
```

## 🎨 Customization

Edit colors, particle counts, and visual effects in `src/config.ts`:

```typescript
export const CONFIG = {
  PARTICLE_COUNT: 5000,
  BAR_COUNT: 64,
  COLOR_SCHEME: 'cyberpunk',
  SMOOTHING: 0.8,
  SENSITIVITY: 1.2,
};
```

## 📊 Performance

- Optimized for 60 FPS on most devices
- Adaptive quality settings based on device capability
- GPU-accelerated rendering with WebGL
- Efficient particle system with instanced rendering

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

MIT License - see LICENSE file for details

## 👨‍💻 Author

**Er. Sangam Krishna** (SnakeEye-sudo)
- GitHub: [@SnakeEye-sudo](https://github.com/SnakeEye-sudo)
- Portfolio: [snakeeye-sudo.github.io](https://snakeeye-sudo.github.io)

## 🙏 Acknowledgments

- Three.js community for amazing 3D library
- Web Audio API documentation and examples
- Inspired by music visualization tools and interactive experiences

## ⭐ Support

If you found this project helpful, please give it a star! Star us on GitHub - it helps!

---

**Made with 💜 by SnakeEye-sudo**
