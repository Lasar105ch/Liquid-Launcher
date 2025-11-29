#Liquid Launcher

A modern, AeroOS-inspired desktop launcher built with Python + PyQt6, featuring smooth animations, a customizable dock, widgets, notifications, and a clean glass-style UI.

Liquid Launcher aims to bring a mobile-OS feel to the desktop, with a focus on fluid design, rounded aesthetics, translucency, and productivity-focused widgets.

--\Features (Planned)/--

--\Desktop Environment/--

Modern AeroOS-style desktop

Glassmorphic wallpaper overlay

Drag-and-drop icon arrangement

Animation-based page transitions

--\Dock/--

Centered dock with customizable apps

Hover zoom animation (like macOS)

Right-click menu for app settings

--\Notification Panel/--

Slide-out right panel

Grouped notifications

Media + quick toggles planned

--\Widgets/--

Liquid Launcher will feature a widget system with:

Clock Widget

Weather Widget (OpenWeather API)

System Monitor (CPU, RAM, Disk)

Notes Widget

Music Player Widget (local audio files)

Pure AeroOS Custom Style

Custom QSS theme

Glass blur, neon accents, floating UI

Light + Dark themes

Pure AeroOS transition curves and animations

-/-Installation-/-
Requirements

Python 3.10+

PyQt6

psutil (for system monitor)

requests (for weather)

pillow (for icons/images)

Install Dependencies
pip install PyQt6 psutil requests pillow

▶️ Running Liquid Launcher
python main.py

🛠️ Project Structure (planned)
liquid-launcher/
│── assets/               # icons, wallpapers, theme files
│── widgets/              # widget modules
│   ├── clock_widget.py
│   ├── weather_widget.py
│   ├── system_monitor.py
│   └── notes_widget.py
│── dock/                 # dock system
│   └── dock.py
│── core/
│   ├── window_manager.py
│   ├── theme_manager.py
│   ├── notifications.py
│   └── utils.py
│── main.py               # entry point
│── README.md
│── requirements.txt

🌈 Themes

Liquid Launcher includes:

AeroOS Pure Light

AeroOS Pure Dark

Glass Neon Blue

Glass Soft Pink
More themes can be added through QSS.

🔧 Configuration

A config.json file will store:

Default wallpaper

Dock apps

Enabled widgets

Theme selection

Weather API key



💬 Credits

Created by Lazar (AeroOS Developer)
UI & Style inspired by AeroOS, OriginOS, HyperOS, and modern glassmorphic design.
