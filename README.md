# WhatsApp UI Clone 📱

A pixel-perfect, cross-platform UI clone of WhatsApp built using Flutter. This project focuses on replicating the classic WhatsApp interface, demonstrating how to build structured, tab-based navigation and responsive layouts using Flutter's widget system.

## Screenshots

<p align="center">
  <img src="lib/WhatsApp%20Pictures/WhatsApp%20Pic%20%23%2001.PNG" width="250" alt="Chats Screen" />
  &nbsp;&nbsp;&nbsp;
  <img src="lib/WhatsApp%20Pictures/WhatsApp%20Pic%20%23%2002.PNG" width="250" alt="Status Screen" />
  &nbsp;&nbsp;&nbsp;
  <img src="lib/WhatsApp%20Pictures/WhatsApp%20Pic%20%23%2003.PNG" width="250" alt="Calls Screen" />
</p>

*Note: The images above are located in the `lib/WhatsApp Pictures/` directory of the repository.*

## Features

* **Authentic Tabbed Interface:** Accurately recreates the core WhatsApp navigation, including **Chats**, **Status**, and **Calls** screens.
* **Modular Codebase:** The UI components are cleanly separated into dedicated directories for easier maintenance and scaling.
* **Cross-Platform Compatibility:** Configured to run on Android, iOS, Web, macOS, Linux, and Windows.
* **Asset Integration:** Includes custom image assets seamlessly integrated into the UI (e.g., profile pictures, status updates).

## Project Structure

The core UI logic is organized within the `lib/` directory:

* `lib/main.dart` & `lib/Home/home.dart`: Main entry points and the primary tab controller layout.
* `lib/Chats/chats.dart`: UI implementation for the active conversations list.
* `lib/Status/status.dart`: UI implementation for the user status updates screen.
* `lib/Calls/calls.dart`: UI implementation for the call history screen.
* `lib/WhatsApp Pictures/`: Contains the mock images used throughout the application to simulate real user data.

## Prerequisites

Before running this project, ensure you have the following installed:
* [Flutter SDK](https://docs.flutter.dev/get-started/install) (latest stable version recommended)
* A supported IDE (e.g., VS Code, Android Studio, IntelliJ IDEA)
* A connected physical device or a configured emulator/simulator

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/flutter-whatsapp-ui.git](https://github.com/your-username/flutter-whatsapp-ui.git)
