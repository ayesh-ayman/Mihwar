# Mihwar

**Smart Waste Collection & Route Optimization Mobile Application**

Mihwar is a Flutter-based smart waste management application designed to improve waste collection operations through data-driven bin monitoring, predictive analysis, and optimized collection routes.

The system provides dedicated interfaces for drivers, supervisors, and governorate-level management, helping transform traditional waste collection into a more efficient and organized workflow.

## Key Features

- Smart monitoring of waste bin status
- Prediction-based collection planning
- Optimized collection routes
- Driver route guidance and trip management
- Supervisor monitoring and compliance tracking
- Governorate dashboard for operational insights
- Diesel consumption tracking
- Driver performance and achievement tracking
- Local data persistence using SQLite
- Role-based application experience
- Arabic and English localization
- Simulated telemetry and operational data for demonstration

## Smart Prediction & Route Optimization

Mihwar includes a Python-based prediction component for processing smart-bin data and generating collection information that can be consumed by the Flutter application.

The project also includes route-planning logic for determining efficient collection sequences and supporting optimized trips between waste-bin locations.

The generated prediction and routing data is integrated into the mobile application to support smarter collection decisions.

## Technology Stack

- **Flutter** — Cross-platform application development
- **Dart** — Core application language
- **Riverpod** — State management
- **SQLite / Sqflite** — Local data persistence
- **Python** — Bin prediction and data processing
- **JSON** — Data exchange between prediction outputs and the Flutter application
- **OSRM** — Road routing support
- **Git & GitHub** — Version control and source-code management

## Application Architecture

The project follows a modular structure that separates core services, data access, routing, state management, and application features.

```text
lib/
├── app/
├── core/
│   ├── config/
│   ├── db/
│   ├── models/
│   ├── repositories/
│   ├── routing/
│   └── services/
├── features/
│   ├── auth/
│   ├── driver/
│   ├── governorate/
│   └── supervisor/
├── shared/
└── main.dart

ai/
├── code/
├── dataset/
└── output/
```

## User Roles

### Driver
Provides drivers with trip information, collection routes, bin status, navigation-related data, and performance information.

### Supervisor
Supports monitoring of collection operations and driver compliance.

### Governorate Management
Provides higher-level operational information, predictive insights, route-planning data, and system settings.

## Project Objective

Mihwar aims to demonstrate how mobile development, data analysis, predictive techniques, and route optimization can be combined to improve municipal waste collection operations.

Instead of relying only on fixed collection schedules, the system uses available bin data and routing logic to support more informed collection decisions.

## Project Status

Mihwar is currently developed as a functional demonstration/prototype using simulated and prepared operational data.

## Developer

**Ayesh Zayed**

Flutter & Mobile Application Developer

GitHub: [ayesh-ayman](https://github.com/ayesh-ayman)
