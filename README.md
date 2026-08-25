<div align="center">
  
# 👋 Mina Mikhail

### 📱 Android Technical Lead | 🏦 FinTech & Digital Banking | 💳 POS Systems

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/minasamirgerges/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mina-Mikhail)
[![Followers](https://img.shields.io/github/followers/Mina-Mikhail?style=for-the-badge&logo=github&label=Followers)](https://github.com/Mina-Mikhail?tab=followers)

<img src="https://i.pinimg.com/originals/e4/26/70/e426702edf874b181aced1e2fa5c6cde.gif" width="400"/>

**10+ years building production-grade Android applications**

</div>

---

## 🚀 About Me

Android engineer based in Cairo, Egypt with deep expertise in **fintech**, **digital banking**, and **payment systems**.

I build apps that handle real money for real users in real markets.

My work spans **POS terminals**, secure transactions, modular architecture, and high-availability applications deployed across Egypt, Pakistan, and Saudi Arabia.

I spend 2 hours daily learning new technologies. Android is a long-term craft, not a trend.

**What I care about:**
- Clean architecture that scales
- Testable code that catches bugs before users do
- Performance under real constraints
- Systems that fail safely

---

## 🏢 Professional Experience

### 🏦 Onebank
**Android Technical Lead**

Building Egypt's first digital bank.

- Modular Android architecture for enterprise-scale apps
- Authentication systems with multiple strategies (OTP, Biometric, DFI)
- FATCA/KYC compliance implementations
- Token and session management systems
- CI/CD with quality gates

---

### 💳 Paymob
**Senior Android Engineer – FinTech & POS**

- Developed Android apps for POS payment terminals
- Worked on card transactions, EMV, and secure payment flows
- Deployed apps used across Egypt, Pakistan, and Saudi Arabia
- Focused on stability, latency, and offline handling

---

## 🛠️ Technical Stack

<div align="center">

| Category | Technologies |
|----------|-------------|
| **Languages** | ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) |
| **Architecture** | Clean Architecture, MVVM, MVI (Orbit), Modularization by Feature |
| **Async** | Coroutines, Flow, StateFlow |
| **DI** | ![Hilt](https://img.shields.io/badge/Hilt-2196F3?style=flat-square&logo=android&logoColor=white) ![Dagger](https://img.shields.io/badge/Dagger-FF6F00?style=flat-square&logo=android&logoColor=white) |
| **Networking** | Retrofit, OkHttp, Ktor |
| **Database** | Room, DataStore |
| **UI** | Jetpack Compose, DataBinding, Navigation Component, Material Design |
| **Testing** | JUnit 4/5, MockK, Mockito, Kover, Orbit Test |
| **CI/CD** | GitHub Actions, Jenkins, SonarQube |
| **Build** | Gradle KTS, buildSrc |
| **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) |

</div>

---

## 📦 Featured Projects

### 💎 [Kotlin-Base-MVVM](https://github.com/Mina-Mikhail/Kotlin-Base-MVVM)
Production-ready Android template with clean architecture and modern tech stack.

![Stars](https://img.shields.io/github/stars/Mina-Mikhail/Kotlin-Base-MVVM?style=flat-square)
![Forks](https://img.shields.io/github/forks/Mina-Mikhail/Kotlin-Base-MVVM?style=flat-square)
![Last Commit](https://img.shields.io/github/last-commit/Mina-Mikhail/Kotlin-Base-MVVM?style=flat-square)

**Features:**
- Clean Architecture with Domain, Data, Presentation layers
- Navigation Component with multiple backstack support
- Hilt dependency injection
- Kotlin Coroutines and Flow with StateFlow
- Git hooks for code quality automation

**Tech Stack:** Kotlin, MVVM, Hilt, Coroutines, Flow, StateFlow, Retrofit, Navigation Component, DataBinding

**Modules:** app, domain, data, presentation, appTutorial, actionChooser, prettyPopUp, imagesSlider

---

### 🔐 [Biometric-With-Crypto](https://github.com/Mina-Mikhail/Biometric-With-Crypto)
Secure biometric authentication with Cipher encryption/decryption for sensitive data.

![Stars](https://img.shields.io/github/stars/Mina-Mikhail/Biometric-With-Crypto?style=flat-square)
![Forks](https://img.shields.io/github/forks/Mina-Mikhail/Biometric-With-Crypto?style=flat-square)

**Features:**
- Biometric login with fingerprint/face authentication
- AES encryption/decryption using Android Keystore
- Secure storage of user credentials
- Clean modular architecture

**Tech Stack:** Kotlin, Biometric API, Android Keystore, Cipher, Hilt, Encrypted SharedPreferences

**Modules:**
- `biometricAuthentication` — Handles biometric prompt and authentication flow
- `crypto` — Manages encryption and decryption operations
- `prefs` — Encrypted SharedPreferences wrapper

**Screens:** Splash (biometric login), Login (credential encryption), Home (user data display)

📚 [Biometric Authentication Presentation](https://docs.google.com/presentation/d/14h8hKSx8B_J4Sw21PWJYL-qh0ae6B4W7W_I543sU2no/edit?usp=sharing)

---

### 🧪 [kotlinFixture](https://github.com/Mina-Mikhail/kotlinFixture)
Test data generation library for Android unit testing.

![Stars](https://img.shields.io/github/stars/Mina-Mikhail/kotlinFixture?style=flat-square)
![Forks](https://img.shields.io/github/forks/Mina-Mikhail/kotlinFixture?style=flat-square)

**Features:**
- Generate dummy values for any data class
- Support for lists with configurable size
- Easy customization with `.copy()` for specific test scenarios
- Reduces boilerplate in unit tests

**Usage:**
```kotlin
// Generate single object
val user = fixture<User>()

// Generate list with specific size
val users = fixtureList<User>(10)

// Override specific fields
val customUser = fixture<User>().copy(name = "Test User")
```

**Why use it:**
- Eliminates hardcoded test data
- Makes tests more readable
- Catches business logic changes when combined with exact mocking

---

### ⚠️ [Network-Error-Handling](https://github.com/Mina-Mikhail/Network-Error-Handling)
Retrofit adapters for handling API responses and exceptions in clean architecture.

![Stars](https://img.shields.io/github/stars/Mina-Mikhail/Network-Error-Handling?style=flat-square)

**Features:**
- Custom Retrofit Call Adapter for unified error handling
- Sealed class response wrapper for success/error states
- Network exception handling without try-catch blocks
- Clean separation between network and domain layers

**Tech Stack:** Kotlin, Retrofit, OkHttp, Clean Architecture

**Use Case:** Centralized API error handling that propagates errors through the architecture without exposing Retrofit exceptions to the domain layer.

---

### 📰 [News-App](https://github.com/Mina-Mikhail/News-App)
Sample news application demonstrating modern Android development practices.

![Stars](https://img.shields.io/github/stars/Mina-Mikhail/News-App?style=flat-square)

**Features:**
- Fetch and display news articles from API
- Local caching with Room for offline support
- Image loading with Coil
- Clean MVVM architecture

**Tech Stack:** Kotlin, Hilt, Coroutines, Coil, Room, Retrofit, MVVM

**Architecture:** Repository pattern with local database as single source of truth. API data is cached locally and served from Room database.

---

### 🌐 [Network-Caching](https://github.com/Mina-Mikhail/Network-Caching)
Cache-first strategy for API response caching to local storage.

![Stars](https://img.shields.io/github/stars/Mina-Mikhail/Network-Caching?style=flat-square)

**Features:**
- Cache-first data loading strategy
- Automatic cache invalidation
- Offline-first architecture
- Seamless online/offline transitions

**Use Case:** Apps that need to work reliably with intermittent network connectivity while keeping data fresh.

---

## 📂 What You'll Find Here

This GitHub contains:
- Android architecture experiments
- Clean code samples
- FinTech-oriented patterns
- Real solutions to real problems

Code here reflects **production thinking**, not tutorials.

---

## 🏆 Achievements

<div align="center">

[![Arctic Code Vault](https://img.shields.io/badge/Arctic%20Code%20Vault-Contributor-blue?style=for-the-badge)](https://archiveprogram.github.com/)
[![Starstruck](https://img.shields.io/badge/Starstruck-Achievement-yellow?style=for-the-badge)](https://github.com/Mina-Mikhail?achievement=starstruck)
[![Pull Shark](https://img.shields.io/badge/Pull%20Shark-Achievement-purple?style=for-the-badge)](https://github.com/Mina-Mikhail?achievement=pull-shark)

</div>

---

## 🧠 Development Philosophy

```
✅ Single Responsibility — Each class has one job
✅ Testability First — Write code that can be tested in isolation
✅ Performance Matters — Optimize for real constraints
✅ Fail Safely — Systems should degrade gracefully
✅ Simplicity Scales — Better than cleverness
✅ FinTech Code Must Be Boring and Correct
```

---

## 📫 Connect

<div align="center">

💼 [LinkedIn](https://www.linkedin.com/in/minasamirgerges/) · 🗂️ [GitHub](https://github.com/Mina-Mikhail) · 📍 Cairo, Egypt

</div>

---

<div align="center">

### ☕ Support My Work

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/mina.mikhail)

---

⭐ **Star my repositories if you find them useful!**

![Profile Views](https://komarev.com/ghpvc/?username=Mina-Mikhail&color=2bbc8a&style=flat-square)

**Always learning. Always shipping.**

</div>
