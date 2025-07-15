# VirtualDrivers

> **Creating virtual hardware solutions for Windows that bridge the gap between software and system integration**

## 🚀 About VirtualDrivers

VirtualDrivers is an open-source organization dedicated to developing professional-grade virtual device drivers for Windows. Our mission is to provide developers, content creators, and IT professionals with powerful tools that emulate hardware devices at the system level, enabling innovative solutions for streaming, virtual reality, remote desktop, and headless server configurations.

Founded and actively led by **MikeTheTech** with key contributions from **Jocke (zjoasan)**, we specialize in creating robust, reliable virtual drivers that seamlessly integrate with Windows 10 and Windows 11 systems.

## 🛠️ Our Core Projects

### 🔊 [Virtual Audio Driver](https://github.com/VirtualDrivers/Virtual-Audio-Driver)
**Add virtual speaker and microphone devices to Windows 10/11**

- **Virtual Speaker Output**: Perfect for headless servers, remote desktop streaming, and audio testing environments
- **Virtual Microphone Input**: Ideal for streaming setups, voice chat testing, and routing audio internally
- **Advanced Features**:
  - Support for 8-bit/8kHz to 32-bit/192kHz audio formats
  - Windows Sonic (Spatial Sound) integration
  - Exclusive Mode and Application Priority support
  - Compatible with VR, OBS, Sunshine, and desktop sharing software

### 🖥️ [Virtual Display Driver](https://github.com/VirtualDrivers/Virtual-Display-Driver)
**Create virtual monitors that function like physical displays**

- **Flexible Resolution Support**: Custom resolutions and refresh rates beyond hardware limitations
- **Key Features**:
  - HDR support for Windows 11 23H2+
  - Custom EDID support for hardware emulation
  - ARM64 compatibility
  - Professional installer with companion app
- **Use Cases**: Streaming, VR applications, screen recording, headless server operations

### ⚙️ [Virtual Driver Control](https://github.com/VirtualDrivers/Virtual-Driver-Control)
**Unified control interface for virtual display management**

- Windows Forms application for easy driver configuration
- XML-based settings management
- System tray integration for quick access
- Toggle specialized features (HDR, SDR 10-bit, custom EDID)

### 🎮 [VirtualBT](https://github.com/itsmikethetech/VirtualBT)
**Bluetooth server for Windows emulating input devices**

- Emulates keyboards, mice, and game controllers
- Leverages Windows Bluetooth Low Energy
- Secure PIN-based authentication
- Future support for expanded device types

## 💡 Why Choose VirtualDrivers?

### Professional Quality
Our drivers are built using the Windows Driver Kit (WDK) and follow Microsoft's development guidelines, ensuring stability and compatibility with modern Windows systems.

### Enterprise Solutions
We offer custom driver development for organizations requiring specialized functionality:
- Named pipes and shared memory buffers
- Zero-latency audio processing
- Direct application integration
- Custom feature development

**Contact us for enterprise solutions**: [contact@mikethetech.com](mailto:contact@mikethetech.com)

### Active Development
Our projects are actively maintained with regular updates, bug fixes, and new feature implementations based on community feedback.

## 🤝 Contributing

We welcome contributions from the community! Whether you're fixing bugs, adding features, or improving documentation, your input helps make VirtualDrivers better for everyone.

### How to Contribute
1. Fork the repository you'd like to contribute to
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 💖 Support Our Work

VirtualDrivers is a labor of love, and your support helps us continue developing and maintaining these tools.

### Support the Team
- **MikeTheTech**: [Patreon](https://www.patreon.com/mikethetech) | [GitHub Sponsors](https://github.com/sponsors/itsmikethetech/)
- **Jocke (zjoasan)**: [GitHub Sponsors](https://github.com/sponsors/zjoasan)

Every contribution, no matter the size, helps us keep building amazing experiences!

## 📋 System Requirements

### General Requirements
- **Operating System**: Windows 10 (Build 1903+) or Windows 11
- **Architecture**: x64 (tested), ARM64 support available
- **Dependencies**: Microsoft Visual C++ Redistributable

### Driver-Specific Requirements
- **Virtual Display Driver**: .NET 6.0 Runtime for control application
- **VirtualBT**: Bluetooth Low Energy capable hardware

## 🔒 Security & Compliance

- All drivers operate in User Mode for enhanced system stability
- Code signing provided by [SignPath.io](https://signpath.io) and [SignPath Foundation](https://signpath.org)
- Open-source code for transparency and community review

## 📄 License

Projects are licensed under various open-source licenses:
- Virtual Audio Driver: MIT
- Virtual Display Driver: MIT
- Virtual Driver Control: MIT
- VirtualBT: GPL-3.0 License (with MIT-licensed components)

Please refer to individual repositories for specific licensing information.

## 📞 Contact

- **General Inquiries**: [contact@mikethetech.com](mailto:contact@mikethetech.com)
- **Bug Reports**: Use GitHub Issues on the relevant repository
- **Feature Requests**: Open a discussion in the repository

## 🌟 Acknowledgments

We extend our gratitude to:
- The Windows driver development community
- Microsoft for the Windows Driver Kit and samples
- All our contributors, sponsors, and supporters
- Lune Studio
- CAMB.ai
- The open-source projects that inspire and enable our work

---

**VirtualDrivers** - *Virtualizing the future of Windows hardware integration*
