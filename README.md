# Pearl - Medical Knowledge Management

<div align="center">
  <img src="Pearl/Pearl/Assets.xcassets/AppIcon.appiconset/AppIcon@2x.png" alt="Pearl App Icon" width="120" height="120">
  
  **Professional medical knowledge management for healthcare providers**
  
  [![Swift](https://img.shields.io/badge/Swift-5.9+-orange.svg)](https://swift.org)
  [![iOS](https://img.shields.io/badge/iOS-16.0+-blue.svg)](https://developer.apple.com/ios/)
  [![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
  [![Privacy](https://img.shields.io/badge/Privacy-First-red.svg)](PrivacyPolicy.html)
</div>

---

## 📋 Overview

Pearl is a comprehensive iOS application designed specifically for healthcare providers to capture, organize, and manage medical knowledge, clinical pearls, and patient insights. **Created by a practicing physician**, Pearl is built with privacy-first principles and ensures that sensitive medical data remains secure and local to your device while providing powerful organizational tools.

### 🎯 Key Benefits

- **Secure & Private**: All data stored locally on your device
- **Comprehensive**: Support for text, audio, and photo pearls
- **Organized**: Smart tagging and categorization system
- **Backed Up**: iCloud integration for secure data backup
- **Professional**: Designed specifically for medical workflows

---

## ✨ Features

### 📝 Multi-Format Pearl Creation
- **Text Pearls**: Rich text notes for clinical insights and case studies
- **Audio Pearls**: Voice recordings for quick capture during procedures
- **Photo Pearls**: Image capture with descriptive notes for visual documentation

### 🏷️ Smart Organization
- **Medical Specialty Tags**: Pre-configured tags for different medical fields
- **Custom Tagging**: Create personalized tags for your workflow
- **Favorites System**: Mark important pearls for quick access
- **Advanced Search**: Find pearls by title, description, or tags

### ☁️ iCloud Backup & Sync
- **Automatic Backups**: Scheduled backups to iCloud
- **Manual Control**: Create backups on-demand
- **Restore Functionality**: Restore data from any backup point
- **Cross-Device Sync**: Access your pearls across all your devices

### 📊 Export & Data Management
- **Multiple Formats**: Export to JSON, CSV, or XML
- **Complete Packages**: Include both data and media files
- **Professional Documentation**: Comprehensive export with README files
- **Secure Sharing**: Share exports via AirDrop, email, or cloud storage

### 🎨 Professional UI/UX
- **Dark/Light Mode**: Automatic theme switching
- **Medical-Focused Design**: Clean, professional interface
- **Accessibility**: Full VoiceOver and accessibility support
- **Responsive Layout**: Optimized for all iOS devices

---

## 🚀 Installation

### Requirements
- iOS 16.0 or later
- iPhone or iPad
- iCloud account (for backup features)

### Download
Pearl is available on the App Store. Search for "Pearl Medical Knowledge" or use the direct link:

[![Download on the App Store](https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-app-store.svg)](https://apps.apple.com/app/pearl-medical-knowledge/id1234567890)

---

## 📖 Usage Guide

### Getting Started

1. **First Launch**: The app will guide you through the tutorial and privacy terms
2. **Create Your First Pearl**: Tap the + button to add a new pearl
3. **Choose Format**: Select text, audio, or photo based on your needs
4. **Add Details**: Include title, description, and relevant tags
5. **Organize**: Use tags and favorites to keep your pearls organized

### Creating Pearls

#### Text Pearls
- Perfect for clinical notes, case studies, and medical insights
- Rich text formatting support
- Add medical specialty tags for organization

#### Audio Pearls
- Ideal for voice memos during procedures
- High-quality audio recording
- Automatic transcription support

#### Photo Pearls
- Capture medical images, documents, or visual references
- Add descriptive notes to each image
- Secure local storage

### Managing Your Data

#### Backup & Restore
1. **Automatic Backups**: Enable in Settings → Profile → Backup Management
2. **Manual Backups**: Create backups anytime from the backup management screen
3. **Restore Data**: Restore from any previous backup point
4. **Export Data**: Export your pearls for external backup or sharing

#### Organization Tips
- Use consistent tagging for easy searching
- Mark important pearls as favorites
- Regular backups ensure data safety
- Export data periodically for additional security

---

## 🔒 Privacy & Security

### Privacy-First Design
- **Local Storage**: All data stored locally on your device
- **No Cloud Processing**: No data sent to external servers
- **End-to-End Encryption**: iCloud backups are encrypted
- **HIPAA Compliant**: Designed with medical privacy in mind

### Data Protection
- **Device Security**: Leverages iOS security features (Face ID, Touch ID, passcode)
- **No Analytics**: No usage data collected or transmitted
- **Transparent**: Open source code for transparency
- **User Control**: Complete control over your data

### Privacy Policy
For detailed information about how we handle your data, please read our [Privacy Policy](PrivacyPolicy.html).

---

## 🛠️ Technical Details

### Architecture
- **Framework**: SwiftUI
- **Language**: Swift 5.9+
- **Storage**: Core Data with CloudKit integration
- **Backup**: CloudKit for iCloud synchronization
- **Export**: Native iOS sharing with multiple formats

### Key Components
- **ContentViewModel**: Central data management
- **ICloudBackupService**: CloudKit integration
- **PearlStyles**: Centralized styling system
- **Core Data**: Local data persistence

### File Structure
```
Pearl/
├── Controllers/          # Business logic and services
├── Model/               # Data models
├── ViewModel/           # View models and state management
├── Views/               # SwiftUI views
│   ├── SettingsView/    # Settings and configuration
│   └── CustomViews/     # Reusable UI components
├── Assets.xcassets/     # App icons and images
└── Supporting Files/    # Configuration and documentation
```

---

## 🤝 Contributing

We welcome contributions from the medical community! Here's how you can help:

### Development Setup
1. Clone the repository
2. Open `Pearl.xcodeproj` in Xcode
3. Configure your development team
4. Build and run on your device

### Contribution Areas
- **Bug Reports**: Report issues through GitHub Issues
- **Feature Requests**: Suggest new features for medical workflows
- **Code Contributions**: Submit pull requests for improvements
- **Documentation**: Help improve documentation and guides

### Guidelines
- Follow Swift and SwiftUI best practices
- Maintain medical privacy standards
- Test thoroughly on multiple devices
- Update documentation for new features

---

## 📄 License

Pearl is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Third-Party Licenses
This project uses the following third-party libraries:
- None currently - built with native iOS frameworks

---

## 📞 Support

### Documentation
- [User Guide](Pearl/Views/SettingsView/HelpTutorialView.swift)
- [iCloud Setup Guide](ICLOUD_SETUP_GUIDE.md)
- [Privacy Implementation Guide](Privacy_Terms_Implementation_Guide.md)

### Legal
- [Privacy Policy](PrivacyPolicy.html)
- [Terms of Service](TermsOfService.html)

### Contact
For support, feature requests, or bug reports:
- **Email**: support@pearl-medical.com
- **GitHub Issues**: [Create an issue](https://github.com/your-username/pearl/issues)

---

## 👨‍⚕️ About the Developer

**Tyee Fellows, MD, MSc, CCFP**  
*General Surgery Resident*

Pearl was created by a practicing physician with firsthand experience in medical knowledge management challenges. As a General Surgery Resident, Dr. Fellows understands the critical need for efficient, secure, and user-friendly tools to capture and organize clinical insights during demanding medical workflows.

This medical background ensures that Pearl is designed with real-world clinical needs in mind, providing healthcare providers with tools that actually work in their daily practice.

## 🙏 Acknowledgments

- **Medical Community**: For feedback and feature suggestions
- **iOS Development Community**: For best practices and guidance
- **Open Source Contributors**: For inspiration and tools
- **Healthcare Providers**: For real-world testing and validation

---

<div align="center">
  <p><strong>Built with ❤️ for the medical community</strong></p>
  <p><em>Empowering healthcare providers to capture and organize medical knowledge</em></p>
</div> 
