# 🎬 YouTube Clone (HTML & CSS Only)

This is a **fully responsive YouTube homepage clone**, built using **pure HTML and CSS**, as a part of my learning journey through the [SuperSimpleDev](https://www.youtube.com/@SuperSimpleDev) HTML & CSS course.

It mimics the structure and layout of YouTube's desktop UI, including the top header, sidebar, and video thumbnail grid — all without using any JavaScript or external frameworks.

## 📸 Preview
<img width="1918" height="1079" alt="Screenshot 2025-07-10 230007" src="https://github.com/user-attachments/assets/b7e3e019-681b-442b-8224-51ec940b1b0e" />
<img width="1919" height="1079" alt="Screenshot 2025-07-10 232740" src="https://github.com/user-attachments/assets/d01cbebc-f833-4ed1-bbba-cd0ffbb32199" />
## 🚀 Features Implemented

### 🔷 Header (Top Navigation Bar)
- Responsive **flex-based header** with fixed position
- YouTube logo and hamburger menu on the left
- Centered **search bar with search and voice search buttons**
- Right side includes:
  - Upload button
  - YouTube apps icon
  - Notification bell with a badge
  - User profile image

### 🔷 Sidebar
- Vertically aligned sidebar with icons
- Sections:
  - Home
  - Explore
  - Subscriptions
  - Originals
  - YouTube Music
  - Library
- All icons styled and aligned with Flexbox

### 🔷 Main Content Area
- **Grid of video thumbnails** mimicking the YouTube home feed
- Each thumbnail card includes:
  - Video thumbnail image
  - Channel profile picture
  - Video title
  - Channel name
  - View count and upload time
- Responsive and adaptive layout using Flexbox and CSS styling

## 🛠️ Tech Stack

- 💻 HTML5
- 🎨 CSS3 (Flexbox)
- 🧠 No JavaScript (purely layout-focused)
- 📂 Visual Studio Code (for development)
- 🌐 Live Server extension for previewing

## 📁 Folder Structure

```plaintext
├── icons/               # SVG icons for UI components
├── sidebar-icons/       # Sidebar-specific icons
├── thumbnails/          # Video thumbnail images
├── styles/
│   ├── head.css         # Header styles
│   ├── sidebar.css      # Sidebar styles
│   ├── videos.css       # Video grid styles
│   └── general.css      # Base and global styles
└── youtube.html         # Main HTML file
