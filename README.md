## About the Project

This is a re-implementation of single-player Tetris in Java. Like the original game, this project is complete with features including:
* a scoring system
* randomized blocks
* block-holding
* level progression

### Built With

* Java
* JavaFX

## Getting Started

### Prerequisites

* JDK 21.0.2 (or later)
  
* JavaFX SDK 21.0.2 (must be compatible with the JDK version)
  
* IntelliJ IDEA 2023.3.4 (or later)
  
* Windows 10 (or later) or macOS 12 (or later)

### Installing & Executing Program

The JavaFX application should be run on IntelliJ IDEA. To download and execute the applications, follow these steps:

* Open the project folder on IntelliJ IDEA.
  
* Go to File -> Project Structure -> Project, and set SDK to 21.
  
* Go to File -> Project Structure -> Libraries, and add the lib folder of the JavaFX 21 SDK as a library.
  
* Go to Run -> Edit Configurations, and add new configuration. Set Main class to the class labeled "App". Add these VM Options to the configuration (replace path with the actual path to JavaFX SDK lib folder):
  
  ```
  --module-path /path/to/javafx-sdk-21.0.2/lib --add-modules javafx.controls,javafx.fxml
  ```
  
* Run the "App" class

## Authors

Sean Zhang
