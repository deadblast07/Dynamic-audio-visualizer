# Dynamic Audio Visualizer (v1.0)

A high-performance audio engine rendering real-time frequency data in-browser. Built with WebGL & Web Audio API for high-fidelity sync, this project was developed through AI-assisted collaborative coding. Features include live/file input, 5-color extraction, and wallpaper optimization.

### Technical Specification

* **Rendering**: Hardware-accelerated WebGL for high-frame-rate graphics.
* **Audio Processing**: Web Audio API for precise frequency analysis (Bass, Mid, Treble).
* **Compatibility**: Native support in all modern desktop and mobile browsers; no external servers or frameworks required.

### Usage Instructions

1. **Launch**: Open `index.html` in any modern web browser.
2. **Audio Activation**: Click anywhere on the screen to initialize the browser's audio engine. If using the **🎙️ LIVE AUDIO** mode, click "Allow" when prompted for microphone access.
3. **File Playback**: Click **🎵 FILE** to open your local file browser. Select any audio file to begin playback. The engine will automatically scan the cover art and extract a custom color palette.
4. **Desktop Wallpaper**: This visualizer is compatible with wallpaper software (e.g., Wallpaper Engine, Lively Wallpaper). The UI is designed to auto-hide after 3.5 seconds of idle time to ensure a clean cinematic background. Moving the mouse or clicking will restore the controls.
5. **Hot-Swapping**: If a track is already playing, click the **🎵 FILE** button again to instantly open your file browser and swap to a new song without stopping the engine.
