# Litra Plugin Support

This repository is the official support channel for the Litra plugin available on the [Logi Marketplace](https://marketplace.logi.com/plugin/Litra/en). Use this space to:

- 🐛 **Report bugs** - Found something not working correctly? Let us know!
- ✨ **Request features** - Have an idea for a new feature or improvement? We'd love to hear it!
- ❓ **Get help** - Need assistance using the plugin? Ask your questions here!

## How to Submit an Issue

1. Click on the [Issues](../../issues) tab
2. Click "New Issue"
3. Select the appropriate template:
   - **Bug Report** - For reporting bugs or unexpected behavior
   - **Feature Request** - For suggesting new features or enhancements
   - **Support Request** - For getting help or asking questions
---

*Note: This repository is for issue tracking only.

## About the Litra Plugin

Control your Logitech Litra devices directly with an MX Creative Console or the Actions Ring. Turn your Litra lights on/off, adjust brightness and color temperature, create custom sync groups, and adjust multiple lights simultaneously.

**Windows and Bluetooth-connected Beam/Beam LX lights:** Due to a *possible* bug with a library used by the Logi Plugin Service, the service crashes on install. Cancelling breaks the loop. *The plugin will be installed and functional regardless.*

### Getting Started

1. Assign actions to buttons or dials on your device
2. Use the "Configure Sync Groups" action to create custom lighting groups
3. Start controlling your lighting with tactile precision!

### Common Actions

 - Toggle Litra Power - Individual devices and synced groups with smart device detection
 - Adjust Litra Brightness - Device-specific limits with real-time feedback (20-250 for Glow, 30-400 for Beam/LX)
 - Adjust Litra Temperature - 2700K-6500K color temperature control with dynamic visual feedback
 - Configure Sync Groups - Modern web-based group management with enhanced UX and persistent configurations

### Usage Scenarios

#### Content Creation

Perfect for YouTubers, streamers, and video creators who need precise lighting control during recording. Create groups for key lights, fill lights, and background lighting that can be adjusted instantly during live streams.

#### Professional Workspaces

Ideal for photographers, designers, and remote workers who need consistent lighting throughout the day. Set up different lighting scenes for video calls, detailed work, and ambient lighting.

#### Gaming & Streaming

Enhance your streaming setup with dynamic lighting control. Adjust lighting intensity and color temperature to match your content or time of day without interrupting your workflow.

### Notes

#### Supported Litra Devices
   - Logitech Litra Glow (USB) - 20-250 lumens brightness range
   - Logitech Litra Beam (USB/Bluetooth) - 30-400 lumens brightness range
   - Logitech Litra Beam LX (USB/Bluetooth) - 30-400 lumens brightness range
   - All devices support color temperature adjustment from 2700K to 6500K.

#### Sync Groups

   - Create custom groups to control multiple lights simultaneously with an intuitive web interface. Organize your lighting setup into logical groups like "Studio Setup" or "Desk Lights" with persistent configurations that survive device reconnections and USB port changes.
   sync groups are designed to be persistent across device reconnections.
      - On Windows: The plugin creates device profiles with stable identifiers that survive USB port changes, allowing groups to reconnect to the same physical devices.
      - On macOS: Devices are identified using actual serial numbers, so groups automatically reconnect when the same devices are detected, regardless of USB port changes.

#### Independent Brightness and Color Temperature Control

By default, actions created for different controls on each Litra light. You can have brightness on a dial and color temperature on another, or use groups to control multiple settings simultaneously.

#### Simultaneous Litra Device Controls

The plugin supports multiple Litra devices connected via USB or Bluetooth. You can control them individually or group them into custom sync groups for simultaneous control.

#### Smart Device Detection

The plugin automatically detects connected Litra devices with clear identification showing product names, connection types (USB/Bluetooth), and serial numbers. Real-time hot-plug detection ensures your setup stays current as you connect or disconnect devices.

#### USB vs Bluetooth Connections

USB connections provide the most reliable control and work even when Logitech G HUB is running. Bluetooth connections are supported but may require closing G HUB for full access.
   
#### GHUB Conflict Detection

The plugin has built-in detection and warnings when Logitech GHUB conflicts with Bluetooth device access. The plugin automatically identifies when G HUB is running and provides helpful guidance to troubleshoot connectivity issues and optimize your lighting setup.

#### Troubleshooting Bluetooth Litra Devices Detection Issues

First ensure the devices are properly paired and connected (not just paired) in your system's Bluetooth settings. If they still don't appear, try closing Logitech G HUB completely as it can maintain exclusive access to Bluetooth-connected Litra devices.

#### Using with Logitech GHUB

For USB devices - they work fine with both applications running. For Bluetooth devices, you may need to close GHUB to allow this plugin full access, as both applications might not be able to control the same Bluetooth device simultaneously.
