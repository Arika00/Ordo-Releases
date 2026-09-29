Ordo





Ordo is a Windows application for hardware monitoring, fan control and audio management, with a modern native interface.

This repository is the public distribution repository for Ordo.
The source code and development repository are kept private.

Download

Latest version

Download Ordo

Download:

Ordo-Setup.exe

Run the installer and follow the setup wizard.

The installer may request administrator permissions because Ordo uses hardware monitoring and control features that require elevated access.

Features

Dashboard

Customizable hardware widgets

Sensor selection

Widget layout persistence

Dashboard configuration saved between launches

Fan control

Automatic and manual fan modes

Temperature-based fan curves

Minimum and maximum fan speeds

Target RPM monitoring

Multiple fan control profiles

Hardware capability detection

Audio

Windows master volume control

Application/session audio controls

WASAPI-based audio management

Microphone input and processing features

Settings

Windows startup

Start minimized

System tray behavior

Automatic update checking

Automatic updates

Ordo includes an automatic update system.

You do not need to open GitHub or manually download every new version.

When a new release is available:

Ordo
  ↓
Check for updates
  ↓
Download the new installer
  ↓
Verify the download
  ↓
Install the new version
  ↓
Restart Ordo

Updates are published through this repository's GitHub Releases.

Requirements

Ordo currently targets:

Windows 10 / Windows 11

64-bit (x64)

The installer handles the main runtime dependencies required by the application:

.NET 8 Desktop Runtime x64

Microsoft Edge WebView2 Runtime

Optional audio component

VB-CABLE is not included with Ordo.

Some audio workflows may require VB-CABLE to be installed separately.

Hardware support

Fan and sensor features depend on the hardware and the interfaces exposed by the system.

Ordo currently uses LibreHardwareMonitor for hardware monitoring and control.

Some hardware may expose sensors as read-only or prevent software fan control. Motherboard, BIOS/firmware and Windows security settings can affect available controls.

Installation

Open the latest release.

Download Ordo-Setup.exe.

Run the installer.

Follow the setup wizard.

Launch Ordo.

Updating

Ordo can check this repository for newer versions from inside the application.

You normally do not need to uninstall the previous version before updating.

Releases

Each version is published as a GitHub Release.

Example:

v0.1.8
└── Ordo-Setup.exe

View all releases

Privacy

This repository contains the public distribution files for Ordo.

The Ordo source code is maintained separately in a private repository.

No GitHub account is required to download Ordo from the public releases page.

Support

When reporting a bug, include:

Ordo version

Windows version

What you were doing when the issue occurred

The exact error message, if any

A screenshot or log when available

License

See the license information included with the distributed version of Ordo.# Ordo Releases
