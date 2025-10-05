# 🚗 Auto Lab Solutions - Staff Mobile App

[![React Native](https://img.shields.io/badge/React%20Native-0.80.0-blue.svg)](https://reactnative.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0.4-blue.svg)](https://www.typescriptlang.org/)
[![iOS](https://img.shields.io/badge/iOS-15.1+-lightgrey.svg)](https://developer.apple.com/ios/)
[![Android](https://img.shields.io/badge/Android-API%2021+-green.svg)](https://developer.android.com/)

A comprehensive mobile application designed for Auto Lab Solutions staff members to manage appointments, customer communications, analytics, and daily operations. Built with React Native and TypeScript, featuring role-based access control and real-time functionality.

## 📱 App Overview

<img src="screenshots/Admin_More_Screen.png" alt="More Screen" width="300"/>

The Staff Mobile App serves as a central hub for Auto Lab Solutions employees, providing different features based on user roles (Admin, Customer Support, Mechanic, Clerk). The app integrates seamlessly with the backend system to provide real-time updates and comprehensive business management tools.

## 🎯 Key Features

### 🔐 **Authentication & Security**
- **OAuth2 Integration**: Secure login via Auth0
- **Role-Based Access Control**: Different features for different staff roles
- **Automatic Session Management**: Token refresh and re-authentication
- **Deep Linking Support**: URL scheme handling for web integration

### 👥 **Role-Based Features**

#### 👑 **Admin Users**
- Full system access and administrative controls
- Business analytics and reporting
- Staff role management
- Invoice generation and management
- Time slot analysis tools

#### 🎧 **Customer Support**
- Customer communication management
- Appointment scheduling and management
- User information updates
- Email thread management
- Invoice viewing capabilities

#### 🔧 **Mechanic**
- Daily schedule viewing
- Work order management
- Appointment status updates
- Report uploads for completed work
- Assigned appointment notifications

#### 📋 **Clerk**
- Appointment management support
- Report management
- Basic scheduling operations
- Administrative support tasks

## 📊 **Core Features by Category**

### 🗓️ **Appointment Management**

<div align="center">
<img src="screenshots/Appointments_List.png" alt="Appointments List" width="300"/>
<img src="screenshots/Appointment_Details.png" alt="Appointment Details" width="300"/>
</div>

**Features:**
- **Complete Appointment Lifecycle**: From pending to completion
- **Real-time Updates**: Live status synchronization
- **Role-based Actions**: Different permissions for each role
- **Scheduling System**: Time slot management with conflict detection
- **Work Reports**: Upload and manage completion reports

<div align="center">
<img src="screenshots/Mechanic_Daily_Schedule.png" alt="Daily Schedule" width="300"/>
<img src="screenshots/Appointment_Details_Scheduled_Time.png" alt="Appointment Details Scheduled Time" width="300"/>
</div>

**Workflow:**
1. **Pending** → Customer Support schedules appointment
2. **Scheduled** → Assigned mechanic starts work
3. **Ongoing** → Work in progress
4. **Completed** → Mechanic/Clerk uploads reports
5. **Reports Reviewed** → Admin approves/rejects reports

### 💬 **Real-time Communication**

<div align="center">
<img src="screenshots/Customer_Support_Chat_Thread.png" alt="Customer Support Chat" width="300"/>
<img src="screenshots/Customer_Support_Chat_Threads_List.png" alt="Chat Threads List" width="300"/>
</div>

**Features:**
- **WebSocket Integration**: Real-time messaging
- **Customer Support Portal**: Live chat with customers
- **Typing Indicators**: Real-time typing status
- **Online Status**: User presence indicators
- **Message Threading**: Organized conversation management

<div align="center">
<img src="screenshots/Customer_Support_Chat_Threads_List.png" alt="Chat Threads List" width="300"/>
</div>

**Communication Workflow:**
1. Customer initiates chat or inquiry
2. Real-time notification to customer support
3. Live conversation with typing indicators
4. Message history and thread management
5. Escalation to appropriate staff members

### 📧 **Email Management**

<div align="center">
<img src="screenshots/Email_Threads_List.png" alt="Email Threads" width="300"/>
<img src="screenshots/View_Email_Details.png" alt="Email Details" width="300"/>
</div>

**Features:**
- **Email Thread Management**: Organized email conversations
- **Customer Communication**: Direct email integration
- **Template System**: Pre-built email templates
- **Attachment Support**: File sharing capabilities

### 📈 **Business Analytics**

<div align="center">
<img src="screenshots/Analytics_Overview_2.png" alt="Analytics Overview" width="300"/>
<img src="screenshots/Analytics_Customer_Analytics_1.png" alt="Customer Analytics 1" width="300"/>
</div>

**Comprehensive Analytics Suite:**
- **Revenue Analytics**: Financial performance tracking
- **Service Analytics**: Popular services and performance
- **Customer Analytics**: Customer behavior and retention
- **Vehicle Analytics**: Vehicle type and brand analysis
- **Today's Analytics**: Real-time daily metrics

<div align="center">
<img src="screenshots/Analytics_Customer_Analytics_1.png" alt="Customer Analytics 1" width="300"/>
<img src="screenshots/Analytics_Customer_Analytics_2.png" alt="Customer Analytics 2" width="300"/>
</div>

**Analytics Features:**
- **Interactive Charts**: Visual data representation
- **Date Range Filtering**: Custom period analysis
- **Export Capabilities**: Data export for reporting
- **Real-time Updates**: Live data synchronization
- **Role-based Access**: Admin and Customer Support only

<div align="center">
<img src="screenshots/Analytics_Todays_Analytics_1.png" alt="Today's Analytics 1" width="300"/>
<img src="screenshots/Analytics_Todays_Analytics_2.png" alt="Today's Analytics 2" width="300"/>
</div>

### 🧾 **Invoice Management**

<div align="center">
<img src="screenshots/Generate_Invoice_Fill_Customer_Details.png" alt="Generate Invoice" width="300"/>
<img src="screenshots/Generate_Invoice_Select_Service_Plan.png" alt="Invoice Service Selection" width="300"/>
</div>

**Features:**
- **Invoice Generation**: Create invoices for external services
- **Service Selection**: Choose from available service plans
- **Customer Information**: Comprehensive customer data entry
- **PDF Generation**: Professional invoice formatting
- **Status Tracking**: Invoice lifecycle management

<div align="center">
<img src="screenshots/Generate_Invoice_Successful.png" alt="Invoice Success" width="300"/>
<img src="screenshots/View_Invoices.png" alt="View Invoices" width="300"/>
</div>

### 👨‍💼 **User Management**

<div align="center">
<img src="screenshots/User_Management.png" alt="User Management" width="300"/>
<img src="screenshots/Admin_Staff_Roles_Management.png" alt="Staff Roles Management" width="300"/>
</div>

**Features:**
- **Customer Information**: View and edit customer details
- **Staff Management**: Role assignments and permissions
- **Online Status**: Real-time user presence
- **Contact Management**: Phone, email, and address information

### 📋 **Reports Management**

<div align="center">
<img src="screenshots/Appointments_With_Reports.png" alt="Appointment Reports" width="300"/>
<img src="screenshots/Appointment_Upload_Reports.png" alt="Upload Reports" width="300"/>
</div>

**Features:**
- **Work Report Uploads**: PDF file upload system
- **Report Approval Workflow**: Admin review and approval
- **Status Tracking**: Report lifecycle management
- **File Management**: Secure cloud storage integration

<div align="center">
<img src="screenshots/Admin_Review_Report.png" alt="Review Reports" width="300"/>
<img src="screenshots/Appointment_Details_Work_Reports.png" alt="Appointment Work Reports" width="300"/>
</div>

### ⏰ **Time Management**

<div align="center">
<img src="screenshots/Admin_Set_Unavailable_Time_Durations.png" alt="Unavailable Time Slots" width="300"/>
</div>

**Features:**
- **Time Slot Management**: Set unavailable periods
- **Schedule Optimization**: Prevent double booking
- **Maintenance Windows**: Block time for facility maintenance
- **Holiday Management**: Recurring unavailable periods

### 💳 **Payment Integration**

<div align="center">
<img src="screenshots/Appointment_Confirm_Payment.png" alt="Payment Confirmation" width="300"/>
</div>

**Features:**
- **Payment Status Tracking**: Real-time payment updates
- **Payment Method Management**: Multiple payment options
- **Transaction History**: Complete payment records
- **Invoice Integration**: Link payments to invoices

## 🏗️ **Technical Architecture**

### **Frontend Stack**
- **React Native 0.80.0**: Cross-platform mobile development
- **TypeScript 5.0.4**: Type-safe development
- **React Navigation 7.x**: Screen navigation and routing
- **React Context API**: Global state management
- **Axios**: HTTP client for API communication
- **WebSocket**: Real-time communication
- **React Native Vector Icons**: Consistent iconography

### **Key Dependencies**
```json
{
  "@react-navigation/native": "^7.1.14",
  "@react-navigation/bottom-tabs": "^7.4.2",
  "@react-native-async-storage/async-storage": "^2.2.0",
  "axios": "^1.10.0",
  "react-native-chart-kit": "^6.12.0",
  "react-native-document-picker": "^9.3.1",
  "react-native-vector-icons": "^10.3.0",
  "reconnecting-websocket": "^4.4.0",
  "date-fns": "^4.1.0",
  "uuid": "^11.1.0"
}
```

### **Architecture Patterns**
- **Context-based State Management**: Global data sharing
- **Service Layer Pattern**: Business logic separation
- **Repository Pattern**: Data access abstraction
- **Role-based Permission System**: Feature access control

### **Core Services**
- **AppointmentService**: Appointment CRUD operations
- **AnalyticsService**: Business metrics and reporting
- **InvoiceService**: Invoice generation and management
- **PaymentService**: Payment processing integration
- **WebSocketService**: Real-time communication handling

## 🌏 **Timezone Support**

The app features comprehensive **Perth, Australia** timezone support:

### **Features:**
- **Centralized Timezone Configuration**: `TimezoneConfig.ts`
- **Consistent Date Handling**: All dates in Perth timezone
- **Daylight Saving Support**: Automatic AWST/AWDT transitions
- **API Integration**: Proper timezone conversion for backend
- **User Interface**: All times displayed in local timezone

### **Timezone Functions:**
```typescript
// Core functions available
getPerthNow()                    // Current Perth time
formatDateForAPI(date)           // API-ready date format
formatDisplayDateTime(date)      // User-friendly display
toLocaleDateString(date)         // Localized formatting
```

## 🔧 **Installation & Setup**

### **Prerequisites**
- Node.js >= 18
- React Native CLI
- iOS Development: Xcode 12+, iOS 15.1+
- Android Development: Android Studio, API Level 21+

### **Installation Steps**

1. **Clone the repository**
```bash
git clone https://github.com/Auto-Lab-Solutions/Staff-Mobile-App.git
cd Staff-Mobile-App
```

2. **Install dependencies**
```bash
npm install
# For iOS
cd ios && pod install && cd ..
```

3. **Environment Setup**
- Configure Auth0 credentials
- Set API endpoints
- Configure WebSocket URLs

4. **Run the application**
```bash
# iOS
npm run ios
# Android
npm run android
```

## 📱 **Platform Support**

### **iOS**
- **Minimum Version**: iOS 15.1+
- **Deployment Target**: iPhone and iPad
- **Features**: Native navigation, deep linking, document picking

### **Android**
- **Minimum API Level**: 21 (Android 5.0)
- **Target API Level**: Latest
- **Features**: Material Design, notifications, file system access

## 🔐 **Security Features**

### **Authentication**
- **OAuth2/OpenID Connect**: Industry-standard authentication
- **JWT Token Management**: Secure token storage and refresh
- **Biometric Authentication**: Device-level security (future feature)

### **Data Protection**
- **Encrypted Storage**: Sensitive data encryption
- **Secure Communication**: HTTPS/WSS protocols
- **Role-based Access**: Granular permission system

## 🚀 **Performance Optimization**

### **Features**
- **Lazy Loading**: Screen-by-screen loading
- **Image Optimization**: Compressed and cached images
- **Bundle Splitting**: Optimized app bundles
- **Memory Management**: Efficient state management

### **Real-time Features**
- **WebSocket Connection Management**: Auto-reconnection
- **Background Sync**: Offline capability
- **Push Notifications**: FireBase Real-time alerts

## 🧪 **Testing Strategy**

### **Test Coverage**
- **Unit Tests**: Service layer testing
- **Integration Tests**: API communication
- **E2E Tests**: User workflow validation
- **Performance Tests**: Load and stress testing

### **Quality Assurance**
- **ESLint Configuration**: Code quality enforcement
- **TypeScript**: Compile-time error detection
- **Prettier**: Consistent code formatting

## 📈 **Future Enhancements**

### **Planned Features**
- **Biometric Authentication**: Face ID/Touch ID support
- **Offline Mode**: Local data synchronization
- **Push Notifications**: FireBase Real-time alerts (Already Implemented in Backend)
- **Advanced Analytics**: Machine learning insights
- **Multi-language Support**: Internationalization

### **Technical Improvements**
- **Performance Optimization**: Bundle size reduction
- **UI/UX Enhancements**: Modern design updates
- **Accessibility**: Screen reader and keyboard support
- **Testing Coverage**: Comprehensive test suite

## 👥 **User Roles & Permissions**

### **Permission Matrix**

| Feature | Admin | Customer Support | Mechanic | Clerk |
|---------|-------|------------------|----------|-------|
| Analytics Overview | ✅ | ❌ | ❌ | ❌ |
| Customer Analytics | ✅ | ✅ | ❌ | ❌ |
| Appointment Management | ✅ | ✅ | ✅ | ✅ |
| Customer Messages | ❌ | ✅ | ❌ | ❌ |
| Invoice Generation | ✅ | ❌ | ❌ | ❌ |
| Invoice Viewing | ✅ | ✅ | ❌ | ❌ |
| Staff Role Management | ✅ | ❌ | ❌ | ❌ |
| Report Uploads | ❌ | ❌ | ✅ | ✅ |
| Report Approval | ✅ | ❌ | ❌ | ❌ |
| Time Slot Management | ✅ | ✅ | ❌ | ❌ |
| Daily Schedule | ✅ | ✅ | ✅ | ❌ |
| User Management | ✅ | ✅ | ❌ | ❌ |

## 📞 **Support & Contributing**

### **Getting Help**
- **Documentation**: Comprehensive inline documentation
- **Issue Tracking**: GitHub Issues for bug reports
- **Feature Requests**: Enhancement proposals welcome

### **Development Guidelines**
- **Code Style**: Follow established patterns
- **Commit Messages**: Conventional commit format
- **Pull Requests**: Detailed descriptions required
- **Testing**: Ensure test coverage for new features

## 📄 **License**

This project is Open Source and available under the [MIT License](LICENSE).

---

## 🏆 **App Highlights**

✨ **Role-based Access Control** - Different features for each staff role  
🔄 **Real-time Updates** - Live data synchronization  
📊 **Comprehensive Analytics** - Business intelligence at your fingertips  
💬 **Live Communication** - Real-time customer support  
🗓️ **Smart Scheduling** - Conflict-free appointment management  
📱 **Cross-platform** - Native experience on iOS and Android  
🌏 **Timezone Aware** - Perfect Perth timezone integration  
🔐 **Enterprise Security** - OAuth2 and role-based permissions  
