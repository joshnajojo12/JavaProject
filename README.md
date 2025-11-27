#  Organ Donation System – Java Swing Desktop Application

---

## Project Title
**Organ Donation System — Desktop Organ Management (Java Swing)**

---

## Description
The **Organ Donation System** is a modular Java desktop application designed to help hospitals and administrators manage organ donation records.

It provides a Swing-based interface for:

- Donor registration  
- Recipient registration  
- Hospital login  
- Admin login  
- Organ availability management  
- Donor–recipient matching  
- Dashboard navigation and record management  

The application follows **MVC architecture** and uses **OOP principles** for a clean and maintainable design.

---

## Features
---

###  Authentication
- Admin login  
- Hospital login  

---

###  Hospital Features
- Register donors  
- Register recipients  
- Update donor/recipient status  
- View organ availability  

---

###  Admin Features
- Approve hospitals  
- View all donors and recipients  
- Match compatible donors and recipients  
- Update or delete records  
- Monitor system dashboard  

---

###  Matching System
- Suggests compatible donor–recipient pairs based on organ type  

---

###  User Interface
- Java Swing–based GUI  
- Multiple screens for login, dashboards, forms, and lists  
- Organized navigation using controllers  

---

## Technical Overview
---

- **Language:** Java (JDK 8 / 11 / 17)  
- **UI:** Java Swing  
- **Architecture:** MVC  
- **Entry Point:** `App.java`  
- **IDE:** Eclipse  

---

## Project Structure
---

```text
organdonation/
│
├── controller/                 → Controllers (Admin, Hospital, Donor, Recipient, Login)
│   ├── AdminDashboardController.class
│   ├── DonorRegistrationController.class
│   ├── RecipientRegistrationController.class
│   ├── HospitalLoginController.class
│   ├── LoginController.class
│   └── ...
│
├── model/                      → Data models & DAO classes
│   ├── Admin.class
│   ├── Donor.class
│   ├── Recipient.class
│   ├── Hospital.class
│   ├── Match.class
│   └── ...
│
├── view/                       → Swing UI screens
│   ├── LoginView.class
│   ├── LandingView.class
│   ├── AdminDashboardView.class
│   ├── DonorRegistrationView.class
│   ├── HospitalDashboardView.class
│   └── ...
│
├── images/                     → UI icons and assets
│
├── JavaProject.jar             → Executable JAR file
├── myorgan (3).zip             → Source code ZIP
└── README.md                   → Project documentation
```

---

## Installation
---

### Prerequisites
- Java JDK **8 / 11 / 17** installed  

### Steps
1. Download or clone the repository  
2. Ensure Java is installed  
3. Run the software using:

---

## Run the Project
---

### Run using:
```bash
java -jar JavaProject.jar
```

Or simply double-click the **JavaProject.jar** file.

---

## Testing
---

The executable JAR has been tested for:

- Login modules  
- Dashboard navigation  
- Donor and recipient registration  
- Matching functionality  
- Button actions & UI performance  

All major flows are verified and working.


