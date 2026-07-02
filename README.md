
# Tool Rental Mobile Application 🛠️📱
**A cross-platform mobile application developed using Flutter and Firebase, designed to facilitate local tool sharing, real-time database management, and rental tracking.**

---

## 📌 Project Overview
This mobile application provides a seamless, localized marketplace for renting and sharing tools (hand tools, power tools, gardening, etc.). Built with an intuitive Arabic interface, the platform connects tool owners with local renters, encouraging sustainable community resource management and lowering utility costs.

The application leverages **Firebase Cloud Storage and Firestore Real-time Database** alongside location-based filtering to provide accurate asset availability checking based on user geographic proximity.

---

## 🚀 Key Technical Features
- **Dynamic Asset Discovery:** Main dashboard featuring popular tools, filtered categories, and responsive search query bars fetching live data from Firebase.
- **Interactive Map Integration:** Employs real-time GPS positioning to display available rental tools on an interactive layout map with status indicators.
- **Structured Tool Listing Management:** Formal multi-step input form enabling owners to add tools with titles, descriptions, accurate daily pricing, and directly upload assets to the database.
- **Comprehensive User Ecosystem:** Fully responsive profile controls, modular categorizations (Electrical, Hand Tools, Gardening, Kitchen), and real-time booking tracker logs.
- **Robust Backend Infrastructure:** Powered by **Firebase** for cloud data persistence, continuous state tracking, and secure asset storage.

---

## 🛠️ Tech Stack & Architecture
- **Framework:** Flutter (Dart) — supporting beautiful, native-performance interfaces.
- **Backend & Database:** Firebase (Firestore Cloud Database / Authentication / Cloud Storage).
- **Core APIs:** Google Maps API & Location Services.

---

## 📸 User Interface Preview
The platform provides a highly localized, clean layout crafted specifically for seamless navigation:

### 🔍 Part 1: Exploration & Communication
| Main Dashboard | Product Details | Chat & Communication | Category Directory |
| :---: | :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/305a0ae2-315d-47b5-a4ba-cbdd13dbd14a" width="180"> | <img src="https://github.com/user-attachments/assets/5a886ff2-0e87-4faa-aa05-2dede140e993" width="180"> | <img src="https://github.com/user-attachments/assets/78922f8b-1723-4407-94a0-0acbf07c0206" width="180"> | <img src="https://github.com/user-attachments/assets/5a3becbe-f17e-4eab-941e-063f9d0ab360" width="180"> |

### 🛠️ Part 2: Actions, Location & Profile
| Add New Asset (Sell/Rent) | Interactive Map View | Booking Tracker | User Profile Center |
| :---: | :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/cf39842b-7944-4093-b19e-6057761e0843" width="180"> | <img src="https://github.com/user-attachments/assets/89d3da6f-837c-4934-ab45-9fdceb2b4661" width="180"> | <img src="https://github.com/user-attachments/assets/99369362-75b3-48f6-beee-d038f97e3d86" width="180"> | <img src="https://github.com/user-attachments/assets/c1424e29-d78f-49b1-afce-2fcf25d096ff" width="180"> |

---

## 💡 Engineering Challenges & Solutions
### 1. Multi-Category State Filtration
- **Challenge:** Efficiently updating the map pins and product grids based on active dynamic categories (e.g., separating electrical tools from hand tools) without degrading device performance.
- **Solution:** Structured the system using optimized reactive state management loops that cleanly isolate UI rebuilding to the product directory component only.

### 2. Location Authorization Safeguards
- **Challenge:** Managing application stability and graceful UI responses when location access permissions are actively rejected or disabled by the user device.
- **Solution:** Implemented clear user notifications and dynamic warning banner interfaces (e.g., permission rejection status bars) directing users instantly back to system configurations.
