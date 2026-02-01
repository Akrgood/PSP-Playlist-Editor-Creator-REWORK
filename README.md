# PSP Playlist Creator
![PSP Playlist Creator](https://img.shields.io/badge/PSP-Playlist_Creator-blueviolet)
![Python](https://img.shields.io/badge/Python-3.6+-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

**Tool for creating and editing playlists (.m3u8) for PSP.**

## 📦 What it does
- Creates playlists for PSP
- Edits existing playlists  
- Automatically finds connected PSP
- Saves to `PSP/PLAYLIST/MUSIC/`
- Supports Ukrainian, Russian, and English languages
- **Works from any folder, doesn't need to be placed in PSP root**

## 🚀 Quick Start
1. Download `psp_playlist_creator.py`
2. Run: `python psp_playlist_creator.py`
3. Program will find PSP automatically (or select manually)
4. Work from anywhere

## ✨ Features
- **3 tabs**: Create / Edit / Rename
- **Double-click** to add/remove tracks
- **Buttons ⬆ ⬇** to change order
- **Auto-detect PSP** - searches all drives and folders
- **Works from any folder** - no need to copy to PSP root
- **Auto-save to PSP** when detected or locally

## 🎮 How to use
1. Click **"Find PSP"** (or select manually)
2. On **"Create Playlist"** tab:
   - Double-click song → adds to playlist
   - Double-click in playlist → removes track
   - Enter name → Save
   
3. On **"Edit Playlist"** tab:
   - Left: list of all playlists from PSP
   - Right: editor like on first tab
   - Use buttons to manage order
   - Save changes

4. On **"Rename Playlist"** tab:
   - Select playlist from list
   - Rename

## 🔍 PSP Detection
Program searches for PSP:
- On all drives (C:\, D:\, etc.)
- In current folder and parent folders
- On desktop, in documents, downloads
- By presence of folders: ISO, PSP, MUSIC, VIDEO, PICTURE

## 📁 Music formats
- MP3, M4A, WMA, WAV, FLAC, AAC

## 💡 Important
- PSP works best with playlists up to 100 tracks
- Use Latin characters in names for compatibility
- Can work with PSP remotely - program will find it when connected

**Run from any folder. Program will find and configure everything automatically.**

Edited by me. Original: https://www.reddit.com/r/PSP/comments/1qrqi74/i_couldnt_get_playlists_to_work_on_my_psp_3000/
