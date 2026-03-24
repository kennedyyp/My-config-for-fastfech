#Fastfetch Configuration – Gengar Theme 👻

Welcome to my Fastfetch setup, themed around Gengar from Pokémon! This configuration blends vibrant purples and dark tones to give my terminal a spooky, ghostly aesthetic while keeping it fully functional and informative.

I’ve customized Fastfetch to show all key system information, organized neatly with colored keys and separators for a clean look.

🌈 Theme & Logo

Logo: /etc/fastfetch/abc.png

Colors:

Main: 38;2;138;43;226 (Gengar purple)

Secondary: 38;2;75;0;130 (dark purple accent)

The logo appears at the top, adding a personalized touch inspired by Gengar’s iconic palette.

⚡ Display Settings

Separator: " "

Breaks added between sections for clarity.

🖥️ Modules & Configuration

System Info:

Key	Description	Color
 OS	Operating system	38;2;186;85;211
 KERNEL	Kernel version	38;2;186;85;211
🛈 VERSION	OS version	38;2;186;85;211
 UPTIME	System uptime	38;2;186;85;211
 PKGS	Installed packages	38;2;186;85;211

Hardware Info:

Key	Description	Color
⚙ CPU	Processor	38;2;199;125;255
 GPU	Graphics card	38;2;199;125;255
󰍛 RAM	Memory usage	38;2;199;125;255
 DISK	Disk usage	38;2;199;125;255
♻ SWAP	Swap usage	38;2;199;125;255

Environment Info:

Key	Description	Color
 WM	Window manager	38;2;160;32;240
 TERM	Terminal emulator	38;2;160;32;240
 SHELL	Shell	38;2;160;32;240

Network & Locale:

Key	Description	Color
 DATE	Current date	38;2;138;43;226
 LOCAL IP	Local IP address	38;2;138;43;226
 PUBLIC IP	Public IP address	38;2;138;43;226
 LOCALE	System locale	38;2;199;125;255

Media:

Key	Description	Color
 MUSIC	Current music player status	38;2;199;125;255
🎨 Colors

The configuration uses gradients of purple and indigo to match Gengar’s palette, giving a ghostly and fun feel to my terminal while maintaining readability.

Primary purple: 38;2;138;43;226

Secondary indigo: 38;2;75;0;130

Accent purple: 38;2;199;125;255

Window manager / terminal keys: 38;2;160;32;240

⚙ How to Use

Place your logo at /etc/fastfetch/abc.png.

Save this JSON configuration to ~/.config/fastfetch/config.json.

Run fastfetch in your terminal and enjoy your Gengar-themed setup!
