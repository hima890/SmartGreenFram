# SmartGreenFarm Project

The SmartGreenFarm project is designed to collect sensor information from a farm environment using a Python Flask server and display this information in a graphical user interface (GUI) application created with C++ and Qt5.

## Project Structure

The project is organized into two main components:

### 1. Server Side

The `server_side` folder contains the Python Flask server responsible for collecting sensor information. The server is executed using the `server.py` script.

#### Setup and Run the Server

1. Navigate to the `server_side` folder:

   ```bash
   cd server_side
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the server:

   ```bash
   python server.py
   ```

   This will start the Flask server to collect and manage sensor information.

### 2. GUI Application

The GUI application, developed in C++ with Qt5, provides an interface to visualize the collected sensor data.

#### Build and Run the GUI Application

Ensure you have the necessary dependencies installed to build C++ applications with Qt5. Then follow these steps:

1. Navigate to the `gui_application` folder:

   ```bash
   cd gui_application
   ```

2. Build the C++ application:

   ```bash
   qmake
   make
   ```

3. Run the GUI application:

   ```bash
   ./main.cpp
   ```

   The GUI application will connect to the Flask server and display the sensor information.

## Configuration

Adjust the server and GUI configurations in their respective files (`server.py`, `gui_app.pro`, etc.) based on your specific project requirements.

## Contributing

Contributions to improve the project, add features, or fix bugs are welcome. Please follow the contribution guidelines in the `CONTRIBUTING.md` file.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
