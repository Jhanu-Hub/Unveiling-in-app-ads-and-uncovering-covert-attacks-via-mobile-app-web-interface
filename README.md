# Unveiling In-App Ads and Uncovering Covert Attacks via Mobile App-Web Interface

Mobile users are increasingly becoming targets of malware, phishing scams, and covert attacks. This project investigates a crucial, often overlooked malware propagation vector — the mobile **App-Web interface**, where seemingly benign mobile apps redirect users via in-app ads to malicious web destinations.

## 📌 Project Objective

To unveil hidden malicious activities embedded in mobile applications by analyzing:
- In-app advertisements and redirects
- App-web interfaces for covert malware delivery
- Campaign provenance to trace back the source

## 🚀 Key Features

- 🔍 **Static Analysis**: Detects embedded ad libraries in APKs.
- 🧪 **Dynamic Analysis**: Automatically triggers ad links and analyzes their web destinations.
- 🕸️ **Provenance Tracking**: Traces source networks of malicious links.
- 📈 **Visualization**: Admin dashboards with reports, user charts, and ad ratings.

## 🛠️ System Modules

### 1. **Admin**
- View users, ads, malicious activity, rankings
- Authorize/block/unblock users
- Monitor malicious ad submissions and scams

### 2. **User**
- Register/Login
- Create bank accounts, launch ads
- Recommend friend ads and monitor ad stats

### 3. **Android User (Attacker Simulation)**
- Perform covert actions like launching fake ads or malicious links

## 🏗️ System Architecture
- Java J2SE, Servlets, JSP
- MySQL database
- HTML, CSS, JS frontend
- Tomcat Server
- JFreeChart for visual analytics

## 💻 Technologies Used

| Component | Technology |
|----------|------------|
| Frontend | HTML, CSS, JavaScript |
| Backend | Java, Servlets, JSP |
| Database | MySQL |
| Server | Apache Tomcat |
| Libraries | JFreeChart, JDBC |
| Tools | NetBeans |

## 📊 Dataset & Results

- Analyzed **600,000+ applications**
- Triggered **1.5 million+ web links**
- Detected **rogue ad networks**, **fake antivirus scams**, **SMS trojans**
- Identified **242 ad libraries**

## ✅ Functional Requirements

- User account creation & role management
- Secure ad publishing and validation
- Attack detection & provenance tracking

## 📎 Non-Functional Requirements

- Platform: Android + Java Backend
- RAM: 4GB+, Disk: 20GB+
- Java 2 SE, NetBeans 8.0, MySQL

## 📷 Screenshots

> See `/screenshots/` folder for interface previews of:
- User dashboard
- Admin monitoring panel
- Advertisement rank analytics
- Malicious user detection interface

## 🧪 Test Cases

Tests were designed for:
- Login/Authentication
- Ad validation & submission
- Malicious ad detection
- Admin approval workflows

All tests passed successfully with no critical failures.

## 📚 References

- Research papers from IEEE, ResearchGate
- Android malware detection studies
- Malware propagation models
- J2ME and Java networking documentation

## 📍 Conclusion

This system enhances Android security by:
- Proactively detecting covert attacks in in-app ads
- Holding ad networks accountable
- Empowering users and admins to fight back against malvertising

## 🌱 Future Enhancements

- Integration with real Android devices
- Real-time threat analytics
- Automatic malware signature updates
