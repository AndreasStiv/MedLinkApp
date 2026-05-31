# MedLinkApp

MedLinkApp is a modern Android application designed to bridge the communication gap between patients, doctors, and caregivers. It provides a comprehensive platform for managing healthcare through medication tracking, vitals monitoring, appointment scheduling, and emergency alerts.

## 🚀 Features

### 👤 Patient Role
- **Dashboard**: Overview of latest vitals, upcoming appointments, and medication reminders.
- **Vitals Monitoring**: Record and track measurements like Blood Pressure, Glucose, Weight, and Oxygen levels.
- **Medication Management**: Track daily intakes, confirm doses, and monitor stock levels with low-stock warnings.
- **Appointments**: View and manage scheduled doctor visits.
- **Messaging**: Direct communication channel with healthcare providers.
- **SOS/Emergency**: One-tap SOS trigger to alert assigned doctors and caregivers.

### ⚕️ Doctor Role
- **Patient Dashboard**: Real-time alerts for critical patient measurements.
- **Search & History**: Access patient medical records and measurement history.
- **Appointments**: Schedule and manage appointments for patients.
- **Patient Linking**: Easily assign existing patients to your care list.

### 🏠 Caregiver Role
- **Supervision Dashboard**: Monitor multiple patients' health status at a glance.
- **Real-time Adherence**: Track patient medication compliance as it happens.
- **Statistics & Reports**: Generate adherence statistics for specific time periods to analyze health trends.
- **Communication Error Handling**: Automatic detection and notification if patient device synchronization fails.

## 🛠 Technology Stack
- **Language**: Kotlin
- **UI Framework**: Jetpack Compose
- **Architecture**: MVVM (Model-View-ViewModel) with Repository pattern.
- **Asynchronous Programming**: Kotlin Coroutines & StateFlow.
- **Navigation**: Navigation Compose.
- **Data Persistence**: JSON-based local storage (Gson + SharedPreferences).
- **Design System**: Material Design 3 (M3).

## 📂 Project Structure
- `ui/`: Compose screens, components, and ViewModels categorized by feature/role.
- `data/`: Repositories and `DBManager` for state management and local persistence.
- `model/`: Data classes and enums representing the app's domain logic.

## ⚙️ Getting Started

### Prerequisites
- Android Studio Ladybug (or newer)
- Gradle 8.0+
- Android Gradle Plugin (AGP) 9.1.0+
- JDK 17+

### Build & Run
1. Clone the repository.
2. Open the project in Android Studio.
3. Sync Gradle files.
4. Run the `:app` module on an emulator or physical device (API 26+ recommended).

## 🧪 Demo Credentials
For testing purposes, the app comes pre-loaded with mock data and the following accounts (Password: `123` for all):
- **Patient**: `patient`
- **Doctor**: `doctor`
- **Caregiver**: `caregiver`

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
