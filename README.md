# 🎙️ mynah - Run speech recognition on your computer

[![](https://img.shields.io/badge/Download-Mynah-blue)](https://github.com/tart-castanopsischrysophylla377/mynah)

Mynah turns your computer into a tool for speech recognition and translation. It processes audio input in real time. It works on your machine without needing a cloud connection. You keep your data private because the software runs locally on your hardware.

## 🛠️ System Requirements

Mynah works on Windows 10 and Windows 11. Your computer requires these components to run the engine well:

*   Processor: An Intel Core i5 or AMD Ryzen 5 processor from the last four years.
*   Memory: 8 GB of RAM.
*   Storage: 2 GB of available space.
*   Graphics: The software uses your CPU by default. If you have an Nvidia graphics card, the software can use it for faster speeds.

## 📥 How to Install

Follow these steps to set up the software on your Windows machine:

1. Visit the project website at [https://github.com/tart-castanopsischrysophylla377/mynah](https://github.com/tart-castanopsischrysophylla377/mynah).
2. Look for the Releases section on the right side of the page.
3. Click the link that matches your operating system.
4. Download the installer file ending in .exe.
5. Double-click the file to start the installation.
6. Follow the instructions on the screen to finish the setup process.

## 🚀 Running Your First Transcription

Once the installation finishes, you can start the application.

1. Open the Mynah application from your Start Menu.
2. The application window appears on your desktop.
3. Click the Open button to select an audio file from your computer. Mynah supports common formats like MP3 and WAV.
4. Choose your preferred language from the list.
5. Click the Start button.
6. The software displays text in the main window as it processes the audio.
7. Click the Save button to export the transcription as a text file.

## ⚙️ Understanding Settings

The Settings menu lets you change how the engine works. You can choose different modes for higher accuracy or faster speeds. 

*   Quantization: Selecting int8 or int4 settings reduces the memory usage of the application. Use these if you notice the software uses too much of your computer’s memory.
*   Streaming Mode: This setting allows you to see text appear as the software listens to audio input.
*   Hardware Acceleration: If you possess an Nvidia graphics card, check the box labeled Use CUDA. This makes transcription happen much faster. If you do not have a supported graphics card, leave this box unchecked.

## 🔍 Frequently Asked Questions

Does Mynah send my audio to the cloud?
No. The engine processes all audio files directly on your computer hardware. Your voice data stays on your machine.

Can I use my own microphone?
The current version focuses on processing recorded audio files. Future updates will add direct support for microphone input.

Why does the text look different sometimes?
Transcription accuracy depends on audio quality. Clear, high-quality audio files produce better results than recordings with background noise.

What should I do if the software closes unexpectedly?
Check your computer’s task manager to ensure no other intensive programs consume your RAM. Restart the application if the issue persists.

## 🏗️ Managing Models

Mynah uses language models to understand speech. The software downloads these files automatically when you select a language for the first time. You can manage these files in the Model folder within the installation directory. If you run out of disk space, you can delete models you no longer need. The software will download them again the next time you select that language.

## 🌐 Performance Tips

For the best experience, close web browsers and other heavy programs while running transcriptions. This gives Mynah more processing power. When using large language models, ensure your computer stays cool and plugged into a power source if you use a laptop.

Keywords: asr, c, cpu-inference, cuda, edge-ai, inference, inference-engine, metal, multilingual, on-device-ai, pure-c, quantization, simd, speech-recognition, speech-to-text, speech-translation, streaming, whisper-alternative