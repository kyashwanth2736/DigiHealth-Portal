# DigiHealth Portal 🏥

A secure, dual-dashboard healthcare web application designed to bridge the gap between doctors and patients. Built entirely with vanilla web technologies, this project demonstrates real-time data synchronization between portals using browser storage.

## ✨ Key Features

### 👨‍⚕️ Doctor Dashboard
* **Patient Management:** View clinical overviews, daily appointments, and pending lab reports.
* **Health Record Submission:** Push prescriptions, scanning results (MRI/X-Rays), lab reports, and medication trackers directly to a specific patient's portal.
* **Profile Settings:** Manage clinical identity, specialization, and security PINs.

### 👤 Patient Dashboard
* **Medical History:** Securely view personalized health records organized by category.
* **Dynamic Record Fetching:** Instantly retrieve notes, prescriptions, and lab results submitted by the doctor.
* **Responsive Design:** Clean, accessible UI that works seamlessly on both desktop and mobile devices.

### ⚡ Core Functionality
* **Data Synchronization:** Utilizes the browser's `localStorage` to simulate a shared database. Records submitted on the Doctor portal instantly render on the Patient portal when accessed on the same device/browser.

## 🛠️ Technologies Used
* **HTML5:** Semantic structure and layout.
* **CSS3:** Custom variables, CSS Grid/Flexbox, sticky headers, and modern animations.
* **Vanilla JavaScript:** DOM manipulation, form handling, and state management via `localStorage`.

## 🚀 Getting Started

Since this project runs entirely in the browser without a backend server, setting it up is incredibly simple.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR-USERNAME/digihealth-portal.git](https://github.com/YOUR-USERNAME/digihealth-portal.git)
