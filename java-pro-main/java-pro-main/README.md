# Campus Course & Records Manager (CCRM)

## 1. Project Overview
CCRM is a comprehensive, menu-driven command-line application built with Java SE 17+. It serves as a robust platform for academic administrators to manage student information, course catalogs, enrollments, and academic records efficiently.

The system demonstrates a wide array of Java features, from core object-oriented principles and advanced language constructs to modern APIs like Streams, NIO.2, and the Date/Time API. It is designed to be a practical showcase of Java SE capabilities in a real-world-like scenario.

### Core Features:
- **Student Management:** Add, update, list, and deactivate student profiles.
- **Course Management:** Manage course details, including search and filtering.
- **Enrollment & Grading:** Handle student enrollments, grade assignments, and GPA calculations.
- **Data Persistence:** Import and export data from/to CSV files.
- **System Utilities:** Create timestamped backups and perform recursive calculations.
- **Reporting:** Generate student transcripts and system-wide academic reports.

---

## 2. How to Run the Application

### Prerequisites
- **Java Development Kit (JDK) 17 or higher.**
- An IDE like **Eclipse**, **IntelliJ IDEA**, or **VS Code** (optional but recommended).
- **Git** for cloning the repository.

### Steps:
1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd CCRM
   ```

2. **Compile the project from the command line:**
   Navigate to the `src` directory and run:
   ```bash
   javac edu/ccrm/cli/MainMenu.java
   ```

3. **Run the application:**
   From the `src` directory, execute the main class:
   ```bash
   java edu.ccrm.cli.MainMenu
   ```

4. A Note on Assertions
Assertions are used in this project to validate assumptions about the program's state. For example, `assert student != null;` could be used to check that a student object is not null before proceeding.

**Important:** Assertions are disabled by default at runtime. To enable them, you must use the `-ea` (or `-enableassertions`) flag when running the application:
```bash
# From the command line
java -cp bin -ea edu.ccrm.cli.MainMenu

# In Eclipse, you can add this to the VM arguments in the Run Configuration.
```

---
<!--
## 9. Acknowledgements
This project was generated with the assistance of GitHub Copilot, an advanced AI programming assistant.
-->
