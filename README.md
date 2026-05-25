# My First Maven Project 🚀

A simple Java application built from scratch using Apache Maven and Visual Studio Code. This project demonstrates the basic structure of a Maven application and how to resolve common compilation version mismatches.

## 🛠️ Tech Stack & Tools
* **Language:** Java
* **Build Tool:** Apache Maven
* **IDE:** VS Code

## ⚙️ How to Build and Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```

2. **Navigate into the project directory:**
   ```bash
   cd my-app
   ```

3. **Compile the project:**
   ```bash
   mvn clean compile
   ```

4. **Run the application:**
   ```bash
   mvn exec:java -Dexec.mainClass="com.myFirstMavenProject.App"
   ```

## 💡 Key Learnings
* Setting up a standard Maven directory structure (`src/main/java`).
* Fixing the missing POM directory issue by navigating with `cd`.
* Resolving Java version mismatch issues (`Source option 7 is no longer supported`) by updating compiler properties to `1.8` in `pom.xml`.
