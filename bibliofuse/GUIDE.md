# BiblioFuse User Guide

Welcome to **BiblioFuse**, your ultimate comic and ebook manager. This guide covers everything from setting up your library to using advanced tools like compression and merging.

## 📚 What is BiblioFuse?

BiblioFuse is a powerful cross-platform (iOS & Android) application designed to:
*   **Read**: Support for CBZ, CBR, ZIP and EPUB formats.
*   **Manage**: Organize your local and cloud libraries with metadata and tags.
*   **Optimize**: Tools to compress, merge, and convert comic archives to save space.
*   **Sync**: Seamlessly sync reading progress and metadata across devices using iCloud (iOS) or local backups.


![1](https://github.com/user-attachments/assets/a1004645-e1de-4d5d-85d8-e8b3abcb524a)


## Table of Contents
1. [Getting Started](#getting-started)
2. [Managing Your Library](#managing-your-library)
   - [Adding Local Folders](#adding-local-folders)
   - [Adding Network (SMB) Folders](#adding-network-smb-folders)
   - [Pinned Folders & Defaults](#pinned-folders--defaults)
3. [Reading Experience](#reading-experience)
   - [Reader Controls](#reader-controls)
   - [Settings & Customization](#settings--customization)
4. [Tools: Compression & Merging](#tools-compression--merging)
   - [Compressing Comics](#compressing-comics)
   - [Merging Files](#merging-files)
5. [Pro Version](#pro-version)
6. [Settings & Legal](#settings--legal)

---

## 1. Getting Started
When you first launch BiblioFuse, your library will be empty. You need to tell the app where your books and comics are stored.

![Screenshot 2026-01-09 145605](https://github.com/user-attachments/assets/55dd9b09-2fb1-447e-8af2-22a171f21896)


## 2. Managing Your Library

### Adding Local Folders
To add a folder from your device:
1. Open the **Navigation Drawer** (hamburger menu top-left).
2. Tap **Add Phone Folder**.
3. Browse and select the folder containing your EPUB, CBZ, or PDF files.
4. The folder will appear in the "Pinned Folders" list.

### Pinned Folders & Defaults
*   **Default Library**: Tap the Heart icon next to a folder in the drawer to set it as your default. The app will open this folder automatically on launch.
*   **Remove Folder**: Tap the 'X' to unpin a folder.

🔒 **Privacy Note:** Bibliofuse is a local-only reader. No data (book files, reading habits, or metadata) is transferred over the internet. Everything stays on your device.

💡 If you added a content folder, open side bar and tap on it again. If **NOTHING SHOW UP**, you may have missed the prompt earlier. If you want to try this feature out, you can enable it manually:
1.	Go to your phone's Settings > search “all files access” >Apps > Bibliofuse.
2.	Choose "Allow management of all files".




### Filtering & Organization
*   **Filter by Format**: Tap the **Filter Icon** to show only EPUB or CBZ/Archive files.
*   **Filter by Rating**: Use the same Filter menu to show books with a specific Star Rating (1-5).
*   **Filter by Tags**: Tap the **Tag (#) Icon** to select one or more custom tags to filter your view.

## 3. Reading Experience

Tap any book cover to open the Reader.

### Reader Controls
*   **Turn Pages**: Tap the **Right** edge (Next) or **Left** edge (Previous).
*   **Menu**: Tap the **Center** of the screen to show/hide the toolbar and scrubber.
*   **Tags & Ratings**: Tap the **Tag Icon** in the top toolbar to Rate the book (1-5 stars) or add Custom Tags (e.g., "Favorite", "To Read").
*   **Zoom**: Double-tap or pinch to zoom in on details.
  


### Settings & Customization
While reading, tap the **Settings (Gear)** icon to:
*   Adjust **Brightness**.
*   Toggle **Reading Direction** (Page or Continuous).
*   Change **Fit Mode** (Fit Width, Fit Height, or Contain).

## 4. Tools: Compression & Merging
BiblioFuse includes powerful tools to optimize your collection.

### Compressing Comics
Reduce file size to save space:
1. Long-press a comic in the library to enter **Selection Mode**.
2. Select multiple files if desired.
3. Tap the **Compression Tool** icon.
4. Choose your compression level for the output format.
5. Tap **Start** to process the file(s).

![Screenshot 2026-01-09 145105](https://github.com/user-attachments/assets/a5b1c925-9339-4230-88e9-f2e053554409)


### Merging Files
Combine multiple issues into a single specific volume:
1. Select multiple files in order.
2. Tap the **Tool** icon and select **Merge**. Sort the files in order.
3. The app will combine them into a single CBZ/EPUB file.

![Screenshot 2026-01-09 145105](https://github.com/user-attachments/assets/2b47be20-4613-4014-8a6a-9cbc9b0c06ab)

## 5. Premium Version
BiblioFuse offers a Premium tier for power users:

![Screenshot 2026-01-09 145105](https://github.com/user-attachments/assets/ad627881-42a9-4bd5-a60c-72089ffead02)

To upgrade, open the Drawer and tap **Go Premium**.


## 6. Settings & Legal
Access global settings from the Drawer:
*   **App Theme**: Switch between Light, Dark, or System Default.
*   **Language**: Change the interface language.
*   **Privacy Policy**: View our data handling policy (link at bottom of drawer).
*   **Guide**: View our user guide (link at bottom of drawer).
*   **Version Info**: Check your current app version.

---

## ☁️ Cloud Sync & Backups

### iCloud Sync (iOS)
*   **How it works**: BiblioFuse automatically syncs your reading positions and metadata (ratings/tags) via iCloud Drive.
*   **Setup**: Ensure iCloud Drive is enabled for BiblioFuse in iOS Settings. No manual setup required.
*   **Status**: Check the "iCloud" section in the Drawer Menu to see synced books.

### Auto-Backup
*   **What is backed up?**: Your entire library database (reading progress, tags, ratings). Book files themselves are NOT backed up (too large).
*   **How to enable**: This is a **Premium** feature. It runs automatically when the app goes to the background.
*   **Location**:
    *   **iOS**: `Files app > iCloud Drive > BiblioFuse > Metadata`
    *   **Android**: `Internal Storage > Documents > BiblioFuse > Metadata`
*   **Retention**: The app keeps the 4 most recent backups + the largest backup from the past.

### Manual Backup / Restore
*   **Backup**: Go to `Drawer > Backup > Export Database`. Save the `.db` file anywhere.
*   **Restore**: Go to `Drawer > Backup > Import Database`. Select a backup file. **Warning**: This replaces your current data.


---

## ❓ FAQ (Frequently Asked Questions)

### Q: Where can I find my Auto-Backup files?
*   **iOS**: Open the "Files" app, navigated to `iCloud Drive` -> `BiblioFuse` -> `Metadata`.
*   **Android**: Use a File Manager to go to `Documents/BiblioFuse/Metadata`.

### Q: Why doesn't EPUB support WebP compression?
EPUB is a strict standard. Most e-readers (iBooks, Google Play Books) do not support the modern WebP image format inside EPUBs. To ensure your generated EPUBs work everywhere, BiblioFuse strictly enforces **JPG** for EPUB output. If you want maximum compression (WebP), please use **CBZ** format.

### Q: How do I reindex a folder that is showing wrong covers?
Open the Left Drawer Menu (hamburger icon) inside the Library tab. Find the folder in the list, click the "Three Dots" (⋮) icon next to it, and select **"Reindex Folder"**. This will clear the cache for that folder and re-scan all files.

### Q: Can I run BiblioFuse on Mac or Windows?
Currently, BiblioFuse is optimized for iOS and Android mobile devices. A desktop version is not yet available.

### Q: What is "Peek Mode"?
Peek Mode is a unique one-handed navigation style designed by BiblioFuse. Instead of full page turns, it allows you to slide your thumb to "peek" at the next panel or page, making it easier to read on large phones with just one hand.


