# MetatechCRM - Flutter Client Portal & Admin Dashboard

<div align="center">
  <img src="assets/logo/Metatech-latest-logo.webp" alt="MetatechCRM Logo" width="300"/>
  <br/>
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&weight=600&size=25&pause=1000&color=1F37F7&center=true&vCenter=true&width=600&lines=Modern+CRM+Solution+%7C+Flutter+%2B+Laravel;Client+Portal+%7C+Admin+Dashboard;Responsive+Design+%7C+Secure+Architecture" alt="Typing SVG" />
</div>

## 📱 Project Overview

MetatechCRM is a comprehensive Customer Relationship Management solution built with Flutter for cross-platform compatibility and Laravel for robust backend services. The project features both a client portal and an admin dashboard with a focus on user experience, security, and scalability.

### 🎯 Key Features

- **Authentication & Security**
  - 🔐 Secure Login System
  - 🔑 Password Reset Functionality
  - 🔒 Token-based Authentication
  - 👤 User Profile Management

- **Client Portal Features**
  - 📊 Interactive Dashboard
  - 📝 Invoice Management
  - 🎫 Support Ticket System
  - 💬 Real-time Chat Support
  - 👥 Profile Customization

- **Admin Dashboard**
  - 📈 Analytics & Reporting
  - 👥 Client Management
  - 📄 Invoice Generation
  - 🎫 Ticket Management
  - 💬 Support System Administration

## 🏗️ Project Architecture

### Frontend Structure (Flutter)
```
lib/
├── core/                  # Core functionality
│   ├── api_service.dart   # API integration
│   ├── navigation.dart    # Route management
│   └── drawer_controller.dart
├── design_system/         # UI/UX components
│   ├── app_colors.dart
│   ├── app_text_styles.dart
│   └── theme_manager.dart
├── features/             # Main application features
│   ├── dashboard/
│   ├── invoice/
│   ├── login/
│   ├── profile/
│   └── support/
└── widgets/              # Reusable widgets
```

### State Management
- **BLoC Pattern Implementation**
  - Separate Business Logic
  - Reactive State Management
  - Event-Driven Architecture

## 🛠️ Technical Stack

### Frontend (Flutter)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![BLoC](https://img.shields.io/badge/BLoC-02569B?style=for-the-badge&logo=flutter&logoColor=white)

### Backend (Laravel)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (latest version)
- Dart SDK
- Firebase CLI
- IDE (VS Code or Android Studio)

### Installation

1. **Clone the repository**
   ```bash
   git clone [repository-url]
   cd MetatechCRM
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Configure Firebase**
   ```bash
   firebase init
   ```

4. **Run the application**
   ```bash
   flutter run
   ```

## 📁 Project Structure

### Core Features
- **Authentication Module**
  - Login/Logout functionality
  - Password reset system
  - Session management

- **Dashboard**
  - Responsive layout
  - Data visualization
  - Quick action buttons

- **Invoice Management**
  - Invoice generation
  - PDF export
  - Payment tracking

- **Support System**
  - Ticket creation
  - Real-time chat
  - File attachments

### Design System
- Custom theme management
- Responsive layouts
- Consistent styling
- Custom widgets

## 🔒 Security Features

- Secure token management
- API request encryption
- Rate limiting
- Input validation
- Secure file handling

## 🌐 API Integration

The application integrates with a Laravel backend API providing:
- RESTful endpoints
- Token-based authentication
- Real-time updates
- File upload/download
- Data validation

## 📱 Responsive Design

- Adaptive layouts
- Cross-platform compatibility
- Device-specific optimizations
- Consistent UI across devices

## 🧪 Testing

- Widget testing
- Integration testing
- BLoC testing
- API testing

## 📚 Documentation

For detailed documentation about the project:
- [API Documentation](docs/api.md)
- [Widget Documentation](docs/widgets.md)
- [State Management](docs/bloc.md)

## 🤝 Contributing

1. Fork the Project
2. Create your Feature Branch
3. Commit your Changes
4. Push to the Branch
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

For any queries regarding this project, please contact:
- 📧 Email: [Your Email]
- 🌐 Website: [Your Website]

---

<div align="center">
  Made with ❤️ by MetaTech Team
</div>
