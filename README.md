# Awesome VTubing on Linux

List of streaming software, VTuber avatar tools, and audio utilities for Linux-based VTubers.  

---

## Streaming Software

- [OBS Studio](https://obsproject.com/)  
  Free, open-source video recording and live streaming software (Windows, macOS, **Linux**).  
  **Linux:** Native  

- [v4l2loopback](https://github.com/v4l2loopback/v4l2loopback)  
  Linux kernel module for creating “virtual” video devices (fake webcams).  
  **Linux:** Native (kernel module)  

- [obs-v4l2sink](https://github.com/CatxFish/obs-v4l2sink)  
  OBS Studio output plugin to send video output to Video4Linux2 devices (enables OBS virtual cam on Linux).  
  **Linux:** Native (plugin)  

- [Webcamoid](https://webcamoid.github.io/)  
  Cross-platform webcam suite (supports many effects, multi-camera setups, and virtual cameras).  
  **Linux:** Native (Snap/Flatpak available)  

---

## VTuber Model Software

- [OpenSeeFace](https://github.com/emilianavt/OpenSeeFace)  
  Open-source 3D facial landmark tracking library for animating Live2D/VRM avatars.  
  **Linux:** Native (Python-based)  

- [XR Animator](https://github.com/ButzYung/SystemAnimatorOnline)  
  AI-powered full-body and face motion capture (single webcam drives 3D MMD/VRM avatars).  
  **Linux:** Native (Electron app)  

- [Kalidoface 3D](https://3d.kalidoface.com/)  
  Web-based VRM avatar tracker (drag-and-drop your VRM; Mediapipe face and body tracking).  
  **Linux:** Native (browser)  

- [Kalidoface (Live2D)](https://kalidoface.com/)  
  Web-based Live2D face-tracking app (upload Live2D models to animate via webcam).  
  **Linux:** Native (browser)  

- [VTube Studio](https://denchisoft.com/)  
  Live2D avatar capture/streaming app (Windows/macOS). Linux users run it via Steam Proton with OpenSeeFace for face tracking.  
  **Linux:** Via Proton (Steam)  

- [VNyan](https://suvidriel.itch.io/vnyan)  
  3D VTuber avatar tool (supports VRM/VSF avatars).  
  **Linux:** Windows-only (works under Proton)
  
- [SnekStudio](https://snekstudio.com/)  
  Open-source 3D VTuber avatar tool with Mediapipe support (body and face tracking via webcam) for VRM avatars.  
  **Linux:** Native (Flatpak available)
- [Shapeweld VRM Version Converter](https://shapeweld.com/tools/vrm-version-converter)  
  Web-based converter between VRM 1.0 and VRM 0.x (drop a .vrm, download the other version).  
  **Linux:** Native (browser)

---

## Audio Tools

- [JACK Audio Connection Kit](https://jackaudio.org/)  
  Professional low-latency audio/MIDI routing server and API.  
  **Linux:** Native  

- [NoiseTorch-ng](https://github.com/noisetorch/NoiseTorch)  
  Real-time microphone noise suppression (RNNoise-based) for PulseAudio/PipeWire, creates a virtual “filtered” mic.  
  **Linux:** Native  

- [EasyEffects (PulseEffects)](https://github.com/wwmm/easyeffects)  
  Modular audio effects processor (equalizer, compressor, reverb, pitch shift, etc.) for PipeWire/PulseAudio.  
  **Linux:** Native  

- [SoX](http://sox.sourceforge.net/)  
  Command-line audio processing tool (effects like pitch-shifting, echo, etc.).  
  **Linux:** Native  

---
