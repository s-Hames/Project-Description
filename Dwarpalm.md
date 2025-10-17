# Dwarpalm App

A comprehensive multi-platform Flutter application designed for Personnel Security Officer (PSO) management and real-time location tracking.

## 🚀 Live Deployment

**Status**: Currently deployed on iOS App Store under TestFlight for enhanced security and controlled distribution.

## 📱 Platform Support

- **iOS** - Available on App Store (TestFlight)
- **Android** - APK Distribution
- **Windows** - Desktop Application
- **macOS** - Desktop Application
- **Web** - Progressive Web App

## ✨ Key Features

### 🎯 Core Functionality
- **Multi-Platform Support**: Single codebase running on iOS, Android, Windows, macOS, and Web
- **Real-Time Location Tracking**: GPS-based location monitoring with background services
- **Comprehensive Attendance Management**: Multiple attendance types (PSO, Yatra, Access Control, Office, VVIP)
- **Role-Based Access Control**: Granular permissions for different user types

### 🔐 Security & Authentication
- **Multi-Factor Authentication**: Email OTP for admins, SMS OTP for PSO users
- **Secure Session Management**: Token-based authentication with automatic session validation
- **Admin Dashboard**: Sophisticated control panel with granular user rights management
- **Kill-Switch Mechanism**: Remote app disable capability for security purposes

### 📊 Advanced Features
- **Real-Time Data Sync**: Firebase-powered instant data synchronization across all devices
- **Offline Support**: App functionality maintained without internet connection
- **Background Services**: Continuous location tracking with battery optimization
- **Email Notifications**: Automated email confirmations and system alerts
- **Responsive Design**: Adaptive UI for optimal experience on all screen sizes

## 🛠️ Technology Stack

- **Framework**: Flutter 3.7.2+
- **State Management**: Riverpod
- **Backend**: Firebase (Firestore, Authentication, Storage, Cloud Functions)
- **Architecture**: MVC (Model-View-Controller)
- **Location Services**: Geolocator with background processing
- **Email Integration**: Custom SMTP with Gmail integration
- **Notifications**: Flutter Local Notifications

## 📋 User Roles

### 👨‍💼 Admin
- Full system access and control
- User management and permissions
- Remote location tracking control
- System configuration and settings
- Kill-switch activation capability

### 👮‍♂️ PSO (Personnel Security Officer)
- Attendance marking with location verification
- Profile management
- Attendance history and reports
- Real-time location sharing (when enabled)

### 👥 Sub-Admin
- Limited administrative access
- Category-specific management
- Delegated user rights

## 🔧 Installation & Setup

### Tech Stack
- **Flutter SDK**: 3.7.2 or higher
- **Dart SDK**: Latest stable version
- **Firebase**: Complete backend solution
- **Platform Tools**: Xcode (iOS), Android Studio (Android), VS Code (Cross-platform)

## 📱 App Store Information

**Current Status**: Available on iOS App Store through TestFlight for secure, controlled distribution.

**Why TestFlight?**
- Enhanced security for sensitive PSO data
- Controlled user access and distribution
- Beta testing capabilities
- Secure deployment environment

## 🔒 Security Features

- **Data Encryption**: All sensitive data encrypted at rest and in transit
- **Secure Authentication**: Multi-factor authentication with OTP verification
- **Privacy Compliance**: GDPR and local privacy law compliance
- **Location Privacy**: User consent management and admin-controlled tracking
- **Session Security**: Automatic session timeout and validation

## 📊 Performance

- **Real-Time Updates**: Instant data synchronization across all connected devices
- **Offline Capability**: Full functionality maintained without internet connection
- **Battery Optimization**: Efficient background location tracking with minimal battery drain
- **Scalable Architecture**: Supports thousands of concurrent users with Firebase infrastructure
- **Memory Management**: Optimized for mobile devices with efficient resource utilization
- **Cross-Platform Consistency**: Identical user experience across all supported platforms

## 💼 Business Impact

### Key Achievements
- **Streamlined Operations**: Reduced manual attendance tracking by 90%
- **Enhanced Security**: Multi-layer authentication and real-time monitoring
- **Improved Efficiency**: Automated email notifications and report generation
- **Cost Reduction**: Single codebase for multiple platforms reduces development and maintenance costs
- **Scalability**: Supports organizational growth with Firebase's cloud infrastructure

### Target Users
- **Security Agencies**: Personnel management and location tracking
- **Corporate Security**: Employee attendance and location verification
- **Event Management**: Special event attendance tracking (Yatra, VVIP events)
- **Government Organizations**: Secure personnel management systems

## 🎯 Project Highlights

### Development Excellence
- **Clean Architecture**: MVC pattern with proper separation of concerns
- **Modern State Management**: Riverpod for reactive programming and efficient state handling
- **Real-Time Capabilities**: Firebase integration for instant data synchronization
- **Security First**: Comprehensive authentication and data protection measures
- **User Experience**: Intuitive design with responsive layouts for all devices

### Technical Innovation
- **Background Location Services**: Continuous tracking without user interaction
- **Smart Notifications**: Context-aware alerts and confirmations
- **Adaptive UI**: Responsive design that works seamlessly across different screen sizes
- **Offline Resilience**: Core functionality maintained during network interruptions
- **Performance Optimization**: Battery-efficient location tracking with configurable intervals
