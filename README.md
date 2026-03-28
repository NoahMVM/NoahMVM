# Hey, I'm Vova (WeeDee)

I reverse-engineer and virtualize Tesla vehicle firmware for research and exploration.

## What I've Been Building

### Tesla Firmware Virtualization

I run real Tesla MCU firmware (ICE/center display) inside QEMU virtual machines on a Windows desktop — full UI, touch input, and all.

**What's working:**
- **Full Tesla UI in QEMU** — display, touch input, and live viewer streaming over TCP
- **3D Car Visualization** — the Godot-based Model 3 renders inside the park panel with virgl GPU acceleration
- **Maps, GPS & Navigation** — offline turn-by-turn routing with Valhalla, lane guidance, and spoofed GPS
- **Multiple firmware versions** — from my own car's 2024.20.3 dump to the latest 2026.2.3
- **Automated setup** — Python scripts handle ConnMan networking, GPS, map tile servers, and routing engines on boot

**Tech stack:** QEMU/KVM, WSL2, virtio-gpu, VNC, D-Bus, Valhalla routing engine, Python, Zig

## About

- 2021 Model 3 owner
- Interested in embedded systems, virtualization, and automotive security research
- Windows 11 + WSL2 + QEMU is my daily setup
