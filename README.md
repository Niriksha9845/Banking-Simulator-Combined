# 🏦 Banking Simulator System (Full-Stack)

A robust, full-stack Banking Application designed to simulate real-world financial operations. This project features a high-performance **Java Spark** backend and a responsive **JavaScript** frontend, communicating via a RESTful JSON API.

---

## 📂 Project Structure
The repository is organized into distinct modules for better maintainability:

* **`banking-simulator-main/`**: The Core Backend. Contains Java source code, Maven configuration (`pom.xml`), and transaction logs.
* **`Banking-Simulator-Frontend-main/`**: The Web Interface. Contains `index.html`, `style.css`, and `script.js`.
* **`Navya agile documnet.xlsx`**: Documentation of the Agile development lifecycle and project planning.
* **`LICENSE`**: Legal permissions and project licensing.

---

## 🚀 Technical Highlights
* **Layered Architecture**: Organized into Model, Service, and Repository layers to ensure "Separation of Concerns."
* **Data Security**: Uses `private` fields in `Account.java` with public Getters/Setters for encapsulation.
* **Concurrency**: Implements `ConcurrentHashMap` in the Repository to handle multiple users safely.
* **Precision**: Uses `BigDecimal` for all monetary calculations to ensure 100% financial accuracy.
* **Automated Alerts**: Features an `AlertService` that triggers email notifications via `EmailUtil.java`.

---

## 🛠️ Technology Stack
* **Backend**: Java 17, Spark Java Framework, Maven.
* **Frontend**: HTML5, CSS3, Vanilla JavaScript (Fetch API).
* **Communication**: Asynchronous JSON requests over HTTP.
* **Persistence**: In-memory storage for high-speed transaction processing.

---

## ⚙️ Execution Instructions

### 1. Launch the Backend
* Import the `banking-simulator-main` folder into your IDE.
* Run `ApiServer.java` as a Java Application.
* The server will start at: `http://localhost:8080`

### 2. Launch the Frontend
* Open `index.html` from the `Banking-Simulator-Frontend-main` folder in any modern browser.
* Perform transactions and view updates in real-time.

---


