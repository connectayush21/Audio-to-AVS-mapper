Speech-to-[A,V,S] Mapper is an interactive social robotics application that interprets how a person speaks rather than only what they say. It analyzes vocal characteristics—pitch, pitch variation, loudness, and pitch contour—and classifies the speaker’s intent as approval, prohibition, attention, comfort, or neutral communication.

Each intent is mapped to a three-dimensional affective tag:

Arousal: calm to excited
Valence: unpleasant to pleasant
Stance: withdraw to approach

The project includes a microphone-powered demo that transcribes speech locally using Whisper and measures tone from the recorded audio. Recognition is confidence-weighted, allowing unclear input to produce weaker robotic responses. The same system can operate through adjustable sliders, preset tones, visual affect charts, and a simulated robot face.

Built with Python, NumPy, Matplotlib, sounddevice, and faster-whisper, the project also provides automated tests, generated results and figures, and a PowerPoint presentation explaining the concept and implementation.
