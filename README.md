🏦 Banking Simulator System (Full-Stack)
A robust, full-stack Banking Application designed to simulate real-world financial operations. This project features a high-performance Java Spark backend and a responsive JavaScript frontend, communicating via a RESTful JSON API.

📂 Project Structure
The repository is organized into distinct modules for better maintainability and separation of concerns:

banking-simulator-main/: The Core Backend. Contains the Java source code, Maven configuration (pom.xml), and local transaction logs.

Banking-Simulator-Frontend-main/: The Web Interface. Contains index.html, style.css, and script.js.

AgileDocument.pdf: Documentation of the Agile development lifecycle and project planning.

LICENSE: Legal permissions and project licensing.

🚀 Technical Highlights
Layered Architecture: Organized into Model, Service, and Repository layers to ensure "Separation of Concerns".

Data Security (Encapsulation): Uses private fields in Account.java with public Getters/Setters to protect sensitive data.

Concurrency Support: Implements ConcurrentHashMap in AccountRepository.java to handle multiple users simultaneously without data corruption.

Financial Precision: Uses BigDecimal for all money-related calculations to avoid the rounding errors common with standard floating-point numbers.

Automated Alerts: Features an AlertService that triggers EmailUtil.java to send notifications if a balance falls below a safe threshold.

🛠️ Technology Stack
Backend: Java 17, Spark Java Framework, Maven.

Frontend: HTML5, CSS3, Vanilla JavaScript (Fetch API).

Communication: Asynchronous JSON requests over HTTP.

Persistence: In-memory storage for high-speed transaction processing.

⚙️ Execution Instructions
1. Launch the Backend
Import the banking-simulator-main folder into Eclipse or IntelliJ.

Run ApiServer.java as a Java Application.

The server will start at: http://localhost:8080.

2. Launch the Frontend
Open index.html from the Banking-Simulator-Frontend-main folder in any modern browser.

Perform transactions (Create Account, Deposit, Withdraw, Transfer) and see the updates in real-time.
