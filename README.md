# YouTube Landing Page Clone

A static frontend recreation of YouTube's video browsing interface, built using HTML5 and CSS3.

The project recreates the familiar YouTube layout, including its top navigation bar, search area, sidebar navigation, video thumbnails, channel images, video information, and hover interactions.

## Overview

This project focuses on recreating the visual structure of YouTube's desktop browsing experience using handwritten HTML and CSS.

The interface is organized into three primary sections:

1. Header — YouTube branding, search field, microphone, upload, notification, and account controls.
2. Sidebar — Navigation icons for home, subscriptions, history, downloads, account, and settings.
3. Video Grid — A responsive grid displaying video thumbnails, channel images, titles, creator names, view counts, upload times, and video durations.

The project uses locally stored image assets for its icons, thumbnails, and channel profile pictures.

## Features

### Header Navigation

- YouTube logo and menu icon.
- Search input field.
- Search button.
- Microphone button.
- Upload button.
- Notification icon with notification count.
- Account icon.

### Sidebar Navigation

- Home
- Subscriptions
- Watch history
- Downloads
- Account
- Settings

### Video Grid

- Video thumbnail cards.
- Channel profile images.
- Video titles and creator names.
- View counts and upload timestamps.
- Video duration labels.
- Responsive CSS Grid layout.
- Hover animation with subtle elevation and shadow effects.

### Visual Interactions

- Hover effects on video cards.
- Sidebar button hover styling.
- Thumbnail and channel image presentation.
- Fixed header and sidebar positioning.

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Layout, styling, and animations |
| CSS Grid | Responsive video grid |
| Flexbox | Header and navigation layout |
| CSS Media Queries | Responsive styling |

This project uses plain HTML and CSS without a JavaScript framework.

## Project Structure

```text
youtube_landing_page/
│
├── authors/
│   ├── author1.jpg
│   ├── author2.jpg
│   └── ...
│
├── icons/
│   ├── youtube.png
│   ├── menu.png
│   ├── searchlens.png
│   ├── mic.png
│   ├── upload.png
│   ├── notification1.png
│   ├── account.png
│   └── ...
│
├── stylesyt/
│   ├── general.css
│   ├── header.css
│   ├── sidebar.css
│   └── video.css
│
├── thumbnails/
│   ├── thumbnail1.avif
│   ├── thumbnail2.avif
│   └── ...
│
├── index.html
└── README.md
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/solapuresanskar01-spec/youtube_landing_page.git
cd youtube_landing_page
```

### 2. Run the project

This is a static HTML and CSS project. No npm installation or build process is required.

You can:

- Open `index.html` directly in your browser.
- Or use the VS Code Live Server extension to serve the project locally.

## Implementation Highlights

- Used CSS Grid to organize video cards into a responsive layout.
- Used Flexbox to structure the header and its navigation sections.
- Used fixed positioning for the header and sidebar.
- Organized styling into separate CSS files for maintainability.
- Used local image assets for thumbnails, channel profiles, and navigation icons.
- Added hover transitions to video cards for visual feedback.

## Current Scope and Limitations

This project focuses on frontend layout and visual recreation.

The current implementation does not include:

- Functional video playback.
- Backend integration.
- User authentication.
- Search functionality.
- Dynamic video loading.
- Functional account or notification systems.

The search field and navigation controls are visual interface elements in the current implementation.

## Author

**Sanskar Solapure**

Computer Science Engineering Student

AISSMS Institute of Information Technology, Pune

GitHub: [@solapuresanskar01-spec](https://github.com/solapuresanskar01-spec)

## License

No license file was included in the repository. All rights reserved unless a license is added.
